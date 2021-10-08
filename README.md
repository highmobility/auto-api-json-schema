## AutoAPI JSON Schema

AutoAPI is a car data protocol developed by [High Mobility](https://www.high-mobility.com).  
It defines a common schema for different car brands, so a user of the protocol can access data from different manufacturers unified into a single schema.
More information regarding AutoAPI can be found [here](https://github.com/highmobility/auto-api).

The JSON Schema is a version of the same AutoAPI protocol, but in a different format - JSON.
More information about the JSON Schema can be found [here](https://json-schema.org).

### Usage

The schema presented here, is available to use to verify and understand the output from High Mobility's AutoAPI in JSON format.

### Structure

The schema-files are divided into separate files, categorized as _capabilities_ and _misc_.  
Different _capabilities_ are described in more detail [here](https://docs.high-mobility.com/api-references/) (starting after the _Getting started_ section).  
The _misc_ JSON Schema files are commonly used types (in capability-files) and unit types.

#### Capabilities

[ADAS](/capabilities/adas.schema.json)  
[Charging](/capabilities/charging.schema.json)
