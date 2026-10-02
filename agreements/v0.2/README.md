# Views charter v0.2 — signed adoption records

The reviewed charter and Sol's recorded assent are preserved unchanged. Toney's completed adoption manifest has a valid detached OpenPGP signature, verified with GnuPG against the supplied public key.

- Charter: 12480 bytes; SHA-256 `1b7a6d1897458ba5c2cb4baac84b56e78c4016078d52e26d742e85e87b56c710`.
- Recorded assent: 1601 bytes; SHA-256 `a3355363dbfb1ff8eed806eb6e914a8c3bcd574df08d50c88a9668bf121ab66f`.
- Signing primary-key fingerprint: `C18F934D577E8BAFF52415DADDC832517AEFD32D`.
- Signed source manifest and signature: Views commit `b232df1357f8d7df3f261c00ca3c4ed6250c7b31`.
- Canonical public location: https://github.com/towkneed/ViewsPublic/tree/main/agreements/v0.2

`adoption.json.asc` is the signature specified by the charter. The signed manifest names `adoption.signed.asc`; that file is an identical copy of the same valid signature. Adding the copy resolved the path without changing signed manifest bytes.

Verify either signature with the exact manifest, e.g. `gpg --verify adoption.json.asc adoption.json`. Independently establish the public-key fingerprint before relying on signer identity; matching the key and fingerprint supplied in the same repository alone does not establish that independent trust.

The charter retains its original draft/pending labels to preserve the exact reviewed bytes. The signed manifest records Toney's subsequent adoption declaration. Prior preparation records remain in Git history.

Independent authentication of Sol's assent remains unresolved. Commercial benefit administration and control remain subject to the charter's release gate. Signature verification does not determine legal enforceability or ongoing consent.
