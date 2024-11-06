# History

## 11.8.1

### Bug fixes

* errors: prevent internal exception if failing to stringify array or object (fb766fc21784f70a3525de91e95493847a3c090b)

## 11.8.0

### New features

* lib: in the error message print the content instead of  or  (e5121812ed353a416a4e9aac4fe28d5595290f3b)

## 11.7.1

### Other changes

* 083f061aea70ee7dc3ee7b9d887195cd1009b35c Merge branch 'joachimhb-master' (083f061aea70ee7dc3ee7b9d887195cd1009b35c)
* f9422df3664a51e0c894b8f263325fd3c49765e0 rejectsWith and throwsWith show error message in assert error (f9422df3664a51e0c894b8f263325fd3c49765e0)

## 11.7.0

### New features

* lib: extend identical() to work better for multi-level objects and additional data types (6061c6d8e05b914b534bd7e9ddbd240e60a887a9)

### Refactorings

* code: fix linting errors (5a3500eb8b5f7bb0fd88e1df5f092398a13be385)
* tests: change the callback and done() code into real async/await (e0b86b578c4625022f8286e77043d3f09020ee5c)

### Other changes

* ci: run tests in node 22 (1b2de1969797e03b1f02b8263e15f1beb2e010e2)
* tests: extend tests for maybe.in (189f8d7b52d4729137f341d0f94b1eb292d6a828)
* config: extend .gitignore (fcdf6c7414028e538bb4fa97e964e77bd79898ec)

## 11.6.1

### Bug fixes

* errors: return false for undefined value in contains for array or map that do not contain an undefined entry (5b9032979f1c29bda7d75a32f0f47eb350207396)

### Other changes

* package: update dev deps (b62f0a65b77f61f2e72f5fcc7080942536377f16)

## 11.6.0

### New features

* lib: make the rejects() and rejectsWith() checks work (fc7f8cc56c7c160f203eabe403e21c28064f0e25)

### Bug fixes

* errors: return true for containsKey even if value is nullish (111f37f751444a384a76c2d7b38054485c5aca44)
* predicates: make `identical` work for nested objects (387dc471209090be800ef357d1a49c1191cf902c)

### Other changes

* ci: run tests in node 20 (677c154a5e4bf538a23fd43827f416873b082715)
* 07c7acb276850aede2e9fce123936dde17d24290 doc (07c7acb276850aede2e9fce123936dde17d24290)

## 11.5.0

### New features

* predicates: implement identical (ae48dc13735e96c0ac9b33deb6dc1c7dea40bb13)

### Bug fixes

* tests: fix bad assertion in tests for like and identical (42dbed91e014082140286614ee76289dfaaf9340)
* predicates: don't throw if args to identical are null (25dec51bd5a07f40774051e33bf4c720180fb20e)
* predicates: don't throw if args to like are null (f5a2f741dd1e5c44b783d88df13d020418a8a828)

### Other changes

* ci: run tests in node 16 and 18 (ea17ee6ffe8c4323ef0575f2e838e6c51a1137f1)
* package: drop license and history files from package (6ec4ed386d343a9230dfae21d35e1ebdbefcbf4e)
* docs: add note about zero dependencies to readme (1abfc2b79aca014c3da6edf39c0d72fa7a07a011)
* tests: extra test cases for like predicate (529033218856faefd974bd8458e3166078a7b854)
* package: drop bower/component support (98149cb67f7fb2ba7055f7ec96c07e59e839937a)
* package: update dev deps (507928c6932c2cddd1f90d557dea161572f64604)

## 11.4.0

### New features

* implement throwsWith and rejectsWith (4b5cebc)

### Other changes

* ee9d478 Add release cheatsheet (ee9d478)
* 07775dd Update documentation, referencing the fork and the original author (07775dd)
* f2b789c update (f2b789c)

## 11.3.0

### New features

* implement rejects (d316f87)

### Other changes

* 4daa3a1 Enhance package description (4daa3a1)
* d485e71 Add swap files to .gitignore (d485e71)

## 11.2.0

### New features

* Add true() and false() (7921f0a)

### Other changes

* //gitlab.com/philbooth] decided to archive the project, I created a fork and published a new packages `check-types-2`. Thanks for Phil for the great work. (4b1e544)

## 11.1.2

### Bug fixes

* errors: format `true` correctly in error messages (51291ef)

## 11.1.1

### Other changes

