# Drone plugin Artifactor

[![Build Status](https://ci-git.jotcdn.net/api/badges/drone/plugin-artifactor/status.svg)](https://ci-git.jotcdn.net/drone/plugin-artifactor)


## Usage

```
publish-artifactor:
  image: jotcdn/drone-artifactor
  endpoint: http://artifactor-git.jotcdn.net
  files:
    - test.*.tgz
    - ./*.txt
```
