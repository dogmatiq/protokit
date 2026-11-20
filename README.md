<div align="center">

# Protokit

Protocol Buffers code generation for Dogma applications.

</div>

Protokit is a planned `protoc` plugin for generating Dogma integration alongside
standard Protocol Buffers code. The initial target is Go, with annotations
intended to support equivalent behavior in other languages later.

The agreed initial scope includes message roles and UUIDs, automatic message
registration, binary serialization, and validation adapters for Protovalidate.
Description templates and snapshot versioning need further design.

See the [design notes] for the feature decisions, constraints, and open
questions. This repository currently contains planning documentation; the
implementation has not been published here.

<!-- references -->

[design notes]: docs/design.md
