[![Artifact HUB](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/sickhub)](https://artifacthub.io/packages/search?org=sickhub)
[![CircleCI](https://img.shields.io/circleci/build/github/SickHub/athens-proxy)](https://app.circleci.com/pipelines/github/SickHub/athens-proxy)
[![license](https://img.shields.io/github/license/sickhub/athens-proxy.svg)](https://github.com/sickhub/athens-proxy/blob/master/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/sickhub/athens-proxy.svg)](https://github.com/sickhub/athens-proxy)
[![Contributors](https://img.shields.io/github/contributors/sickhub/athens-proxy.svg)](https://github.com/sickhub/athens-proxy/graphs/contributors)
[![Paypal](https://img.shields.io/badge/donate-paypal-00457c.svg?logo=paypal)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=FTXDN7LCDWUEA&source=url)
[![GitHub Sponsor](https://img.shields.io/badge/github-sponsor-blue?logo=github)](https://github.com/sponsors/DrPsychick)

[![GitHub issues](https://img.shields.io/github/issues/sickhub/athens-proxy.svg)](https://github.com/sickhub/athens-proxy/issues)
[![GitHub closed issues](https://img.shields.io/github/issues-closed/sickhub/athens-proxy.svg)](https://github.com/sickhub/athens-proxy/issues?q=is%3Aissue+is%3Aclosed)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/sickhub/athens-proxy.svg)](https://github.com/sickhub/athens-proxy/pulls)
[![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/sickhub/athens-proxy.svg)](https://github.com/sickhub/athens-proxy/pulls?q=is%3Apr+is%3Aclosed)

## Helm chart for Athens Go Proxy
* [gomods/athens](https://github.com/gomods/athens)
* requires helm v3

```shell script
helm repo add athens https://sickhub.github.io/athens-proxy
helm search repo athens
```

On Artifact Hub: https://artifacthub.io/packages/search?org=sickhub

## Contribute
* Create issues, create PRs, ... let's make this better together.
* See [Contributing](CONTRIBUTING.md)

### Publish new chart version
Change the version in `Chart.yaml`, when the change is merged to main, it will trigger creating a release.
