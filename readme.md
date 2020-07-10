# Documentation of "Meta data on (album and single) releases to Spotify (2015/10/30 - 2018/6/26)"

This is a repository which hosts the source code to prepare the public version of the data set:

Datta, Hannes, 2020, "Meta data on (album and single) releases to Spotify", https://doi.org/10.34894/DX857S, DataverseNL.

If you are a (potential) user of the data, please directly access its documentation using the link above.

## Maintaining new releases of the data

Use this repository to maintain the dataset.

* `init.sh` loads the most recent version of the uploading tool for dataverse
* `push_raw.sh` pushes the raw data to Dataverse (done once)
* `push_release.sh` pushes (updates) to the documentation in `\doc`, or the prepared data set in `\release`.