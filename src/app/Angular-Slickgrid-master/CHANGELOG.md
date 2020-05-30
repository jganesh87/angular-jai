# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [2.18.7](https://github.com/ghiscoding/angular-slickgrid/compare/v2.18.6...v2.18.7) (2020-05-26)


### Features

* **gridMenu:** update SlickGrid & add new Grid Menu options, fixes [#464](https://github.com/ghiscoding/angular-slickgrid/issues/464) ([#473](https://github.com/ghiscoding/angular-slickgrid/issues/473)) ([10f0b7d](https://github.com/ghiscoding/angular-slickgrid/commit/10f0b7d94f81569d238d411153aac4a559242302))


### Bug Fixes

* **footer:** custom footer metric texts could not be changed, fixes [#470](https://github.com/ghiscoding/angular-slickgrid/issues/470) ([#472](https://github.com/ghiscoding/angular-slickgrid/issues/472)) ([2681596](https://github.com/ghiscoding/angular-slickgrid/commit/2681596620d238eb738658f28dfb8d35968dd904))
* **gridMenu:** command "Toggle Filter Row" header row ([#466](https://github.com/ghiscoding/angular-slickgrid/issues/466)) ([4858794](https://github.com/ghiscoding/angular-slickgrid/commit/48587941e758d9396f38f0d2edf2da8a22ebb93d)), closes [#448](https://github.com/ghiscoding/angular-slickgrid/issues/448)
* **locale:** use correct locale text operator tooltip, closes [#468](https://github.com/ghiscoding/angular-slickgrid/issues/468) ([#469](https://github.com/ghiscoding/angular-slickgrid/issues/469)) ([d978946](https://github.com/ghiscoding/angular-slickgrid/commit/d978946391fd21bf1f30fdf9a612fe0621922ae7))
* **odata:** encode URI also for IN/NIN operators, fixes [#463](https://github.com/ghiscoding/angular-slickgrid/issues/463) ([#471](https://github.com/ghiscoding/angular-slickgrid/issues/471)) ([92bf9e3](https://github.com/ghiscoding/angular-slickgrid/commit/92bf9e3498173cdc6bd9b0307328b7809c11263f))
* **resizer:** check for undefined option instead of fallback ([#474](https://github.com/ghiscoding/angular-slickgrid/issues/474)) ([59975f0](https://github.com/ghiscoding/angular-slickgrid/commit/59975f042002eab4b49cde6b867dff3cdd881cc9))

### [2.18.6](https://github.com/ghiscoding/angular-slickgrid/compare/v2.18.5...v2.18.6) (2020-05-19)


### Bug Fixes

* **styling:** remove fixed header height ([9cef192](https://github.com/ghiscoding/angular-slickgrid/commit/9cef192a93aa9152f4954eca1ef4ac3c0f7a2d96))

### [2.18.5](https://github.com/ghiscoding/angular-slickgrid/compare/v2.18.4...v2.18.5) (2020-05-19)

### [2.18.4](https://github.com/ghiscoding/angular-slickgrid/compare/v2.18.3...v2.18.4) (2020-05-19)

### [2.18.3](https://github.com/ghiscoding/angular-slickgrid/compare/v2.18.2...v2.18.3) (2020-05-19)

### [2.18.2](https://github.com/ghiscoding/angular-slickgrid/compare/v2.17.12...v2.18.2) (2020-05-19)

### [2.18.1](https://github.com/ghiscoding/angular-slickgrid/compare/v2.17.11...v2.18.1) (2020-05-19)


### Features

* **editor:** add new Dual Input Editor & extract all Editor Validators ([#446](https://github.com/ghiscoding/angular-slickgrid/issues/446)) ([06f5dc9](https://github.com/ghiscoding/angular-slickgrid/commit/06f5dc9ba4826e2b018e71d4991ba04f6bec17a4))
* **extension:** add column position option for checkbox row selector ([fc72ba0](https://github.com/ghiscoding/angular-slickgrid/commit/fc72ba0217712f5c085b2274dd0dbf3f41a6b6d4))
* **extension:** add column position option for Row Detail icon ([#419](https://github.com/ghiscoding/angular-slickgrid/issues/419)) ([36bdcd1](https://github.com/ghiscoding/angular-slickgrid/commit/36bdcd1e9ff9cd6e931967445240e234dad86bbd))
* **extension:** add latest slickgrid with RowMove improvements ([#428](https://github.com/ghiscoding/angular-slickgrid/issues/428)) ([4f4b231](https://github.com/ghiscoding/angular-slickgrid/commit/4f4b2316c668f23460212de5b7480d7f7f72dce4)), closes [#256](https://github.com/ghiscoding/angular-slickgrid/issues/256)
* **grouping:** add missing Grouping interface properties, closes [#430](https://github.com/ghiscoding/angular-slickgrid/issues/430) ([#432](https://github.com/ghiscoding/angular-slickgrid/issues/432)) ([fe7a65a](https://github.com/ghiscoding/angular-slickgrid/commit/fe7a65add869f7b708dc8dbb75d3c39b5e753a8c))
* **query:** add queryFieldNameGetterFn callback know which field to use ([#434](https://github.com/ghiscoding/angular-slickgrid/issues/434)) ([0d5a150](https://github.com/ghiscoding/angular-slickgrid/commit/0d5a150c324e000e1de5bc7ebeb846c6c48ba122))
* **sort:** add valueCouldBeUndefined column flag to help sorting ([#429](https://github.com/ghiscoding/angular-slickgrid/issues/429)) ([dcd7a41](https://github.com/ghiscoding/angular-slickgrid/commit/dcd7a410602313dc65559091a0945cca599f8269))
* **style:** add Sort icon hint on hover when column is sortable ([#435](https://github.com/ghiscoding/angular-slickgrid/issues/435)) ([a746c2d](https://github.com/ghiscoding/angular-slickgrid/commit/a746c2d5e3f78a5c7f759ae94b2d0c1c698231ee))
* **styling:** add CSS/SASS Material Design & Salesforce styling themes ([#454](https://github.com/ghiscoding/angular-slickgrid/issues/454)) ([0030763](https://github.com/ghiscoding/angular-slickgrid/commit/00307637bed9dd575f250af3919a4949f6902ce3))
* **translate:** add namespace prefix + separator grid option ([#462](https://github.com/ghiscoding/angular-slickgrid/issues/462)) ([c23370e](https://github.com/ghiscoding/angular-slickgrid/commit/c23370ed12e36edd64e1d897210f09ec8f2827f3))
* **treeData:** add new Tree Data View feature, closes [#178](https://github.com/ghiscoding/angular-slickgrid/issues/178) ([#455](https://github.com/ghiscoding/angular-slickgrid/issues/455)) ([3250bde](https://github.com/ghiscoding/angular-slickgrid/commit/3250bde0696a81913d196a2f97dfca5f6e53ab5b))


### Bug Fixes

* **editor:** disregard Flatpickr error on Date Editor and fix output format ([#445](https://github.com/ghiscoding/angular-slickgrid/issues/445)) ([96e2973](https://github.com/ghiscoding/angular-slickgrid/commit/96e2973745b77237306fdbb7cd3ed504224a5147))
* **export:** add grouped header title (from pre-header) into exports ([#436](https://github.com/ghiscoding/angular-slickgrid/issues/436)) ([a315f85](https://github.com/ghiscoding/angular-slickgrid/commit/a315f859ca842db7ef8cb53205bfd7117c802f48))
* **export:** remove unsupported file type, closes [#452](https://github.com/ghiscoding/angular-slickgrid/issues/452) ([#458](https://github.com/ghiscoding/angular-slickgrid/issues/458)) ([c00b6ab](https://github.com/ghiscoding/angular-slickgrid/commit/c00b6ab3915eb02dafed48d9bf51fa6b29e285f3))
* **filter:** string filter should also work when using Contains ([#427](https://github.com/ghiscoding/angular-slickgrid/issues/427)) ([2c0765b](https://github.com/ghiscoding/angular-slickgrid/commit/2c0765bcc95c22620645d82810e021fc9f622d93))
* **filter:** when entering filter operator it shouldn't do any filtering ([#431](https://github.com/ghiscoding/angular-slickgrid/issues/431)) ([9d53315](https://github.com/ghiscoding/angular-slickgrid/commit/9d5331505fab44c5f1d977631d85092c84329675))
* **formatter:** exportWithFormatter should work with undefined item prop ([#457](https://github.com/ghiscoding/angular-slickgrid/issues/457)) ([3cfcab1](https://github.com/ghiscoding/angular-slickgrid/commit/3cfcab1f63b1bfa5625bceb4151e0ac6aa02675c))
* **gridMenu:** column picker list should include grouped header titles ([#460](https://github.com/ghiscoding/angular-slickgrid/issues/460)) ([e4a34a0](https://github.com/ghiscoding/angular-slickgrid/commit/e4a34a0dff7c330afaa746b3b79a4ce7e0425a7d))
* **gridMenu:** command "Togge Filter" disappeared, fixes [#438](https://github.com/ghiscoding/angular-slickgrid/issues/438) ([#448](https://github.com/ghiscoding/angular-slickgrid/issues/448)) ([b10c5be](https://github.com/ghiscoding/angular-slickgrid/commit/b10c5bee31129263df9fcd7c17c5a6e4e06eb9d1))
* **gridService:** crud methods should support custom dataset id ([#453](https://github.com/ghiscoding/angular-slickgrid/issues/453)) ([2c91f35](https://github.com/ghiscoding/angular-slickgrid/commit/2c91f353537de738d71e7d7fd97151831d167943))
* **pagination:** passing custom pagination sizes should work, fixes [#456](https://github.com/ghiscoding/angular-slickgrid/issues/456) ([#459](https://github.com/ghiscoding/angular-slickgrid/issues/459)) ([0367625](https://github.com/ghiscoding/angular-slickgrid/commit/0367625b926ea05d4afee970ce0b02c5939d15e2))
* **resizer:** remove scrollbar measure compensate patch ([#424](https://github.com/ghiscoding/angular-slickgrid/issues/424)) ([bca1f0b](https://github.com/ghiscoding/angular-slickgrid/commit/bca1f0b5520cd9ed1b97ce1730feaeeda7953cb4))
* **rowDetail:** use latest SlickGrid to fix issue with id, fixes [#440](https://github.com/ghiscoding/angular-slickgrid/issues/440) ([#449](https://github.com/ghiscoding/angular-slickgrid/issues/449)) ([8f16559](https://github.com/ghiscoding/angular-slickgrid/commit/8f1655940d9359b17307bc874301cc7ff86d0ecd))
* **sort:** header menu sorting should include columnId property ([0c47038](https://github.com/ghiscoding/angular-slickgrid/commit/0c47038367d4d5aa4b0dd572b860e7de87901650))

### [2.17.11](https://github.com/ghiscoding/angular-slickgrid/compare/v2.17.10...v2.17.11) (2020-03-18)


### Features

* **sort:** add default sort field as grid option ([00b0751](https://github.com/ghiscoding/angular-slickgrid/commit/00b0751277a7d1c4311e56e282700a745c34275f))


### Bug Fixes

* **formatters:** decimalSeparator & thousandSeparator work tgt, fix [#411](https://github.com/ghiscoding/angular-slickgrid/issues/411) ([67318d5](https://github.com/ghiscoding/angular-slickgrid/commit/67318d53f4828a6631a3bf6c5174260005031399))
* **tests:** fix failing Cypress E2E from last commit ([72870f4](https://github.com/ghiscoding/angular-slickgrid/commit/72870f4cdddd97f092aaff2fc3e6d312b1b54879))
* **types:** fix TS type warnings ([af146fb](https://github.com/ghiscoding/angular-slickgrid/commit/af146fb73e30ed9bae2cb067fd653d06b5016cf8))

### [2.17.10](https://github.com/ghiscoding/angular-slickgrid/compare/v2.17.9...v2.17.10) (2020-03-03)


### Bug Fixes

* **columns:** remove columns dynamically with Editors, fixes [#406](https://github.com/ghiscoding/angular-slickgrid/issues/406) ([903473d](https://github.com/ghiscoding/angular-slickgrid/commit/903473d280b6d9f4992603c1b867a442a50ffa99))

### [2.17.9](https://github.com/ghiscoding/angular-slickgrid/compare/v2.17.8...v2.17.9) (2020-03-02)


### Bug Fixes

* **columns:** add/remove columns dynamically, fixes [#406](https://github.com/ghiscoding/angular-slickgrid/issues/406) ([324cb1a](https://github.com/ghiscoding/angular-slickgrid/commit/324cb1a97fcd8e0362e2c656a091f3289e155119))
* **example:** should re-render after clearing groups, fixes [#407](https://github.com/ghiscoding/angular-slickgrid/issues/407) ([7752abd](https://github.com/ghiscoding/angular-slickgrid/commit/7752abd27933a51d5e58c3e305ceff791400ea88))

### [2.17.8](https://github.com/ghiscoding/angular-slickgrid/compare/v2.17.7...v2.17.8) (2020-02-27)


### Bug Fixes

* **mousewheel:** add jquery mousewheel lib to fix scroll in frozen grid ([d2bc0e7](https://github.com/ghiscoding/angular-slickgrid/commit/d2bc0e7afd9fd507c4214e12289cf2ef39930c29))

### [2.17.7](https://github.com/ghiscoding/angular-slickgrid/compare/v2.17.6...v2.17.7) (2020-02-27)

### [2.17.6](https://github.com/ghiscoding/angular-slickgrid/compare/v2.17.5...v2.17.6) (2020-02-27)


### Bug Fixes

* **editor:** LongText Editor save button that was not working properly ([90beeac](https://github.com/ghiscoding/angular-slickgrid/commit/90beeacebdc03d8bdfdb163c9813a54a7d2e68b6))

### [2.17.5](https://github.com/ghiscoding/angular-slickgrid/compare/v2.17.4...v2.17.5) (2020-02-21)


### Features

* **excel:** add some extra styling & width options for Excel export ([#403](https://github.com/ghiscoding/angular-slickgrid/issues/403)) ([d87ce2c](https://github.com/ghiscoding/angular-slickgrid/commit/d87ce2c89aa9fc8142a0a694e445f193a92ea19e))
* **tests:** update to latest Cypress version ([dc3afa9](https://github.com/ghiscoding/angular-slickgrid/commit/dc3afa93751761c06c222b9765c44dd9afb18525))

### [2.17.4](https://github.com/ghiscoding/angular-slickgrid/compare/v2.17.3...v2.17.4) (2020-02-06)


### Bug Fixes

* **selection:** row selection always be kept, closes [#295](https://github.com/ghiscoding/angular-slickgrid/issues/295) again ([#399](https://github.com/ghiscoding/angular-slickgrid/issues/399)) ([5e8f1df](https://github.com/ghiscoding/angular-slickgrid/commit/5e8f1df472b899e488fa9b930bedca8895f5e8f4))

### [2.17.3](https://github.com/ghiscoding/angular-slickgrid/compare/v2.17.2...v2.17.3) (2020-02-05)


### Bug Fixes

* **pagination:** on filter change pagination should reset to 1st page ([#397](https://github.com/ghiscoding/angular-slickgrid/issues/397)) ([af64dd6](https://github.com/ghiscoding/angular-slickgrid/commit/af64dd61523363cc7677a0e6d5813cfa753d2213))
* **selection:** filter data should work with row selection, closes [#295](https://github.com/ghiscoding/angular-slickgrid/issues/295) ([#393](https://github.com/ghiscoding/angular-slickgrid/issues/393)) ([f36a4f7](https://github.com/ghiscoding/angular-slickgrid/commit/f36a4f794458f68434de4edad4a52a93dcbafc51))

### [2.17.2](https://github.com/ghiscoding/angular-slickgrid/compare/v2.17.1...v2.17.2) (2020-02-03)

### [2.17.1](https://github.com/ghiscoding/angular-slickgrid/compare/v2.17.0...v2.17.1) (2020-02-03)


### Bug Fixes

* **backend:** updateOptions can be use with partial options - TS type ([80bdaa5](https://github.com/ghiscoding/angular-slickgrid/commit/80bdaa5270aa613a1bbc6794c7d97950089a3e2e))
* **footer:** custom footer should work anytime pagination is disabled ([7d9798a](https://github.com/ghiscoding/angular-slickgrid/commit/7d9798aedf25653375f0344afa04297fb2c7ef69))
* **locales:** fix some Locales not showing up when not using Translate ([#392](https://github.com/ghiscoding/angular-slickgrid/issues/392)) ([4d5e65b](https://github.com/ghiscoding/angular-slickgrid/commit/4d5e65b0697276cb827f1bc0355e8dff378304b1))

## [2.17.0](https://github.com/ghiscoding/angular-slickgrid/compare/v2.16.5...v2.17.0) (2020-01-31)


### Features

* **menus:** add "onAfterMenuShow" event to all possible menu plugins ([#389](https://github.com/ghiscoding/angular-slickgrid/issues/389)) ([141d01a](https://github.com/ghiscoding/angular-slickgrid/commit/141d01ac9aa52ffe182453c31318456f67c74788))
* **selection:** add flag to disable syncGridSelection w/BackendService ([#390](https://github.com/ghiscoding/angular-slickgrid/issues/390)) ([f29c6f0](https://github.com/ghiscoding/angular-slickgrid/commit/f29c6f0298d02f4eddf528d034afa0e5dd2747a6))
* **selection:** preserve row selection & add it to Grid State & Presets ([#388](https://github.com/ghiscoding/angular-slickgrid/issues/388)) ([a50d489](https://github.com/ghiscoding/angular-slickgrid/commit/a50d489080a11490d54b728962849408f6ae091a)), closes [#295](https://github.com/ghiscoding/angular-slickgrid/issues/295)

### [2.16.5](https://github.com/ghiscoding/angular-slickgrid/compare/v2.16.4...v2.16.5) (2020-01-23)


### Bug Fixes

* **state:** Clear Sort should trigger only 1 event & fix Pagination ([8e4f931](https://github.com/ghiscoding/angular-slickgrid/commit/8e4f93102329173f65e2e6054dec54824bd0b85a))

### [2.16.4](https://github.com/ghiscoding/angular-slickgrid/compare/v2.16.3...v2.16.4) (2020-01-23)


### Bug Fixes

* **backend:** fix build warnings ([c72ccc9](https://github.com/ghiscoding/angular-slickgrid/commit/c72ccc92ede37504efc7e19798082765e486bdfc))
* **columns:** Column Grouping should re-render after cols reordering ([bd991f0](https://github.com/ghiscoding/angular-slickgrid/commit/bd991f06ee6b891f9d26e28325e32a9e1ad38c11))
* **formatter:** refine condition to display a checkmark icon ([507b299](https://github.com/ghiscoding/angular-slickgrid/commit/507b2995f10f0c1475e41044a959244b3b928980))

### [2.16.3](https://github.com/ghiscoding/angular-slickgrid/compare/v2.16.2...v2.16.3) (2020-01-22)


### Bug Fixes

* **build:** remove extensionUtility DI to fix build ([42cc4b4](https://github.com/ghiscoding/angular-slickgrid/commit/42cc4b44917bccdb189e571c369403047ac69f01))

### [2.16.2](https://github.com/ghiscoding/angular-slickgrid/compare/v2.16.1...v2.16.2) (2020-01-22)


### Features

* **columnGroup:** add columnGroupKey property in order to use translate ([147470f](https://github.com/ghiscoding/angular-slickgrid/commit/147470febe5327f36e569fb934a883059ba76a30))


### Bug Fixes

* **tests:** fix a Cypress E2E flaky test ([8fb09e2](https://github.com/ghiscoding/angular-slickgrid/commit/8fb09e21660b8a02ce420aa08ed62bcefb735f8f))

### [2.16.1](https://github.com/ghiscoding/angular-slickgrid/compare/v2.16.0...v2.16.1) (2020-01-21)


### Bug Fixes

* **build:** create & use separate excel-builder package to fix security ([c114ae0](https://github.com/ghiscoding/angular-slickgrid/commit/c114ae0df149ebef361701d25253a570ed43077f))
* **footer:** fix Custom Footer styling issues with Bootstrap 4 ([658a9fd](https://github.com/ghiscoding/angular-slickgrid/commit/658a9fdd3aee12071396aa455901fd22f61c0352))
* **pagination:** should be empty (0) when filtering an empty dataset ([7409832](https://github.com/ghiscoding/angular-slickgrid/commit/74098325661b012f90acb9c57cf4aac2fe47e04b))

## [2.16.0](https://github.com/ghiscoding/angular-slickgrid/compare/v2.15.4...v2.16.0) (2020-01-20)


### Features

* **backend:** add OData & GraphQL Service API interfaces ([43d3a00](https://github.com/ghiscoding/angular-slickgrid/commit/43d3a00deed0e0ab8ecda3fa10f5cb2a7cb47973))
* **backend:** add OData & GraphQL Service API interfaces ([11cc71c](https://github.com/ghiscoding/angular-slickgrid/commit/11cc71cb23bc173494c7af1a87364e452cc9854e))
* **backend:** add option to use local filtering/sorting strategy ([73c288b](https://github.com/ghiscoding/angular-slickgrid/commit/73c288b9faccdd93e17b7b67d1df984adcd51725))
* **examples:** add new GraphQL without Pagination Example ([f02ac2d](https://github.com/ghiscoding/angular-slickgrid/commit/f02ac2d4c6519a6267aa398ccc745c1e02b21901))
* **footer:** add custom footer to show metrics ([2054319](https://github.com/ghiscoding/angular-slickgrid/commit/205431935e33e81f82332dabd85f94a74a9a0fb6))
* **pagination:** add Pagination to local grid ([53aa9dc](https://github.com/ghiscoding/angular-slickgrid/commit/53aa9dc0c3fd8209c8a667ad27c9ef2e0f88340f))
* **rowDetail:** add few object instances that can be used in child comp ([9cc52c3](https://github.com/ghiscoding/angular-slickgrid/commit/9cc52c331dcfc7af413783518e739e44674c426c))
* **rowDetail:** add Parent property to pass ref to parent comp ([dd8c1cd](https://github.com/ghiscoding/angular-slickgrid/commit/dd8c1cdb4bbd0a867dfca61adb2ddb2f3b674afe))
* **tests:** add Cypress E2E for Local Pagination and fix new bugs found ([b7b1a73](https://github.com/ghiscoding/angular-slickgrid/commit/b7b1a7362a50e0994a585c9e57a6df50342fd774))


### Bug Fixes

* **backend:** cancel prior http calls to avoid inconsistent data shown ([f9aaf54](https://github.com/ghiscoding/angular-slickgrid/commit/f9aaf545d3f5f9444f606a9a706245fb6cc5f0af))
* **build:** TS warning on a missing Type ([b894ee1](https://github.com/ghiscoding/angular-slickgrid/commit/b894ee1606363c891615cd87ef9a4182ea07c78b))
* **cypress:** fix failing Cypress E2E test ([e78b2d9](https://github.com/ghiscoding/angular-slickgrid/commit/e78b2d96a499db4ecedc196c80ad3c3db0e44dab))
* **examples:** use spinner only when loading data ([d0b4820](https://github.com/ghiscoding/angular-slickgrid/commit/d0b48201637870d33a3b12664a22bfc0903a1c39))
* **examples:** use valid date format ([f66703a](https://github.com/ghiscoding/angular-slickgrid/commit/f66703adf4e9b4f9f0d46e648d829b761c1a9b6e))
* **filter:** creating blank entry should only be entered once ([3b769a4](https://github.com/ghiscoding/angular-slickgrid/commit/3b769a4ee2005d4ea240050699e2323e78112a8e))
* **filters:** remove filter DOM element IDs to avoid duplicate IDs ([4b83133](https://github.com/ghiscoding/angular-slickgrid/commit/4b83133ff717f1f839bf2912b5b14ff9ef38bec2))
* **header:** column header grouping should be re-render after a resize ([beda628](https://github.com/ghiscoding/angular-slickgrid/commit/beda628ce4b1ef61c2565f514e1356480b3c29be))
* **menu:** remove unused code in Context Menu to select cell ([a2ae4bb](https://github.com/ghiscoding/angular-slickgrid/commit/a2ae4bba4bde279d0174aeb6bb91699f686a6612))
* **pagination:** reload local grid with pagination presests w/same data ([80eef1a](https://github.com/ghiscoding/angular-slickgrid/commit/80eef1aa2b66e1e310d821b09ec856e5ea22bad8))
* **pagination:** should work with page number defined in presets ([95428ad](https://github.com/ghiscoding/angular-slickgrid/commit/95428ad7d94660fc3138b0e97955f9b1753608f0))
* **resizer:** grid size fix for backend service with pagination disabled ([6c4bcca](https://github.com/ghiscoding/angular-slickgrid/commit/6c4bccaa4fdb877a4526c3feea42c7be469ba93e))
* **styling:** add missing SASS variable import ([6de44e6](https://github.com/ghiscoding/angular-slickgrid/commit/6de44e610696a2489d38e53d58bf808d60caaa37))
* **styling:** fix some styling issues found with menu dividers ([6f375c9](https://github.com/ghiscoding/angular-slickgrid/commit/6f375c9c9c71f73631685ab0bb8461f744c2e899))
* **test:** fix failing Cypress E2E test after GraphQL changes ([dc50117](https://github.com/ghiscoding/angular-slickgrid/commit/dc50117505dfad9bfa7f62befe42966d4963cac2))
* **test:** fix Jest failing unit test ([761fa4a](https://github.com/ghiscoding/angular-slickgrid/commit/761fa4ad91c44debd6ed3f3d2b2ed7d35bf906ae))

### [2.15.4](https://github.com/ghiscoding/angular-slickgrid/compare/v2.15.3...v2.15.4) (2020-01-10)


### Bug Fixes

* **build:** TS warning on a missing Type ([97b25f7](https://github.com/ghiscoding/angular-slickgrid/commit/97b25f72cd448a348f3adf1a795cfde541268621))

### [2.15.3](https://github.com/ghiscoding/angular-slickgrid/compare/v2.15.2...v2.15.3) (2020-01-10)


### Bug Fixes

* **styling:** use latest SlickGrid version and fix some styling issues ([dc0a688](https://github.com/ghiscoding/angular-slickgrid/commit/dc0a688cc982113ce298f9f22d6fecdc0e131b00))

### [2.15.2](https://github.com/ghiscoding/angular-slickgrid/compare/v2.15.1...v2.15.2) (2020-01-07)


### Bug Fixes

* **security:** update DOMpurify to fix potential xss vulnerability ([63c1ddc](https://github.com/ghiscoding/angular-slickgrid/commit/63c1ddc748932671c4b168fbeab09278715dfcf9))

### [2.15.1](https://github.com/ghiscoding/angular-slickgrid/compare/v2.15.0...v2.15.1) (2020-01-06)


### Features

* **styling:** add more SASS variables to header menu ([373641f](https://github.com/ghiscoding/angular-slickgrid/commit/373641f33f27eacec43068ed81aeb24d65d91601))

## [2.15.0](https://github.com/ghiscoding/angular-slickgrid/compare/v2.14.5...v2.15.0) (2020-01-06)


### Features

* **cellMenu:** starting adding new CellMenu Extension ([5ab64a1](https://github.com/ghiscoding/angular-slickgrid/commit/5ab64a12406ee7eb1374ca2d284250f12cea89c5))
* **github:** change issue templates and add auto close bot ([90271bf](https://github.com/ghiscoding/angular-slickgrid/commit/90271bf1fa5079f9a481f196717ee1d520e8a7ae))
* **menu:** add action & override callbacks to all Menu plugins ([a7967bb](https://github.com/ghiscoding/angular-slickgrid/commit/a7967bbae769b73f9a21e8454542a39b6a43660e))
* **menu:** add Context Menu feature POC ([8d04406](https://github.com/ghiscoding/angular-slickgrid/commit/8d04406545cb4687966784128bf8279055374b07))
* **menu:** starting adding new ContextMenu Extension ([95d3227](https://github.com/ghiscoding/angular-slickgrid/commit/95d322782f1eff77dc8e084a12ad6aab50c8bdb2))
* **styling:** change Column Picker & Grid Menu styling ([b9dc977](https://github.com/ghiscoding/angular-slickgrid/commit/b9dc977a03e9bd4ed1740430d1c22934453bc4a6))
* **styling:** change Column Picker & Grid Menu styling ([d91086b](https://github.com/ghiscoding/angular-slickgrid/commit/d91086bf1734b392adaf4c13cb5e42672cb5eb8e))


### Bug Fixes

* **graphql:** disable pagination should remove any page info from query ([63190c8](https://github.com/ghiscoding/angular-slickgrid/commit/63190c8bdca3312a317480772c48fdf7bd7edb50))
* **sort:** add sort icons to grouping examples ([0bb9844](https://github.com/ghiscoding/angular-slickgrid/commit/0bb98444a9be52d20e0f77e78b61c163ca7c0a82))
* **translations:** align all Export translations and add missing locales ([d3e45bc](https://github.com/ghiscoding/angular-slickgrid/commit/d3e45bc799aa7fad0b7fe615effd1a0a6b502786))

### [2.14.4](https://github.com/ghiscoding/angular-slickgrid/compare/v2.14.3...v2.14.4) (2019-12-06)


### Features

* **build:** add Build Demo site to CircleCI task ([62ed009](https://github.com/ghiscoding/angular-slickgrid/commit/62ed009c73c4d6b2f1583e2246da894b2f9c0538))


### Bug Fixes

* **backend:** make sure pagination object exist before using it ([07dbbb1](https://github.com/ghiscoding/angular-slickgrid/commit/07dbbb18622d8af02335bf58609fa3334e70c172))

### [2.14.3](https://github.com/ghiscoding/angular-slickgrid/compare/v2.14.2...v2.14.3) (2019-11-29)


### Bug Fixes

* **filter:** Date Filters using Flatpickr throw error w/invalid locale ([7c55a26](https://github.com/ghiscoding/angular-slickgrid/commit/7c55a26b35969d1071f3af28389564d6a39c6e4d)), closes [#346](https://github.com/ghiscoding/angular-slickgrid/issues/346)
* **filter:** default operator of input filter should be empty ([17c905d](https://github.com/ghiscoding/angular-slickgrid/commit/17c905da02fcf53c9c1ffac95569babbf09b4c80))
* **filter:** number filter condition, parse number before comparing ([55f5fc9](https://github.com/ghiscoding/angular-slickgrid/commit/55f5fc9e87a5f3d73cec680f0e19245a3e38d432))

### [2.14.2](https://github.com/ghiscoding/angular-slickgrid/compare/v2.14.1...v2.14.2) (2019-11-27)


### Features

* **tests:** add missing unit tests to have 100% test coverage ([99736fc](https://github.com/ghiscoding/angular-slickgrid/commit/99736fc39476428c08914aa4438af185642008d8))
* **tests:** add more unit tests & cleanup some code ([644e1dc](https://github.com/ghiscoding/angular-slickgrid/commit/644e1dc14b3bb09b29901955514c413639c51e0e))


### Bug Fixes

* **editor:** Select Editor with option "0" were incorrectly filtered out ([e116340](https://github.com/ghiscoding/angular-slickgrid/commit/e116340bbc0c2af17ba22b63053a886b220f48b7))

### [2.14.1](https://github.com/ghiscoding/angular-slickgrid/compare/v2.14.0...v2.14.1) (2019-11-26)


### Bug Fixes

* **filter:** updateFilters w/BackendService should call query only once ([8228799](https://github.com/ghiscoding/angular-slickgrid/commit/82287995eb103088d3acf671594363ad74059074))

## [2.14.0](https://github.com/ghiscoding/angular-slickgrid/compare/v2.13.1...v2.14.0) (2019-11-21)


### Features

* **cypress:** add Dynamic Filters feature E2E Cypress tests ([043ce89](https://github.com/ghiscoding/angular-slickgrid/commit/043ce895ba3b6db33de55b58378bb6f92a24ab9a))
* **filters:** allow to bypass changed events when calling updateFilters ([62c807e](https://github.com/ghiscoding/angular-slickgrid/commit/62c807e85a2c8203f32826075e271523f702a4c8))
* **filters:** provide method to apply grid filters dynamically ([8c10e5a](https://github.com/ghiscoding/angular-slickgrid/commit/8c10e5af9b34448c0d9cda6b42e4acc063074a68))
* **sorting:** allow to bypass changed events when calling updateSorting ([35936ad](https://github.com/ghiscoding/angular-slickgrid/commit/35936addc7d8b9287bb04c16489fbd927d5623ec))
* **sorting:** provide method to apply grid sorting dynamically ([9a99ca0](https://github.com/ghiscoding/angular-slickgrid/commit/9a99ca04b1d18624614a4f310e32a1f9f08ab654))
* **tests:** add Jest & Cypress tests for Dynamic Sorting feature ([d0fa65e](https://github.com/ghiscoding/angular-slickgrid/commit/d0fa65e186c77ffbfe1d471d580a926e299669f9))


### Bug Fixes

* **odata:** no single quote escape required for IN operator for non-string column ([6e4a855](https://github.com/ghiscoding/Angular-Slickgrid/pull/341/commits/6e4a85537dbb628c3f174d939fca888f7d443e45))
* **picker:** make sure picker addon is available before translating ([e295c26](https://github.com/ghiscoding/angular-slickgrid/commit/e295c26b99a59664219fd457215308f305933d6a))

### [2.13.1](https://github.com/ghiscoding/angular-slickgrid/compare/v2.13.0...v2.13.1) (2019-11-12)


### Bug Fixes

* **filter:** add missing radius (right) on compound input filters ([e1aaefd](https://github.com/ghiscoding/angular-slickgrid/commit/e1aaefd1937fda39e7554303e69acd570f8c2b38))
* **firefox:** thousand separator regex lookbehind not allow, fixes [#336](https://github.com/ghiscoding/angular-slickgrid/issues/336) ([4c3ed76](https://github.com/ghiscoding/angular-slickgrid/commit/4c3ed76e0df75dd792d498a4a162c76cc9f35ed3))
* **pagination:** never display page 0, minimum should be page 1 ([a44af9f](https://github.com/ghiscoding/angular-slickgrid/commit/a44af9f3aa1dff44862d2e01ead8698711339954))

## [2.13.0](https://github.com/ghiscoding/angular-slickgrid/compare/v2.12.3...v2.13.0) (2019-11-07)


### Features

* **cypress:** upgrade to latest version of Cypress ([0f1fd87](https://github.com/ghiscoding/angular-slickgrid/commit/0f1fd873582ffe75b3abd0ad376a0e6ae2103265))
* **formatterOptions:** add decimal,thousand separator to all Formatters ([20345bb](https://github.com/ghiscoding/angular-slickgrid/commit/20345bba13ac8c678a8318995cb1cd2856901c98))
* **tests:** add missing unit tests for Excel Export Service ([eb0a536](https://github.com/ghiscoding/angular-slickgrid/commit/eb0a536df7bc305a7ed91c04213fa162ed4bfcaa))
* **tests:** add more Angular-Slickgrid component unit tests ([01bfd6f](https://github.com/ghiscoding/angular-slickgrid/commit/01bfd6f7bd56efe679ebbff35d424f3488f1aa24))
* **tests:** Angular-Slickgrid Component add missing unit tests ([0094494](https://github.com/ghiscoding/angular-slickgrid/commit/0094494d7f715fa527bb347b5dbc78a91c3f524d))

### [2.12.3](https://github.com/ghiscoding/angular-slickgrid/compare/v2.12.2...v2.12.3) (2019-10-29)


### Features

* **cypress:** add Pagination Service E2E tests ([72f6df3](https://github.com/ghiscoding/angular-slickgrid/commit/72f6df309b834180709de70fbbae37b4a19f2184))
* **styling:** improve header menu styling ([ba28d2b](https://github.com/ghiscoding/angular-slickgrid/commit/ba28d2b466169f82d9bd785497e85960db022e20))
* **tests:** add Angular-Slickgrid component tests ([1e84911](https://github.com/ghiscoding/angular-slickgrid/commit/1e84911c69949de469f3b0d797f3a04e46a418d7))
* **tests:** add more Angular-Slickgrid unit tests ([60192cd](https://github.com/ghiscoding/angular-slickgrid/commit/60192cd9c1c6d537da81863f723b94bbe99702eb))
* **tests:** starting adding Slick-Pagination Component unit tests ([b48ee06](https://github.com/ghiscoding/angular-slickgrid/commit/b48ee0616047d3077ebb5afb13d4ee109c48839a))


### Bug Fixes

* **editor:** use editorOptions only ([08b1930](https://github.com/ghiscoding/angular-slickgrid/commit/08b19302d0c852aef8e0d0e6bd709aef6eee40e2))
* **graphql:** pagination offset should never be below zero ([41e321f](https://github.com/ghiscoding/angular-slickgrid/commit/41e321f2f8a2f62cc70c7b05cf73e27690b3c5e0))
* **graphql:** translate pagination texts on initial load ([3ecd9b9](https://github.com/ghiscoding/angular-slickgrid/commit/3ecd9b91c771e90284ecd5b3eb900b4892cec361))
* **odata:** filter with single quote should be escaped, fixes [#328](https://github.com/ghiscoding/angular-slickgrid/issues/328) ([1cd0b47](https://github.com/ghiscoding/angular-slickgrid/commit/1cd0b47e6b355ca601330dc35ac597b22a4b726a))
* **styling:** hidden menu visible in BS4 for Picker/Grid Menu, fix [#321](https://github.com/ghiscoding/angular-slickgrid/issues/321) ([9d597c4](https://github.com/ghiscoding/angular-slickgrid/commit/9d597c4b71ac83b32ccae75e88c6ee472d7e6bdc))

### [2.12.2](https://github.com/ghiscoding/angular-slickgrid/compare/v2.12.1...v2.12.2) (2019-10-21)


### Bug Fixes

* **frozen:** fix header grouping grid with frozen columns, fixes [#290](https://github.com/ghiscoding/angular-slickgrid/issues/290) ([b851224](https://github.com/ghiscoding/angular-slickgrid/commit/b851224))

### [2.12.1](https://github.com/ghiscoding/angular-slickgrid/compare/v2.12.0...v2.12.1) (2019-10-21)


### Bug Fixes

* **editor:** autocommit should not save if value is the same as before ([a07d239](https://github.com/ghiscoding/angular-slickgrid/commit/a07d239))
* **editor:** provide complex object override path for select editor ([a93a53d](https://github.com/ghiscoding/angular-slickgrid/commit/a93a53d))


### Features

* **rowDetail:** expose public all render/redraw methods of Row Detail ([de0b3e9](https://github.com/ghiscoding/angular-slickgrid/commit/de0b3e9))

## [2.12.0](https://github.com/ghiscoding/angular-slickgrid/compare/v2.11.3...v2.12.0) (2019-10-17)


### Bug Fixes

* **gridService:** addItem/updatedItemById must pass an array to setSelectedRows ([#308](https://github.com/ghiscoding/Angular-Slickgrid/pull/308))
* **excel:** exporting to Excel should also work from Grid Menu ([b2f0680](https://github.com/ghiscoding/angular-slickgrid/commit/b2f0680))
* **filter:** should be able to filter even on hidden columns, fixes [#310](https://github.com/ghiscoding/angular-slickgrid/issues/310) ([47a1ab7](https://github.com/ghiscoding/angular-slickgrid/commit/47a1ab7))


### Features

* **bootstrap:** add Bootstrap Action Dropdown example ([0b96746](https://github.com/ghiscoding/angular-slickgrid/commit/0b96746))
* **excel:** add Excel Export feature and add full unit test suite ([d787131](https://github.com/ghiscoding/angular-slickgrid/commit/d787131))
* **export:** add Export to Excel feature ([f06977f](https://github.com/ghiscoding/angular-slickgrid/commit/f06977f))
* **tests:** add more grid service unit tests ([a2ddab2](https://github.com/ghiscoding/angular-slickgrid/commit/a2ddab2))

### [2.11.3](https://github.com/ghiscoding/angular-slickgrid/compare/v2.11.2...v2.11.3) (2019-10-08)


### Features

* **example:** add Bootstrap Dropdown Action demo, closes [#304](https://github.com/ghiscoding/angular-slickgrid/issues/304) ([ba6082c](https://github.com/ghiscoding/angular-slickgrid/commit/ba6082c))
* **export:** add delimiter/listSeparator override to use with GraphQL ([de52614](https://github.com/ghiscoding/angular-slickgrid/commit/de52614))

### [2.11.2](https://github.com/ghiscoding/angular-slickgrid/compare/v2.11.1...v2.11.2) (2019-10-07)


### Bug Fixes

* **gridService:** upsertItem(s) should trigger onItemAdded/Updated event ([df9af21](https://github.com/ghiscoding/angular-slickgrid/commit/df9af21))
* **pagination:** when item is added it should trigger pagination changed ([c953a23](https://github.com/ghiscoding/angular-slickgrid/commit/c953a23))
* **pagination:** don't reset page 1 after manually adding items to grid ([f61285d](https://github.com/ghiscoding/angular-slickgrid/commit/f61285d))


### Features

* **example:** add programmatically Pagination change sample ([a150807](https://github.com/ghiscoding/angular-slickgrid/commit/a150807))

### [2.11.1](https://github.com/ghiscoding/angular-slickgrid/compare/v2.11.0...v2.11.1) (2019-10-04)


### Bug Fixes

* **styling:** styling issue in Firefox after col reordering, fixes [#297](https://github.com/ghiscoding/angular-slickgrid/issues/297) ([a2c7e39](https://github.com/ghiscoding/angular-slickgrid/commit/a2c7e39))


### Features

* **backend:** extract Pagination into its own Service to expose methods ([4a4a708](https://github.com/ghiscoding/angular-slickgrid/commit/4a4a708))

## [2.11.0](https://github.com/ghiscoding/angular-slickgrid/compare/v2.10.5...v2.11.0) (2019-10-02)


### Bug Fixes

* **build:** use latest SlickGrid version which might fix ES2015 build ([ff9f9d8](https://github.com/ghiscoding/angular-slickgrid/commit/ff9f9d8))
* **editors:** complex objects should work with all editors ([01f53ed](https://github.com/ghiscoding/angular-slickgrid/commit/01f53ed))
* **insert:** add item to bottom position should highlight correctly ([9f9e6eb](https://github.com/ghiscoding/angular-slickgrid/commit/9f9e6eb))


### Features

* **insert:** add option to insert item at bottom of grid ([32764fb](https://github.com/ghiscoding/angular-slickgrid/commit/32764fb))
* **metrics:** deprecated Statistic and renamed to Metrics ([aea60a9](https://github.com/ghiscoding/angular-slickgrid/commit/aea60a9))
* **odata:** add "enableCount" flag to add to OData query, closes [#287](https://github.com/ghiscoding/angular-slickgrid/issues/287) ([1d70037](https://github.com/ghiscoding/angular-slickgrid/commit/1d70037))
* **tests:** add AutoComplete Filter test suite ([8ccea92](https://github.com/ghiscoding/angular-slickgrid/commit/8ccea92))
* **tests:** add AutoComplete missing test ([313da78](https://github.com/ghiscoding/angular-slickgrid/commit/313da78))
* **tests:** add missing AutoComplete unit tests ([24487a4](https://github.com/ghiscoding/angular-slickgrid/commit/24487a4))
* **tests:** add missing unit tests for all Editors ([c275b87](https://github.com/ghiscoding/angular-slickgrid/commit/c275b87))
* **tests:** add more Single & MultipleSelectEditor unit tests ([9dc1abe](https://github.com/ghiscoding/angular-slickgrid/commit/9dc1abe))
* **tests:** add some tests for the AutoComplete Editor ([360da3e](https://github.com/ghiscoding/angular-slickgrid/commit/360da3e))
* **upsert:** add option to upsert item at bottom of grid & view scroll ([7b25dd7](https://github.com/ghiscoding/angular-slickgrid/commit/7b25dd7))

### [2.10.5](https://github.com/ghiscoding/angular-slickgrid/compare/v2.10.4...v2.10.5) (2019-08-29)

### [2.10.4](https://github.com/ghiscoding/angular-slickgrid/compare/v2.10.3...v2.10.4) (2019-08-29)

### [2.10.3](https://github.com/ghiscoding/angular-slickgrid/compare/v2.10.2...v2.10.3) (2019-08-29)


### Bug Fixes

* **core:** dowgrade to previous SlickGrid version to fix issues ([1fd11ab](https://github.com/ghiscoding/angular-slickgrid/commit/1fd11ab))


### Features

* **tests:** add CompoundDate Filter unit tests ([45348a0](https://github.com/ghiscoding/angular-slickgrid/commit/45348a0))
* **tests:** add CompoundSlider Filter unit tests ([06abb3d](https://github.com/ghiscoding/angular-slickgrid/commit/06abb3d))
* **tests:** add NativeSelect Filter unit tests & tweak some Filters ([4b952c9](https://github.com/ghiscoding/angular-slickgrid/commit/4b952c9))
* **tests:** add slider unit tests ([5ae1a85](https://github.com/ghiscoding/angular-slickgrid/commit/5ae1a85))

### [2.10.2](https://github.com/ghiscoding/angular-slickgrid/compare/v2.10.1...v2.10.2) (2019-08-26)


### Bug Fixes

* **backend:** queries should not include pagination option when disabled ([d648b80](https://github.com/ghiscoding/angular-slickgrid/commit/d648b80))
* **test:** fix a Cypress flaky test that was sometime failing ([4ed5a29](https://github.com/ghiscoding/angular-slickgrid/commit/4ed5a29))


### Features

* **tests:** add SelectFilter unit tests ([5115e08](https://github.com/ghiscoding/angular-slickgrid/commit/5115e08))

## [2.10.0](https://github.com/ghiscoding/angular-slickgrid/compare/v2.9.9...v2.10.0) (2019-08-19)


### Bug Fixes

* **dom:** ColumnPicker & GridMenu were creating multiple DOM elements ([8916f90](https://github.com/ghiscoding/angular-slickgrid/commit/8916f90))
* **gridMenu:** add more type checks to avoid console error, fixes [#268](https://github.com/ghiscoding/angular-slickgrid/issues/268) ([328c9af](https://github.com/ghiscoding/angular-slickgrid/commit/328c9af))
* **odata:** use contains with OData version 4 ([e936f33](https://github.com/ghiscoding/angular-slickgrid/commit/e936f33))
* **presets:** Grid State & Presets stopped working for columns ([4e0b528](https://github.com/ghiscoding/angular-slickgrid/commit/4e0b528))
* **styling:** fix some Bootstrap 4 styling ([ee4931c](https://github.com/ghiscoding/angular-slickgrid/commit/ee4931c))


### Build System

* **deps:** bump fstream from 1.0.11 to 1.0.12 ([6813234](https://github.com/ghiscoding/angular-slickgrid/commit/6813234))
* **deps:** bump jquery from 3.3.1 to 3.4.0 ([4175f25](https://github.com/ghiscoding/angular-slickgrid/commit/4175f25))
* **deps:** bump lodash.mergewith from 4.6.1 to 4.6.2 ([f538320](https://github.com/ghiscoding/angular-slickgrid/commit/f538320))


### Features

* **filter:** add a few input/compoundInput filters ([190176a](https://github.com/ghiscoding/angular-slickgrid/commit/190176a))
* **filter:** add Cypress E2E tests for the Filter by Range grid ([7da17f8](https://github.com/ghiscoding/angular-slickgrid/commit/7da17f8))
* **filter:** add DateRange Filter unit test & refactor code ([308082f](https://github.com/ghiscoding/angular-slickgrid/commit/308082f))
* **filter:** add input search range functionality, ref issue [#240](https://github.com/ghiscoding/angular-slickgrid/issues/240) ([7273cf8](https://github.com/ghiscoding/angular-slickgrid/commit/7273cf8))
* **filter:** add new rangeDate Filter ([0878569](https://github.com/ghiscoding/angular-slickgrid/commit/0878569))
* **filter:** add new SliderRange Filter ([26dc63c](https://github.com/ghiscoding/angular-slickgrid/commit/26dc63c))
* **filter:** add optional placeholder to multiple select ([1b1274b](https://github.com/ghiscoding/angular-slickgrid/commit/1b1274b))
* **filter:** add SliderRange Filter unit tests & fix searchTerms input ([be136be](https://github.com/ghiscoding/angular-slickgrid/commit/be136be))
* **locales:** add unit tests when using locales with enableTranslate ([413ea71](https://github.com/ghiscoding/angular-slickgrid/commit/413ea71))
* **locales:** add unit tests when using locales with enableTranslate ([ae48ddf](https://github.com/ghiscoding/angular-slickgrid/commit/ae48ddf))
* **sorters:** consolidate & provide all date sorters ([fdc1155](https://github.com/ghiscoding/angular-slickgrid/commit/fdc1155))
* **tests:** add Cypress E2E tests to cover hidden columns, closes [#250](https://github.com/ghiscoding/angular-slickgrid/issues/250) ([22868f5](https://github.com/ghiscoding/angular-slickgrid/commit/22868f5))
* **translate:** add optional Locale functionality ([8f24d2d](https://github.com/ghiscoding/angular-slickgrid/commit/8f24d2d))
* **translate:** make ngx-translate an optional dependency ([86b1214](https://github.com/ghiscoding/angular-slickgrid/commit/86b1214))
* **translate:** make ngx-translate optional in all necessary Editors ([5eb1ec1](https://github.com/ghiscoding/angular-slickgrid/commit/5eb1ec1))
* **translate:** make translate optional in SlickPagination component ([0d6b2e2](https://github.com/ghiscoding/angular-slickgrid/commit/0d6b2e2))
