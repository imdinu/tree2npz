# **tree2npz**: extract ROOT Tree branches as numpy binaries

Given a Tree and a Branch name, the script provided here will extract the data from that branch and store the content as a *.npz* archive. This tool can read and decompress ROOT Tree files in parallel, making it a fast option for Machine Learning Feature Engineering.

## Quick setup
After making sure you have ```Python``` and ```pip``` installed; you just need to install a few dependencies:
```sh
$ pip install --user -r requirements.txt 
```

For basic usage instructions try:
```sh
$ ./extract.py --help
```

## TODO:
- add options for exporting *.npx* and *.hdf*

## Additional Notes:
- ⚠️ This utility is **NOT** compatible with irregular data structures ⛔️
- Although this tool was designed to be used in conjuncture with [nsw_data_wrangler](https://gitlab.cern.ch/ml4nswtp/nsw_data_wrangler)'s output. It may be adapted to any other use-case requiring parallel extraction of highly compressed ROOT data.

