> Originally published on March 26, 2015 at the [M-Way Solutions Blog](http://blog.mwaysolutions.com/2015/03/26/generator-m-the-state-of-html5-mobile-app-development-at-m-way/).

# Generator-M: the state of HTML5 mobile app development at M-Way

![image](img/header.jpg)

Technology-wise, the past years at our HTML5 mobile app department have been very turbulent. We ditched our ambitious goals of further developing our own mobile framework and settled for much more humble goals. This has helped us become more productive, more valuable for the open source community and more attractive for our applicants. Do you want to know how? Then keep on reading!


## Contemplation

From time to time in life, in every industry, it is important to take a step away from everything, look at everything that has been and at everything that is. Reevaluate the decision you made, focus, reflect and finally take a deep breath and move ahead with new energy. The past year and a half has been such time for contemplation regarding our HTML5 mobile app development.

## Looking back

Since 2011 we have been developing our own framework for HTML5 mobile apps at M-Way. It’s called TMP, which stands for [The-M-Project](https://github.com/mwaylabs/The-M-Project).

In early versions, TMP was based on [jQuery](https://github.com/jquery/jquery) for DOM-Manipulation and [jQuery Mobile](https://github.com/jquery/jquery-mobile) to spice up the mobile apps’ user interfaces. It provided an easy to understand MVC (Model-View-Controller) architecture and even brought its own [Node.js](https://nodejs.org/)-based development tool called [Espresso](https://github.com/mwaylabs/Espresso). Espresso was able to scaffold TMP apps, run tasks, tests and deliver a live preview of your app without having to build it first. Note that this was long before [Yeoman](http://yeoman.io/) and [Grunt.js](http://gruntjs.com/), which are used perform similar tasks were released and became immensely popular in 2012/2013.

When I first started working for M-Way in late 2013, I was intrigued with TMP and wrote a *first steps* [blog article](http://blog.the-m-project.org/2013/11/11/first-steps-with-the-m-project/) about my initial experiences with TMP. This was about the time when M-Way invested heavily in the development of TMP 2.0 Absinthe which dropped jQuery Mobile in favor of a built in ui-framework, dropped its own MVC architecture in favor of [Backbone](https://github.com/jashkenas/backbone) and dropped Espresso in favor of Yeoman and Grunt to make the framework’s technology stack and its look and feel more 2014-worthy. In the course of this, TMP 2.0 brought [a ton of new features and technologies](https://github.com/mwaylabs/The-M-Project/#whats-new) to the framework like: 2-way-data binding, routing, Sass support and even a component for automatic data model synchronization between clients and servers, called [Bikini](http://www.the-m-project.org/bikini.html).

It sounded great, rich and exciting, we were all thrilled!

A few months into the development of TMP 2.0 the excitement stalled a little bit, things were taking longer than expected, the framework didn’t feel as easy-to-use and natural as it should and many of us HTML5 developers were peeking at other exciting alternatives out there. We needed to face questions of doubt:

- *”Maybe TMP 2.0 was trying to do too much?”*
- *”Why are investing in a framework when there’s great alternatives out there?”*
- *”Maybe M-Way simply can’t deliver the man-power that is needed in 2014 to stem the development of a framework that would compete against projects backed by giants like Google, Yahoo and Facebook?”*

We were stuck.

## Taking a deep breath

In early 2014 we were ready to face consequences, we benchmarked all the frameworks that seemed interesting to us against TMP 2.0. Benchmarking factors included: speed of development, performance, community size and activity, maintainability, flexibility, architecture, how easy it was to learn and how natural it felt to us as HTML5 developers. The result was speaking a clear language.

[Angular](https://angularjs.org/) blew us away in nearly all categories.

It was painful to realize that we had run into a dead end with TMP 2.0, but it was necessary in order to escape paralysis.

## Moving ahead

We accepted the fact that TMP 2.0 didn’t turn out the way we hoped, and that there are other, better-suited open-source alternatives out there.

We abandoned TMP 2.0 for our project business and made the transition to angular. Since our product team [had been using Angular since 2013](http://blog.mwaysolutions.com/2014/07/02/angularjs-in-action/), we were able to transfer knowledge quickly and build solid and performant apps at stunning speed.

In the course of switching to angular, we also realized that the decisions we made was not only one of productivity, it was also one of culture. By focussing on what’s already there we took a deeper dive into the community. We saw how other’s build software, how the communities work and most importantly we learned that it’s a lot more rewarding to contribute to an existing solutions than developing your own. It not only gives back to the community and saves you a lot of time, it also teaches you how to explain and develop your ideas and most of all it teaches you how to code better.
Everybody benefits!

In the next months we moved most of our projects to angular. Having spared a lot of time by not investing in our own technology anymore, we were able to cultivate our own processes, experimented with different components and develop a technology stack that we’re now more than confident with.

## Reaping the rewards

A few months into 2014 the desire to experiment declined and we were finding ourselves craving to somehow capture our newly gained expertise, wisdom and culture. In order to keep ourselves structured and focused but also be free to keep innovating at the same time, we started a new, much more humble open source project.

We present to you: **[Generator-M](https://github.com/mwaylabs/generator-m)**!

## Generator-M

This project channels almost everything we’ve learned in the past year and allows us to kick-start our projects in no-time. It manifests a great starting point for all our projects, provides best-practices, an awesome technology stack and great integration in our development and deployment process.

We made it open source, because we want to give back to the community that we profit from on a daily basis and without which our jobs would be a lot harder and less fun and exciting.

Only two weeks ago, we launched version 1.0.0, since we’re confident that the project now is at a state where others can benefit from it as well.

Generator-M is a [Yeoman](http://yeoman.io/) generator and allows us to build mobile apps efficiently. We are constantly evolving our ideas and bring new features to the generator regularly. Nevertheless it’s important to us that while we keep experimenting with new ideas and technologies that the generator’s core concepts evolve with expertise and not with haste. It’s not a playground-project anymore and we want to make it a valuable resource for you!
It provides patterns, features and technologies that are well established and were thoughtfully selected rather than the latest bleding-edge fancy-tech framework firework.

If you want to experience how we at M-Way build our HTML5 mobile apps, head over to the Generator-M’s [Github repository](https://github.com/mwaylabs/generator-m) or [npm package](https://www.npmjs.com/package/generator-m) to see what all the fuzz is about. Github is also the best way to get in touch with us in case you want to share your concerns, ideas and comments about Generator-M or simply want to find out what we are planning for future releases.

With this in mind: Happy Coding!
