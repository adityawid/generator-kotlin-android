# generator-kotlin-android

[![Join the chat at https://gitter.im/generator-kotlin-android/Lobby](https://badges.gitter.im/generator-kotlin-android/Lobby.svg)](https://gitter.im/generator-kotlin-android/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url] [![Coverage Status](https://coveralls.io/repos/github/ravidsrk/generator-kotlin-android/badge.svg?branch=master)](https://coveralls.io/github/ravidsrk/generator-kotlin-android?branch=master)

> An Kotlin MVP Boilerplate to save me having to create the same project over from scratch every time! :)

<p align="center">
  <img src="http://g.recordit.co/L5selg7aIv.gif" width="250">
  <img src="http://g.recordit.co/aJOXLF6WgR.gif">
</p>

## How it works?
It provides a generator to create and maintain a android application based on the latest  frameworks and patterns used by the community.

Stack:
- [Kotlin](https://kotlinlang.org/)
- [RxJava](https://github.com/ReactiveX/RxJava) and [RxAndroid](https://github.com/ReactiveX/RxAndroid)
- [Retrofit](http://square.github.io/retrofit/) / [OkHttp](http://square.github.io/okhttp/)
- [Gson](https://github.com/google/gson)
- [Dagger 2](http://google.github.io/dagger/)
- [Butterknife](https://github.com/JakeWharton/butterknife)
- [Google Play Services](https://developers.google.com/android/guides/overview)
- [Timber](https://github.com/JakeWharton/timber)
- [Glide 3](https://github.com/bumptech/glide)
- [Stetho](http://facebook.github.io/stetho/)
- [Espresso](https://google.github.io/android-testing-support-library/) for UI tests
- [Robolectric](http://robolectric.org/) for framework specific unit tests
- [Mockito](http://mockito.org/)

## Installation

First, install [Yeoman](http://yeoman.io) and generator-kotlin-android using [npm](https://www.npmjs.com/) (we assume you have pre-installed [node.js](https://nodejs.org/)).

```bash
npm install -g yo
npm install -g generator-kotlin-android
```

Then generate your new project:

```bash
mkdir NewApp
cd NewApp
yo kotlin-android
```

### Created & Maintained By
[Ravindra Kumar](https://github.com/ravidsrk) ([@ravidsrk](https://www.twitter.com/ravidsrk))

> If you found this repo helpful or you learned something from the source code and want to thank me, consider [buying me a cup of](https://www.paypal.me/ravidsrk) :coffee:


## License

Apache-2.0 © [Ravindra Kumar](https://github.com/ravidsrk/)

[npm-image]: https://badge.fury.io/js/generator-kotlin-android.svg
[npm-url]: https://npmjs.org/package/generator-kotlin-android
[travis-image]: https://travis-ci.org/ravidsrk/generator-kotlin-android.svg?branch=master
[travis-url]: https://travis-ci.org/ravidsrk/generator-kotlin-android
[daviddm-image]: https://david-dm.org/ravidsrk/generator-kotlin-android.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/ravidsrk/generator-kotlin-android
[coveralls-image]: https://coveralls.io/repos/github/ravidsrk/generator-kotlin-android/badge.svg?branch=master
[coveralls-url]: https://coveralls.io/github/ravidsrk/generator-kotlin-android?branch=master
