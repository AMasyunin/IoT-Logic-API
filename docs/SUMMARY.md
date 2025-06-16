# Table of contents

* [Navixy IoT Logic API](README.md)
* [Technical details](Technical-details.md)
* [Websocket access to Data Stream Analyzer](Websocket-access-for-DSA.md)
* [Flow schemas](flow-schemas/README.md)
  * [Flow schema structure](<Flow schemas/Flow-schema-structure.md>)
  * [JSON-schema template](<Flow schemas/General-JSON-schema-example.md>)
* [Guides](guides/README.md)
  * [Advanced configurations](Guides/Advanced-configurations.md)
  * [Guides](Guides/navixy-iot-guide.md)
  * [Sending device data to an external system](Guides/scenario1.md)
  * [Managing your flows and endpoints](Guides/scenario2.md)

## Resources

* [Navixy IoT Logic API reference](resources/navixy-iot-logic-api-reference/README.md)
  * ```yaml
    type: builtin:openapi
    props:
      models: true
    dependencies:
      spec:
        ref:
          kind: openapi
          spec: iot-logic
    ```
