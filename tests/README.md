# Test suite

This directory houses proof-of-functionality tests.
* [`cli/`](cli/) - Uses the installed package's command-line interface, generating validated CASE output.
* [`package/`](package/) - Uses importable features of the installed package's modules to run Python unit tests.


## Running the test suite

Run `make check`.  `make check` should be run from one directory up, at least once, to trigger some downloads.
