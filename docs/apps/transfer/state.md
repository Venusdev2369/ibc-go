<!--
order: 2
-->

# State

The IBC transfer application module keeps state of the port to which the module is binded and the denomination trace information as outlined in [ADR 001](../../architecture/adr-001-coin-source-tracing.md).

- `Port`: `0x01 -> ProtocolBuffer(string)`
- `DenomTrace`: `0x02 | []bytes(traceHash) -> ProtocolBuffer(DenomTrace)`
