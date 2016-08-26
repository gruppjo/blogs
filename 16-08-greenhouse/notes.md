# Ideas for improvement

## Greenhouse
- Automatically recognize generator-m-ionic project & platforms (.yo-rc.json / config.xml) without having to build first
  - get rid of: necessity of first build to discover ios & android project
- build according to greenhouse-ci.sh (deliver with project, sub-generator!)
  - get rid of: set environment variable and add greenhouse-ci.sh script
- that would allow the certificates to be configured immediately
- allow to configure publishing before second build
- speed up `npm i && bower i` by not discarding them every time, or npm caching on greenhouse servers
- which Cordova version is used? make it selectable or configurable using script

## Relution
- Introduction Videos/Documentation - User Centric
- why do we need provisioning profile and signing certificate
- Login with Github
