# Redaction - Red Action!

A compilation of github actions scripts to build the useful binaries for Offensive and Defensive Purpose.

## Motivation
- Build binaries instead of using the prebuilt one
- Use free resources and automation to achieve the above.

## References
- Compiling using .NET Framework 3.5 - https://github.com/orgs/community/discussions/25825
- At the time of working on this project I found a good research working along the same area ( https://medium.com/@two06/building-tooling-with-github-actions-59401648e61d ). The content is well written, however it was created during 2019 and there has been some significant changes in Github Actions since then.
  - For example, the private fork of the repo is not required
  - we need to use the 2019 windows runner as the latest does not ship .NET 3.5
