# Mux (mux-com)

Mux is a video infrastructure platform that gives developers an end-to-end API for ingesting, encoding, storing, delivering, and analyzing video. The platform spans Mux Video (on-demand and live streaming), Mux Data (quality-of-experience analytics), Mux Robots (AI workflows for captions, chapters, summarization, and moderation), and Mux Player (drop-in playback components). Mux exposes a unified REST API at api.mux.com plus delivery hosts at stream.mux.com, image.mux.com, and stats.mux.com, backed by official SDKs in Node, Python, Ruby, PHP, Go, and Elixir, a CLI, and player integrations across web, iOS, Android, Roku, and major HTML5 players.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/mux-com/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

- Video Infrastructure, Video Streaming, Live Streaming, Video Analytics, Video AI, Encoding

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Mux Video API
The Mux Video API manages the lifecycle of on-demand video, including Assets, Direct Uploads, Playback IDs, URL Signing Keys, Playback Restrictions, DRM Configurations, Transcription Vocabularies, and Delivery Usage. Developers can create assets from source URLs or chunked direct uploads, generate secure playback IDs (public, signed, or DRM-protected), and retrieve playback manifests, thumbnails, GIFs, and storyboards through stream.mux.com and image.mux.com.

**Human URL:** [https://www.mux.com/docs/api-reference](https://www.mux.com/docs/api-reference)
**Base URL:** `https://api.mux.com`

#### Tags:
- Video, Encoding, Assets, Direct Uploads, Playback

#### Properties
- [Documentation](https://www.mux.com/docs/core/stream-video-files)
- [APIReference](https://www.mux.com/docs/api-reference)
- [OpenAPI](openapi/mux-openapi.yml)

### Mux Live Streaming API
Mux Live Streaming creates managed RTMP and SRT ingest endpoints (rtmp://global-live.mux.com:5222/app) with reusable stream keys, simulcast targets for restreaming to YouTube, Twitch, and other platforms, and live-to-VOD recordings. The API supports standard and low-latency live, auto-generated live captions, live stream health monitoring, and disable/enable operations for per-event lifecycle management.

**Human URL:** [https://www.mux.com/docs/guides/start-live-streaming](https://www.mux.com/docs/guides/start-live-streaming)
**Base URL:** `https://api.mux.com`

#### Tags:
- Live Streaming, RTMP, SRT, Low Latency

#### Properties
- [Documentation](https://www.mux.com/docs/guides/start-live-streaming)
- [APIReference](https://www.mux.com/docs/api-reference#tag/Live-Streams)
- [OpenAPI](openapi/mux-openapi.yml)

### Mux Data API
The Mux Data API exposes video quality-of-experience analytics including Video Views, Errors, Filters, Dimensions, Exports, Metrics, Monitoring, Real-Time data, Incidents, and Annotations. Customers instrument their players with Mux Data SDKs (web, iOS, Android, Roku, Chromecast, ExoPlayer, AVPlayer, JWPlayer, THEOplayer) and query aggregated playback quality, viewer engagement, rebuffering, startup time, and error rates through this API.

**Human URL:** [https://www.mux.com/docs/core/monitor-your-video-streaming-performance](https://www.mux.com/docs/core/monitor-your-video-streaming-performance)
**Base URL:** `https://api.mux.com`

#### Tags:
- Video Analytics, Quality Of Experience, Monitoring, Metrics

#### Properties
- [Documentation](https://www.mux.com/docs/core/monitor-your-video-streaming-performance)
- [APIReference](https://www.mux.com/docs/api-reference#tag/Video-Views)
- [OpenAPI](openapi/mux-openapi.yml)

### Mux Stream Delivery API
The Mux Stream Delivery API serves HLS and DASH playback manifests, captions, transcripts, and redundant media segments from stream.mux.com keyed on Playback IDs. It honors signed playback tokens, DRM license handshakes, and playback restrictions configured through the Video API to enforce domain, geo, and user-agent rules.

**Human URL:** [https://www.mux.com/docs/guides/play-your-videos](https://www.mux.com/docs/guides/play-your-videos)
**Base URL:** `https://stream.mux.com`

#### Tags:
- Delivery, HLS, DASH, Playback

#### Properties
- [Documentation](https://www.mux.com/docs/guides/play-your-videos)
- [APIReference](https://www.mux.com/docs/api-reference#tag/Streaming)
- [OpenAPI](openapi/mux-openapi.yml)

### Mux Image API
The Mux Image API generates on-the-fly thumbnails (JPG, PNG, WebP), animated GIFs, and VTT storyboard sprites for any asset playback ID via image.mux.com. URL parameters control time offset, width, height, fit mode, FPS, and duration, enabling responsive video posters and scrub-bar previews without server-side image processing.

**Human URL:** [https://www.mux.com/docs/guides/get-images-from-a-video](https://www.mux.com/docs/guides/get-images-from-a-video)
**Base URL:** `https://image.mux.com`

#### Tags:
- Thumbnails, Storyboards, Animated Images

#### Properties
- [Documentation](https://www.mux.com/docs/guides/get-images-from-a-video)
- [APIReference](https://www.mux.com/docs/api-reference#tag/Thumbnails)
- [OpenAPI](openapi/mux-openapi.yml)

### Mux Robots AI API
Mux Robots is an asynchronous job API for running AI workflows against video assets. Robots include Ask Questions (Q&A over a video), Edit Captions, Find Key Moments, Generate Chapters, Moderate (NSFW and violence detection), Summarize, and Translate Captions. Jobs follow a pending then processing then completed lifecycle and emit robots.job.* webhook events when complete.

**Human URL:** [https://www.mux.com/docs/guides/mux-robots](https://www.mux.com/docs/guides/mux-robots)
**Base URL:** `https://api.mux.com`

#### Tags:
- Video AI, Captions, Summarization, Content Moderation, Chaptering

#### Properties
- [Documentation](https://www.mux.com/docs/guides/mux-robots)
- [APIReference](https://www.mux.com/docs/api-reference#tag/Jobs)
- [OpenAPI](openapi/mux-openapi.yml)

### Mux System API
The Mux System API manages account-wide resources such as Signing Keys used to mint short-lived JWTs for signed playback URLs, thumbnails, and storyboards, plus utility endpoints (e.g., dimensions and account-level metadata) used across Video and Data products.

**Human URL:** [https://www.mux.com/docs/api-reference#tag/Signing-Keys](https://www.mux.com/docs/api-reference#tag/Signing-Keys)
**Base URL:** `https://api.mux.com`

#### Tags:
- Signing Keys, Account Management, Utilities

#### Properties
- [Documentation](https://www.mux.com/docs/guides/signing-jwts)
- [APIReference](https://www.mux.com/docs/api-reference#tag/Signing-Keys)
- [OpenAPI](openapi/mux-openapi.yml)

### Mux Webhooks
Mux Webhooks deliver signed HTTP callbacks for asset, upload, live stream, and robots job lifecycle events (video.asset.created, video.asset.ready, video.live_stream.active, video.upload.asset_created, robots.job.completed, and many more). Each delivery carries a Mux-Signature header (HMAC-SHA256 over the raw body and a per-endpoint secret) and includes attempt history visible in the dashboard.

**Human URL:** [https://www.mux.com/docs/webhook-reference](https://www.mux.com/docs/webhook-reference)
**Base URL:** `https://api.mux.com`

#### Tags:
- Webhooks, Events, Notifications

#### Properties
- [Documentation](https://www.mux.com/docs/system/make-api-requests#webhook-security)
- [APIReference](https://www.mux.com/docs/webhook-reference)

## Common Properties

- [Website](https://www.mux.com/)
- [Documentation](https://www.mux.com/docs)
- [API Reference](https://www.mux.com/docs/api-reference)
- [Getting Started](https://www.mux.com/docs/core/make-your-first-api-request)
- [Authentication](https://www.mux.com/docs/guides/signing-jwts)
- [Dashboard / Console](https://dashboard.mux.com/)
- [Sign Up](https://dashboard.mux.com/signup)
- [Pricing](https://www.mux.com/pricing/video)
- [Changelog](https://www.mux.com/docs/changelog)
- [Blog](https://www.mux.com/blog)
- [Status Page](https://status.mux.com/)
- [Support](https://www.mux.com/support)
- [Terms of Service](https://www.mux.com/terms)
- [Privacy Policy](https://www.mux.com/privacy)
- [Security](https://www.mux.com/security)
- [GitHub Organization](https://github.com/muxinc)
- [LinkedIn](https://www.linkedin.com/company/mux/)
- [X (Twitter)](https://x.com/MuxHQ)
- [YouTube](https://www.youtube.com/@MuxHQ)
- [Node SDK](https://github.com/muxinc/mux-node-sdk)
- [Python SDK](https://github.com/muxinc/mux-python)
- [Ruby SDK](https://github.com/muxinc/mux-ruby)
- [PHP SDK](https://github.com/muxinc/mux-php)
- [Go SDK](https://github.com/muxinc/mux-go)
- [Elixir SDK](https://github.com/muxinc/mux-elixir)
- [Mux CLI](https://github.com/muxinc/cli)
- [UpChunk (Chunked Upload Library)](https://github.com/muxinc/upchunk)
- [Mux Elements (Web Components)](https://github.com/muxinc/elements)
- [Media Chrome (Player Controls)](https://github.com/muxinc/media-chrome)
- [next-video (Next.js Integration)](https://github.com/muxinc/next-video)
- [Mux Data SDK for AVPlayer (iOS)](https://github.com/muxinc/mux-stats-sdk-avplayer)
- [Mux Data SDK for ExoPlayer (Android)](https://github.com/muxinc/mux-stats-sdk-exoplayer)
- [Swift Upload SDK](https://github.com/muxinc/swift-upload-sdk)
- [Mux Player Swift](https://github.com/muxinc/mux-player-swift)
- [LLMs.txt](https://www.mux.com/llms.txt)

## Maintainers

- **FN:** Kin Lane
- **Email:** kin@apievangelist.com
