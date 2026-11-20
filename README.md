# OpenVector

An open-source hardware and data repository for **VectorCam** — an AI-enabled mosquito-imaging tool built around a smartphone and a 3D-printed lens/light attachment. This repo holds everything needed to build your own device: the bill of materials, reference documents, and 3D-printable parts.

The full build guide — with an interactive parts list, cost calculator, and step-by-step instructions is here: **[Build VectorCam](https://build-vectorcam.org/)**

Visit the official [vectorcam.org](https://vectorcam.org) for more details.

Email inquiries to vectorcamhardware@gmail.com.

## Repository structure
catalog/
catalog.csv Bill of materials — hardware, filament, and field equipment (the phone is supplied by the builder),
with sourcing links and cost (source of truth for the build guide's parts list; the guide re-syncs from this file)

docs/
tool-specifications.pdf
assembly-instructions.pdf   (v2.0, VectorCam 2.0)
print-specifications.pdf
app-install.pdf
qualification-instructions.pdf
documentation-guidelines.pdf
archive/   Earlier versions kept for reference (assembly-instructions-v1.pdf)

stl/
3D-printable parts. See stl/README.md for the folder layout and naming convention.


tools/
image-calibration/ Image Quality Test, a web page for checking photos from a device
([open it](https://build-vectorcam.org/tools/image-calibration/)).
