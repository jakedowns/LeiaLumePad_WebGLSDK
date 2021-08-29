# Leia Inc. Lume Pad / RED Hydrogen One WebGL SDK Demo

Disclaimer: I do not own or claim to own any rights to this software. I am simply uploading it so that it might be easier for other devs like my self to discover and work with it.
If it needs to be taken down, please let me know.

I was having trouble getting this demo running, so i modified it to use laravel-mix (a simplified wrapper for webpack)

To run this demo:
1. npm install
1. npm run mix / npm run watch (see: laravel-mix documentation for more info)
1. in another terminal window, use something like `npx http-server` or your http server of choice to serve the files

---

as of this writing, npm i `leiawebglsdk` in the official leialoft docs > WebGL SDK section points to a 404-ing npm package
instead, i found `sevensummitswebglsdkdemo` which seems to work (tho has no github repo associated with it)
rather than npm installing that package, i've left it in the src folder of this repo in case it goes away.

i've also included a copy of the backlight_switch_url-release.apk, in case it goes away (used for backlight switching via verified android app links)

Releated Links:
- https://docs.leialoft.com/developer/webgl-sdk/initializing-the-sdk
- https://www.npmjs.com/package/sevensummitswebglsdkdemo
- https://github.com/antoinealiotti/LeiaCore