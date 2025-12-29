# Maud

A GitHub Action that sighs. That's it. When your CI pipeline reaches Maud's step, she lets out a small, tired exhale — and then lets the rest of your pipeline carry on. She changes nothing. She breaks nothing. She just sighs.

Every time.

## Motivation

CI pipelines are relentless. They run and run and run. They never complain. They never pause to feel the weight of yet another `fix: lint` commit pushed at 11:47 PM on a Sunday. Someone should.

Maud does.

## Usage

```yaml
steps:
  - uses: vladcuciureanu/maud@v1
```

There is nothing to configure.

## What it does

When your CI pipeline reaches Maud's step, she prints:

```
*sigh*
```

Then she exits. Successfully. She is tired, not spiteful.

## Inputs

None. Maud doesn't need anything from you.

## Outputs

None. Maud has nothing left to give.

## Requirements

- **Sigh on start.** When the action begins, Maud emits a sigh to the workflow log. One sigh. A small, tired exhale. Not dramatic — she's past that.
- **No side effects.** Maud does not alter files, set outputs, fail the build, or affect any other step. She is purely observational in her exhaustion.
- **Always sighs.** Maud sighs regardless of the trigger event, the branch, the repository, the time of day. There are no conditions under which Maud does not sigh. She has tried.
- **Exits successfully.** After sighing, Maud exits with code 0. She is tired, not spiteful.
- **Fast.** The sigh should be near-instantaneous. Maud is efficient in her weariness.
- **Lightweight.** Minimal image size. Maud carries enough already.
- **No dependencies.** Maud does not need your tokens, your secrets, or your environment variables. She just needs a moment.

## Non-Goals

- Maud will not offer encouragement.
- Maud will not explain why she is sighing. You know why.
- Maud will not sigh louder based on how many times the workflow has been re-run. She considered it.
- Maud will not integrate with Slack, Discord, or any notification service. She is not looking for attention. She is just tired.

## Success Criteria

Maud is successful if, upon seeing her sigh in the logs, the developer pauses — just for a moment — and thinks: "yeah."
