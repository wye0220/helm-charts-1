# helm-charts

Repository for Helm-charts used by me.

> **_NOTE:_** Never commit company specific configuration into this repo.
>
> Even though this github repo is "private" the helm chart repository (`gh-pages`) hosting the packaged charts is [public](https://comjf-io.github.io/helm-charts/).
>
> Once [OCI format for helm sources](https://github.com/fluxcd/source-controller/issues/124) is supported by flux, we can move these charts to [ECR](https://docs.aws.amazon.com/AmazonECR/latest/userguide/push-oci-artifact.html).


### Bootstrap documentation

- [Github action for chart deployment](https://helm.sh/docs/howto/chart_releaser_action/)
  - Note: [In your repo, go to Settings/Pages. Change the Source Branch to gh-pages.](https://github.com/marketplace/actions/helm-chart-releaser#example-workflow)
- [Chart Test & Linting](https://github.com/helm/chart-testing-action)
