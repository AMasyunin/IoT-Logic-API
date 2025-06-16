# Table of contents

* [Navixy IoT Logic API](README.md)
* [Technical details](Technical-details.md)
* [Websocket access to Data Stream Analyzer](Websocket-access-for-DSA.md)
* [Flow schemas](flow-schemas/README.md)
  * [Flow schema structure](<Flow schemas/Flow-schema-structure.md>)
  * [JSON-schema template](<Flow schemas/General-JSON-schema-example.md>)
* [Guides](navixy-iot-guide/README.md)
  * [Sending device data to an external system](navixy-iot-guide/scenario1.md)
  * [Managing your flows and endpoints](navixy-iot-guide/scenario2.md)
  * [Advanced configurations](navixy-iot-guide/advanced-configurations.md)

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
