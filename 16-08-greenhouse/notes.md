# Ideas for improvement
- Automatically recognize generator-m-ionic project (.yo-rc.json / config.xml)
  - get rid of: necessity of first build to discover ios & android project
- build according to greenhouse-ci.sh (deliver with project, sub-generator!)
  - get rid of: set environment variable and add greenhouse-ci.sh script
- configure certificates & publishing before second build
- which Cordova version is used? make it selectable or configurable using script
- speed up `npm i && bower i` by not discarding them every time, or npm caching on greenhouse servers
