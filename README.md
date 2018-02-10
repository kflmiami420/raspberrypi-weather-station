# project-template
Template for projects

TODO: Enter the more description here.

# Supported Platforms

TODO: List your supported platforms.

# Contents
Name | Description
-----|------------
`bom.md` | Bill of Materials - List of parts, counts, approximate prices and where to find.
`drawings/`|Mockups, SketchUp Files
`schematics/`| Fritzing Schematics for electronics
`README.md`|This file
`LICENSE`|Apache 2.0 License



## Attributes
Key| Type | Description | Default
---|------|-------------|--------
`-a`| Boolean | whether to include bacon | `true`


# Usage

## default


```json
{
  "item": [
    "otheritem"
  ]
}
```

# Python Packages
- pip3 install pyyaml 

# Components
- Leverages gitlab and pipelines to do tasks
- Started with Database is Postgresql and the pgadmin interface to get GUI
representation.
- Moved to TSDB (Time Series Database) for better trending, anomaly detection, etc.


# License and Authors

Author:: Kevin Kingsbury ([@kmkingsbury](https://twitter.com/kmkingsbury))

Apache 2.0
