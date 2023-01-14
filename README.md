# k8s-rized_dev_env

#### Advantages
- Spin up a new environment in seconds.
- No local setup needed, less drift, repetable development environment.
- Project onboarding. Start coding on day one instead of fighting for setting up the local dev environment.
- Change environments in seconds.
  - Ex: You work on a feature, a critical bug has been assigned to you.
    Spin up a new environment in seconds, fix it, PR/merge it, then get back to your previous task's environment in seconds)
- No need for powerful laptops. (Even cheap chromebooks are enough)
- Greater compute power available if needed. (32 cores + 32GB ram enough ?)
- Work the same on windows, linux and macos.
- Cost Effective. Containers are stopped and restarted automatically.
- Security. The source code always stay on the remote server. Even if the laptop is stolen it should be no big deal.


#### Inconvenient
- Very few solutions, they are quite new.
- Few of them allow self-hosting, and open source.

### List of all available tools (I found)


#### Comparing solutions

| ✔️ | ❌  | ❔           | ➖             |
| --- | --- | ---         |   ---           |
| Yes | No  | Don't know  | Not Applicable  |

<!-- copy/paste: ✔️  ❌ ➖ ❔ -->
|   | Github Codespace  | Gitpod  | Gitpod Dedicated | Jetbrain Space  | Coder   |
|---| ---               |    ---  | --- |---             | ---     |
| SAAS                  | ✔️      |                 |         |   |
|---| ---               |    ---  | --- |---             | ---     |

| Self Hosted           | ❌      |   |   |   |
|   |   |   |   |   |
|   |   |   |   |   |

#### Ressources
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
