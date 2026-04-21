# Binary Format (binary-format)
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
