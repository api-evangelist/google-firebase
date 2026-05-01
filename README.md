# Google Firebase (google-firebase)
Google Firebase is a comprehensive app development platform provided by Google that offers backend services, SDKs, and REST APIs for building and scaling mobile and web applications. Its developer APIs cover real-time databases, cloud messaging (push notifications), authentication, hosting, remote configuration, and more.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/google-firebase/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Mobile, Backend as a Service, Real-Time Database, Authentication, Cloud Messaging, Hosting, Analytics, Google Cloud

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-04-28

## APIs

### Firebase Realtime Database API
The Firebase Realtime Database API provides RESTful access to Firebase's cloud-hosted NoSQL database. It enables developers to store and sync data in real time across all connected clients using JSON. The API supports reading, writing, updating, and deleting data, along with server-sent events for real-time streaming and query filtering.

**Human URL:** [https://firebase.google.com/docs/database](https://firebase.google.com/docs/database)


#### Tags:

 - Real-Time, NoSQL, Database, JSON

#### Properties

- [Documentation](https://firebase.google.com/docs/reference/rest/database)
- [OpenAPI](openapi/firebase-realtime-database-openapi.yml)
- [JSONSchema](json-schema/google-firebase-database-node-schema.json)

### Firebase Cloud Messaging API (FCM)
The Firebase Cloud Messaging API enables developers to send notifications and data messages to client apps on Android, iOS, and the web. The HTTP v1 API provides per-platform message customization, topic messaging, device group messaging, and delivery tracking.

**Human URL:** [https://firebase.google.com/docs/cloud-messaging](https://firebase.google.com/docs/cloud-messaging)


#### Tags:

 - Push Notifications, Messaging, Mobile

#### Properties

- [Documentation](https://firebase.google.com/docs/reference/fcm/rest/v1/projects.messages)
- [OpenAPI](openapi/firebase-cloud-messaging-openapi.yml)
- [JSONSchema](json-schema/google-firebase-fcm-message-schema.json)

### Firebase Authentication REST API
The Firebase Authentication REST API enables developers to manage user authentication using email/password, phone, and federated identity providers such as Google, Facebook, and Apple. The API supports creating and signing in users, verifying tokens, managing user accounts, sending verification emails, and password resets through the Identity Toolkit endpoints.

**Human URL:** [https://firebase.google.com/docs/auth](https://firebase.google.com/docs/auth)


#### Tags:

 - Authentication, Identity, Users

#### Properties

- [Documentation](https://firebase.google.com/docs/reference/rest/auth)

### Firebase Hosting REST API
The Firebase Hosting REST API allows developers to programmatically manage web hosting deployments on Firebase. It supports creating new releases, managing site versions, uploading files, configuring custom domains, and managing release channels for preview deployments.

**Human URL:** [https://firebase.google.com/docs/hosting](https://firebase.google.com/docs/hosting)


#### Tags:

 - Hosting, Web, Deployment

#### Properties

- [Documentation](https://firebase.google.com/docs/reference/hosting/rest)

### Firebase Remote Config API
The Firebase Remote Config API enables developers to change the behavior and appearance of their apps without requiring users to download an update. The API allows publishing new Remote Config templates, managing conditions and parameters, and rolling back to previous configurations.

**Human URL:** [https://firebase.google.com/docs/remote-config](https://firebase.google.com/docs/remote-config)


#### Tags:

 - Configuration, Feature Flags, Remote Config

#### Properties

- [Documentation](https://firebase.google.com/docs/reference/remote-config/rest)

## Common Properties

- [GettingStarted](https://firebase.google.com/docs)
- [Pricing](https://firebase.google.com/pricing)
- [Authentication](https://firebase.google.com/docs/admin/setup)
- [Console](https://console.firebase.google.com)
- [SDKs](https://firebase.google.com/docs/libraries)
- [Support](https://firebase.google.com/support)
- [Status](https://status.firebase.google.com)
- [JSON-LD](json-ld/google-firebase-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
