# k8s-rized_dev_env

#### Advantages
- Spin up a new environment in seconds.
- No local setup needed, less drift, repetable development environment.
- Project onboarding. Start coding on day one instead of fighting for setting up the local environment.
- Change environments in seconds.
  - Ex: You work on a feature, a critical bug has been assigned to you.
    Spin up a new environment in seconds, fix it, PR/merge it, then get back to your previous task's environment in seconds)
- No need for powerful laptops.
- Greater compute power available if needed. (64 cores enough ? )
- Work the same on windows, linux and macos since there is no local setup appart from setting up the connexion to the the distant server.
- Cost Effective. Containers are stopped and restarted automatically.
- Security. The source code always stay on the remote server. Even if the laptop is stolen it should be no big deal.


#### Inconvenient
- Very few solutions, and they are quite new.
- Very few of them allow self-hosting, most of them are not open source

### List of all available tools (I found)
#### github codespace]()
##### Solution
  - SAAS

##### [Gitpod](https://www.gitpod.io/)
  - SAAS, previous licences allowed self hosted, but new licences don't.
##### [coder](https://coder.com/)
  - SAAS, Self Hosted

##### Jetbrain 

#### Ides
- IntelliJ
  -
  -

#### Comparing solutions

| e  | Github Codespace | Gitpod | Jetbrain Space |
| ---| --- | --- | 
| Self Hosted | ✔️ | ❌ | Yes |
| Jetbrain IDSs  | yes | Yes |


|   | Github Codespace  | Gitpod  | Jetbrain Space  | Coder   |
|---| ---               |    ---  | ---             | ---     |
| SAAS                  | ✔️      |                 |         |   |
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
[tool-github-codespace]: https://coder.com/
[tool-jetbrain-space]: https://www.jetbrains.com/space/

<!-- Other -->
[jetbrain-space-dev-env]: https://www.jetbrains.com/space/features/dev-environments.html
