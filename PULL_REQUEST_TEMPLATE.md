<!--
Please remove the appropriate section.
For example, if this is a new feature, remove all sections except for the "New feature" section

If this is your first time opening a PR, be sure to check the contribution guide:
https://gazebosim.org/docs/all/contributing
-->

# 🦟 Bug fix

Fixes #<NUMBER>

## Summary
<!-- Describe your fix, including an explanation of how to reproduce the bug
before and after the PR.-->

## Backport Policy
<!-- Should this PR be backported to older versions? Important factors to consider include API/ABI and behavior changes. If so, which versions? Choose one pre-written option or suggest your own. If you're unsure leave this empty and let the maintainer advise. -->
- [ ] This is safe to backport to the following versions:
    - [ ] Jetty
    - [ ] Ionic
    - [ ] Harmonic
    - [ ] Fortress
- [ ] This **should not** be backported
- [ ] I am not sure
- [ ] Other (fill in yourself)

## Checklist
- [ ] Signed all commits for DCO
- [ ] Added a screen capture or video to the PR description that demonstrates the fix (as needed)
- [ ] Added tests
- [ ] Updated documentation (as needed)
- [ ] Updated migration guide (as needed)
- [ ] Consider updating Python bindings (if the library has them)
- [ ] `codecheck` passed (See [contributing](https://gazebosim.org/docs/all/contributing#contributing-code))
- [ ] All tests passed (See [test coverage](https://gazebosim.org/docs/all/contributing#test-coverage))
- [ ] Updated Bazel files (if adding new files). Created an issue otherwise.
- [ ] While waiting for a review on your PR, please help review [another open pull request](https://github.com/pulls?q=is%3Aopen+is%3Apr+user%3Agazebosim+archived%3Afalse+) to support the maintainers
- [ ] Was GenAI used to generate this PR? If so, make sure to add "Generated-by" to your commits. (See [this policy](https://osralliance.org/wp-content/uploads/2025/05/OSRF-Policy-on-the-Use-of-Generative-Tools-Generative-AI-in-Contributions.pdf) for more info.)

Generated-by: Remove this if GenAI was not used.

**Note to maintainers**: Remember to use **Squash-Merge** and edit the commit message to match the pull request summary while retaining `Signed-off-by` and `Generated-by` messages.

**Backports:** If this is a backport, please use **Rebase and Merge** instead.

🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸

# 🎉 New feature

Closes #<NUMBER>

## Summary
<!--Explain changes made, the expected behavior, and provide any other additional
context (e.g., screenshots, gifs) if appropriate.-->

## Backport Policy
<!-- Should this PR be backported to older versions? Important factors to consider include API/ABI and behavior changes. If so, which versions? Choose one pre-written option or suggest your own. If you're unsure leave this empty and let the maintainer advise. -->
- [ ] This is safe to backport to the following versions:
    - [ ] Jetty
    - [ ] Ionic
    - [ ] Harmonic
    - [ ] Fortress
- [ ] This **should not** be backported
- [ ] I am not sure
- [ ] Other (fill in yourself)
## Test it
<!--Explain how reviewers can test this new feature manually.-->

## Checklist
- [ ] Signed all commits for DCO
- [ ] Added a screen capture or video to the PR description that demonstrates the feature
- [ ] Added tests
- [ ] Added example and/or tutorial
- [ ] Updated documentation (as needed)
- [ ] Updated migration guide (as needed)
- [ ] Consider updating Python bindings (if the library has them)
- [ ] `codecheck` passed (See [contributing](https://gazebosim.org/docs/all/contributing#contributing-code))
- [ ] All tests passed (See [test coverage](https://gazebosim.org/docs/all/contributing#test-coverage))
- [ ] Updated Bazel files (if adding new files). Created an issue otherwise.
- [ ] While waiting for a review on your PR, please help review [another open pull request](https://github.com/pulls?q=is%3Aopen+is%3Apr+user%3Agazebosim+archived%3Afalse+) to support the maintainers
- [ ] Was GenAI used to generate this PR? If so, make sure to add "Generated-by" to your commits. (See [this policy](https://osralliance.org/wp-content/uploads/2025/05/OSRF-Policy-on-the-Use-of-Generative-Tools-Generative-AI-in-Contributions.pdf) for more info.)

Generated-by: Remove this if GenAI was not used.

**Note to maintainers**: Remember to use **Squash-Merge** and edit the commit message to match the pull request summary while retaining `Signed-off-by` and `Generated-by` messages.

**Backports:** If this is a backport, please use **Rebase and Merge** instead.

🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸🔸

<!-- For maintainers only -->

# 🎈 Release

Preparation for <X.Y.Z> release.

Comparison to <x.y.z>: https://github.com/gazebosim/<REPO>/compare/<LATEST_TAG_BRANCH>...<RELEASE_BRANCH>

<!-- Add links to PRs that require this release (if needed) -->
Needed by <PR(s)>

## Checklist
- [ ] Asked team if this is a good time for a release
- [ ] There are no changes to be ported from the previous major version
- [ ] No PRs targeted at this major version are close to getting in
- [ ] Bumped minor for new features, patch for bug fixes
- [ ] Updated changelog
- [ ] Updated migration guide (as needed)
- [ ] Link to PR updating dependency versions in appropriate repository in [gazebo-release](https://github.com/gazebo-release) (as needed): <LINK>

<!-- Please refer to https://github.com/gazebo-tooling/release-tools#for-each-release for more information -->

**Note to maintainers**: Remember to use **Squash-Merge** and edit the commit message to match the pull request summary while retaining `Signed-off-by` messages.
