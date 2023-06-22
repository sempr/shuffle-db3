# iPod shuffle Database Builder

`src/python/rebuild_db3.py` is a python3 version
`src/python/rebuild_db2.py` is a python2 version I found but doesn't depend on `eyed3` so it's probably missing some functionality.

# Usage

Place the python script (`rebuild_db[2/3].py`) on the root of your IPod and put your audio files in a directory in the root of the IPod as well. Then run `rebuild_db[2/3].py AUDIO_DIRECTORY` to index the DB.

# NOTE

Don't remove your IPod Control directory. You can't regenerate it without iTunes.
