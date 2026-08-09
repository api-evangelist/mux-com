# Mux GraphQL

## Overview

Mux does not currently offer a public GraphQL API. All Mux Video and Mux Data operations are available exclusively through the Mux REST API, served from `https://api.mux.com` and authenticated via HTTP Basic auth using a Mux Access Token ID and Secret.

A GraphQL endpoint probe (`POST https://api.mux.com/graphql`) returns a 404 not-found response, confirming the absence of a GraphQL surface as of June 2026.

## Hypothetical Schema

The schema file `mux-schema.graphql` in this directory provides a representative GraphQL schema derived from the Mux REST API reference and OpenAPI specification (`https://www.mux.com/api-spec.json`). It covers the two Mux product families:

- **Mux Video** — asset ingest, transcoding, storage, playback, live streaming, simulcast, signing, DRM, direct uploads, webhooks
- **Mux Data** — QoE analytics, video views, playback sessions, metrics, errors, experiments, insights, exports, dimensions

## Type Coverage

The schema defines 55+ types spanning both product areas:

| Domain | Types |
|---|---|
| Assets | Asset, AssetTrack, VideoTrack, AudioTrack, TextTrack, AssetError, AssetMaster |
| Playback | PlaybackID, PlaybackRestriction, PlaybackPolicy |
| Live Streaming | LiveStream, SimulcastTarget |
| Signing & DRM | SigningKey, DRMLicenseKeyServer |
| Uploads | DirectUpload, UploadLink |
| Data / Analytics | VideoView, PlaybackSession, Error, Experiment, Metric, Score |
| Insights | Insights, Breakdown, ComparisonTimeseries, Timeseries |
| Webhooks | WebhookEvent |
| Usage | DeliveryUsage, Data, Export, Dimension |
| Video Quality | VideoQualityScore |
| Pagination | PageInfo |
| Common | Environment, Filter, TimeRange |

## Source

- REST API Reference: https://www.mux.com/docs/api-reference
- OpenAPI Specification: https://www.mux.com/api-spec.json
- GitHub Organization: https://github.com/muxinc
