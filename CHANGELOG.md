# Smart Issue Creator Changelog

## [0.2.1](https://github.com/dryvist/raycast-smart-issue/compare/v0.2.0...v0.2.1) (2026-06-12)


### Bug Fixes

* **ci:** repoint markdown-lint to dryvist/.github hub ([#36](https://github.com/dryvist/raycast-smart-issue/issues/36)) ([f4fc336](https://github.com/dryvist/raycast-smart-issue/commit/f4fc33694e0d6058aa860fcc15bfb14b0f9ccf79))

## [0.2.0](https://github.com/dryvist/raycast-smart-issue/compare/v0.1.0...v0.2.0) (2026-06-01)


### Features

* initial implementation of Smart Issue Creator extension ([a131ea0](https://github.com/dryvist/raycast-smart-issue/commit/a131ea04a5f07a69d2e160862ac843e844c2542a))
* Migrate to vllm-mlx, add label dropdowns, use useCachedPromise ([#8](https://github.com/dryvist/raycast-smart-issue/issues/8)) ([21d04e3](https://github.com/dryvist/raycast-smart-issue/commit/21d04e3cdef6a855771656b48a2f08106b3394fc))


### Bug Fixes

* Add CLAUDE.md, update flake.nix for bun, fix lint issues ([#9](https://github.com/dryvist/raycast-smart-issue/issues/9)) ([54f5db4](https://github.com/dryvist/raycast-smart-issue/commit/54f5db41588dc9360a98092cf32dbe394b3d36d8))
* **ci:** repoint release-please caller to org-native reusable workflow ([#34](https://github.com/dryvist/raycast-smart-issue/issues/34)) ([50e6220](https://github.com/dryvist/raycast-smart-issue/commit/50e6220cd7fd632cebfd17dcad7ecbc3c55c3739))
* **ci:** retarget reusable-workflow uses: refs to current org homes ([#32](https://github.com/dryvist/raycast-smart-issue/issues/32)) ([f08650c](https://github.com/dryvist/raycast-smart-issue/commit/f08650ce0a5579e60fb149a764c031d5f7cee5ef))
* **deps:** update dependency @octokit/rest to v22 ([#4](https://github.com/dryvist/raycast-smart-issue/issues/4)) ([cc23965](https://github.com/dryvist/raycast-smart-issue/commit/cc23965101eed482ef72ace830bcd3c1a7e3c491))
* **deps:** update dependency @raycast/utils to v2 ([#6](https://github.com/dryvist/raycast-smart-issue/issues/6)) ([6bc1fab](https://github.com/dryvist/raycast-smart-issue/commit/6bc1fabd3c888fbace31fdb0394601f2590b06aa))
* fetch model list fresh on every command open ([#18](https://github.com/dryvist/raycast-smart-issue/issues/18)) ([64130d6](https://github.com/dryvist/raycast-smart-issue/commit/64130d6bbad6f190ce4c458c8fd156ea7cf04dd6))
* Purge all Ollama references, rename preference to llmUrl ([#10](https://github.com/dryvist/raycast-smart-issue/issues/10)) ([f0b1fb5](https://github.com/dryvist/raycast-smart-issue/commit/f0b1fb590d5f7e39325e2fc91b9e19b48674851d))
* reduce max_tokens, add CI/CD and project config ([#19](https://github.com/dryvist/raycast-smart-issue/issues/19)) ([fb2ac11](https://github.com/dryvist/raycast-smart-issue/commit/fb2ac11005f080a71e932cf5972f70d55d1dc3b3))
* **renovate:** extend org-wide preset for auto-merge trust ([#11](https://github.com/dryvist/raycast-smart-issue/issues/11)) ([76bc64a](https://github.com/dryvist/raycast-smart-issue/commit/76bc64a4e9ac099ece6c56a898ecbeb0f44d6d31))
* silent failure in LLM response parsing, add dynamic model dropdown ([#17](https://github.com/dryvist/raycast-smart-issue/issues/17)) ([87e34cf](https://github.com/dryvist/raycast-smart-issue/commit/87e34cfbdb594c1257cf8e795c21f1fb73917fcf))

## [1.0.0] - 2026-03-01

### Added

- Initial release
- AI-powered GitHub issue generation using local Ollama models
- Repository selection from your GitHub organization/user
- Priority selection (Critical, High, Medium, Low)
- Automatic label detection and assignment from repo labels
- Duplicate issue detection
- Detail view showing created issue with metadata
- Configurable Ollama URL and model preferences
- Fallback model support when primary model is unavailable
