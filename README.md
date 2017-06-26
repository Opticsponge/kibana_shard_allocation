# Elasticsearch Shards Allocation Visualization
A kibana plugin adding app that visualize elasticsearch shard allocation

![image](screenshots/main.png)

## Compatibility
This plugin support kibana 5.0.x - 5.4.1.

## Installation

### Kibana 5.4.1:
```
bin/kibana-plugin install https://github.com/Opticsponge/kibana_shard_allocation/releases/tag/5.4.2
```

### Other kibana versions:
check [releases](https://github.com/asileon/kibana_shard_allocation/releases) for the required version.
if the required version is missing, try the following:
* extract the source code into a new folder named `kibana_shard_allocation` in your `kibana/plugins` folder
* edit `package.json` file and set `version` field to your kibana version

## Uninstall

### Kibana 5.x:
```
bin/kibana-plugin remove kibana_shard_allocation
```
