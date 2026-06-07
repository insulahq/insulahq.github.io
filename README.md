# insulahq.github.io

Hosts the **Insula documentation site** at <https://insulahq.github.io/>.

⚠️ **Do not edit docs here.** The manual's source lives in the
[`insulahq/insula`](https://github.com/insulahq/insula) monorepo under
`documentation/`. This repo only runs `.github/workflows/build-docs.yml`,
which pulls that source on a schedule and deploys it to Pages. The
`.last-deployed-sha` marker tracks the last source commit published.
