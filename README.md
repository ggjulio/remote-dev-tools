# Remote dev environment

Just a README to compare solutions/tools, and regroup all informations available I found.

#### Advantages
- Spin up a new environment in seconds.
- No local setup needed, less drift, repetable development environment.
- Project onboarding. Start coding on day one instead of fighting for setting up the local dev environment.
- Change environments in seconds.
  - Ex: You work on a feature, a critical bug has been assigned to you.
    Spin up a new environment from a specific branch in seconds, fix it, PR/merge it, then get back to your previous task's environment in seconds)
- No need for powerful laptops (Even chromebooks are enough)
- Greater compute power available if needed. (32 cores + 32GB ram enough ?)
- Platform independent. Works the same on windows, linux and macos. (No need of platform independent setup)
- Cost Effective. Containers are stopped and restarted automatically.
- Security. The source code always stay on the remote server. Even if the laptop is stolen it should be no big deal.

#### Inconvenient
- Very few solutions, plus they are quite new.
- Few of them allow self-hosting, and open source.
- No internet, no dev.
  - Can be mitigated by having a powerful enough laptop + docker. (fully containerized environment to avoid maintaining platform dependent code.
- More ?

### List of all available tools (I found)

#### Comparing solutions

| ✔️ | ❌  | ❔           | ➖             |
| --- | --- | ---         |   ---           |
| Yes | No  | Don't know  | Not Applicable  |
<!-- Default line
| ❔❔❔❔❔❔❔❔   | ❔                | ❔      | ❔                 | ❔     | ❔             |
-->
<!-- copy/paste: ✔️  ❌ ➖ ❔ -->
|  🐋+🐧=❤️       | Github Codespace  | Gitpod  | Gitpod Dedicated  | Coder | Jetbrain Space |
|---              | ---               |    ---  | ---               | ---   | ---            |
| SAAS            | ✔️                |   ❔    | ❔                | ❔     | ❔             |
| Self Hosted     | ❌                | ✔️❌   | ❌               | ✔️     | ✔️            |
| Jetbrain's IDEs | ✔️                | ✔️     | ✔️❔              | ❔     | ❔             |
| Vscode IDEs     | ✔️                | ✔️     | ❔                 | ❔     | ❔             |
| ❔❔❔❔❔❔❔❔   | ❔                | ❔      | ❔                 | ❔     | ❔             |

SSO Support

#### Ressources (Don't mind, I like to keep sources.)
- https://blog.jetbrains.com/blog/2022/11/09/remote-development-in-jetbrains-ides-now-available-to-github-codespaces-users/
- https://coder.com
- https://www.jetbrains.com/space/features/dev-environments.html
- https://medium.com/@jeremysf/visual-studio-code-github-codespaces-kubernetes-bonkers-c85acfee5148
- https://coder.com/blog/coder-or-gitpod-which-is-better-for-your-team



<!-- Tools -->
[tool-coder]: https://coder.com/
[tool-gitpod]: https://www.gitpod.io/
[tool-gitpod-dedicated]: https://https://www.gitpod.io/dedicated
[tool-jetbrain-space]: https://www.jetbrains.com/space/

<!-- Other -->
[jetbrain-space-dev-env]: https://www.jetbrains.com/space/features/dev-environments.html
