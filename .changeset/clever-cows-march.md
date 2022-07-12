---
'@mobile-reality/react-native-select-pro': minor
---

* update dependencies by @irekrog

### Breaking Changes during development
* This repository is now a monorepo using `pnpm workspaces` and `turborepo`, divided on:
  * src/packages/
    * react-native-select-pro - main package published on npm
  * src/apps/
    * e2e - e2e testing
    * expo - expo app to development
* `pnpm` instead `yarn`
* `changesets` instead `release-it`