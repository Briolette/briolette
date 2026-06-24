# Contributing to Briolette

Thanks for your interest in contributing to Briolette! This document describes
how to contribute and the requirements your contributions must meet.

## Developer Certificate of Origin

All contributions to this project must be made under the terms of the
[Developer Certificate of Origin (DCO), Version 1.1](https://developercertificate.org/).
The full text is included in the [`DCO`](DCO) file at the root of this
repository.

By signing off on your commits, you certify that you wrote the contribution or
otherwise have the right to submit it under the project's open source license
(the Apache License 2.0; see [`LICENSE`](LICENSE)).

### Signing off your work

Every commit must include a `Signed-off-by` line matching the author's real name
and email address. Add it automatically by passing `-s` (or `--signoff`) when you
commit:

```
git commit -s -m "Short description of the change"
```

This appends a line of the form:

```
Signed-off-by: Jane Developer <jane@example.com>
```

If you forget to sign off the most recent commit, you can amend it:

```
git commit --amend -s --no-edit
```

To sign off a series of commits on your branch, rebase with the signoff option:

```
git rebase --signoff main
```

Pull requests whose commits are not signed off cannot be merged.

## Submitting changes

1. Open an issue first to discuss substantial changes — it saves everyone time.
2. Fork the repository and create a topic branch for your work.
3. Make your changes, keeping commits focused and signed off.
4. Ensure the project builds and tests pass.
5. Update documentation where appropriate.
6. Open a pull request describing the change and referencing any related issue.

## Code of conduct

Be respectful and constructive. Maintainers may remove contributions or
contributors that do not uphold a welcoming, collaborative environment.
