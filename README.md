# Remote dev environment

#### TODO - to check :
- [ ] https://devpod.sh/
- [ ] https://developers.redhat.com/products/openshift-dev-spaces/overview  
      https://www.eclipse.org/che/  
      https://github.com/eclipse/che
      https://en.wikipedia.org/wiki/Eclipse_Che
      https://en.wikipedia.org/wiki/Eclipse_Theia
      https://github.com/eclipse-theia/theia
      https://newsroom.eclipse.org/eclipse-newsletter/2022/may/eclipse-che-gets-new-dev-environments-engine
      https://eclipsesource.com/blogs/2022/03/09/eclipse-theia-is-the-next-generation-eclipse-platform-for-ides-and-tools/
      https://access.redhat.com/documentation/en-us/red_hat_codeready_workspaces/2.2/html/end-user_guide/che-theia-ide-basics_crw
- [ ] https://azure.microsoft.com/en-us/products/dev-box
      https://techcommunity.microsoft.com/t5/azure-developer-community-blog/create-ready-to-code-dev-boxes-using-config-as-code-now-in/ba-p/3835034
      https://techcommunity.microsoft.com/t5/azure-developer-community-blog/reimagining-developer-workstations-with-microsoft-dev-box/ba-p/3825055
- [ ] https://blog.jetbrains.com/space/2021/11/29/introducing-remote-development-with-space/
- [ ] https://github.blog/2022-04-20-codespaces-multi-repository-monorepo-scenarios/
- [ ] nix/devcontainer conversation: https://news.ycombinator.com/item?id=34513877
- [ ] DevPod (not from loft...that's a k8s operator) https://www.uber.com/en-FR/blog/devpod-improving-developer-productivity-at-uber/
- [ ] https://www.kenmuse.com/blog/improving-dev-container-feature-performance/
- [ ] https://www.gitpod.io/blog/root-docker-and-vscode
- [ ] https://github.com/gitpod-io/Gitpod-Eclipse
- [ ] https://codeanywhere.com/
- [ ] https://stackblitz.com/
- [ ] https://codecatalyst.aws/explore

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

#### Ressources (Don't mind, I like to keep sources for later retrieval (eg `CTRL` + `F`))
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
