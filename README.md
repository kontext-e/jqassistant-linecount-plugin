# jQAssistant Linecount Plugin

This is a plugin for jQAssistant that adds a linecount property to file nodes. This is the continuation of the project previously maintained at [github.com/kontext-e/jqassistant-plugins](https://github.com/kontext-e/jqassistant-plugins).

## How to install
### jQAssistant 1.12+

Use the jqassistant.yaml as described [here](https://jqassistant.github.io/jqassistant/current/) and add the following 3 lines in the plugins section:

```
    - group-id: de.kontext-e.jqassistant.plugin
      artifact-id: jqassistant.plugin.linecount
      version: 2.1.0
```

### Prior to jQAssistant 1.12

Download the desired version from maven (e.g. [here](https://mvnrepository.com/artifact/de.kontext-e.jqassistant.plugin/jqassistant.plugin.linecount)) and put the jar in the jqassistant plugins directory.