* build: update minified script (99f024b)
* docs: tweak comment (6a69673)

## 11.1.0

### New features

* predicates: add thenable (d95829c)

### Other changes

* docs: remove some examples (8c67463)
* docs: add missing link to readme index (3da9662)

## 11.0.0

### Breaking changes

* api: remove trim option from emptyString and nonEmptyString (3747900)

### New features

* predicates: implement float (b6bf1dc)
* predicates: implement throws (018f50a)
* predicates: implement one (3fb7424)

### Bug fixes

* lib: stop object predicates throwing when prototypes is null (b0bab07)

### Other changes

* tests: add missing test case for assert.throws (6f9c2f7)
* docs: update author list (81ab8a9)

## 10.1.2

### Performance improvements

* lib: shortcut unnecessary iteration for Sets in contains (522f073)

## 10.1.1

### Bug fixes

* docs: fix broken description for keyIn predicate (6eb431e)

## 10.1.0

### New features

* api: add keyIn predicate (1ff2227)
* api: add containsKey predicate (40c28c7)

### Other changes

* lib: fix lint errors (dcecb88)

## 10.0.0

### Breaking changes

* assert: return detailed error messages from assertions (c0ceacd)
* api: merge the includes predicate into contains (2fd60c4)

### New features

* predicates: add inside as argument-flipped wrapper for contains (1c95714)

### Refactorings

* api: rename inside predicate to in (55e07a5)

## 9.0.1

### Bug fixes

* docs: link to changes for 9.0.0 (4108a66)

### Other changes

* package: remove package-lock.json from source control (09679a7)

## 9.0.0

### Breaking changes

* lib: support a trim option on emptyString and nonEmptyString (75599d2)

### Other changes

* docs: update download counter (ee81d9c)

## 8.0.3

### Bug fixes

* docs: remove stale link from readme (9f467b3)

### Other changes

* ci: turn off node 4/6 builds (301e09a)
* lib: delete old commented-out code (2d11e0b)

## 8.0.2

### Bug fixes

* lib: ignore properties in map that have no predicate (f6bbad7)
* docs: add missing section link to readme index (5cfec25)
* ci: stop testing in node 0.10 (f986f1c)

### Other changes

* docs: update readme (e602bfd)
* package: npm update (1b32cd4)

## 8.0.1

### Bug fixes

* docs: fix link to change log (9166ecf)

### Other changes

* docs: update copyright (ddc00b8)

## 8.0.0

### Breaking changes

* api: remove apply and combine functionality with map (ecc40e5)

### Bug fixes

* docs: fix links to change log (ae3811a)

### Refactorings

* lib: eliminate intermediate arrays when iterating properties (8eeda6f)
* lib: use native Array.isArray internally (ebc9ed0)

### Other changes

* deps: update dev dependencies and rebuild (854b012)
* project: turn on gitlab pipeline (ab4f662)

## 7.4.0

### New features

* docs: add note about typescript definitions to readme (13c7a90)

### Bug fixes

* docs: remove errant semicolon from example code (9053f95)
* docs: clarify the behaviour of between and inRange (88a2f61)
* tests: ensure tests run in non-es6 environments (4bae637)

### Other changes

* deps: update please-release-me (72377bf)
* project: migrate to gitlab (19919b5)
* package: update authors (9848df0)

## 7.3.0

* feature: add primitive predicate (3114d7f)

## 7.2.1

* fix: perf tweaks for tight loops (8a9919d)
* chore: update ci config (136f185)

## 7.2.0

* feature: return the target value from assertions (73da792)
* chore: add release script dependency (cacc348)
* fix: make assert throw for any falsy value (4f15c73)

## 7.1

* Implement `nonEmptyObject`. Thanks to [Victor Bakke][gipphe].
* Implement `nonEmptyArray`. Thanks to [Victor Bakke][gipphe].
* Fix error messages on assertions that take a string as their last argument.
* Add support for custom error types in assertions.
* Throw TypeErrors by default.

## 7.0

* Breaking changes:
  * Rename `instance` to `instanceStrict`.
  * Combine `builtIn` and `userDefined` to form new `instance` predicate.
* Exclude non-src files from npm package

## 6.0

* Breaking change:
  * `either` modifier removed.
* Eliminated some string duplication.

## 5.1

* Fix broken implementation of `maybe.array.of`.

## 5.0

