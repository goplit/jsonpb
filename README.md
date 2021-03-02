# Json to protobuf and back
This is the fork of JsonPB module of gogo/protobuf 

[JsonPB GOGO version](https://github.com/gogo/protobuf/tree/master/jsonpb)

[JsonPB Golang Protobuf version](https://github.com/golang/protobuf/tree/master/jsonpb)

# Why fork
Additional options for conversion

## Int64 as number
When applications on the other end allows int64

## Any type type_url prefix manipulation
Use custom property name for `Any` property 
named `type_url` which original `jsonpb` encodes
as `@type` by default.

With this fork this property is configurable in `Marshaler` and `Unmarshaler`
structs
