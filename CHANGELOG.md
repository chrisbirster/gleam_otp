# Changelog

## Unreleased

- `actor.start` returns a channel rather than a channel and a pid.
- `actor.StartError` includes a case for the child crashing while
  initialising.
- `actor.Spec` has an `init_timeout` field which specifies how long the actor
  has to initialise.
- `process.make_*` functions have been renamed to `process.new_*`.
- `actor.Message` is no longer a public type.

## v0.0.1 - 2020-08-20

- Initial minimal release.