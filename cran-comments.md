## Test environments
* local Windows install, R 3.2.3
* ubuntu 12.04 (on travis-ci), R 3.2.4
* win-builder (devel and release)

## R CMD check results
There were no ERRORs or WARNINGs.

There was 1 NOTE:

```
* checking CRAN incoming feasibility ... NOTE
Maintainer: 'Seward Lee <sewardlee337@gmail.com>'
New submission
```

* This is the first submission for this package. I understand that this NOTE is a non-issue, as it is meant to "remind CRAN maintainers to check that the submission comes actually from his maintainer and not anybody else." See: [R-devel mailing list](https://mailman.stat.ethz.ch/pipermail/r-devel/2014-March/068497.html)

win-builder has also flagged the following:

```
Possibly mis-spelled words in DESCRIPTION:
  XBRL (10:22)
  scalable (11:25)
```

* I understand that neither "XBRL" (short for "eXtensible Business Reporting Language") nor "scalable" are spelling errors.

## Downstream dependencies
There are currently no downstream dependencies.

## Resubmission
This is a resubmission. In this version I have:

* Per CRAN Repository Policy, reduced the runtime of "checking examples" to only a few seconds.

* Included url to EDGAR homepage in DESCRIPTION.