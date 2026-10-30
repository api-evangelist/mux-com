# Mux

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Mux is a video infrastructure platform that gives developers an end-to-end API for ingesting, encoding, storing, delivering, and analyzing video. The platform spans Mux Video (on-demand and live streaming), Mux Data (quality-of-experience analytics), Mux Robots (AI workflows for captions, chapters, summarization, and moderation), and Mux Player (drop-in playback components). Mux exposes a unified REST API at api.mux.com plus delivery hosts at stream.mux.com, image.mux.com, and stats.mux.com, backed by official SDKs in Node, Python, Ruby, PHP, Go, and Elixir, a CLI, and player integrations across web, iOS, Android, Roku, and major HTML5 players.

**Areas:** Video Infrastructure · Video Streaming · Live Streaming · Video Analytics · Video AI · Encoding

## Mux on APIs.io

Everything profiled for Mux is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/mux-com/](https://apis.io/providers/mux-com/)** — or go straight to one of the APIs or properties below.

### APIs (38)

- [Mux Webhooks](https://apis.io/apis/mux-com/webhooks/) — Mux Webhooks deliver signed HTTP callbacks for asset, upload, live stream, and robots job lifecycle events (video.asset.created, video.asset.ready,…
- [Mux Animated Images API](https://apis.io/apis/mux-com/mux-com-animated-images-api/) — APIs for retrieving animated images from videos hosted using Mux.
- [Mux Annotations API](https://apis.io/apis/mux-com/mux-com-annotations-api/) — Annotations allow you to add notes at a specific datetime to view in the Mux Data dashboard.
- [Mux Ask Questions API](https://apis.io/apis/mux-com/mux-com-ask-questions-api/) — Ask questions about a video and get structured answers.
- [Mux Assets API](https://apis.io/apis/mux-com/mux-com-assets-api/) — An asset refers to a piece of media content that is stored or is being live streamed through the Mux system. An asset always has a duration and one or more…
- [Mux Captions and Transcripts API](https://apis.io/apis/mux-com/mux-com-captions-and-transcripts-api/) — APIs for retrieving captions and transcripts from videos hosted using Mux that have had captions generated automatically.
- [Mux Delivery Usage API](https://apis.io/apis/mux-com/mux-com-delivery-usage-api/) — The Delivery Usage API allows you to get delivery/streaming usage details for each asset and across all assets. Delivery usage details are aggregated every…
- [Mux Dimensions API](https://apis.io/apis/mux-com/mux-com-dimensions-api/) — Dimensions are the types of metadata that can be collected for a video view. Some dimensions are collected automatically based on the playback or device,…
- [Mux Direct Uploads API](https://apis.io/apis/mux-com/mux-com-direct-uploads-api/) — Direct upload allows you to push assets directly to Mux storage instead of needing to go through your own first. When you create a new direct upload, we'll…
- [Mux DRM Configurations API](https://apis.io/apis/mux-com/mux-com-drm-configurations-api/) — DRM Configurations allow you to adjust the security level of content delivered through Mux Video's Digital Rights Management (DRM) feature.
- [Mux Edit Captions API](https://apis.io/apis/mux-com/mux-com-edit-captions-api/) — Edit an existing caption track with find-and-replace edits and optional profanity censoring. This workflow is currently in beta.
- [Mux Errors API](https://apis.io/apis/mux-com/mux-com-errors-api/) — Playback errors are tracked and aggregated by Mux Data. Errors can be listed by the API, which contains data about the error code, message, and how often…
- [Mux Exports API](https://apis.io/apis/mux-com/mux-com-exports-api/) — Exports allow you to download the daily CSV files that are generated from the video views that occurred in the previous day. Please contact…
- [Mux Filters API](https://apis.io/apis/mux-com/mux-com-filters-api/) — Deprecated, please refer to the Dimensions APIs.
- [Mux Find Key Moments API](https://apis.io/apis/mux-com/mux-com-find-key-moments-api/) — Identify key moments in a video.
- [Mux Generate Chapters API](https://apis.io/apis/mux-com/mux-com-generate-chapters-api/) — Generate chapters for a video.
- [Mux Incidents API](https://apis.io/apis/mux-com/mux-com-incidents-api/) — Incidents occur when an anomaly alert is triggered in Mux Data. The Incidents API provides operations related to the raising and managing of alerting incidents.
- [Mux Jobs API](https://apis.io/apis/mux-com/mux-com-jobs-api/) — List and cancel jobs across all workflows.
- [Mux Live Streams API](https://apis.io/apis/mux-com/mux-com-live-streams-api/) — A Live Stream represents a unique live stream of video being pushed to Mux. It includes configuration details (a Stream Key) for live broadcasting…
- [Mux Metrics API](https://apis.io/apis/mux-com/mux-com-metrics-api/) — Historical metrics are used for tracking KPIs, diagnosing issues, and measuring viewers' quality of experience. Metrics are calculated using the video views…
- [Mux Moderate API](https://apis.io/apis/mux-com/mux-com-moderate-api/) — Analyze a video for inappropriate content.
- [Mux Monitoring API](https://apis.io/apis/mux-com/mux-com-monitoring-api/) — Monitoring metrics are used for operational monitoring of a video platform. The metrics are aggregated in five second intervals, across the views that are…
- [Mux Playback ID API](https://apis.io/apis/mux-com/mux-com-playback-id-api/) — Operations related to the manipulation of playback IDs, through which users are able to stream videos and live streams from Mux.
- [Mux Playback Restrictions API](https://apis.io/apis/mux-com/mux-com-playback-restrictions-api/) — Playback Restrictions allows you to set additional rules for playing videos. You can set the domains/hostnames allowed to play your videos. For instance,…
- [Mux Signing Keys API](https://apis.io/apis/mux-com/mux-com-signing-keys-api/) — Signing keys are used to sign JSON Web Tokens (JWTs) for securing certain requests, such as secure playback URLs and access to real-time viewer counts in…
- [Mux Storyboards API](https://apis.io/apis/mux-com/mux-com-storyboards-api/) — APIs for retrieving storyboards, sprites, and metadata about the storyboards from videos hosted using Mux.
- [Mux Streaming API](https://apis.io/apis/mux-com/mux-com-streaming-api/) — APIs for streaming video content via HLS and MP4 with customizable playback options.
- [Mux Summarize API](https://apis.io/apis/mux-com/mux-com-summarize-api/) — Generate a title, description, and tags for a video.
- [Mux Thumbnails API](https://apis.io/apis/mux-com/mux-com-thumbnails-api/) — APIs for retrieving still thumbnails from videos hosted using Mux.
- [Mux Transcription Vocabularies API](https://apis.io/apis/mux-com/mux-com-transcription-vocabularies-api/) — Transcription Vocabularies allows you to provide collections of phrases like proper nouns, technical jargon, and uncommon words as part of captioning…
- [Mux Translate Captions API](https://apis.io/apis/mux-com/mux-com-translate-captions-api/) — Translate captions from one language to another.
- [Mux URL Signing Keys API](https://apis.io/apis/mux-com/mux-com-url-signing-keys-api/) — A URL signing key is used as the secret when signing any Mux URL. Mux requires a [JSON Web Token](https://jwt.io/) as the value of the token query…
- [Mux Utilities API](https://apis.io/apis/mux-com/mux-com-utilities-api/) — Collection of utility methods for using Mux APIs. There's only one thing in here right now, maybe there will be more later.
- [Mux Video Views API](https://apis.io/apis/mux-com/mux-com-video-views-api/) — An individual video view tracked by Mux Data. For the full list of properties for each view please refer to the table of data fields in the [Export raw…
- [Mux View and Viewer Counts API](https://apis.io/apis/mux-com/mux-com-view-and-viewer-counts-api/) — API for retrieving the real-time count of views and viewers based on ID as collected by Mux Data.
- [Mux Playback IDs API](https://apis.io/apis/mux-com/mux-com-playback-ids-api/) — Manage playback IDs for assets.
- [Mux API](https://apis.io/apis/mux-com/mux-com-mux-api-api/) — The Mux API API from Mux — 0 operation(s) for mux api.
- [Mux Realtime API](https://apis.io/apis/mux-com/mux-com-realtime-api/) — The Mux Data Real-time API has been deprecated, please refer to the Mux Data `Monitoring` APIs which provide the same functionality. Mux Data Monitoring…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (26)

Multi-step workflows that chain operations into a business task.

- [Mux Account Delivery Usage Audit](https://apis.io/arazzos/mux-com/mux-com-account-delivery-usage-workflow/)
- [Mux AI Summarize Asset](https://apis.io/arazzos/mux-com/mux-com-ai-summarize-asset-workflow/)
- [Mux Manage Data Annotation](https://apis.io/arazzos/mux-com/mux-com-annotation-manage-workflow/)
- [Mux Add Caption Track to Asset](https://apis.io/arazzos/mux-com/mux-com-asset-add-caption-track-workflow/)
- [Mux Add Playback ID to Asset](https://apis.io/arazzos/mux-com/mux-com-asset-add-playback-id-workflow/)
- [Mux Asset Library Drilldown](https://apis.io/arazzos/mux-com/mux-com-asset-library-drilldown-workflow/)
- [Mux Generate Downloadable Static Rendition](https://apis.io/arazzos/mux-com/mux-com-asset-mp4-rendition-workflow/)
- [Mux Asset Tag and Cleanup](https://apis.io/arazzos/mux-com/mux-com-asset-tag-and-cleanup-workflow/)
- [Mux Create Asset From URL](https://apis.io/arazzos/mux-com/mux-com-create-asset-from-url-workflow/)
- [Mux Dimension Exploration](https://apis.io/arazzos/mux-com/mux-com-dimension-exploration-workflow/)
- [Mux Direct Upload to Ready Asset](https://apis.io/arazzos/mux-com/mux-com-direct-upload-to-asset-workflow/)
- [Mux Errors Impact Analysis](https://apis.io/arazzos/mux-com/mux-com-errors-impact-analysis-workflow/)
- [Mux Incident Drilldown](https://apis.io/arazzos/mux-com/mux-com-incident-drilldown-workflow/)
- [Mux Add Playback ID to Live Stream](https://apis.io/arazzos/mux-com/mux-com-live-stream-add-playback-id-workflow/)
- [Mux Live Stream Generated Subtitles](https://apis.io/arazzos/mux-com/mux-com-live-stream-generated-subtitles-workflow/)
- [Mux Live Stream Lifecycle Control](https://apis.io/arazzos/mux-com/mux-com-live-stream-lifecycle-workflow/)
- [Mux Live Stream With Simulcast Target](https://apis.io/arazzos/mux-com/mux-com-live-stream-with-simulcast-workflow/)
- [Mux Metric Breakdown Analysis](https://apis.io/arazzos/mux-com/mux-com-metric-breakdown-analysis-workflow/)
- [Mux Metric Timeseries Trend](https://apis.io/arazzos/mux-com/mux-com-metric-timeseries-trend-workflow/)
- [Mux Monitoring Metric Breakdown](https://apis.io/arazzos/mux-com/mux-com-monitoring-breakdown-workflow/)
- [Mux Configure Playback Restriction](https://apis.io/arazzos/mux-com/mux-com-playback-restriction-setup-workflow/)
- [Mux Real-Time Metric Breakdown](https://apis.io/arazzos/mux-com/mux-com-realtime-breakdown-workflow/)
- [Mux Rotate Live Stream Key](https://apis.io/arazzos/mux-com/mux-com-reset-stream-key-workflow/)
- [Mux Rotate System Signing Key](https://apis.io/arazzos/mux-com/mux-com-system-signing-key-rotation-workflow/)
- [Mux Rotate URL Signing Key](https://apis.io/arazzos/mux-com/mux-com-url-signing-key-rotation-workflow/)
- …and 1 more published on APIs.io

#### GraphQL (1)

GraphQL schemas.

- [Moved to /providers/mux-com/](https://apis.io/graphqls/mux-com/mux-com-graphql/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [mux-com](https://apis.io/servers/mux-com/mux-com/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Mux Com Agentic Access](https://apis.io/agentic-access/mux-com/mux-com-agentic-access/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Mux Com Context](https://apis.io/jsonld/mux-com/mux-com-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Mux Vocabulary](https://apis.io/vocabularies/mux-com/mux-com-vocabulary/)

#### Collections (38)

Postman and Open Collection request collections.

- [Mux API](https://apis.io/collections/mux-com/open-mux/)
- [Mux Animated Images API](https://apis.io/collections/mux-com/open-mux-com-animated-images-api/)
- [Mux Animated Images Annotations API](https://apis.io/collections/mux-com/open-mux-com-annotations-api/)
- [Mux Animated Images Ask Questions API](https://apis.io/collections/mux-com/open-mux-com-ask-questions-api/)
- [Mux Animated Images Assets API](https://apis.io/collections/mux-com/open-mux-com-assets-api/)
- [Mux Animated Images Captions and Transcripts API](https://apis.io/collections/mux-com/open-mux-com-captions-and-transcripts-api/)
- [Mux Animated Images Delivery Usage API](https://apis.io/collections/mux-com/open-mux-com-delivery-usage-api/)
- [Mux Animated Images Dimensions API](https://apis.io/collections/mux-com/open-mux-com-dimensions-api/)
- [Mux Animated Images Direct Uploads API](https://apis.io/collections/mux-com/open-mux-com-direct-uploads-api/)
- [Mux Animated Images DRM Configurations API](https://apis.io/collections/mux-com/open-mux-com-drm-configurations-api/)
- [Mux Animated Images Edit Captions API](https://apis.io/collections/mux-com/open-mux-com-edit-captions-api/)
- [Mux Animated Images Errors API](https://apis.io/collections/mux-com/open-mux-com-errors-api/)
- [Mux Animated Images Exports API](https://apis.io/collections/mux-com/open-mux-com-exports-api/)
- [Mux Animated Images Filters API](https://apis.io/collections/mux-com/open-mux-com-filters-api/)
- [Mux Animated Images Find Key Moments API](https://apis.io/collections/mux-com/open-mux-com-find-key-moments-api/)
- [Mux Animated Images Generate Chapters API](https://apis.io/collections/mux-com/open-mux-com-generate-chapters-api/)
- [Mux Animated Images Incidents API](https://apis.io/collections/mux-com/open-mux-com-incidents-api/)
- [Mux Animated Images Jobs API](https://apis.io/collections/mux-com/open-mux-com-jobs-api/)
- [Mux Animated Images Live Streams API](https://apis.io/collections/mux-com/open-mux-com-live-streams-api/)
- [Mux Animated Images Metrics API](https://apis.io/collections/mux-com/open-mux-com-metrics-api/)
- [Mux Animated Images Moderate API](https://apis.io/collections/mux-com/open-mux-com-moderate-api/)
- [Mux Animated Images Monitoring API](https://apis.io/collections/mux-com/open-mux-com-monitoring-api/)
- [Mux Animated Images Playback ID API](https://apis.io/collections/mux-com/open-mux-com-playback-id-api/)
- [Mux Video Assets Playback IDs API](https://apis.io/collections/mux-com/open-mux-com-playback-ids-api/)
- [Mux Animated Images Playback Restrictions API](https://apis.io/collections/mux-com/open-mux-com-playback-restrictions-api/)
- …and 13 more published on APIs.io

#### Overlays (36)

OpenAPI overlays, including conversational phrasing for each operation.

- [Mux Com Animated Images Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-animated-images-api-phrasing-overlay/)
- [Mux Com Annotations Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-annotations-api-phrasing-overlay/)
- [Mux Com Ask Questions Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-ask-questions-api-phrasing-overlay/)
- [Mux Com Assets Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-assets-api-phrasing-overlay/)
- [Mux Com Captions And Transcripts Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-captions-and-transcripts-api-phrasing-overlay/)
- [Mux Com Delivery Usage Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-delivery-usage-api-phrasing-overlay/)
- [Mux Com Dimensions Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-dimensions-api-phrasing-overlay/)
- [Mux Com Direct Uploads Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-direct-uploads-api-phrasing-overlay/)
- [Mux Com Drm Configurations Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-drm-configurations-api-phrasing-overlay/)
- [Mux Com Edit Captions Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-edit-captions-api-phrasing-overlay/)
- [Mux Com Errors Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-errors-api-phrasing-overlay/)
- [Mux Com Exports Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-exports-api-phrasing-overlay/)
- [Mux Com Filters Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-filters-api-phrasing-overlay/)
- [Mux Com Find Key Moments Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-find-key-moments-api-phrasing-overlay/)
- [Mux Com Generate Chapters Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-generate-chapters-api-phrasing-overlay/)
- [Mux Com Incidents Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-incidents-api-phrasing-overlay/)
- [Mux Com Jobs Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-jobs-api-phrasing-overlay/)
- [Mux Com Live Streams Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-live-streams-api-phrasing-overlay/)
- [Mux Com Metrics Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-metrics-api-phrasing-overlay/)
- [Mux Com Moderate Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-moderate-api-phrasing-overlay/)
- [Mux Com Monitoring Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-monitoring-api-phrasing-overlay/)
- [Mux Com Playback Id Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-playback-id-api-phrasing-overlay/)
- [Mux Com Playback Ids Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-playback-ids-api-phrasing-overlay/)
- [Mux Com Playback Restrictions Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-playback-restrictions-api-phrasing-overlay/)
- [Mux Com Realtime Api Phrasing Overlay](https://apis.io/overlays/mux-com/mux-com-realtime-api-phrasing-overlay/)
- …and 11 more published on APIs.io

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Mux API Rules](https://apis.io/rules/mux-com/mux-com-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Mux Com Authentication](https://apis.io/security/mux-com/mux-com-authentication/)
- [Mux Com Domain Security](https://apis.io/security/mux-com/mux-com-domain-security/)
- [Mux Com Trust Center](https://apis.io/security/mux-com/mux-com-trust-center/)
- [Mux Com Vulnerability Disclosure](https://apis.io/security/mux-com/mux-com-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Mux Com Plans Pricing](https://apis.io/plans/mux-com/mux-com-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Mux Com Rate Limits](https://apis.io/rate-limits/mux-com/mux-com-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Mux Com Finops](https://apis.io/finops/mux-com/mux-com-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.mux.com/)
- [Documentation](https://www.mux.com/docs)
- [Getting started](https://www.mux.com/docs/core/make-your-first-api-request)
- [API reference](https://www.mux.com/docs/api-reference)
- [Pricing](https://www.mux.com/pricing/video)
- [Support](https://www.mux.com/support)
- [Changelog](https://www.mux.com/docs/changelog)
- [Blog](https://www.mux.com/blog)
- [Security](https://www.mux.com/security)
- [Terms of service](https://www.mux.com/terms)
- [Privacy policy](https://www.mux.com/privacy)
- [GitHub](https://github.com/muxinc)
- [Status](https://status.mux.com/)

## API Evangelist rating

**Kin Score 65.9** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 60.1 |
| Contract governance | 25.0 |
| Operational transparency | 55.3 |
| Developer ergonomics | 79.8 |
| Access clarity | 60.5 |

**Agent readiness 43.7** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | mostly |

**Regulatory alignment 35.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/mux-com/](https://apis.io/providers/mux-com/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Mux: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/mux-com/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
