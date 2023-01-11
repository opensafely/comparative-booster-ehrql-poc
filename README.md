# Proof-of-concept ehrQL translation of "Comparative effectiveness of BNT162b2 versus Moderna COVID-19 booster doses"

This is a proof-of-concept translation of the study definition from the
below repo into an ehrQL dataset definition:
https://github.com/opensafely/comparative-booster

It was initially developed as part of the [Data Builder](https://github.com/opensafely-core/databuilder)
test suite and was then extracted in this PR:
https://github.com/opensafely-core/databuilder/pull/931

Git history was preserved using [`git-filter-repo`](https://github.com/newren/git-filter-repo):

    git filter-repo --subdirectory-filter tests/acceptance/comparative_booster_study
