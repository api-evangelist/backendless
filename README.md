# Backendless (backendless)

Backendless is a visual app development and backend-as-a-service (BaaS) platform that exposes a full set of REST APIs for data persistence, user management, file storage, publish-subscribe messaging, push notifications, geolocation, caching, and atomic counters, plus serverless Cloud Code (custom API services and timers). Requests are authenticated with an application id and REST API key carried in the URL path and a user-token header for authenticated sessions.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/backendless/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/backendless/refs/heads/main/apis.yml)

## Tags

- BaaS
- Backend as a Service
- Visual Development
- Low Code
- Database
- Realtime

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Backendless Data Service API

CRUD persistence over schema-backed tables - save, update, upsert, and delete single or bulk objects, plus rich search with where clauses, paging, sorting, relations, grouping, and aggregate functions.

- **Human URL:** [https://backendless.com/docs/rest/data_data_object_management.html](https://backendless.com/docs/rest/data_data_object_management.html)
- **Base URL:** `https://api.backendless.com/{app-id}/{rest-api-key}/data`

#### Tags

- Data
- Database
- CRUD
- Tables

#### Properties

- [Documentation](https://backendless.com/docs/rest/data_data_object_management.html)
- [API Reference](https://backendless.com/docs/rest/)
- [OpenAPI](openapi/backendless-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/backendless.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/backendless.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Backendless User Service API

User registration, login, logout, password recovery, email confirmation, current-user lookup, and role assignment. Login returns a user-token used as a header on subsequent authenticated requests.

- **Human URL:** [https://backendless.com/docs/rest/users_login.html](https://backendless.com/docs/rest/users_login.html)
- **Base URL:** `https://api.backendless.com/{app-id}/{rest-api-key}/users`

#### Tags

- Users
- Authentication
- Roles
- Sessions

#### Properties

- [Documentation](https://backendless.com/docs/rest/users_user_registration.html)
- [API Reference](https://backendless.com/docs/rest/)
- [OpenAPI](openapi/backendless-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/backendless.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/backendless.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Backendless File Service API

Upload, download, copy, move, rename, and delete files and directories in the hosted file repository, with directory listing and permission controls.

- **Human URL:** [https://backendless.com/docs/rest/files_file_upload.html](https://backendless.com/docs/rest/files_file_upload.html)
- **Base URL:** `https://api.backendless.com/{app-id}/{rest-api-key}/files`

#### Tags

- Files
- Storage
- Upload
- Hosting

#### Properties

- [Documentation](https://backendless.com/docs/rest/files_file_upload.html)
- [API Reference](https://backendless.com/docs/rest/)
- [OpenAPI](openapi/backendless-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/backendless.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/backendless.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Backendless Messaging and Push API

Publish-subscribe message exchange over named channels, polling-based message retrieval, mobile push notifications (singlecast/broadcast), device registration, and templated email delivery.

- **Human URL:** [https://backendless.com/docs/rest/pubsub_overview.html](https://backendless.com/docs/rest/pubsub_overview.html)
- **Base URL:** `https://api.backendless.com/{app-id}/{rest-api-key}/messaging`

#### Tags

- Messaging
- Pub Sub
- Push Notifications
- Email

#### Properties

- [Documentation](https://backendless.com/docs/rest/pubsub_general_publish_api.html)
- [API Reference](https://backendless.com/docs/rest/push_push_with_api.html)
- [OpenAPI](openapi/backendless-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/backendless.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/backendless.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Backendless Geo Service API

Geo point management organized into categories with metadata, plus radius and rectangle proximity search and relative-distance queries against stored geo points.

- **Human URL:** [https://backendless.com/docs/rest/geo_geocategories.html](https://backendless.com/docs/rest/geo_geocategories.html)
- **Base URL:** `https://api.backendless.com/{app-id}/{rest-api-key}/geo`

#### Tags

- Geo
- Geolocation
- Spatial

#### Properties

- [Documentation](https://backendless.com/docs/rest/geo_geocategories.html)
- [API Reference](https://backendless.com/docs/rest/)
- [OpenAPI](openapi/backendless-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/backendless.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/backendless.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Backendless Cache and Atomic Counters API

Server-side key/value cache with put, get, contains, expire, and delete operations, and thread-safe atomic counters supporting increment, decrement, add-and-get, get, compare-and-set, and reset.

- **Human URL:** [https://backendless.com/docs/rest/cache_overview.html](https://backendless.com/docs/rest/cache_overview.html)
- **Base URL:** `https://api.backendless.com/{app-id}/{rest-api-key}`

#### Tags

- Cache
- Counters
- Atomic

#### Properties

- [Documentation](https://backendless.com/docs/rest/cache_overview.html)
- [API Reference](https://backendless.com/docs/rest/counters_overview.html)
- [OpenAPI](openapi/backendless-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/backendless.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/backendless.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Backendless Cloud Code API

Invoke developer-defined serverless API services and methods deployed as Cloud Code, alongside event handlers and scheduled timers that run custom business logic in the Backendless runtime.

- **Human URL:** [https://backendless.com/docs/rest/doc.html](https://backendless.com/docs/rest/doc.html)
- **Base URL:** `https://api.backendless.com/{app-id}/{rest-api-key}/services`

#### Tags

- Cloud Code
- Serverless
- Custom API
- Timers

#### Properties

- [Documentation](https://backendless.com/docs/rest/doc.html)
- [API Reference](https://backendless.com/docs/rest/)
- [OpenAPI](openapi/backendless-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/backendless.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/backendless.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/Backendless)
- [LinkedIn](https://www.linkedin.com/company/backendless)
- [Website](https://backendless.com)
- [Documentation](https://backendless.com/docs/rest/)
- [Plans](plans/backendless-plans-pricing.yml)
- [Rate Limits](rate-limits/backendless-rate-limits.yml)
- [Fin Ops](finops/backendless-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
