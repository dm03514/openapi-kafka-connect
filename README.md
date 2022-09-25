# openapi-kafka-connect
[OpenAPI (Swagger) Definition for Kafka Connect REST API](https://docs.confluent.io/platform/current/connect/references/restapi.html)

## Usage

```
cd $(LANG_CODEGEN_DIR)
cp ../openapi-kafka-connect/.openapi-generator-ignore .
openapi-generator generate -i ../openapi-kafka-connect/kafka-connect-spec.yaml -g $(LANG) -o .
```
