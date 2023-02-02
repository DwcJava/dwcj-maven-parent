# DWCJ Maven Parent

This maven parent is intended to make it convenient to start
base project within the organization DWCJ.

## Manual Version Increment

The version upgrade for the major version can be achieved by using:

```shell
mvn build-helper:parse-version versions:set@major 
```
The version upgrade for the minor version can be achieved by using:
```shell
mvn build-helper:parse-version versions:set@minor 
```
and the patch version increment can be achieved by:
```shell
mvn build-helper:parse-version versions:set@patch 
```
