# 0.2.0 (Tue Aug 30 2022)

#### 🚀 Enhancement

- Sync changes up to 57537b9 [#69](https://github.com/player-ui/player/pull/69) ([@adierkens](https://github.com/adierkens))

#### 🐛 Bug Fix

- Remove exit on error flag in release script [#75](https://github.com/player-ui/player/pull/75) ([@adierkens](https://github.com/adierkens))
- Release main [#73](https://github.com/player-ui/player/pull/73) ([@intuit-svc](https://github.com/intuit-svc))
- add delay before screenshotting for animations to finish [#72](https://github.com/player-ui/player/pull/72) ([@hborawski](https://github.com/hborawski))
- Release main [#71](https://github.com/player-ui/player/pull/71) ([@intuit-svc](https://github.com/intuit-svc))
- split out test helper functionality so XCTest isn't a hard requirement [#70](https://github.com/player-ui/player/pull/70) ([@hborawski](https://github.com/hborawski))
- Remove unused react-types package [#68](https://github.com/player-ui/player/pull/68) ([@adierkens](https://github.com/adierkens))
- switch removal from empty node [#67](https://github.com/player-ui/player/pull/67) (marlon_ercillo@intuit.com [@mercillo](https://github.com/mercillo))
- upgrade to xcode 13.4.1 [#65](https://github.com/player-ui/player/pull/65) ([@hborawski](https://github.com/hborawski))
- dont use bazel to push since the stamping wont work after shipit [#63](https://github.com/player-ui/player/pull/63) ([@hborawski](https://github.com/hborawski))
- try/catch pod push in plugin [#62](https://github.com/player-ui/player/pull/62) ([@hborawski](https://github.com/hborawski))
- move pod push to afterShipIt to have upload-assets finish first [#61](https://github.com/player-ui/player/pull/61) ([@hborawski](https://github.com/hborawski))
- Add workflow for fixing tags after failed release [#60](https://github.com/player-ui/player/pull/60) ([@adierkens](https://github.com/adierkens))
- fix pod release plugin [#59](https://github.com/player-ui/player/pull/59) ([@hborawski](https://github.com/hborawski))
- add local auto plugin to run bazel pod push after release [#57](https://github.com/player-ui/player/pull/57) ([@hborawski](https://github.com/hborawski))
- Fix the bin entry for the cli [#58](https://github.com/player-ui/player/pull/58) ([@adierkens](https://github.com/adierkens))
- allow caching ios tests again [#56](https://github.com/player-ui/player/pull/56) ([@hborawski](https://github.com/hborawski))
- set applitools env variables for iOS tests [#27](https://github.com/player-ui/player/pull/27) ([@hborawski](https://github.com/hborawski))
- fix IR backend for kotlinx serialization [#55](https://github.com/player-ui/player/pull/55) ([@sugarmanz](https://github.com/sugarmanz))
- Add subpath support for published docs [#54](https://github.com/player-ui/player/pull/54) ([@adierkens](https://github.com/adierkens))
- enhance error state deserialization & stacktrace logging in player view model [#50](https://github.com/player-ui/player/pull/50) ([@sugarmanz](https://github.com/sugarmanz))

#### 📝 Documentation

- added templates to content navigation, fixed the link to reference as… [#51](https://github.com/player-ui/player/pull/51) (marlon_ercillo@intuit.com [@mercillo](https://github.com/mercillo))

#### Authors: 6

- [@intuit-svc](https://github.com/intuit-svc)
- Adam Dierkens ([@adierkens](https://github.com/adierkens))
- Harris Borawski ([@hborawski](https://github.com/hborawski))
- Jeremiah Zucker ([@sugarmanz](https://github.com/sugarmanz))
- Marlon Ercillo ([@mercillo](https://github.com/mercillo))
- mercillo (marlon_ercillo@intuit.com)

---

# 0.1.0 (Tue Aug 02 2022)

### Release Notes

#### Fix version stamping. Add stamping to nextjs docs ([#11](https://github.com/player-ui/player/pull/11))

- Fixes the stamping for version and sha in `core` and `web` modules
- Stamps the nextjs docs for analytics id

#### NPM publishing support ([#3](https://github.com/player-ui/player/pull/3))

Adding build integration to publish all js packages to `npm`

---

#### 🚀 Enhancement

- Migrate from tapable to tapable-ts [#14](https://github.com/player-ui/player/pull/14) ([@adierkens](https://github.com/adierkens))

#### 🐛 Bug Fix

- Release main [#45](https://github.com/player-ui/player/pull/45) ([@intuit-svc](https://github.com/intuit-svc))
- rebuild pod zip in release [#43](https://github.com/player-ui/player/pull/43) ([@hborawski](https://github.com/hborawski))
- Publish vscode extension [#42](https://github.com/player-ui/player/pull/42) ([@adierkens](https://github.com/adierkens))
- persist iOS zip from iOS part of build [#41](https://github.com/player-ui/player/pull/41) ([@hborawski](https://github.com/hborawski))
- remove version prefix [#40](https://github.com/player-ui/player/pull/40) ([@hborawski](https://github.com/hborawski))
- add release flag to run command [#39](https://github.com/player-ui/player/pull/39) ([@hborawski](https://github.com/hborawski))
- add proper flag to build for podspec stamping [#38](https://github.com/player-ui/player/pull/38) ([@hborawski](https://github.com/hborawski))
- rebuild the podspec, not the pod [#37](https://github.com/player-ui/player/pull/37) ([@hborawski](https://github.com/hborawski))
- change version to placeholder for stamping [#36](https://github.com/player-ui/player/pull/36) ([@hborawski](https://github.com/hborawski))
- change version to placeholder for stamping [#35](https://github.com/player-ui/player/pull/35) ([@hborawski](https://github.com/hborawski))
- update rules_player to 0.5.1 [#34](https://github.com/player-ui/player/pull/34) ([@hborawski](https://github.com/hborawski))
- read sha as batch id [#31](https://github.com/player-ui/player/pull/31) ([@sugarmanz](https://github.com/sugarmanz))
- Update default sideEffects flag for npm packages [#33](https://github.com/player-ui/player/pull/33) ([@adierkens](https://github.com/adierkens))
- get directory of script instead of relative path [#30](https://github.com/player-ui/player/pull/30) ([@hborawski](https://github.com/hborawski))
- Port android changes [#29](https://github.com/player-ui/player/pull/29) (sentony03@gmail.com [@brocollie08](https://github.com/brocollie08))
- dont persist everything, just the ios-build-number [#28](https://github.com/player-ui/player/pull/28) ([@hborawski](https://github.com/hborawski))
- CocoaPod publishing [#20](https://github.com/player-ui/player/pull/20) ([@hborawski](https://github.com/hborawski))
- Applitools Test [#10](https://github.com/player-ui/player/pull/10) (sentony03@gmail.com [@sugarmanz](https://github.com/sugarmanz) [@brocollie08](https://github.com/brocollie08))
- Sync updates [#26](https://github.com/player-ui/player/pull/26) ([@adierkens](https://github.com/adierkens))
- Fix validation namespace collision in compiled module [#25](https://github.com/player-ui/player/pull/25) ([@adierkens](https://github.com/adierkens))
- bring over latest jvm code [#22](https://github.com/player-ui/player/pull/22) ([@sugarmanz](https://github.com/sugarmanz))
- Use remote caching for bazel targets [#21](https://github.com/player-ui/player/pull/21) ([@adierkens](https://github.com/adierkens))
- Add missing package.json attrs [#15](https://github.com/player-ui/player/pull/15) ([@adierkens](https://github.com/adierkens))
- fix maven repos [#18](https://github.com/player-ui/player/pull/18) ([@sugarmanz](https://github.com/sugarmanz))
- import GPG key [#17](https://github.com/player-ui/player/pull/17) ([@sugarmanz](https://github.com/sugarmanz))
- configure JAR publishing to Maven Central via rules [#16](https://github.com/player-ui/player/pull/16) ([@sugarmanz](https://github.com/sugarmanz))
- Fix version stamping. Add stamping to nextjs docs [#11](https://github.com/player-ui/player/pull/11) ([@adierkens](https://github.com/adierkens))
- Analytics for docs [#9](https://github.com/player-ui/player/pull/9) ([@adierkens](https://github.com/adierkens))
- Fix peer dependency in metrics plugin [#6](https://github.com/player-ui/player/pull/6) ([@adierkens](https://github.com/adierkens))
- Bump rules_player. Fix package.json generation [#5](https://github.com/player-ui/player/pull/5) ([@adierkens](https://github.com/adierkens))
- Add registry to cli pkg [#4](https://github.com/player-ui/player/pull/4) ([@adierkens](https://github.com/adierkens))
- NPM publishing support [#3](https://github.com/player-ui/player/pull/3) ([@adierkens](https://github.com/adierkens))

#### ⚠️ Pushed to `main`

- Update build dependencies ([@adierkens](https://github.com/adierkens))
- project scaffold ([@intuit-svc](https://github.com/intuit-svc))

#### 🏠 Internal

- Reorder docs match for CODEOWNERS [#23](https://github.com/player-ui/player/pull/23) ([@adierkens](https://github.com/adierkens))
- Update code-owners [#8](https://github.com/player-ui/player/pull/8) ([@adierkens](https://github.com/adierkens))

#### 📝 Documentation

- Fix formatting in getting-started docs [#7](https://github.com/player-ui/player/pull/7) ([@adierkens](https://github.com/adierkens))

#### Authors: 6

- [@brocollie08](https://github.com/brocollie08)
- [@intuit-svc](https://github.com/intuit-svc)
- Adam Dierkens ([@adierkens](https://github.com/adierkens))
- brocollie08 (sentony03@gmail.com)
- Harris Borawski ([@hborawski](https://github.com/hborawski))
- Jeremiah Zucker ([@sugarmanz](https://github.com/sugarmanz))
