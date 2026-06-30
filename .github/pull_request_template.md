<!-- Provide a concise, imperative summary in the Title above -->

## Description
<!-- What does this PR do, and why?
     Note: This repository squash-merges PRs by default. Write this section as-if it was a commit message body:
      - Imperative mood ("Add X", "Fix Y"), not "This PR adds...".
      - Explain *what* changes and *why*, briefly; For bug fixes, state the root cause, not just the symptom.
      - Preferably, wrap lines around 72 chars for `git log` readability. -->


## Review notes
<!-- Reviewer-facing only (put `n/a` if description is self explanatory); NOT carried into the commit message.
     - Link prior discussion on https://community.intel.com/t5/Intel-Software-Guard-Extensions/bd-p/software-guard-extensions
       and please open an issue first for non-trivial features.
     - Anything reviewers need that doesn't belong in `git log` (alternatives considered, follow-ups left out of scope, etc.). -->



## Related issues / PRs
<!-- Use GitHub keywords so issues auto-close on merge, e.g. - Fixes #123,  - Refs #789 -->
- `n/a`


## Type of change
<!-- Select `(*)` the primary category (usually one).
      If you tick "Breaking change", the *Backwards compatibility* and *Release note* lines under *Impact* are required. -->
- `( )` Bug fix (non-breaking change that fixes an issue)
- `( )` New feature (non-breaking change that adds functionality)
- `( )` Breaking change (fix or feature that changes existing behavior or ABI/API)
- `( )` Code quality / refactor / docs / tests
- `( )` Other: <!-- replace with one short phrase -->


## Testing
<!-- How did you verify the change?
      - For bug fixes: include reproduction steps and the platform you tested on (CPU, OS/distro, SGX driver, DCAP version), matching ../CONTRIBUTING.md.
      - For features: describe the test cases added and the manual coverage; "Covered by CI" is acceptable for trivial changes; please still name the job. -->


## Impact
<!-- Fill in each line below; `n/a` is fine where it doesn't apply. Keep entries short — one sentence each. -->
- **Affected components:** <!-- e.g. SDK, urts, edger8r, samples, build, CI, docs -->
- **Backwards compatibility:** <!-- source/binary/ABI, on-disk formats, configuration, public API; migration path if anything breaks -->
- **Third-party dependencies:** <!-- added/updated/removed; name, version, license -->
- **Security:** <!-- TCB, attestation, crypto, enclave entry/exit, trust boundaries. Do NOT include exploit details in a public PR; follow ../SECURITY.md for disclosures -->
- **Documentation:** <!-- README, man pages, developer reference, samples; included in this PR? -->
- **Release note:** <!-- one short, user-visible sentence for the changelog, or `NONE` -->


## Checklist
<!-- Tick the boxes that apply. If an item does not apply or you're unsure,
      add a short comment as a sub-bullet rather than leaving it blank. -->
- [ ] PR is focused on one thing; commits are atomic, squashed where appropriate, and signed off (`git commit -s`), per [`CONTRIBUTING.md`](https://github.com/intel/confidential-computing.sgx.sdk/blob/main/CONTRIBUTING.md).
- [ ] Tests and documentation are added/updated for new or changed behavior (or noted as `n/a` in *Impact*).
- [ ] I have built and run the relevant tests locally, or explained in *Testing* why CI alone is sufficient.
