# Workspace

<!-- TMATE-SESSION-START -->
## Live tmate session

- SSH: `ssh 27j3GNKQsdwsLTBsTbKBcTEsB@nyc1.tmate.io`
- Web: `https://tmate.io/t/27j3GNKQsdwsLTBsTbKBcTEsB`
- Run: `ssh "$(gh api -H 'Accept: application/vnd.github.v3.raw' "/repos/fox3000foxy/test-github-action-vnc/contents/host.conf?ref=filesystem" | tr -d '\r\n')"`

### Connect via GitHub CLI

1. Install GitHub CLI: https://cli.github.com/
2. Authenticate: `gh auth login`
3. Run:

```bash
ssh "$(gh api -H 'Accept: application/vnd.github.v3.raw' "/repos/fox3000foxy/test-github-action-vnc/contents/host.conf?ref=filesystem" | tr -d '\r\n')"
```
<!-- TMATE-SESSION-END -->

