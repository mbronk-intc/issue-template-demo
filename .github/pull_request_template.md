<!-- Thanks for contributing to the Intel® SGX SDK! Fill in each section, replacing its guidance; `n/a` is always fine. -->
<!-- Give the PR a concise, imperative title above — e.g. "Fix X", "Add Y". -->

## Description
<!-- What changes, and why? This repo squash-merges by default — write this as the commit-message body:
      - Imperative mood, not "This PR adds…"; preferably, wrap ~72 chars for `git log`.
      - Explain *what* and *why*; for a bug fix, give the root cause, not just the symptom.
      - State the motivating use-case, and if you weighed other approaches, why you chose this one
        (reviewers routinely ask "why is this needed / did you consider X?").
      - Reviewer-only notes that shouldn't land in the commit message? Put them under a `### Details` sub-heading. -->


## Type of change
<!-- Pick one, delete the rest: Bug fix | Feature | Breaking (behavior/API/ABI/format) | Refactor/docs/tests/build.
      If Breaking, fill *Backward compatibility* under Impact. -->


## Testing
<!-- How did you verify this?
      - Bug fixes: give repro steps and the platform tested (CPU, OS/distro, SGX driver/DCAP), per CONTRIBUTING.md.
      - Note the build modes exercised: hardware vs `SGX_MODE=SIM`, debug + release (mitigation flavors if relevant).
      - "Covered by CI" is fine for trivial changes — name the job. -->


## Impact
<!-- One short line each; `n/a` where it doesn't apply. -->
- **Backward compatibility:** <!-- source/binary/ABI, public headers & error codes, signed/on-disk/wire format, MRENCLAVE, config; note any break + migration -->
- **Security:** <!-- TCB, attestation, crypto, trust boundary, side-channel/constant-time. Do NOT include exploit detail in a public PR; follow SECURITY.md -->
- **Dependencies / docs:** <!-- external/ submodules or third-party added/updated (name, version, license); README/man/samples updated?; one-line release note, or `n/a` -->


## Related issues / PRs
<!-- Link with GitHub keywords so issues auto-close on merge: Fixes #123, Refs #789.
      First check no open issue/PR or newer release already covers this. For a large feature or design
      change, please open an issue first (or discuss on the community forum:
      https://community.intel.com/t5/Intel-Software-Guard-Extensions/bd-p/software-guard-extensions). -->
- `n/a`


## Checklist
<!-- Change `[ ]` to `[x]` for each item as you complete it (you can also tick them after opening the PR). -->
- [ ] I filled in the template above :point_up: — real input in the sections that apply, `n/a` where they don't.
- [ ] PR is focused on one thing; commits are atomic and signed off (`git commit -s`), per [`CONTRIBUTING.md`](https://github.com/intel/confidential-computing.sgx.sdk/blob/HEAD/CONTRIBUTING.md).
- [ ] Tests and docs are added/updated for the change (or noted `n/a` under *Impact*).
- [ ] I built the change and verified it works locally, or explained in *Testing* why CI alone is sufficient.
