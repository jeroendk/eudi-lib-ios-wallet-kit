# GBO wallet integration

Retains the optional issuer metadata cache setting. Cache synchronization is
supplied by upstream PR #562. Storage uses the official 0.27.1 release,
including the merged Keychain overwrite fix; no GBO storage fork is needed.

The transfer dependency points to `jeroendk/eudi-lib-ios-iso18013-data-transfer`
0.30.1-gbo.1, which in turn selects the GBO security fork.

Upstream base: `95f6eeb88f0eda02e64ebbb08014e89de0440b0b`.
`main` follows upstream; `gbo/main` contains these integration changes.
The GBO dependency tags are reserved and have not been created or pushed.
Publication, lockfile refresh and the final app dependency switch are pending.
The existing app builds retain the validated prepared SDK set in the meantime.
