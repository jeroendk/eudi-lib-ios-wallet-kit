# GBO Wallet dependency patch

Modified by Jeroen de Kok on 2026-11-10 for GBO Wallet.

The existing GBO patch sends credential_identifier when returned by the token endpoint and otherwise retains configuration-based issuance. The OpenID4VCI dependency is pinned to the GBO fork.

The upstream base is `2e0b5912e024baa9fe0fb0d2a55de82820aa1d0a`. The GBO release tag is `0.54.5-gbo.1`.
Upstream copyright and Apache 2.0 license notices are retained.
