# @redux-saga/types

## 1.1.1
### Patch Changes

- 20f22a8: A generic type has been added to the `Task` interface and that should be preferred over using a generic parameter in `Task#result` and `Task#toPromise`.
- 20f22a8: Inlined Redux `Action` type to fix compatibility with strict package managers.
