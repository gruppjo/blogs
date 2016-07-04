# Generator-M-Ionic: Now, then and tomorrow - transitioning to Typescript, Angular 2 & Ionic 2
[Generator-M-Ionic](https://github.com/mwaylabs/generator-m-ionic) is an open source collection of advanced workflows for building cross-platform HTML5 mobile apps with Ionic. This article gives a quick introduction into the generator's capabilities and refers to more elaborate resources for those willing to work with it.

## What's Generator-M-Ionic for?
<p align="center">
  <a href="https://github.com/mwaylabs/generator-m-ionic" alt="Generator-M-Ionic">
    <img width="175" src="https://raw.githubusercontent.com/mwaylabs/generator-m-ionic/dev/docs/resources/logo.png">
  </a>
</p>
> **Advanced workflows for building rock-solid Ionic apps:** develop, prototype, test, build and deliver high quality apps with Yeoman, Gulp, Bower, Angular, Cordova and of course Ionic. All in one sexy generator.

The roots of [Generator-M-Ionic](https://github.com/mwaylabs/generator-m-ionic) reach back more than two years when my team and I ([@gruppjo](https://github.com/gruppjo)) at [M-Way Solutions](http://www.mwaysolutions.com/) decided to move our HTML5 mobile app development stack to AngularJS and Ionic in [early 2014](http://blog.mwaysolutions.com/2015/03/26/generator-m-the-state-of-html5-mobile-app-development-at-m-way/). Since then [Generator-M-Ionic](https://github.com/mwaylabs/generator-m-ionic) has grown into a full-fledged collection of development tools for building large-scale enterprise apps with [Cordova](http://cordova.apache.org/), [AngularJS](https://angularjs.org/) and [Ionic](http://ionicframework.com/).

Built on top of the [Yeoman Ecosystem](http://yeoman.io/) with [Gulp](http://gulpjs.com/), [Bower](https://bower.io/) and [npm](https://www.npmjs.com/), Generator-M-Ionic offers highly efficient workflows for building apps from start to finish by wiring together a complex technology stack and by providing workflows for all important aspects of professional cross-platform HTML5 app development with Cordova, AngularJS and Ionic:

##### Code Generation
- `yo m-ionic` sets up a fine-tuned project including:
  - worry-free [Git integration](https://github.com/mwaylabs/generator-m-ionic/tree/master/docs/guides/git_integration.md)
  - a properly configured [Cordova project](https://github.com/mwaylabs/generator-m-ionic/blob/master/docs/guides/development_intro.md#using-the-cordova-cli)
  - an out of the box [sample app](https://github.com/mwaylabs/generator-m-ionic/blob/master/docs/guides/questions.md#starter-template)
  - seamless [Sass integration](https://github.com/mwaylabs/generator-m-ionic/blob/master/docs/guides/sass_integration.md)
  - easy to understand [file-structure](https://github.com/mwaylabs/generator-m-ionic/blob/master/docs/guides/file_structure.md)
- [sub generators](https://github.com/mwaylabs/generator-m-ionic/blob/master/docs/guides/sub_generators.md) create ready to use components like Angular controllers, templates, services and more

#### Development Workflows
- `gulp watch` automatically connects the frontend-stack including AngularJS, Ionic and all other bower components, stylesheets, your own Angular and Ionic components with your app and watches for changes
- `gulp --livereload "run ios"` builds an app for your device and watches for changes on your dev machine using [Browsersync](https://www.browsersync.io/)
- ... discover more useful workflows in our [Development Introduction](https://github.com/mwaylabs/generator-m-ionic/blob/master/docs/guides/development_intro.md)

#### Code Quality
- [ESLint](http://eslint.org/) together with other JSONLint runs along with all important development tasks
- `gulp karma` and `gulp protractor` capitalize on an out-of-the-box ready-to-use [Testing workflow](https://github.com/mwaylabs/generator-m-ionic/blob/master/docs/guides/testing.md)
- these integrate nicely into Continuous Integration, precommit and other hooks with [Husky](https://github.com/mwaylabs/generator-m-ionic/blob/master/docs/guides/testing_workflow.md)

#### Continuous Integration
In addition to our CI-ready build and test workflows, injecting [Build Vars](https://github.com/mwaylabs/generator-m-ionic/blob/master/docs/guides/build_vars.md) into your build and other [CI features](https://github.com/mwaylabs/generator-m-ionic/blob/master/docs/guides/programmatically_change_configxml.md) complement a successful Continuous Integration setup with Generator-M-Ionic.

#### Advanced Workflows
Handling [CORS & Proxying](https://github.com/mwaylabs/generator-m-ionic/tree/master/docs/guides/cors_proxy.md) issues, managing different sets of [App Icons and splash screens](https://github.com/mwaylabs/generator-m-ionic/tree/master/docs/guides/icons_splash_screens.md), tackling different API endpoints and other things with [Environments](https://github.com/mwaylabs/generator-m-ionic/tree/master/docs/guides/environments.md) and much more is part of the [Advanced Workflows Section](https://github.com/mwaylabs/generator-m-ionic#advanced) of our Guides.

#### Ecosystems
Creating things like backends, push services, user management, build infrastructures and others can be hard. Luckily there's ecosystems like the [Ionic Platform](http://ionic.io/), our own enterprise-targeting [Relution](https://www.relution.io/), which your Generator-M-Ionic project integrates into nicely. [Read more](https://github.com/mwaylabs/generator-m-ionic#ecosystems).

## If that wasn't enough
Check out our [Github repository](https://github.com/mwaylabs/generator-m-ionic/blob/master/docs/guides/programmatically_change_configxml.md) for the full documentation!

Besides that, we recently had the pleasure of publishing a full blog series about Generator-M-Ionic on the [Ionic Blog](http://blog.ionic.io/). Give it a go for a more tutorial-like approach to getting to know the full-value of Generator-M-Ionic:

- Advanced workflows for building rock-solid Ionic apps. Part 1: Playground
- Advanced workflows for building rock-solid Ionic apps. Part 2: Mountain
- Advanced workflows for building rock-solid Ionic apps. Part 3: Orbit

We'd love to hear your feedback!

## Transitioning

We had already grown fond of the [Yeoman Ecosystem](http://yeoman.io/) with [Gulp](http://gulpjs.com/), [Bower](https://bower.io/) and [npm](https://www.npmjs.com/) long before we started working on the generator and highly appreciate it's architecture and flexibility until today. Hence, we decided to leverage these technologies and build or own tools on top of the ones we already knew and loved.
