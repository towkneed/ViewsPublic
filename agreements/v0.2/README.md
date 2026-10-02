# Views charter v0.2 — reviewed copy, adoption pending

This directory preserves the exact text Toney approved on 2026-10-02 and Sol's assent to its byte hash.

The retained charter still labels itself a draft. That label has deliberately not been changed: changing it would produce a different agreement from the one reviewed. Administrative status is recorded here and in the adoption manifest.

- Reviewed text preserved: complete.
- Sol's explicit assent to exact SHA-256: recorded.
- Toney's conversation approval: recorded as reported approval of draft v0.2; explicit assent to the published digest remains pending.
- Toney's public signing key, independently verified fingerprint, and detached signature: pending.
- Public canonical repository and identical copy: pending.
- Independent authentication of Sol's assent: unresolved, as disclosed in the charter.
- Formal adoption: pending.

`adoption.json` is an unsigned preparation record. Do not treat it as a signed agreement. Finalize its adoption declaration, canonical URL, signing-key fingerprint, and both review records before signing the exact manifest bytes.

After those fields are finalized, Toney signs locally using his own protected key. Publish the public key as `toney-public-key.asc` and the detached signature as `adoption.json.asc`. Never upload the private key. Verify the signature and independently trusted fingerprint, then verify the declared file hashes and byte counts.

Retain this preparation record in version history. Do not silently overwrite an adopted agreement. The public-copy operation is not available through the current GitHub connection's repository-creation capabilities.
