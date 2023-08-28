# retrosheet-mirror

This repo is a mirror of the [alldata.zip file](https://www.retrosheet.org/downloads/alldata.zip) on Retrosheet's website.
It specifically exists to help with Retrosheet's QA process and is not meant for broad public consumption.
You are welcome to use it, but it comes with no guarantees around maintenence, freshness, or correctness.
For a reliably maintained copy, I recommend using the [Chadwick Bureau's Retrosheet repo](https://github.com/chadwickbureau/retrosheet)
or accessing the data from Retrosheet's site directly.


There are three permanent branches:
  - *official* represents the current alldata.zip file from the website, with any nested archives changed to directories.
  - *submitted* represents the state of the corrected files to be submitted back to Retrosheet,
   along with any modifications discussed during handoff.
  - *working* represents any changes that that are made to make local development easier,
    but should not be submitted as corrections (e.g. deleting problematic lines).

```
 The information used here was obtained free of
 charge from and is copyrighted by Retrosheet.  Interested
 parties may contact Retrosheet at "www.retrosheet.org".
```
