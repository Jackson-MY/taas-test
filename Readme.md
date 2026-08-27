## TaaS Guide

This repo contains `.github/workflows/taas.yml`, which submits a TaaS job with callback information.

Configure this repository secret in GitHub before running the workflow:
https://github.com/Jackson-MY/taas-test/settings/secrets/actions

```text
QCOM_API_KEY
```

Job parameters are defined in [`.github/taas-config.json`](.github/taas-config.json).

Run it from the Actions tab with `workflow_dispatch`, or trigger it by pushing to `main` / opening a pull request.
