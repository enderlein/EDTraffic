# EDSM Logger
A module for logging data from edsm.net

# Usage
You can use the stuff under `edsm/api.py` as a barebones Python interface for some EDSM API endpoints.

The models defined in `models.py` bundle data from the 'systems', 'traffic', 'station', and 'market' endpoints under a single dict-like container model (see class `Systems` in `models.py`)

Check `log.py` for an example implementation of `models.py`

Check `example.py` for some example driver code for `log.py`
