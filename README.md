# Adjustable-Configs
Assorted config files that are redistributed across servers

These are KV files that utilize conditional tags as filters when distributed across servers. For example, generating a file for Open Fortress will ignore any lines with the [TeamFortress2] conditional.

## Valid Conditionals

### Open Fortress
[OpenFortress], [PassionFruit]

### Team Fortress 2
[TeamFortress2], [Chocolate], [Rainbow], [Strawberry], [MvM], [Vanilla]

You can combine conditionals with a pipe "|, like so, [Chocolate|Rainbow]. The line will only be removed if *every word in the chain fails*.
