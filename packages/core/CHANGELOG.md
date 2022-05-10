# @redux-saga/core

## 1.1.4
### Patch Changes

- 20f22a8: Require `CpsCallback` in all functions passed to the `cps` effect creator. This fixes a regression caused by TS 4.0 changing the behavior around spreading `never` into tuple types
- 20f22a8: A generic type has been added to the `Task` interface and that should be preferred over using a generic parameter in `Task#result` and `Task#toPromise`.
- 20f22a8: Added warnings when using `take(channelOrPattern)` incorrectly with more than one parameter. It helps to surface problem with `take(ACTION_A, ACTION_B)` being used instead of `take([ACTION_A, ACTION_B])`.

- Updated dependencies [20f22a8]
- Updated dependencies [20f22a8]
  - @redux-saga/types@1.1.1
