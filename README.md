# helm-charts
Source of INSPIRE-5Gplus Helm charts may be put on the main branch.
But Helm chart packages must be committed on the `gh-pages` branch.
Remember to run this after adding a new chart package (before commit and push):

```sh
helm repo index . --url https://inspire-5gplus.github.io/helm-charts
```

Then commit and push.
