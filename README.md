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
self-updating bash script. 
git pre-commit hook.
docker.

## next
fault tolerance in self-update routine.
more languages.
run only on new files.