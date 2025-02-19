[![Website](https://img.shields.io/badge/sitcomtn--138-lsst.io-brightgreen.svg)](https://sitcomtn-138.lsst.io)
[![CI](https://github.com/lsst-sitcom/sitcomtn-138/actions/workflows/ci.yaml/badge.svg)](https://github.com/lsst-sitcom/sitcomtn-138/actions/workflows/ci.yaml)

# Rotator Emergency Stopping Distance

## SITCOMTN-138

The Rotator Emergency Stopping Distance was engineered to characterize and optimize the rotator's emergency stopping distance without faulting the System. The measured data provided the minimum stopping distance of such a subsystem in both positive and negative rotations and its maximum stopping time for a given emergency deceleration. Also, it was essential to ensure that the camera did not sense any accelerations or rotator motor currents that were too high when decelerating.
	


**Links:**

- Publication URL: https://sitcomtn-138.lsst.io
- Alternative editions: https://sitcomtn-138.lsst.io/v
- GitHub repository: https://github.com/lsst-sitcom/sitcomtn-138
- Build system: https://github.com/lsst-sitcom/sitcomtn-138/actions/


## Build this technical note

You can clone this repository and build the technote locally if your system has Python 3.11 or later:

```sh
git clone https://github.com/lsst-sitcom/sitcomtn-138
cd sitcomtn-138
make init
make html
```

Repeat the `make html` command to rebuild the technote after making changes.
If you need to delete any intermediate files for a clean build, run `make clean`.

The built technote is located at `_build/html/index.html`.

## Publishing changes to the web

This technote is published to https://sitcomtn-138.lsst.io whenever you push changes to the `main` branch on GitHub.
When you push changes to a another branch, a preview of the technote is published to https://sitcomtn-138.lsst.io/v.

## Editing this technical note

The main content of this technote is in `index.md` (a Markdown file parsed as [CommonMark/MyST](https://myst-parser.readthedocs.io/en/latest/index.html)).
Metadata and configuration is in the `technote.toml` file.
For guidance on creating content and information about specifying metadata and configuration, see the Documenteer documentation: https://documenteer.lsst.io/technotes.
