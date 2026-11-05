# Lightning Stream for StartOS (Kilombino's registry)

[Lightning Stream](https://github.com/AwokenLazarus/Lightning-Stream) is made by **Lazarus**. This repository only
hosts copies of its official StartOS packages, re-signed with Kilombino's developer key, so that
[registry.kilombino.com](https://registry.kilombino.com) can offer them under the same signer as the rest of the store.

- Each release here takes the `.s9pk` files from the matching `startos-v<version>` release of
  [AwokenLazarus/Lightning-Stream](https://github.com/AwokenLazarus/Lightning-Stream/releases), checked against
  their `SHA256SUMS`.
- The package content is unchanged: same manifest, same images. Only the signature changes (start-cli
  re-signs the package when the manifest is rewritten, with the same values).
- The release notes of each release list the original checksums and the new ones.

Problems with the app itself go to [its project's issues](https://github.com/AwokenLazarus/Lightning-Stream/issues).
If you prefer to trust Lazarus's own signature, install it from their registry instead: install it from one
registry only.
