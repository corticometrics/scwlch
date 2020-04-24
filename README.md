# sCWLch
> Squelch bugs with this suite for creating CWL Checker workflows


Code base to create [Checker workflows](https://docs.dockstore.org/en/develop/advanced-topics/checker-workflows.html) to unit test your CWL workflows.

`cwltest` provides means to compare results to a reference for any CWL document, but it only uses the CWL output json for this. That means if results are functionally the same, but have minor differences (such as small numerical differences, or file metadata), `cwltest` will say they are different due to changes in the checksum.

Checker workflows are a wrapper for your Workflow, where your results are fed into the checker, and the checker outputs a result (such as `true`/`false`) that is compatible with `cwltest`.

## Install

For now, clone this repo and run:
`pip install .`

Coming to PyPI soon!

## How to use

WIP

## Acknowledgements

This work has been partially funded by the following NIH grants
  - R42CA183150
  - R42AG062026

Thanks to the CWL comminity (see [here](https://gitter.im/common-workflow-language/common-workflow-language?at=5ea0d848f6a6e539796ddecd) for the discussion that led to this project)
