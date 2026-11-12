# watchos-hermes CI

`main` mirrors [pookjw/HermesEnabler](https://github.com/pookjw/HermesEnabler). This branch only holds CI.

IPAs live under [Releases](../../releases) and [Actions](../../actions).

The `Build unsigned IPA` workflow runs daily. It fast-forwards `main` from upstream and builds when `main` has a commit without a `build-<sha7>` release.
