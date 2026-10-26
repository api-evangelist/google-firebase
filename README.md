# Google Firebase (google-firebase)

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
