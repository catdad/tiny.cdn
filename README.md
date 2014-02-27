# Tiny CDN

Hi. Welcome to my little CDN. This is a place where I host my libraries, so that you may use them quickly without needing to host them natively. If you are looking for one of the major libraries, try the [Google Hosted Libraries](https://developers.google.com/speed/libraries/devguide) or maybe [cdnjs](http://cdnjs.com/). If you are interested in setting up a CDN for your projects, I will have a guide to set up one of these bad boys soon.

## General Usage

The structure of CDN is as such:

	//catdad.github.io/tiny.cdn/lib/{name}/{version}/{file}

The latest version of each library will always be available under the `latest` version, with previous versions listed by number. Note that the latest version may change, so if you are adamant about using a specific version, link to that version instead of `latest`.

## Libraries

### [tiny.toast](https://github.com/catdad/tiny.toast)

	<script src="//catdad.github.io/tiny.cdn/lib/toast/latest/toast.min.js"></script>