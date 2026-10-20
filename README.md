# Maud

A GitHub Docker action that sighs in your workflow log and lets the rest of the job carry on.

When the job reaches Maud's step, the log shows:

```
*sigh*
```

Then she exits with code 0. She is tired, not spiteful.

## Requirements

A Linux runner, such as `ubuntu-latest`. Maud is a Docker container action (Alpine 3.21), and GitHub runs those only on Linux.

## Usage

```yaml
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: VladCuciureanu/Maud@main
```

Maud has no inputs and no outputs. She needs nothing from you and has nothing left to give.

She does not read your secrets, touch your files or fail your build, and she sighs on every run, whatever the event, branch or time of day. She will not explain why. You know why.

## License

MIT. See [LICENSE](LICENSE).
