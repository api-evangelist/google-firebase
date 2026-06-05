# Google Firebase (google-firebase)

Google Firebase is a comprehensive app development platform that provides backend services, SDKs, and APIs for building and scaling mobile and web applications, including authentication, real-time databases, cloud messaging, hosting, and analytics.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/google-firebase/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/google-firebase/refs/heads/main/apis.yml)

## Tags

- Analytics
- Authentication
- Backend as a Service
- Cloud Messaging
- Google Cloud
- Hosting
- Mobile
- Real-Time Database

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-05-19

## APIs

### Firebase Realtime Database API

The Firebase Realtime Database API provides RESTful access to Firebase's cloud-hosted NoSQL database. It enables developers to store and sync data in real time across all connected clients using JSON. The API supports reading, writing, updating, and deleting data, along with server-sent events for real-time streaming and query filtering.

- **Human URL:** [https://firebase.google.com/docs/database](https://firebase.google.com/docs/database)
- **Base URL:** `https://firebaseio.com`

#### Tags

- Database
- JSON
- NoSQL
- Real-Time

#### Properties

- [Documentation](https://firebase.google.com/docs/reference/rest/database)
- [OpenAPI](openapi/firebase-realtime-database-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/firebase-realtime-database.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/firebase-realtime-database.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/google-firebase-database-node-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Firebase Cloud Messaging API (FCM)

The Firebase Cloud Messaging API enables developers to send notifications and data messages to client apps on Android, iOS, and the web. The HTTP v1 API provides per-platform message customization, topic messaging, device group messaging, and delivery tracking. It uses OAuth 2.0 for authentication and supports both notification and data payloads.

- **Human URL:** [https://firebase.google.com/docs/cloud-messaging](https://firebase.google.com/docs/cloud-messaging)
- **Base URL:** `https://fcm.googleapis.com`

#### Tags

- Messaging
- Mobile
- Push Notifications

#### Properties

- [Documentation](https://firebase.google.com/docs/reference/fcm/rest/v1/projects.messages)
- [OpenAPI](openapi/firebase-cloud-messaging-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/firebase-cloud-messaging.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/firebase-cloud-messaging.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/google-firebase-fcm-message-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Firebase Authentication REST API

The Firebase Authentication REST API enables developers to manage user authentication using email/password, phone, and federated identity providers such as Google, Facebook, and Apple. The API supports creating and signing in users, verifying tokens, managing user accounts, sending verification emails, and password resets through the Identity Toolkit endpoints.

- **Human URL:** [https://firebase.google.com/docs/auth](https://firebase.google.com/docs/auth)
- **Base URL:** `https://identitytoolkit.googleapis.com`

#### Tags

- Authentication
- Identity
- Users

#### Properties

- [Documentation](https://firebase.google.com/docs/reference/rest/auth)
- [Postman Collection](collections/firebase-cloud-messaging.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/firebase-cloud-messaging.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/firebase-realtime-database.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/firebase-realtime-database.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Firebase Hosting REST API

The Firebase Hosting REST API allows developers to programmatically manage web hosting deployments on Firebase. It supports creating new releases, managing site versions, uploading files, configuring custom domains, and managing release channels for preview deployments.

- **Human URL:** [https://firebase.google.com/docs/hosting](https://firebase.google.com/docs/hosting)
- **Base URL:** `https://firebasehosting.googleapis.com`

#### Tags

- Deployment
- Hosting
- Web

#### Properties

- [Documentation](https://firebase.google.com/docs/reference/hosting/rest)
- [Postman Collection](collections/firebase-cloud-messaging.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/firebase-cloud-messaging.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/firebase-realtime-database.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/firebase-realtime-database.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Firebase Remote Config API

The Firebase Remote Config API enables developers to change the behavior and appearance of their apps without requiring users to download an update. The API allows publishing new Remote Config templates, managing conditions and parameters, and rolling back to previous configurations.

- **Human URL:** [https://firebase.google.com/docs/remote-config](https://firebase.google.com/docs/remote-config)
- **Base URL:** `https://firebaseremoteconfig.googleapis.com`

#### Tags

- Configuration
- Feature Flags
- Remote Config

#### Properties

- [Documentation](https://firebase.google.com/docs/reference/remote-config/rest)
- [Postman Collection](collections/firebase-cloud-messaging.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/firebase-cloud-messaging.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/firebase-realtime-database.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/firebase-realtime-database.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/firebase)
- [LinkedIn](https://www.linkedin.com/showcase/firebase)
- [Getting Started](https://firebase.google.com/docs)
- [Pricing](https://firebase.google.com/pricing)
- [Authentication](https://firebase.google.com/docs/admin/setup)
- [Console](https://console.firebase.google.com)
- [S D Ks](https://firebase.google.com/docs/libraries)
- [Support](https://firebase.google.com/support)
- [Status Page](https://status.firebase.google.com)
- [JSON-LD](json-ld/google-firebase-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Integrations](https://firebase.google.com/integrations)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
