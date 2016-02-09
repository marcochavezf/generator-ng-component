<a name="0.2.0"></a>
### 0.2.0 (2015-09-06)


#### Notable Changes

* We now honor the `.ts` extension. (Note: The code will not be typed by default)
* If you provide a new `'es6'` filter, ECMAScript 2015 code will be generated
* The route generator now uses the 'MyController' naming convention, instead of 'MyCtrl'
* Will now prompt for a module name to use (ex: `'myApp.foo'` instead of `'myApp'`). Set `modulePrompt` to false to disable.

#### Features

* **gen:**
  * prompt for module name when `config.modulePrompt` ([3bd75b3](https://github.com/DaftMonk/generator-ng-component/commit/3bd75b357f5563bf33d913ff4b23d8e0237689c7))
  * make .ts files ([4c6a389](https://github.com/DaftMonk/generator-ng-component/commit/4c6a389e685f838796f2fe15aa0a8221ab03400f))
* **route:** use a class and controllerAs if es6 filter present ([678c01f](https://github.com/DaftMonk/generator-ng-component/commit/678c01ffde5c59e38a15d6e74828c32ca5210535))

#### Chore

* **gen:** update yeoman-generator to `~0.20.3` ([51c560a](https://github.com/DaftMonk/generator-ng-component/commit/51c560a300738e3ce12ab0247d74f487bfc7437d))


<a name="0.1.1"></a>
### 0.1.1 (2015-09-06)


#### Features

* **gen:**
  * use yeoman's grouped queues ([e265f34](https://github.com/DaftMonk/generator-ng-component/commit/e265f34f74cf74d19d70c1baa7e67665fc7e3545))
  * add dynamic mocha assertions ([b64455d](https://github.com/DaftMonk/generator-ng-component/commit/b64455d62c00b3cb6134c9a35538dab74d6d452b))
  * config can be force updated via `options.forceConfig` ([0e81bb4](https://github.com/DaftMonk/generator-ng-component/commit/0e81bb47b56280d94cc45a784c81f2ee8113e9e6))

#### Chore

* **gen:** update yeoman-generator to `~0.19.2` ([a861e29](https://github.com/DaftMonk/generator-ng-component/commit/a861e292a6aa5d4c5980a6c31f82fec6ae7850c9))

#### Breaking Changes

* `yeoman-generator@0.19.2` deprecates the use of `this._`. If your templates use lodash methods, you should now reference `this.lodash`.


<a name="0.1.0"></a>
## 0.1.0 (2015-08-05)


#### Bug Fixes

* **gen:**
  * removed bootstrap class dependency from route html and jade templates ([d725057](https://github.com/DaftMonk/generator-ng-component/commit/d725057006c7b8785ada77bf340bc6bf48c12c41))
  * fix indention spacing ([82a4201](https://github.com/DaftMonk/generator-ng-component/commit/82a420173a5c43d1829f96551f627fcaa81cd4b1))
* **app:** ensure all files end with a newline ([bd312ce](https://github.com/DaftMonk/generator-ng-component/commit/bd312ce1366e74d2d208dffca8232cc051ec1664))
* **dependencies:** remove peer dependencies ([3fb83ea](https://github.com/DaftMonk/generator-ng-component/commit/3fb83ea9bb31266f2b1721469c6b9d50ab5f52bb))

#### Features

* **gen:** add hasFilter function ([fa39978](https://github.com/DaftMonk/generator-ng-component/commit/fa399784dfac16ee742b62bd9299c9c7bcccc125))
* **test:** add support for mocha+chai ([aaca1e8](https://github.com/DaftMonk/generator-ng-component/commit/aaca1e83c916cae84079cd2e24dddbc5d4bee360))
* **dependencies:** update to `yeoman-generator@~0.18.10` ([dc63875](https://github.com/DaftMonk/generator-ng-component/commit/dc63875965a95bf0604d627e953dea4b6784fe5a))
