# Juniper Commons — synthetic ATProto community demo

This repository publishes a fictional community called **Juniper Commons**.
It demonstrates one product idea:

> A community can curate posts without taking ownership of them, while any
> compatible renderer remains a replaceable window onto the community’s
> published choices.

Visit the demo at
<https://unpingable.github.io/atproto-community-demo/>.

Nothing here came from a live account or Space. The site contains no OAuth
token, Space credential, private source data, moderator capability, analytics,
cookies, or browser script.

## What is here

The root is the human-facing synthetic showcase. It includes:

* three fictional author-owned posts featured by Juniper Commons;
* plain-language “Why is this here?” explanations;
* explicit changed, unavailable, and removed lifecycle examples;
* a separate technical-audit disclosure;
* exact feed JSON, a canonical manifest, and checksums.

The original specification-like boundary demonstration remains byte-exact
under [`lab/`](https://unpingable.github.io/atproto-community-demo/lab/).

## Custody and verification

Showcase bundle ID:
`sha256:210d22fda8f5fc918fca8dec5c7b391fd3e2ef97dcfd2fa8a0881a220f899a21`

Embedded boundary bundle ID:
`sha256:9bc2a8935f1f239fbcd311287fcf3602fa4a7f1ebfd9bcada0d413dc26455b5e`

Generator custody commit:
`f974f9ced571fd8210051f3f795c20ba4be93050`

Verify every generated payload with:

```sh
sha256sum -c checksums.txt
```

The semantic generator currently lives in a private research repository. That
commit identifies custody but is not presented as a public regeneration path.
This repository is the complete public artifact and byte-verification surface;
the limitation is stated rather than papered over.

The manifest records the exact claims and non-claims. Publication does not
prove reader authorization, membership, moderator or governance authority,
source truth, repository currentness, human usability, or production
readiness.

## License

Dual-licensed under Apache-2.0 or MIT, at your option. See
`LICENSE-APACHE` and `LICENSE-MIT`.
