# cheatsheet-knative-A4
Knative CheatSheets In A4

<a href="https://github.com/DennyZhang?tab=followers"><img align="right" width="200" height="183" src="https://raw.githubusercontent.com/USDevOps/mywechat-slack-group/master/images/fork_github.png" /></a>

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

[![LinkedIn](https://raw.githubusercontent.com/USDevOps/mywechat-slack-group/master/images/linkedin_icon.png)](https://www.linkedin.com/in/dennyzhang001) <a href="https://www.dennyzhang.com/slack" target="_blank" rel="nofollow"><img src="http://slack.dennyzhang.com/badge.svg" alt="slack"/></a> [![Github](https://raw.githubusercontent.com/USDevOps/mywechat-slack-group/master/images/github.png)](https://github.com/DennyZhang)

File me [tickets](https://github.com/DennyZhang/cheatsheet-knative-A4/issues) or star [the repo](https://github.com/DennyZhang/cheatsheet-knative-A4).

Printable version on A4 page: [cheatsheet-knative-A4.pdf](cheatsheet-knative-A4.pdf)

<a href="https://www.dennyzhang.com"><img align="right" width="185" height="37" src="https://raw.githubusercontent.com/USDevOps/mywechat-slack-group/master/images/dns_small.png"></a>

See more CheatSheets from Denny: [here](https://github.com/topics/denny-cheatsheets)

- Query status

| Name                        | Command                                                                                                           |
| :-------------------------- | ----------------------------------------------------------------------------------------------------------------  |
| List configurations         | `kubectl get configurations`                                                                                      |
| List all revisions          | `kubectl get revisions`                                                                                           |
| List all functions          | `kubectl get route`                                                                                               |
| List all gateways           | `kubectl get gateway --all-namespaces`                                                                            |
| List all related pods       | `watch "kubectl get pods -n istio-system; echo "\n"; kubectl get pods -n knative-serving"`                        |
| Get function domain name    | `kubectl get services.serving.knative.dev $conf_name -o=custom-columns=NAME:.metadata.name,DOMAIN:.status.domain` |
| Get ingress gateway service | `kubectl get svc knative-ingressgateway -n istio-system`                                                          |

<img align="right" width="500" height="400" src="https://github.com/dennyzhang/cheatsheet-knative-A4/blob/master/images/object_model.png" />

<a href="https://www.dennyzhang.com"><img align="right" width="201" height="268" src="https://raw.githubusercontent.com/USDevOps/mywechat-slack-group/master/images/denny_201706.png"></a>

<a href="https://www.dennyzhang.com"><img align="right" src="https://raw.githubusercontent.com/USDevOps/mywechat-slack-group/master/images/dns_small.png"></a>
# License
- Code is licensed under [MIT License](https://www.dennyzhang.com/wp-content/mit_license.txt).
