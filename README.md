# Json to protobuf and back
This is the fork of JSONPB module of gogo/protobuf 

# What fork can do
Mainly fork is ultimately allows to use custom property name
for `Any` property named `type_url` which original `jsonpb` encodes
as `@type` by default.

With this fork this property is configurable in `Marshaler` and `Unmarshaler`
structs

# Example

```go

```
