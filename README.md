# app-policies

Static legal pages for app OAuth and store submissions. Deploy via GitHub Pages.

## Apps

| App | Privacy Policy | Terms of Service |
|-----|----------------|------------------|
| [IELTS Speaking Templates](./ieltsspeakingtemplates/) | [privacy](./ieltsspeakingtemplates/index.html) | — |
| [Sage Marketing (sage_mkt)](./sage_mkt/) | [privacy](./sage_mkt/privacy-policy.html) | [terms](./sage_mkt/terms-of-service.html) |

## Deploy (GitHub Pages)

1. Push to `main` on [shannon1102/app-policies](https://github.com/shannon1102/app-policies)
2. Enable GitHub Pages: repo **Settings → Pages → Deploy from branch `main` / root**
3. URLs follow pattern:

```
https://shannon1102.github.io/app-policies/{app-folder}/privacy-policy.html
https://shannon1102.github.io/app-policies/{app-folder}/terms-of-service.html
```

### sage_mkt URLs (after deploy)

- Privacy Policy: `https://shannon1102.github.io/app-policies/sage_mkt/privacy-policy.html`
- Terms of Service: `https://shannon1102.github.io/app-policies/sage_mkt/terms-of-service.html`
- Home: `https://shannon1102.github.io/app-policies/sage_mkt/`
