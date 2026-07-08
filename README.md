# homebrew-localmask

Homebrew tap for [LocalMask](https://www.localmaskpro.com) — privacy-first
secret & PII masking for code. 100% local, no phone-home.

## Install

```bash
brew install sgury/localmask/localmask
```

Then:

```bash
localmask scan ./my-repo      # detect + mask secrets/PII locally
localmask --help
```

> Note: LocalMask depends on `cryptography` and `pydantic-core`, which build
> from source (Rust). First install compiles them, so it isn't instant.
> Prefer no compile? `pipx install localmask` pulls prebuilt wheels instead.

Free edition (MIT). Pro/Team/Enterprise: https://www.localmaskpro.com
