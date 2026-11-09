# nxnative-ios-build

A GitHub Actions workflow that builds an unsigned iOS app with [nxnative](https://github.com/seedds/nxnative)
from the owner's own game dump. The repository holds no game data: the input is encrypted and lives in a
private repository, the app name comes from a secret, tool output is encrypted before it leaves the runner,
and the outputs go back to the private repository. Only the owner can start a run.
