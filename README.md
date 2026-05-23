<p align="center"><strong>codex-termux</strong> is a Termux-focused fork of Codex CLI for Android ARM64.
<p align="center">
  <img src="https://github.com/openai/codex/blob/main/.github/codex-cli-splash.png" alt="Codex CLI splash" width="80%" />
</p>
</br>
This repository is tuned for <strong>Termux on Android (aarch64/arm64)</strong>: build pipeline, npm packaging, and update channel all target the Termux distribution.</p>

---

## Quickstart

### Install (Termux)

Install from npm:

```shell
npm install -g @dopaemon/codex-termux
codex
```

### Scope

- This fork is intended for Termux users.
- Releases and update checks point to `dopaemon/codex-termux`.
- If you want the generic upstream multi-platform installer (brew/install scripts/official npm), use `openai/codex`.

<details>
<summary>You can also go to the <a href="https://github.com/dopaemon/codex-termux/releases/latest">latest GitHub Release</a> and download the appropriate binary for your platform.</summary>

For this fork, prefer Android ARM64 / Termux artifacts.

</details>

### Using Codex with your ChatGPT plan

Run `codex` and select **Sign in with ChatGPT**. We recommend signing into your ChatGPT account to use Codex as part of your Plus, Pro, Business, Edu, or Enterprise plan. [Learn more about what's included in your ChatGPT plan](https://help.openai.com/en/articles/11369540-codex-in-chatgpt).

You can also use Codex with an API key, but this requires [additional setup](https://developers.openai.com/codex/auth#sign-in-with-an-api-key).

## Docs

- [**Codex Documentation**](https://developers.openai.com/codex)
- [**Contributing**](./docs/contributing.md)
- [**Installing & building**](./docs/install.md)
- [**Open source fund**](./docs/open-source-fund.md)

This repository is licensed under the [Apache-2.0 License](LICENSE).
