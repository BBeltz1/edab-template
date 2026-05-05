PRs into `dev` contained the info we needed. They have already been approved. If you've got this far we're in good shape!

### List PRs

List the PRs that made it into `dev` that are waiting to be pulled into `main`:

* PR #? which fixes #?

### Types of changes

What types of changes does this pull request introduce? Put an `x` in the boxes that apply.
This will inform the new release number.

- [ ] Fix (non-breaking change which fixes a bug)
- [ ] Feature (non-breaking change which adds or changes functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] Other change (if none of the other choices apply)

### Reviewer instructions

The underlying PRs should have been reviewed. Please check that the proposed merge is correct before approving.
If any checkboxes other than "Other change" have been selected a new version needs to be released.
Please prepare the following file changes:
- [ ] NEWS.md - add release notes
- [ ] DESCRIPTION - increment the version number according to [Semantic Versioning](semver.org)
