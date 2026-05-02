# MockServer (mockserver)

MockServer enables easy mocking of any system you integrate with via HTTP or HTTPS (services, websites, etc.) with clients in Java, JavaScript, and Ruby and a simple REST API. MockServer can be used to mock APIs that are not yet fully developed, isolate the system under test for reliable testing, simulate slow or faulty endpoints, and record / replay requests.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/mockserver/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

 - Mocking, Mock Server, Testing, Service Virtualization, HTTP, REST API, Platform

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-04-28

## APIs

### MockServer

MockServer is a flexible open-source tool for mocking and proxying HTTP and HTTPS requests. It exposes a simple REST control plane for creating expectations, verifying received requests, retrieving recorded traffic, and managing the running mock or proxy process.

**Human URL:** [https://www.mock-server.com/](https://www.mock-server.com/)
**Base URL:** `http://localhost:1080/`

#### Tags

 - Mocking, Mock Server, Testing, Proxy, HTTP

#### Properties

- [Documentation](https://www.mock-server.com/)
- [Getting Started](https://www.mock-server.com/mock_server/getting_started.html)
- [GitHub Repository](https://github.com/mock-server/mockserver)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/mockserver/refs/heads/main/openapi/mockserver-openapi-original.yml)

## OpenAPI

The MockServer control-plane REST API is defined in this repository:

- `openapi/mockserver-openapi-original.json`
- `openapi/mockserver-openapi-original.yml`

Endpoints (all `PUT`):

- `/mockserver/expectation` - create expectations
- `/mockserver/openapi` - create expectations from OpenAPI or Swagger
- `/mockserver/clear` - clear matching expectations and recorded requests
- `/mockserver/reset` - clear all expectations and recorded requests
- `/mockserver/retrieve` - retrieve recorded requests, expectations, or logs
- `/mockserver/verify` - verify a request was received a specific number of times
- `/mockserver/verifySequence` - verify a sequence of requests was received in order
- `/mockserver/status` - return listening ports
- `/mockserver/bind` - bind additional listening ports
- `/mockserver/stop` - stop the running process

## Common Properties

- [Website](https://www.mock-server.com/)
- [Documentation](https://www.mock-server.com/)
- [GitHub Organization](https://github.com/mock-server)
- [Getting Started](https://www.mock-server.com/mock_server/getting_started.html)
- [Issues](https://github.com/mock-server/mockserver/issues)
- [License](https://github.com/mock-server/mockserver/blob/master/LICENSE.md)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
