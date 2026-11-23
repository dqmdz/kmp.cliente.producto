# Changelog

All notable changes to this project are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2026-11-23

### Added

- Kotlin Multiplatform client targeting Android, iOS (device and simulator on
  arm64), Desktop (JVM), and Web (JS and Wasm).
- Product list screen built with Compose Multiplatform Material 3, with a
  Voyager tab navigator, a refresh action, and a loading indicator.
- Ktor HTTP client with JSON content negotiation and a configurable API base URL
  (defaults to `http://10.0.2.2:8080`) used to fetch `GET /products`.
- Serializable `Product` model with `id`, `description`, and `price` fields.
- Internet permission for the Android target.
