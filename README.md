# pi-meta-oauth

Meta Model API OAuth for [pi](https://pi.dev). Use Muse Spark models through Pi's `openai-responses` provider.

## Install

```bash
pi install git:github.com/geocine/pi-meta-oauth@geocine
pi --list-models meta
```

## Login

```text
/login meta
```

Pick browser login (device flow) or paste a Model API key. Device-flow keys are re-minted daily; pasted keys are stored as-is. Or skip login entirely with `META_API_KEY` / `MODEL_API_KEY`.

## Models

`muse-spark-1.3`, `muse-spark-1.3-contributor`, `muse-spark-1.2`, `muse-spark-1.2-contributor`, `muse-spark-1.1`

## Verify

```bash
pi -p --provider meta --model muse-spark-1.3 "Reply exactly: META_OK"
```
