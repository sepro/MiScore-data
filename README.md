[![Validate data](https://github.com/sepro/MiScore-data/actions/workflows/validate.yml/badge.svg)](https://github.com/sepro/MiScore-data/actions/workflows/validate.yml)

# MiScore Data

Repo with my own high scores, the records file (```./data/records.json```) will be automatically validated (using
the [MiScore](https://github.com/sepro/MiScore) package combined with a GitHub Action).

If you wish to check locally, create a virtual environment and install all packages from ```requirements.txt```,
then run the command below.

```commandline
 python -m miscore validate .\data\records.json
```

The MiScore package now also has features to add games using a text based interface. For more details check out [MiScore on GitHub](https://github.com/sepro/MiScore).
