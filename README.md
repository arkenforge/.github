<!-- Save as .github/profile/README.md in a public repo named ".github" in the org.
     Put the two banner PNGs in that same repo at profile/assets/. -->

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/gh-org-banner-dark.png">
    <img src="./assets/gh-org-banner-light.png" alt="arken/auth — The server holds nothing." width="100%">
  </picture>
</p>

**Arken builds authentication where the server keeps nothing worth stealing.** A client signs a one-time nonce with a key it owns, the server verifies the signature, and no credentials are stored.

### Projects

| Repo | What it is |
|---|---|
| [arken-auth](https://github.com/ORG/arken-auth) | Express and FastAPI middleware. Rust core, `did:key` identity. |

### Get involved

- **Try it:** `npm i arken-auth`
- **Break it:** see `SECURITY.md` for how to report a flaw. Valid finds are credited.
- **Shape 1.0:** we're looking for a few teams to try it on a real API. [Apply here](https://tally.so/r/kbbjWR).
- **Follow releases:** Watch → Custom → Releases on the repo.
