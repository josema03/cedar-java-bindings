# Cedar Policy Bindings For Java

This is an example of how to generate the types needed to ensure type safety in Java when working with the cedar package. 

## How to generate types

1. Clone this repo
2. Make sure the json schemas in the `src/main/resources/schemas` directory are up to date. These are supposed to be the schemas produced by the original cedar policy library written in Rust.
3. Run ```$ mvn package```
4. Check the directory `target/generated-sources/jsonschema2pojo/com/cedar`. Generated types will be inside.