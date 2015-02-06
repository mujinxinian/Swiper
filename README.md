[![Build Status](https://travis-ci.org/nolimits4web/Swiper.svg?branch=master)](https://travis-ci.org/nolimits4web/Swiper)
[![devDependency Status](https://david-dm.org/nolimits4web/swiper/dev-status.svg)](https://david-dm.org/nolimits4web/swiper#info=devDependencies)
[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=nolimits4web&url=https://github.com/nolimits4web/swiper/&title=Framework7&language=JavaScript&tags=github&category=software)

Swiper
==========

Swiper - is the free and ultra lightweight mobile touch slider with hardware accelerated transitions (where supported) and amazing native behavior. It is intended to use in mobile websites, mobile web apps, and mobile native apps. Designed mostly for iOS, but also works on Android and latest Desktop browsers. Swiper is created by iDangero.us

## Getting Started
  * [Getting Started Guide](http://www.idangero.us/swiper/get-started/)

## Dist vs Build versions

On production use files (JS and CSS) only from `dist/` folder, there will be the most stable versions, `build/` folder is only for development purpose

## Build

Swiper uses `gulp` to build a development (build) and dist versions.

First you need to have `gulp-cli` which you should install globally.

```
$ npm install --global gulp
```

Then install all dependencies, in repo's root:

```
$ npm install
```

And build development version of Swiper:
```
$ gulp build
```

The result is available in `build/` folder.

## Dist/Release

After you have made build:

```
$ gulp dist
```

Distributable version will available in `dist/` folder.

## Contributing

All changes should be commited to `src/` files. Swiper uses LESS for CSS compliations, and concatenated JS files (look at gulpfile.js for concat files order)

## Forum

If you have questions about Swiper or want to help others you are welcome to special forum at http://www.idangero.us/swiper/forum/

## Docs

Documentation available at http://idangero.us/swiper/api/