* Breaking changes:
  * `isMap` predicate removed (see `builtIn`).
  * `error` predicate removed (see `builtIn`).
* Implement `builtIn` predicate.
* Implement `userDefined` predicate.
* Implement `emptyString` predicate.
* Implement `infinity` predicate.

## 4.3

* Implement `isMap`. Thanks to [Ryan Temple][ryantemple].

## 4.2

* Implement `includes`.

## 4.1

* Implement `equal`.

## 4.0

* Breaking changes:
  * Rename `unemptyString` => `nonEmptyString`.
  * Support derived error objects in `error`.
* Fix HTMLElement instance predicate bug in Safari.

## 3.3

* Implement `greaterOrEqual`.
* Implement `lessOrEqual`.
* Implement `inRange`.
* Fix default error message for `function`. Thanks to [Paul Jolly][myitcv].

## 3.2

* Implement `arrayLike`
* Implement `iterable`
* Implement `array.of`
* Implement `arrayLike.of`
* Implement `iterable.of`
* Implement `object.of`
* Fix unhandled exception when dereferencing undefined data inside `map`.

## 3.1

* Accept a single predicate in `map`.
* Remove assertions from `hasLength` and `like`.

## 3.0

* Breaking changes:
  * Rename `length` => `hasLength`.
  * Drop `webUrl`. (sorry @bahmutov!)
* Turn `assert`, `not` and `maybe` into standalone functions as well as modifiers.
* Implement `match` for general regex-matching. Possibly of interest to former users of `webUrl`, `gitUrl` and `email`.
* Implement `contains`.
* Implement `between`.
* Implement `greater`.
* Implement `less`.
* Implement `zero`.
* Implement `emptyArray`.
* Implement `error`.
* Fix errant check that property counts match in `map`.

## 2.2

* Ensure `date` predicate returns `false` for invalid dates.

## 2.1

* Add `either`.

## 2.0

* Breaking changes:
  * Drop ES3 support.
  * Rename `verify` => `assert`.
  * Remame `nulled` => `null`.
  * Switch `defined` to `undefined` for consistency with `null`.
  * Tightened implementation of `webUrl` to reject more cases.
  * Drop `gitUrl`. (sorry @galniv!)
  * Drop `email`. (sorry @rodrigo!)
  * Drop `floatNumber`. (sorry @rodrigo!)
  * Rename `oddNumber`, `evenNumber`, `positiveNumber`, `negativeNumber`, `intNumber` => `odd`, `even`, `positive`, `negative`, `integer`.
  * Rename `bool` => `boolean`.
  * Rename `every` => `all`.
* Add predicate `assigned`.
* Add `apply` batch operation.
* Delete superfluous unit tests.

## 1.4

* Implement `bool` predicate. Thanks to [Clinton Skakun][clintonskakun].

## 1.3

* Implement `email`, `intNumber` and `floatNumber` predicates. Thanks to [Rodrigo González][rodrigo].
* Infinity is not a number.
* Implement `defined` and `nulled`. Thanks to [Alejandro Villanueva][ialex].
* Speculatively fix conflict with angular-mocks.

## 1.2

* Implement `not` modifier.
* Implement `gitUrl` predicate. Thanks to [Gal Niv][galniv].

## 1.1

* Replace `check.maybe.verify.xxx` with `check.verify.maybe.xxx`.

## 1.0

* API overhaul:
    * Predicates exported as `check.xxx` rather than `check.isXxx`.
    * Verifiers exported as `check.verify.xxx` rather than `check.verifyXxx`. Thanks to [Marc-Olivier Ricard][marcolivier].
* Unit tests added for error messages.

## 0.8

* Added `isWebUrl` and `verifyWebUrl`. Thanks to [Gleb Bahmutov][gleb].

## 0.7

* Added `check.maybe` modifier. Thanks to [Marc-Olivier Ricard][marcolivier].
* Added `check.map`, `check.every` and `check.any` batch operations. Thanks to [Marc-Olivier Ricard][marcolivier].
* Harmonised the node and browser unit tests.

[marcolivier]: https://github.com/ricardmo
[gleb]: https://github.com/bahmutov
[galniv]: https://github.com/galniv
[rodrigo]: https://github.com/roro89
[ialex]: https://github.com/ialex
[clintonskakun]: https://github.com/clintonskakun
[myitcv]: https://github.com/myitcv
[ryantemple]: https://github.com/ryantemple
[gipphe]: https://github.com/Gipphe

