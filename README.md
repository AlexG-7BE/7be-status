# 7be-status

Uptime check for [7be.io](https://7be.io): every 10 minutes a GitHub Actions run fetches
`/`, `/pricing`, `/scan` and `/sitemap.xml`. A page that does not answer HTTP 200 within 10
seconds (checked twice, 30 s apart) fails the run, and GitHub emails the repository owner.

Runs: [Actions → Uptime](../../actions/workflows/uptime.yml). Run it by hand with
"Run workflow".
