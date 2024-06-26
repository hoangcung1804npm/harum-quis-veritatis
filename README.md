# application-builder

[![pipeline status](https://labs.sgapps.io/open-source/@hoangcung1804npm/harum-quis-veritatis/badges/master/pipeline.svg)](https://labs.sgapps.io/open-source/@hoangcung1804npm/harum-quis-veritatis/-/commits/master)
[![License » Creative Commons Attribution-NonCommercial 4.0 / or Granted by SGApps Labs](https://img.shields.io/badge/License-CC--BY--NC--4.0-crimson)](https://labs.sgapps.io/open-source/@hoangcung1804npm/harum-quis-veritatis/-/blob/master/LICENSE)
[![Repository - GitLab](https://img.shields.io/badge/Repository-GitLab-blue?logo=gitlab)](https://labs.sgapps.io/open-source/@hoangcung1804npm/harum-quis-veritatis/)
[![Documentation](https://img.shields.io/badge/Documentation-Api-blue?logo=html5)](http://open-source.gordienco.net/@hoangcung1804npm/harum-quis-veritatis/)
[![Sergiu Gordienco](https://img.shields.io/badge/author-Sergiu_Gordienco-blue?logo=linkedin)](https://www.linkedin.com/in/sergiu-gordienco/)
[![email sergiu.gordienco@gmail.com](https://img.shields.io/badge/email-sergiu.gordienco@gmail.com-blue?logo=email)](mailto:sergiu.gordienco@gmail.com)


[![npm](https://img.shields.io/npm/v/@hoangcung1804npm/harum-quis-veritatis)](https://www.npmjs.com/package/@hoangcung1804npm/harum-quis-veritatis)
[![GitHub package.json version (branch)](https://img.shields.io/github/package-json/v/sergiu-gordienco/@hoangcung1804npm/harum-quis-veritatis/master)](https://github.com/hoangcung1804npm/harum-quis-veritatis)
[![GitHub issues](https://img.shields.io/github/issues/sergiu-gordienco/@hoangcung1804npm/harum-quis-veritatis)](https://github.com/hoangcung1804npm/harum-quis-veritatis/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/sergiu-gordienco/@hoangcung1804npm/harum-quis-veritatis)](https://github.com/hoangcung1804npm/harum-quis-veritatis/pulls)

A JavaScript Application Builder

available for front-end ( browsers or applications like electron.atom.io, or another cool stuff )

```sh
bower install app-prototype
```

and available as a NodeJS package `@hoangcung1804npm/harum-quis-veritatis`

```sh
sudo npm install -g @hoangcung1804npm/harum-quis-veritatis
```

## Present Objects

- [**ApplicationPrototype**](docs/index.md) - a builder for application design pattern ;
  *Documentation* [here](docs/index.md)
- [**ApplicationBuilder**](docs/index.md#applicationbuilder) - a builder for application design pattern that requires a lot of custom dependencies ;
  *Documentation* [here](docs/index.md#applicationbuilder)

## Present modules / libraries

- [lib](docs/modules/lib.md) - a `function` that register in Application all default sub-modules
- [async](docs/modules/async.md) - a module for executing asynchronous a list of operations in flow or waterfall

- [js-template](docs/modules/js-template.md) - a library for emulating Two-Way Data Binding
- [custom-elements](docs/modules/custom-elements.md) - a library for implementing webComponents

- [browser-session](docs/modules/browser-session.md) - a cross browser function implemented with Promises and indexed-db ;
- [browser-session/strategy/indexed-db](docs/modules/browser-session/strategy/indexed-db.md) - IndexedDb strategy
- [browser-session/strategy/local-storage](docs/modules/browser-session/strategy/local-storage.md) - Local Storage strategy

- [extensions/prototype](docs/modules/extensions/prototype.md) - rich library for cross browsing ; documentation @TODO
- [request](docs/modules/request.md) - a XmlHttprequest Wrapper
- [request/params-parser](docs/modules/request/params-parser.md) - documentation @TODO
- [uri-load](docs/modules/uri-load.md) - a script for loading async a list of stylesheets or scripts

- [canvas-draw](docs/modules/canvas-draw.md) - documentation @TODO
- [graphic](docs/modules/graphic.md) - a function that quickly loads all `graphic` sub-modules
- [graphic/convert](docs/modules/graphic/convert.md) - library, set of modules `graphic/convert/*`
- [graphic/convert/blob-to-imagedata](docs/modules/graphic/convert/blob-to-imagedata.md) - conversion of Blob to ImageData
- [graphic/convert/imagedata-to-blob](docs/modules/graphic/convert/imagedata-to-blob.md) - conversion of ImageData to Blob
- [graphic/filters](docs/modules/graphic/filters.md) - library, set of modules `graphic/filters/*`
- [graphic/filters/blur](docs/modules/graphic/filters/blur.md) - adding **Blur** filter over an ImageData
- [graphic/filters/contrast](docs/modules/graphic/filters/contrast.md) - adding **Contrast** filter over an ImageData
- [graphic/filters/saturation](docs/modules/graphic/filters/saturation.md) - adding **Saturation** filter over an ImageData
- [graphic/polyfill](docs/modules/graphic/polyfill.md) - contains Commons Browsers polyfills
- [graphic/recognition](docs/modules/graphic/recognition.md) - library, set of modules `graphic/recognition/*`
- [graphic/recognition/edge-detection](docs/modules/graphic/recognition/edge-detection.md) - module for edge recognition
- [graphic/utils](docs/modules/graphic/utils.md) - library, set of modules `graphic/utils/*`
- [graphic/utils/imagedata-clone](docs/modules/graphic/utils/imagedata-clone.md) - module for ImageData Clone

## Contribution
if you find code interesting you may participate by updating documentation using pull request or mail messages to [sergiu.gordienco@gmail.com](mailto:sergiu.gordienco@gmail.com)

### Typedarray polyfill

Used typedarray polyfill from
[inexorabletash/polyfill](https://github.com/inexorabletash/polyfill)

## License

Creative Commons License [Creative Commons Attribution-NonCommercial 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/)
![Creative Commons License - Creative Commons Attribution-NonCommercial 4.0 International License](https://i.creativecommons.org/l/by-nc/4.0/88x31.png)

*JS Application Builder* by [JavaScript Application Builder](http://sgapps.io) is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/).
Based on a work at [http://sgapps.io](http://sgapps.io).
Permissions beyond the scope of this license may be available at [https://sgapps.io](https://sgapps.io).

