# Binary Format (binary-format)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Binary format refers to data encoding and serialization methods that use binary rather than text representations, including formats like Protocol Buffers, MessagePack, Avro, Thrift, CBOR, and others used in APIs and data storage systems for efficiency. Binary formats offer significant advantages over text-based formats in terms of size, parsing speed, and type safety.

## Tags:

 - Binary Format, Data Encoding, Protocol Buffers, Serialization, MessagePack, Apache Avro, Apache Thrift, CBOR

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-21

## Formats

| Name | Description |
|------|-------------|
| Protocol Buffers (protobuf) | Google's language-neutral, platform-neutral extensible serialization format with schema-first design. |
| MessagePack | Efficient binary serialization format that is JSON-compatible with smaller encoding size. |
| Apache Avro | Row-oriented remote procedure call and data serialization framework developed in Apache Hadoop. |
| Apache Thrift | Facebook-originated framework for scalable cross-language services development with binary transport. |
| CBOR | IETF RFC 8949 binary data format based on JSON data model with compact encoding. |
| FlatBuffers | Google's cross-platform serialization library for memory-efficient access without parsing. |
| Cap'n Proto | Ultra-fast data interchange format and RPC system with zero-copy reads. |
| Apache Arrow | Cross-language columnar memory format for flat and hierarchical data. |

## Use Cases

| Name | Description |
|------|-------------|
| High-Performance API Communication | Using binary serialization to reduce payload size and parsing overhead in API calls. |
| gRPC Service Definition | Defining gRPC service contracts using Protocol Buffers IDL. |
| Event Streaming | Encoding Kafka and event streaming messages using Avro with Schema Registry. |
| IoT Data Transmission | Using compact binary formats like CBOR or MessagePack for bandwidth-constrained IoT devices. |
| Columnar Data Processing | Using Apache Arrow for zero-copy analytics across language boundaries. |
| Microservice Communication | Replacing JSON/XML with binary formats for internal microservice RPC efficiency. |

## Conformance

| Standard | Description |
|----------|-------------|
| RFC 8949 - CBOR | IETF standard for Concise Binary Object Representation. |
| Protocol Buffers Language Guide | Google's specification for Protocol Buffers schema definition language. |
| Apache Avro Specification | Apache Software Foundation specification for the Avro serialization format. |

## Vocabulary

| Term | Definition |
|------|------------|
| Schema | Formal definition of data structure used by binary format encoders/decoders. |
| Serialization | Converting in-memory data structures into binary byte sequences for transmission or storage. |
| Deserialization | Reconstructing in-memory data structures from binary byte sequences. |
| IDL | Interface Definition Language used to define data schemas and service interfaces. |
| Wire Format | The binary encoding used when data is transmitted over a network. |
| Schema Evolution | Ability to add, remove, or modify schema fields while maintaining backward/forward compatibility. |
| Varint | Variable-length integer encoding used by Protocol Buffers for compact integer storage. |

## References

- [Protocol Buffers](https://protobuf.dev)
- [MessagePack](https://msgpack.org)
- [Apache Avro](https://avro.apache.org)
- [Apache Thrift](https://thrift.apache.org)
- [CBOR](https://cbor.io)
- [RFC 8949](https://datatracker.ietf.org/doc/html/rfc8949)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
