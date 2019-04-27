## Last Week's Accomplishments

> Finished up with the backend refactor, found some weird stuff going on though with our data.

## This Week's Plan

> Working on debugging the roster errors we're running into with the source package.

## Anything Blocking?

> Kinda with this roster thing.

## Notes

> The roster error that we're having is that some of the new players on NFL.com don't seem to have their unique GSIS Identifiers assigned yet, which causes some roster mismatch errors when we try to generate our stats.
> Additionally, some players just have complete id mismatches somehow in the roster data, so I'll probably have to dive into the source code of our data package.