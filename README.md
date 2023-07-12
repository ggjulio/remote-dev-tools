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
- Platform independent. Works the same on windows, linux and macos. (No need of maintaining setup scripts foreach platform)
- Cost Effective. Containers are stopped and restarted automatically.
- Security. The source code always stay on the remote server. Even if the laptop is stolen it should be no big deal.

#### Inconvenient
- Very few solutions, plus they are quite new.
- Few of them allow self-hosting, and open source.
- No internet, no dev.
  - Can be mitigated by having a powerful enough laptop + docker. (fully containerized environment to avoid maintaining platform dependent code.
- More ?

### List of all available tools (I found)

#### TODO - tools to check :
- [ ] https://devpod.sh/
- [ ] https://developers.redhat.com/products/openshift-dev-spaces/overview  
      https://www.eclipse.org/che/  
      https://github.com/eclipse/che  

#### Comparing solutions

| ✔️ | ❌  | ❔           | ➖             |
| --- | --- | ---         |   ---           |
| Yes | No  | Don't know  | Not Applicable  |
<!-- Default line
| ❔❔❔❔❔❔❔❔   | ❔                 | ❔            | ❔                    | ❔             | ❔             | ❔                  | ❔                |
-->
<!-- copy/paste: ✔️  ❌ ➖ ❔ -->
|  🐋+🐧=❤️      | [Codespace][gh-cs] | [Gitpod][gp] | [GP Dedicated][gp-dc] | [Coder][coder] | [Space][jb-s] | [Cloud dev][jb-cd] | [cloud 9][cloud9] |
|---              | ---                |    ---       | ---                   | ---            | ---           | ---                | ---               |
| Owner           | Github             |   ➖         | Gitpod                | ➖           | Jetbrain       | Jetbrain            | Aws              |
| Open source     | ❌                | ✔️           | ❔                    | ✔️             | ❔             | ❔                  | ❔                |
| OSS Licence     | ➖                | AGPL-3.0     | ❔                    |  AGPL-3.0       | ❔             | ❔                  | ❔                |
| SSO Support     | ❔                 | ❔            | ❔                    | ❔             | ❔             | ❔                  | ❔                 |
| Cost            | ❔                 | ❔            | ❔                    | ❔             | ❔             | ❔                  | ❔                 |
|                 | ➖                | ➖            | ➖                   | ➖             | ➖             | ➖               | ➖                |
| SAAS            | ✔️                | ✔️             | ✔️                  | ❌             | ✔️             | ✔️                 | ❔                |
| Self Hosted     | ❌                | ✔️➡❌        | ❌                   | ✔️            | ✔️            | ❔                  | ❔                |
|                 | ➖                | ➖            | ➖                   | ➖             | ➖             | ➖               | ➖                |
| Bitbucket       | ❌                | ❔            | ❔                    | ✔️             | ❔             | ❔                  | ❔                |
| Gitlab          | ❌                | ✔️            | ❔                    | ✔️             | ❔             | ❔                  | ❔                |
| Github          | ✔️                | ❔            | ❔                    | ✔️             | ❔             | ❔                  | ❔                |
|                 | ➖                | ➖            | ➖                   | ➖             | ➖             | ➖               | ➖                |
| Jetbrain's IDEs | ✔️                | ✔️            | ✔️❔                  | ❔             | ❔             | ❔                  | ❔                |
| Vscode IDEs     | ✔️                | ✔️            | ❔                    | ❔            | ❔             | ❔                   | ❔               |
| Jupyter         | ✔️                | ❔            | ❔                    | ✔️            | ❔             | ❔                   | ❔               |
| ❔❔❔❔❔❔❔❔   | ❔                 | ❔            | ❔                    | ❔             | ❔             | ❔                  | ❔                |

#### Ressources (Don't mind, I like to keep sources for later retrieval (aka CTRL + F))
- https://blog.jetbrains.com/blog/2022/11/09/remote-development-in-jetbrains-ides-now-available-to-github-codespaces-users/
- https://coder.com
- https://www.jetbrains.com/space/features/dev-environments.html
- https://medium.com/@jeremysf/visual-studio-code-github-codespaces-kubernetes-bonkers-c85acfee5148
- https://coder.com/blog/coder-or-gitpod-which-is-better-for-your-team
- https://aws.amazon.com/fr/blogs/architecture/field-notes-use-aws-cloud9-to-power-your-visual-studio-code-ide/
- https://coder.com/blog/coder-the-github-codespaces-alternative 
- https://coder.com/pricing
- https://www.gitpod.io/docs/configure/authentication/

#### alternatives
- https://devenv.sh/ # compatible devcontainer

<!-- Tools -->
[coder]: https://coder.com/
[gp]: https://www.gitpod.io/
[gp-dc]: https://www.gitpod.io/dedicated
[gh-cs]: https://github.com/features/codespaces
[jb-s]: https://www.jetbrains.com/space/
[jb-cd]: https://www.jetbrains.com/space/features/dev-environments.html
[cloud9]: https://aws.amazon.com/fr/cloud9/

<!-- Other -->
[jetbrain-space-dev-env]: https://www.jetbrains.com/space/features/dev-environments.html

https://www.infoq.com/articles/devcontainers/
