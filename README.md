# StreamYard

StreamYard is a professional live streaming and recording studio in your browser. Stream directly to multiple platforms simultaneously (YouTube, Facebook, LinkedIn, Twitch, Twitter/X), interview guests, share your screen, and manage brand overlays. The StreamYard API enables programmatic management of broadcasts, destinations, and recordings.

**Human URL:** [https://streamyard.com](https://streamyard.com)  
**Base URL:** `https://api.streamyard.com`

## Links

- [Developer Portal](https://developers.streamyard.com)
- [API Documentation](https://developers.streamyard.com/docs)
- [Authentication](https://developers.streamyard.com/docs/authentication)
- [Dashboard](https://streamyard.com/dashboard)
- [Pricing](https://streamyard.com/pricing)
- [Blog](https://streamyard.com/blog)
- [Status](https://status.streamyard.com)
- [Terms of Service](https://streamyard.com/resources/terms)

## APIs

### StreamYard API

Programmatic access to manage live broadcasts, streaming destinations, and recordings. OAuth 2.0 authentication with scope-based access.

- [OpenAPI Spec](openapi/streamyard-openapi.yml)
- [Documentation](https://developers.streamyard.com/docs)

## Artifacts

### OpenAPI Specifications

| File | Description |
|---|---|
| [streamyard-openapi.yml](openapi/streamyard-openapi.yml) | StreamYard API — broadcasts, destinations, recordings |

### JSON Schema

| File | Description |
|---|---|
| [streamyard-broadcast-schema.json](json-schema/streamyard-broadcast-schema.json) | JSON Schema for StreamYard broadcast objects |

### JSON Structure

| File | Description |
|---|---|
| [streamyard-broadcast-structure.json](json-structure/streamyard-broadcast-structure.json) | Field structure for broadcast objects |

### JSON-LD Context

| File | Description |
|---|---|
| [streamyard-context.jsonld](json-ld/streamyard-context.jsonld) | JSON-LD context mapping StreamYard vocabulary to schema.org |

### Examples

| File | Description |
|---|---|
| [streamyard-create-broadcast-example.json](examples/streamyard-create-broadcast-example.json) | Create a new broadcast |
| [streamyard-list-broadcasts-example.json](examples/streamyard-list-broadcasts-example.json) | List broadcasts with destinations |

### Spectral Rules

| File | Description |
|---|---|
| [streamyard-rules.yml](rules/streamyard-rules.yml) | Spectral ruleset enforcing StreamYard API conventions |

### Naftiko Capabilities

#### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/streamyard-api.yaml](capabilities/shared/streamyard-api.yaml) | StreamYard API — broadcasts, destinations, recordings |

#### Workflow Capabilities

| File | Description |
|---|---|
| [capabilities/live-streaming.yaml](capabilities/live-streaming.yaml) | Live streaming and broadcast management workflow (10 tools) |

### Vocabulary

| File | Description |
|---|---|
| [vocabulary/streamyard-vocabulary.yml](vocabulary/streamyard-vocabulary.yml) | StreamYard domain vocabulary and live streaming terminology |

## Tags

- Broadcasting
- Live Streaming
- Multi-Streaming
- Recordings
- Video

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
