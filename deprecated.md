# Deprecated and Outdated state of repository

## Initial run `npm i`

### Deprecated
```
$ npm i
npm WARN deprecated cryptiles@3.1.2: This version has been deprecated in accordance with the hapi support policy (hapi.im/support). Please upgrade to the latest version to get the best features, bug fixes, and security patches. If you are unable to upgrade at this time, paid support is available for older versions (hapi.im/commercial).
npm WARN deprecated urix@0.1.0: Please see https://github.com/lydell/urix#deprecated
npm WARN deprecated sntp@2.1.0: This module moved to @hapi/sntp. Please make sure to switch over as this distribution is no longer supported and may contain bugs and critical security issues.
npm WARN deprecated har-validator@5.0.3: this library is no longer supported
npm WARN deprecated request-promise-native@1.0.5: request-promise-native has been deprecated because it extends the now deprecated request package, see https://github.com/request/request/issues/3142
npm WARN deprecated boom@5.2.0: This version has been deprecated in accordance with the hapi support policy (hapi.im/support). Please upgrade to the latest version to get the best features, bug fixes, and security patches. If you are unable to upgrade at this time, paid support is available for older versions (hapi.im/commercial).
npm WARN deprecated boom@4.3.1: This version has been deprecated in accordance with the hapi support policy (hapi.im/support). Please upgrade to the latest version to get the best features, bug fixes, and security patches. If you are unable to upgrade at this time, paid support is available for older versions (hapi.im/commercial).
npm WARN deprecated resolve-url@0.2.1: https://github.com/lydell/resolve-url#deprecated
npm WARN deprecated browserslist@2.11.3: Browserslist 2 could fail on reading Browserslist >3.0 config used in other tools.
npm WARN deprecated circular-json@0.3.3: CircularJSON is in maintenance only, flatted is its successor.
npm WARN deprecated chokidar@2.1.8: Chokidar 2 will break on node v14+. Upgrade to chokidar 3 with 15x less dependencies.
npm WARN deprecated left-pad@1.2.0: use String.prototype.padStart()
npm WARN deprecated hoek@4.2.0: This version has been deprecated in accordance with the hapi support policy (hapi.im/support). Please upgrade to the latest version to get the best features, bug fixes, and security patches. If you are unable to upgrade at this time, paid support is available for older versions (hapi.im/commercial).
npm WARN deprecated hawk@6.0.2: This module moved to @hapi/hawk. Please make sure to switch over as this distribution is no longer supported and may contain bugs and critical security issues.
npm WARN deprecated uuid@3.2.1: Please upgrade  to version 7 or higher.  Older versions may use Math.random() in certain circumstances, which is known to be problematic.  See https://v8.dev/blog/math-random for details.
npm WARN deprecated mkdirp@0.5.1: Legacy versions of mkdirp are no longer supported. Please update to mkdirp 1.x. (Note that the API surface has changed to use Promises in 1.x.)
npm WARN deprecated request@2.83.0: request has been deprecated, see https://github.com/request/request/issues/3142
npm WARN deprecated uglify-es@3.3.10: support for ECMAScript is superseded by `uglify-js` as of v3.13.0
npm WARN deprecated core-js@2.5.3: core-js@<3.3 is no longer maintained and not recommended for usage due to the number of issues. Because of the V8 engine whims, feature detection in old core-js versions could cause a slowdown up to 100x even if nothing is polyfilled. Please, upgrade your dependencies to the actual version of core-js.

48 vulnerabilities (28 low, 12 moderate, 7 high, 1 critical)
```

### After first `npm audit fix`
```
32 vulnerabilities (20 low, 7 moderate, 5 high)
```

## Outdated
```
$ npm outdated
Package                 Current  Wanted  Latest  Location                             Depended by
babel-preset-env          1.6.1   1.7.0   1.7.0  node_modules/babel-preset-env        node-gantt
deepmerge                 2.0.1   2.2.1   4.2.2  node_modules/deepmerge               node-gantt
eslint                   4.19.1  4.19.1  7.29.0  node_modules/eslint                  node-gantt
eslint-config-prettier   2.10.0  2.10.0   8.3.0  node_modules/eslint-config-prettier  node-gantt
eslint-plugin-prettier    2.7.0   2.7.0   3.4.0  node_modules/eslint-plugin-prettier  node-gantt
jest                     22.4.4  22.4.4  27.0.4  node_modules/jest                    node-gantt
prettier                 1.10.2  1.10.2   2.3.1  node_modules/prettier                node-gantt
rollup                   0.55.3  0.55.5  2.52.1  node_modules/rollup                  node-gantt
rollup-plugin-uglify      3.0.0   3.0.0   6.0.4  node_modules/rollup-plugin-uglify    node-gantt
```
