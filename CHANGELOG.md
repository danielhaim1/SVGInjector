## Change Log

### 1.1.3 (2015/06/23 23:12 +00:00)
- [e01b63e](https://github.com/iconic/SVGInjector/commit/e01b63e586b8ab61203eb58e1d94b3b2626873ec) changelog update (@protodave)
- [d00ef1f](https://github.com/iconic/SVGInjector/commit/d00ef1f0d8ddfff7e61147ca48955ef740d3a226) updated svg/png assets and js library for examples and tests (@protodave)
- [77ce693](https://github.com/iconic/SVGInjector/commit/77ce693181ba059714081ead83b598e70ebed162) Added keyword (@protodave)
- [db7f1e7](https://github.com/iconic/SVGInjector/commit/db7f1e7d2c1ecbf00e0abc2cd81dc07b631f8d08) Added CORS test in prep for adding XDomainRequest for IE9 (@protodave)
- [9f25052](https://github.com/iconic/SVGInjector/commit/9f25052fcc815aa719ba86506470b6ac2003612a) Updated author info in prep for npm publishing (@protodave)
- [2b209bb](https://github.com/iconic/SVGInjector/commit/2b209bbc0de09ce9257cf55b582ebf859f444d8b) Added npm install details (@protodave)
- [fae3a70](https://github.com/iconic/SVGInjector/commit/fae3a704af7283277051bd038760a656fff3a37f) Workaround/Fix for IE not using style tags from injected SVG files. Ref: issue #23 - Internet Explorer 11 svg images appears all black (@protodave)
- [e84f9b4](https://github.com/iconic/SVGInjector/commit/e84f9b47eadb501e68a4d0d5b6593935e8d25c19) version bump for RC 1.1.3 testing (@protodave)
- [6eb754f](https://github.com/iconic/SVGInjector/commit/6eb754f058b15bb15553edd884386fd250e849ca) Rewrite all iri reference attribute ids (@Pwntastic)
- [32dadf5](https://github.com/iconic/SVGInjector/commit/32dadf59c419ca038ddb34b0325ec25bf4ac1a01) Start of IRI reference element/property test cases (@protodave)
- [dc36886](https://github.com/iconic/SVGInjector/commit/dc36886f47fb5787a13e1c34ae72c0e6e95f4d9d) Added more IRI tests for fill and filter (@protodave)
- [#24](https://null/iconic/SVGInjector/pull/24) Rewrite all iri reference attribute ids (@Pwntastic)
- [aea524b](https://github.com/iconic/SVGInjector/commit/aea524b1149b08473b8187c87ec1fa746fff6cd7) reworked IRI re-enumeration code to explicitly map elements to properties that can address them (@protodave)
- [55c2465](https://github.com/iconic/SVGInjector/commit/55c2465350b519a8ef99f1ea40aee6ecf2c8ad2c) copyright update (@protodave)
- [f9c5248](https://github.com/iconic/SVGInjector/commit/f9c5248b4ddba4f8113a03dd814fe90beaa546f0) version bump to 1.1.3 (@protodave)
- [d294d1a](https://github.com/iconic/SVGInjector/commit/d294d1adccc7aa6cfe6b0594cf38ede8a61337bd) New dist build: v1.1.3 (@protodave)
- [8fefa15](https://github.com/iconic/SVGInjector/commit/8fefa156b0028746562520a47cb1ef6121196d34) updated svg-injector.min.js in all examples/ and tests/ (@protodave)
- [21cbe6c](https://github.com/iconic/SVGInjector/commit/21cbe6c94a38659173ad16fb14e3ab31e2127869) changelog update (@protodave)
- [bd355be](https://github.com/iconic/SVGInjector/commit/bd355bebb1903e1eac608883a8b5af5e7e6d5fd2) bower version bump to 1.1.3 (@protodave)

### 1.1.2 (2014/10/27 21:50 +00:00)
- [8da3cfb](https://github.com/iconic/SVGInjector/commit/8da3cfbf239b286c6046f7cd1f80261690ad9a5d) changelog update (@protodave)
- [e498e03](https://github.com/iconic/SVGInjector/commit/e498e03eb2c40d3907c5cddb035a1705bfa5f384) Make sure any mask ids and their references are unique so we can safely use the same SVG multiple times on the same page (like we already do for clipPaths) (@protodave)
- [eae8b22](https://github.com/iconic/SVGInjector/commit/eae8b2268f5cc3a1430f76a318b7eac3c31fdc3d) New build and version bump (@protodave)
- [7266bcf](https://github.com/iconic/SVGInjector/commit/7266bcf7eeda3e4c33d2fa15bc9365ea57985959) updated changelog (@protodave)

### 1.1.1 (2014/10/15 21:08 +00:00)
- [55ac808](https://github.com/iconic/SVGInjector/commit/55ac808b03bf691d69230359d2436156def0d0bd) Fix for issue #17 - "SVG Injector doesn't work if there is a URL parameter". Updated the regex that was matching for an svg file extension to allow for query strings. (@protodave)
- [0b76f3b](https://github.com/iconic/SVGInjector/commit/0b76f3b82529757508d0fb7a9fba582089f16abe) version bump, v1.1.1 (@protodave)

### 1.1.0 (2014/07/01 21:01 +00:00)
- [e2d6d62](https://github.com/iconic/SVGInjector/commit/e2d6d626560911154257367d629e6a59d6e239b2) Updated bower package name in the install command (@protodave)
- [972fdf6](https://github.com/iconic/SVGInjector/commit/972fdf62f98ee2c68c8c8f132c2e2f64867581ff) different forEach approach (@stryju)
- [207dee9](https://github.com/iconic/SVGInjector/commit/207dee91f44423c8396d8c8f157c22d37834bb72) small cleanup (@stryju)
- [1814600](https://github.com/iconic/SVGInjector/commit/18146006fc751a484aff0ecba473b0d7ef276a7d) TODO: don't add dups (@stryju)
- [1f09fd9](https://github.com/iconic/SVGInjector/commit/1f09fd944b32071cf6cb00448806085fda474e87) Added per-element PNG fallback functionality via setting a data-fallback or data-png attribute. (@protodave)
- [#11](https://null/iconic/SVGInjector/pull/11) TODO: don't add class dups (@stryju)
- [4350111](https://github.com/iconic/SVGInjector/commit/43501118d127c678dbe5adb951ec7b88d4f7ff5b) Simplified class merging (@protodave)
- [8066bf6](https://github.com/iconic/SVGInjector/commit/8066bf60026ec8c98af36d30a2cd3f1c3cbb65a2) updated dist build and examples svg-injector.min.js files (@protodave)
- [56d22c0](https://github.com/iconic/SVGInjector/commit/56d22c06b02cfc6faae090a2943f38a060e07eff) Conflicts: 	svg-injector.js (@protodave)
- [fa118b0](https://github.com/iconic/SVGInjector/commit/fa118b0f8df40885ebe0c2698f1749ad36b46a75) Merge branch 'stryju-patch-1' (@protodave)
- [70ec72e](https://github.com/iconic/SVGInjector/commit/70ec72e1901e33c3687d25b1ce93af6632a0f1a0) updated dist build and examples (@protodave)
- [8f04917](https://github.com/iconic/SVGInjector/commit/8f04917452f0ad18903ea0281c4be04716f5977b) Conflicts: 	svg-injector.js (@protodave)
- [fd321d6](https://github.com/iconic/SVGInjector/commit/fd321d61f8108fedb49c34d3b6bfb6c7ae65ca16) to explain why this merge is necessary, (@protodave)
- [f6eb3a7](https://github.com/iconic/SVGInjector/commit/f6eb3a740dc2884d96a1b97156b1926933544ac1) reverted the isFunction() and isDefined() refactor PR since you can't pass undefined/undeclared vars to functions in JS (@protodave)
- [88778d7](https://github.com/iconic/SVGInjector/commit/88778d7a9491af523d48ece8595c6abd8f8e8430) new dist build and examples updates (@protodave)
- [26545d9](https://github.com/iconic/SVGInjector/commit/26545d96dc3a889c35350a79f98a89ed2473f1d4) readme update (@protodave)
- [10c2a24](https://github.com/iconic/SVGInjector/commit/10c2a244e50a1680001ad657803cfcd92b76f055) removed some extra classes that were added for testing in the all-the-things examples (@protodave)
- [f37d0ad](https://github.com/iconic/SVGInjector/commit/f37d0adafc1ecc90e3e6cf0cca4525b752276321) added "examples" to bower.json ignore (@protodave)
- [2ee9f87](https://github.com/iconic/SVGInjector/commit/2ee9f87c8ba0a8c97eddfcb8d64006c603a7bbf5) Address Issue #12 - Injection race condition (@protodave)
- [67c2355](https://github.com/iconic/SVGInjector/commit/67c2355f260c8f277efa9983ceeb01160c48e56a) Added test for race condition during injection, Issue #12 (@protodave)
- [96cb187](https://github.com/iconic/SVGInjector/commit/96cb187a14e14dfda303612d1b66d8477643d9c8) Updated build and examples svg-injector.min.js files (@protodave)
- [f3e1bfb](https://github.com/iconic/SVGInjector/commit/f3e1bfb77358ca6404c3aeffea9aae316cc5d919) Clean up references to the replaced elements during injection, which end up as detached DOM elements, so they can be GC'd (@protodave)
- [ce1eaa8](https://github.com/iconic/SVGInjector/commit/ce1eaa84eef55776926799818c4f8fcdbe43725a) Move the use of injectOf() until _after_ the check for SVG support during injection so we can avoid adding the extra code for an IE8 indexOf() polyfill (@protodave)
- [9be5041](https://github.com/iconic/SVGInjector/commit/9be50413b67bff29d9fc799c0553dbee06fb2fad) min/map dist build and updated lib in examples and tests (@protodave)
- [e2e2438](https://github.com/iconic/SVGInjector/commit/e2e24383f97a60adbc64cfe546f21813964f9bd9) Unlink elements var to aid GC and avoid detacted DOM elements (@protodave)
- [fe70317](https://github.com/iconic/SVGInjector/commit/fe703175448b3ba2768b8425eebf7f01ee3ae2c8) updated min/map dist build (@protodave)
- [0e1cce5](https://github.com/iconic/SVGInjector/commit/0e1cce5e792358bc0ce4ac3158cd3e77e10c5245) Updated CHANGELOG for 1.1.0 release (@protodave)
- [173dc9b](https://github.com/iconic/SVGInjector/commit/173dc9b9c205c8ff1441391d3fb70e7172caf162) update version in bower.json (@protodave)

### 1.0.1 (2014/05/08 22:31 +00:00)
- [13a2af6](https://github.com/iconic/SVGInjector/commit/13a2af6af1bd61dab6b1ff34c84c7d6f6fd79dcf) Added jshintrc and some jshint wrapper rules to svg-injector.js (@protodave)
- [3c69267](https://github.com/iconic/SVGInjector/commit/3c692679056e3270b97e0718d50255983b05e8e5) added a package.json and .gitignore (@protodave)
- [f61e766](https://github.com/iconic/SVGInjector/commit/f61e766220e3c70e98704b265d653977a96344a7) created first min/map dist build (@protodave)
- [9a4a8ba](https://github.com/iconic/SVGInjector/commit/9a4a8ba8910fc991a76ac889b43bbf1993571321) Updated CHANGELOG (@protodave)
- [f40df63](https://github.com/iconic/SVGInjector/commit/f40df632f1e413eb1bdcfa2a036ad845edba7af3) Update README.md (@protodave)
- [60c74dc](https://github.com/iconic/SVGInjector/commit/60c74dc119c24e6ae160c86031be0128da625979) Missing a closing `)` on example console.log (@FStop)
- [#2](https://null/iconic/SVGInjector/pull/2) Missing a closing `)` on example console.log (@FStop)
- [172e267](https://github.com/iconic/SVGInjector/commit/172e267b7cd119728070003675e0a6453df32442) Update README.md (@protodave)
- [7adef6e](https://github.com/iconic/SVGInjector/commit/7adef6e409bef6e490524f33b831eab2089e39eb) Updated documentation (@protodave)
- [4fc172a](https://github.com/iconic/SVGInjector/commit/4fc172a2d54b7ed02e5dd42165b970db398bb4ff) Added examples (@protodave)
- [c5a7fb4](https://github.com/iconic/SVGInjector/commit/c5a7fb40e379b566c7577f0f3b9b1c00d2c7278c) Fixed a link in the README (@protodave)
- [52b0483](https://github.com/iconic/SVGInjector/commit/52b0483e913fe89c1aeafefd6d3399ab75f77b07) init bower (@hoetmaaiers)
- [7d78660](https://github.com/iconic/SVGInjector/commit/7d786602a1b62c327a21cbaaf9a9bef36e772fe6) add install with bower to README (@hoetmaaiers)
- [#5](https://null/iconic/SVGInjector/pull/5) Bower (@hoetmaaiers)
- [b0c055c](https://github.com/iconic/SVGInjector/commit/b0c055c778430878e8a12ce14389c9812fbe9ffc) Bump to v1.0.1 (@protodave)
- [fbb6fce](https://github.com/iconic/SVGInjector/commit/fbb6fce1c9670c160f2c23638e759ed6fa304225) updated changelog (@protodave)

### 1.0.0 (2014/03/31 17:33 +00:00)
- [0280954](https://github.com/iconic/SVGInjector/commit/02809541241ab8ebf88135124bac2be27d9e2538) Initial commit (@protodave)
- [49adbde](https://github.com/iconic/SVGInjector/commit/49adbde371b3d9d7fcdaab411d01a976a46ef41c) first code commit (@protodave)
- [ff3b341](https://github.com/iconic/SVGInjector/commit/ff3b34194cab2a4655463c7d2f3cabbd242fcb28) copy formatting update (@protodave)
- [495f468](https://github.com/iconic/SVGInjector/commit/495f4681485831140d417003eac7b734430ab388) spelling fix (@protodave)
- [af53074](https://github.com/iconic/SVGInjector/commit/af530747f8039ddabb41d5238a5cd120d4989a51) code format fixes (@protodave)
- [9aeec36](https://github.com/iconic/SVGInjector/commit/9aeec3623a33770ddebdfbe54c6585e0d63a60e3) copy header update (@protodave)