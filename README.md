# pre-commit-hook

## motivation
checking for bad code in CI sucks, it's already checked in.
rejecting bad code before commit would be nice.

## goals
prohibit commits with bad code.
require only ONE manual step, forever.
support for multiple languages.
no requirements for native tools.

## how
bash. 
git pre-commit hook.
docker.
