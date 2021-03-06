#### 3.1.4 (2017-12-12)

##### Chores

* update release scripts ([6f81ed9a](https://github.com/wopian/kitsu/commit/6f81ed9ac521f434fc3c169faf4c773ab3499f1c))
* remove 3.1.2 commits from 3.1.3 changelog ([64acafd5](https://github.com/wopian/kitsu/commit/64acafd55bb623d1464afcd4ed8027ba66e7b46a))
* fix changelog versioning ([53c10dab](https://github.com/wopian/kitsu/commit/53c10dab5f539adc8b1c81566da7831ff2eb6159))
* update build scripts ([bc3b1807](https://github.com/wopian/kitsu/commit/bc3b1807238391afbe536a0f65271abf56da12c6))
* use common error function ([c25e4dc2](https://github.com/wopian/kitsu/commit/c25e4dc2cf81c7f4058239039ecdd5bff8604270))
* **deps:**
  * renovate eslint packages (#68) ([151405ff](https://github.com/wopian/kitsu/commit/151405ff5df73b9c2b41b833699a8a61575357a5))
  * renovate eslint packages (#67) ([b8c66c25](https://github.com/wopian/kitsu/commit/b8c66c256f96733636e6bb605956ee265d240b4f))
  * update generate-changelog to ~1.6.0 (#65) ([563fc22b](https://github.com/wopian/kitsu/commit/563fc22bf2af8fc5b15b8d844d22fb15d5591700))
  * update rollup to ~0.52.0 (#66) ([853fa39d](https://github.com/wopian/kitsu/commit/853fa39d6b2e8a017428324493a4f8b123d5cdfc))

##### Continuous Integration

* **travis:**
  * use existing oauth token ([1f7f8373](https://github.com/wopian/kitsu/commit/1f7f83733796774b4941600cd43b7f2138a5a7d7))
  * add package files to github releases ([2c6e577e](https://github.com/wopian/kitsu/commit/2c6e577e9a7712dfc2305f319bc28ef436aac4a2))
* test against LTS node versions ([184ee6f7](https://github.com/wopian/kitsu/commit/184ee6f7b4a0bcf909fea3ef9594155f89b0f605))

##### Documentation Changes

* add contributors badge ([7bb04ba8](https://github.com/wopian/kitsu/commit/7bb04ba8860f3741285a9dba1c04074c4fbf0439))
* fix kitsu.io docs url ([39b337a1](https://github.com/wopian/kitsu/commit/39b337a1ea61de2ff7194dee17e280f163a93a69))
* update donation link ([c43b10b3](https://github.com/wopian/kitsu/commit/c43b10b38cd053f8608f3ae1816044143e97d216))
* use https for kitsu.io api docs link ([c0494cbc](https://github.com/wopian/kitsu/commit/c0494cbc1fa51fb465c2888e8ca9edb1170d8cf6))
* update badges and add example response comparison ([70be0a71](https://github.com/wopian/kitsu/commit/70be0a71707b81cc2a19e324f7ff1485faedcbed))

##### Bug Fixes

* add parentheses to fix short-circuiting of URL version (#64) ([b74fd7e3](https://github.com/wopian/kitsu/commit/b74fd7e37c9913a20b6efbe6a96503b48473817c))

#### 3.1.3 (2017-11-26)

##### Bug Fixes

* add parentheses to fix short-circuiting of URL version (#64) ([b74fd7e3](https://github.com/wopian/kitsu/commit/b74fd7e37c9913a20b6efbe6a96503b48473817c))

#### 3.1.2 (2017-11-24)

##### Chores

* update build scripts ([bc3b1807](https://github.com/wopian/kitsu/commit/bc3b1807238391afbe536a0f65271abf56da12c6))
* use common error function ([c25e4dc2](https://github.com/wopian/kitsu/commit/c25e4dc2cf81c7f4058239039ecdd5bff8604270))

##### Continuous Integration

* test against LTS node versions ([184ee6f7](https://github.com/wopian/kitsu/commit/184ee6f7b4a0bcf909fea3ef9594155f89b0f605))

#### 3.1.1 (2017-11-24)

##### Chores

* **deps:**
  * renovate eslint packages (#62) ([115a8b0d](https://github.com/wopian/kitsu/commit/115a8b0d2bb1f3b2f4b200db7713d0540f655ea0))
  * update rollup to ~0.51.0 (#63) ([0b4ae24f](https://github.com/wopian/kitsu/commit/0b4ae24fb88fc6269e13a01bd145ebe0f55c044f))

##### Continuous Integration

* **travis:** remove greenkeeper integrations ([bfae4aae](https://github.com/wopian/kitsu/commit/bfae4aae8d9aefee2e37b38acc32af2e021ae458))

##### Bug Fixes

* handle empty data arrays ([d95f0593](https://github.com/wopian/kitsu/commit/d95f059364d4083cb362c4ff487050878a8a0850))

##### Tests

* add empty data array spec ([122387a1](https://github.com/wopian/kitsu/commit/122387a1262a9908fc130dceabf29feb207d3b5d))

### 3.1.0 (2017-11-07)

##### Chores

* add kitsu.io to npm tags ([fec517ba](https://github.com/wopian/kitsu/commit/fec517badb4103a36e23cb63330316333d46448c))
* disable lockfile maintenance ([aef0a52b](https://github.com/wopian/kitsu/commit/aef0a52b1d829fed8f48ac55d672710e1d996749))
* enable renovate (#60) ([27608b1f](https://github.com/wopian/kitsu/commit/27608b1f14914ed0346b0829a38e9fc2de198059))
* **deps:** update lock file (#61) ([dd37a4c6](https://github.com/wopian/kitsu/commit/dd37a4c6efb0986441d65ac065d32e70c8625989))

##### New Features

* allow additional headers with requests ([6872b4e5](https://github.com/wopian/kitsu/commit/6872b4e512dc31ea8e14a5aa307d2d4328d58802))

#### 3.0.4 (2017-11-02)

##### Chores

* HTTPS -> HTTP for Apiary API docs link ([ee6fd365](https://github.com/wopian/kitsu/commit/ee6fd36548490c7c40549d66e4bb3ec04a402d7c))

#### 3.0.3 (2017-11-01)

##### Chores

* loosen production dependencies to major versions ([8bb3bc35](https://github.com/wopian/kitsu/commit/8bb3bc35a65416e295f4e198ecbbe8756e768c69))
* remove oauth2 and authorisation tags ([fc13f42d](https://github.com/wopian/kitsu/commit/fc13f42d75bb3a1a0f145043b392361941c4bad2))

##### Continuous Integration

* disable appveyor cache until they fix unzipping it ([2b3f8d70](https://github.com/wopian/kitsu/commit/2b3f8d70f31e89e278ed8d483125c68163542f69))

##### Documentation Changes

* fix typos ([3a8c0aad](https://github.com/wopian/kitsu/commit/3a8c0aadcf4848399da0a5428db1bcaa2b39601e))
* fix timeout capitalisation ([eae07a2f](https://github.com/wopian/kitsu/commit/eae07a2fcb5ea69275e42d4334faca4ae0f9096b))
* reword features list ([ee3d0ccb](https://github.com/wopian/kitsu/commit/ee3d0ccbca924f89eb3ea507325523ba644b009a))
* fix compliant typo in README ([657cc188](https://github.com/wopian/kitsu/commit/657cc1886d2e730cb1566decf516cd6284ee46d9))
* reword kitsu.io api documentation ([eb814cec](https://github.com/wopian/kitsu/commit/eb814cec91865709c737f702e4620baee4486348))

#### 3.0.2 (2017-10-13)

##### Documentation Changes

* fix typo in header example (#53) ([0b682aee](https://github.com/wopian/kitsu/commit/0b682aee79bb361e58b0e28b0eb224f5c90f06ef))

#### 3.0.1 (2017-10-09)

##### Chores

* remove unused globals from rollup config ([f0e002ba](https://github.com/wopian/kitsu/commit/f0e002baec59767886e64f97cf08b072fc41e930))

## 3.0.0 (2017-10-09)

##### **BREAKING CHANGES**

- Built in oAuth2 authentication has been removed. Use `client-oauth2` directly (example in `auth.js`)

- Option variable for the API URL and version on creating a new instance has changed
  - `apiUrl` is now `baseURL`
  - `apiVer` is now `version`

- Removed the `compact` option in the `whoAmI` function

- Removed the network failure retry ability (was a built-in feature of `got` not included with `axios`)

##### Chores

* readd header (broken) ([4d2ad285](https://github.com/wopian/kitsu/commit/4d2ad285c13c14673af8b53ac6ac9b015376a943))
* add doc linter command ([2481775d](https://github.com/wopian/kitsu/commit/2481775d19ee9411e04f939b6d99fd350a5cb6f9))

##### Documentation Changes

* update documentation and examples ([a43bc4fa](https://github.com/wopian/kitsu/commit/a43bc4fa4a289dc552ef452e08c667ad7d2f62f2))
* add destructuring example to readme ([28585a34](https://github.com/wopian/kitsu/commit/28585a349fe5c16aa2efe463c08c4464e64a3193))

##### New Features

* migrate utils to axios ([6a4ea87d](https://github.com/wopian/kitsu/commit/6a4ea87d6f2c86850810b1e75e9977e8983ee388))
* migrate whoAmI to axios ([e741b0fc](https://github.com/wopian/kitsu/commit/e741b0fc5532f303de45f033b9953af4298135ae))
* migrate update to axios ([581805b5](https://github.com/wopian/kitsu/commit/581805b5674c64b777569c2f6ebbf4a98bbea8b8))
* migrate remove to axios ([3eb7d335](https://github.com/wopian/kitsu/commit/3eb7d3354bea91eb01e89c4fd7e56656d62a2439))
* migrate fetch to axios ([6f255f84](https://github.com/wopian/kitsu/commit/6f255f84b1916ac7a388ec88af50159df39fc61a))
* migrate create to axios ([dbaacfae](https://github.com/wopian/kitsu/commit/dbaacfae5d0003b6fe0e8ae83afaf4f739841e52))
* switch to axios ([3cd7e5f8](https://github.com/wopian/kitsu/commit/3cd7e5f84942f3adae80fd7c7a1b0e14a49e7539))

##### Bug Fixes

* fix changing headers ([bdab1937](https://github.com/wopian/kitsu/commit/bdab1937471fc01242712bd720ac7f1648956671))

#### 2.0.4 (2017-08-10)

##### Chores

* update yarn.lock ([c7bfbc79](https://github.com/wopian/kitsu/commit/c7bfbc79d50c1adfa410ec3d06f379b28cce6a98))

##### Documentation Changes

* fix compliant typo ([95dbdd18](https://github.com/wopian/kitsu/commit/95dbdd189a4bae51cc16a2f19a343e908960e629))

#### 2.0.3 (2017-07-23)

##### Build System / Dependencies

* codeclimate ignore spec files ([eacdfea5](https://github.com/wopian/kitsu/commit/eacdfea546f4bab653fd51b7f68cd48321136609))

##### Documentation Changes

* fix link to repo LICENSE ([dccdb9ea](https://github.com/wopian/kitsu/commit/dccdb9eae252711dd25395cb299c9586f15e6da4))
* add resource relationship example ([794bf978](https://github.com/wopian/kitsu/commit/794bf97898ef9fb3421e4a028b1189119c23262e))
* update apiUrl override example ([8ce83d27](https://github.com/wopian/kitsu/commit/8ce83d27e14b5b41d286ef50b751dae4238dc252))

##### Bug Fixes

* bind methods outside of constructor (fixes aliases) ([9d3f74fd](https://github.com/wopian/kitsu/commit/9d3f74fd84a7f4296577b8d7c0bc08c8f751063b))

#### 2.0.2 (2017-07-19)

##### Build System / Dependencies

* codeclimate ignore spec files ([eacdfea5](https://github.com/wopian/kitsu/commit/eacdfea546f4bab653fd51b7f68cd48321136609))

##### Bug Fixes

* bind methods outside of constructor (fixes aliases) ([ed319d9c](https://github.com/wopian/kitsu/commit/ed319d9c692d15a94cdec7b4859c387c8a35e205))

#### 2.0.1 (2017-07-18)

##### Documentation Changes

* update package description ([61968965](https://github.com/wopian/kitsu/commit/619689659c3a1065884dd5df19338694063aeb31))

## 2.0.0 (2017-07-18)

##### **BREAKING CHANGES**

- Attributes have been moved to the parent object
  - `data.attributes.canonicalTitle` becomes `data.canonicalTitle`

- The relationship name is now used in the `GET` output instead of the relationship type, i.e:
  - In 1.x, the `waifu` relationship erroneously became `characters: {}`
  - In 2.x it remains `waifu: {}`

- Removing resources has been simplified
  - `kitsu.remove('model', { id: 1 })` becomes `kitsu.remove('model', 1)`

- `header` (previously `setHeader`) has been **removed**. Identical implementation was already provided
  by `headers`
  - `kitsu.header('key', 'value')` becomes `kitsu.headers['key'] = 'value'`
  - `kitsu.headers['key']` returns the header's `value` (1.x)

##### Build System / Dependencies

* update path to test coverage ([a167daa4](https://github.com/wopian/kitsu/commit/a167daa494d0f36b3e4dd59cd984a6b6647254c4))

##### Chores

* add apiVer back ([dc6bf3ed](https://github.com/wopian/kitsu/commit/dc6bf3ed1a9ee91fe6d40b908739a1dfb6709d22))
* add new example to package.json ([b3a78fb8](https://github.com/wopian/kitsu/commit/b3a78fb864a80594fbdf2a9355d4cc4c4954e6e8))
* remove debugging calls ([7f57f736](https://github.com/wopian/kitsu/commit/7f57f736e70ba009baa9131ff59ecf0fb8ff2215))
* update examples ([ae390a88](https://github.com/wopian/kitsu/commit/ae390a8816df62799045caddd62998f27946bef4))
* move aliases to top of class ([8701af60](https://github.com/wopian/kitsu/commit/8701af6078a4281cdac55a134bbeaf8dddf478d0))

##### Documentation Changes

* split contributing into seperate file ([494f15a4](https://github.com/wopian/kitsu/commit/494f15a439686d6990c2d7da08cff76542cb9808))
* mention existing functionality of kitsu.headers ([4ea1c848](https://github.com/wopian/kitsu/commit/4ea1c848ab7fa55e9917cd4b1cd25d87c253274e))
* add 2.0 migration guide ([db148b3c](https://github.com/wopian/kitsu/commit/db148b3c0b1676ccc719db6f5048f4f99b128de8))
* add a more complex example ([dbc700fb](https://github.com/wopian/kitsu/commit/dbc700fbf9a8d12a42375ce7ea406e2a74856a11))
* update auth example ([b03fcff9](https://github.com/wopian/kitsu/commit/b03fcff9b61a372ede6375c7109aa948b741891e))

##### New Features

* simplify remove method ([a3325fda](https://github.com/wopian/kitsu/commit/a3325fda580d18802439a1f74766edcf7c33cbf8))
* removed header (use headers) ([f3a0af63](https://github.com/wopian/kitsu/commit/f3a0af6328aefcf2d6df40b9e5cfa29f6d2d6032))

##### Bug Fixes

* link relationship arrays without discarding everything after first ([0d76f02e](https://github.com/wopian/kitsu/commit/0d76f02ed7780b7fac8cf707f133d48f20091c95))
* prevent linking relationships twice ([71cc4e86](https://github.com/wopian/kitsu/commit/71cc4e86637499ec7787f75ae97ef700e59e526e))
* correct deserialise implementation for arrays ([17965b38](https://github.com/wopian/kitsu/commit/17965b3803d979c4750de99c0a5ade2d537ea84c))
* properly pass request errors ([93c89f67](https://github.com/wopian/kitsu/commit/93c89f67a3fcc5aea5192af938fa6faecfaba59a))
* handle relationship arrays ([faf2884c](https://github.com/wopian/kitsu/commit/faf2884c2138d0c4a21c8b8f9e6b6403ec2300f0))
* move attributes into parent object ([80785480](https://github.com/wopian/kitsu/commit/8078548015d3d5b12067c014059c8d24b03ce0f5))
* use relationship name instead of type for deserialised relationships key ([9640f318](https://github.com/wopian/kitsu/commit/9640f318a38302c3e8e1a65832a70f560961c129))

##### Reverts

* json parse before throwing errors ([6fd7962d](https://github.com/wopian/kitsu/commit/6fd7962d01e3620816110d64f3290275d3c296b9))

##### Tests

* add assertions to ensure async failures ([f2f262bf](https://github.com/wopian/kitsu/commit/f2f262bf369dd4a5568983d6e092f0b39d4f2063))
* update deattribute test name ([a2b07be1](https://github.com/wopian/kitsu/commit/a2b07be133e15569d1b3be4e149feb39ecaf7185))
* add tests for util functions ([11443d70](https://github.com/wopian/kitsu/commit/11443d707672d6741a24db090620f87a3f16c707))

### 1.3.0 (2017-07-16)

##### Build System / Dependencies

* correct EOL type ([bbd51d1b](https://github.com/wopian/kitsu/commit/bbd51d1b86e6f185fc903044e92d5d42dc4cfbb2))

##### Performance Improvements

* bind methods instead of assigning ([d14599b9](https://github.com/wopian/kitsu/commit/d14599b93a9cc50a9a549e0947935e9184f376ef))

##### Refactors

* rename setHeader to header ([6bd9ae92](https://github.com/wopian/kitsu/commit/6bd9ae9231d87b9896b88c8fa93f065e00af7aee))
* change opts to options ([c1a89b20](https://github.com/wopian/kitsu/commit/c1a89b2027b4237c5dbc9862cb5ecafdfa8c4251))

##### Reverts

* change options back to opts ([c55b0ecc](https://github.com/wopian/kitsu/commit/c55b0ecc8e52eab968d9d1b975a43593ed7d8d9c))

#### 1.2.2 (2017-07-16)

##### Build System / Dependencies

* use rollup-cleanup over uglify-es ([2eb60f3c](https://github.com/wopian/kitsu/commit/2eb60f3c441224cb060a18ffd49d1e308d612641))

##### Documentation Changes

* add more get examples ([005bd996](https://github.com/wopian/kitsu/commit/005bd99644e2f49c60baf14c78866048b1ccc00a))

##### Refactors

* split class into multiple files ([8cf599e0](https://github.com/wopian/kitsu/commit/8cf599e0324c0e7492e96b4f4a0d09992583ea80))

#### 1.2.1 (2017-07-08)

##### Build System / Dependencies

* cause release script to fail on test failures ([b10dc982](https://github.com/wopian/kitsu/commit/b10dc98256468b63c9a2f86e44202af817674f8c))

##### Bug Fixes

* ensure isAuth returns true when header set ([1f3ee195](https://github.com/wopian/kitsu/commit/1f3ee19549855df77fb3609d74819d7196154f2a))

### 1.2.0 (2017-07-06)

##### Bug Fixes

* throw new errors ([5aaf154a](https://github.com/wopian/kitsu/commit/5aaf154aac4c2785835c5564a431d1d4b0181c1a))

### 1.1.0 (2017-07-06)

##### Chores

* update examples ([1b5ed7b5](https://github.com/wopian/kitsu/commit/1b5ed7b56196843af2c2ad7e9ef2f8c9a64c80ee))

##### Bug Fixes

* throw errors ([8fd2979e](https://github.com/wopian/kitsu/commit/8fd2979e9a747219377293364ee0c40a0f05ae07))
* kebab-case method names ([97907060](https://github.com/wopian/kitsu/commit/97907060ef713fa8e97e05a5deae0492227edb28))

#### 1.0.3 (2017-07-06)

##### Chores

* remove debug log ([17e54311](https://github.com/wopian/kitsu/commit/17e5431188e923ce9bc72f917d288c46f2bd99c0))

##### Continuous Integration

* disable email notifications ([e2baf0f8](https://github.com/wopian/kitsu/commit/e2baf0f8ecf770d637ffb131c35a70ea782f1a01))

#### 1.0.2 (2017-07-06)

##### Chores

* add npm publish to release command ([d23c4fa0](https://github.com/wopian/kitsu/commit/d23c4fa0348190777bb5ba1d350ba7ee771a4dac))
* improve release commit message ([d06e5ff3](https://github.com/wopian/kitsu/commit/d06e5ff350bb7c6ffdb893dee238439dc0b41ea2))

##### New Features

* check if console exists before logging ([046f3ab6](https://github.com/wopian/kitsu/commit/046f3ab6b63092f24fdaae017363cfc923950b24))

#### 1.0.1 (2017-07-06)

##### Build System / Dependencies

* bump version ([aefdf577](https://github.com/wopian/kitsu/commit/aefdf57738e918b4a71317b553031f05780666da))

##### Chores

* changelog adjustments ([3a7bc94f](https://github.com/wopian/kitsu/commit/3a7bc94ff385f9b7ee5829f6b9c644cdb9faa419))
* add docs to npm releases ([c00e2f0b](https://github.com/wopian/kitsu/commit/c00e2f0bcfa976f090f35b8563958fe6a3ca4933))

## 1.0.0 (2017-07-06)

##### Added

- POST requests (`kitsu.<post|create>`)
- PATCH requests (`kitsu.<patch|update>`)
- DELETE requests (`kitsu.<remove|destroy>`)
- Aliases for GET requests (`kitsu.<fetch|find>`)

## 0.2.0 (2017-07-05)

##### Added

- Exposed headers (`kitsu.headers`)

##### Changed

- Updated package description
- Documented the api

## 0.1.2 (2017-06-30)

##### Added

- ES6 module version for webpack 2/3

## 0.1.1 (2017-06-29)

##### Fixed

- Added `babel-runtime` to dependencies

##### Removed

- Removed build files from published package

## 0.1.0 (2017-06-29)

##### Added

- GET requests for all models
- JSON API query parameters
- Authentication
