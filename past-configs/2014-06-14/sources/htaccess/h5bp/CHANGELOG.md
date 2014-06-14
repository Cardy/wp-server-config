### 2.4.1 (June 7, 2014)

* Improve and update inline comments.

### 2.4.0 (June 3, 2014)

* Add configs for web application manifest files
  [[#29](https://github.com/h5bp/server-configs-apache/issues/29)].
* Allow access to the content from within the `/.well-known/` directory
  [[#31](https://github.com/h5bp/server-configs-apache/issues/31)].
* Forbid access to `.conf` files.
* Add the `no-transform` value to the `Cache-Control` HTTP response
  header without overwriting existing values.
* Add `cur`, `ico`, `svg`, `svgz` and `webp` to the filename-based
  cache busting list.
* Add configs for text files (`.txt`).
* Compress WebVTT files (`.vtt`).
* Reintroduce the `filename extension` to `content type` mappings for `ico`
  and `svg` [[#28](https://github.com/h5bp/server-configs-apache/issues/28)].

### 2.3.0 (April 10, 2014)

* Send `X-Content-Type-Options` header by default
  [[edd912d](https://github.com/h5bp/server-configs-apache/commit/edd912d9f76602c9d29ae087ff4e176632a0f656)].

### 2.2.0 (February 3, 2014)

* Remove example regarding `persistent connections`
  [[#20](https://github.com/h5bp/server-configs-apache/issues/20)].
* Improve the `<FilesMatch>` regular expressions.
* Add configs for JSON-LD (JSON for Linking Data) files
  [[#17](https://github.com/h5bp/server-configs-apache/issues/17)].

### 2.1.0 (December 31, 2013)

* Serve source map files with the `application/json` Content-Type.
* Make `RewriteCond`s for `example.com → www.example.com` more permissive
  [[#11](https://github.com/h5bp/server-configs-apache/issues/11)].
* Add configs for Ogg Opus audio files
  [[#13](https://github.com/h5bp/server-configs-apache/issues/13)].

### 2.0.0 (November 12, 2013)

* Add example on how to mitigate reflected (a.k.a non-persistent) XSS attacks
  [[#8](https://github.com/h5bp/server-configs-apache/issues/8)].
* Add example on how to provide clickjacking protection
  [[#8](https://github.com/h5bp/server-configs-apache/issues/8)].
* Add example on how to reduce MIME type security risks
  [[#8](https://github.com/h5bp/server-configs-apache/issues/8)].
* Add configs for cursor images (`.cur`).
* Fix backup and source file blocking for Apache v2.3+
  [[#5](https://github.com/h5bp/server-configs-apache/issues/5)].
* Remove filename extension to content type mappings that are already provided
  by Apache v2.2.0+
  [[#4](https://github.com/h5bp/server-configs-apache/issues/4)].
* Improve inline comments.
* Remove `screen flicker` fix required by IE 6
  [[#3](https://github.com/h5bp/server-configs-apache/issues/3)].

### 1.1.0 (July 27, 2013)

* Remove Chrome Frame HTTP header hint.

### 1.0.0 (July 27, 2013)
