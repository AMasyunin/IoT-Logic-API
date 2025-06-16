# Table of contents

* [IoT-Logic-API](README.md)
* [docs](docs/README.md)
  * [Navixy IoT Logic API](docs/Overview.md)
  * [Technical Details](docs/Technical-details.md)
  * [Websocket access to Data Stream Analyzer](docs/Websocket-access-for-DSA.md)
  * [Flow schemas](docs/flow-schemas/README.md)
    * [Flow schema structure](<docs/Flow schemas/Flow-schema-structure.md>)
    * [JSON-schema template](<docs/Flow schemas/General-JSON-schema-example.md>)
  * [Guides](docs/guides/README.md)
    * [Advanced configurations](docs/Guides/Advanced-configurations.md)
    * [Guides](docs/Guides/navixy-iot-guide.md)
    * [Sending device data to an external MQTT system](docs/Guides/scenario1.md)
    * [Managing your flows and endpoints](docs/Guides/scenario2.md)
* ```yaml
  type: builtin:openapi
  props:
    models: true
  dependencies:
    spec:
      ref:
        kind: openapi
        spec: navixy-docs-api
  ```
