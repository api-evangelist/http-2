# HTTP/2 (http-2)
HTTP/2 is the second major version of the Hypertext Transfer Protocol, defined by the IETF in RFC 7540 and standardized in 2015. It optimizes use of network resources and reduces perceived latency by introducing a binary framing layer over a single TCP connection, with full request and response multiplexing across independent bidirectional streams. HTTP/2 uses HPACK header compression to eliminate redundant header data, credit-based flow control via WINDOW_UPDATE frames, stream prioritization through dependencies and weights, and server push via PUSH_PROMISE frames to proactively deliver anticipated resources. Core frame types include DATA, HEADERS, PRIORITY, RST_STREAM, SETTINGS, PUSH_PROMISE, PING, and GOAWAY, with the protocol preserving the existing HTTP semantics of methods, status codes, and headers while transforming how they are transported on the wire.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/http-2/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Binary Framing, HPACK, HTTP, HTTP/2, IETF, Multiplexing, Networking, Performance, Protocol, RFC 7540, Server Push

## Timestamps

- **Created:** 2025
- **Modified:** 2026-04-28

## Common Properties

- [Reference](https://httpwg.org/specs/rfc7540.html)
- [Website](https://http2.github.io/)
- [HPACK Specification](https://httpwg.org/specs/rfc7541.html)
- [Wikipedia](https://en.wikipedia.org/wiki/HTTP/2)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
