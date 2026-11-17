VectorCam is universal: one set of printed parts fits every compatible phone.

Duplicate parts are labeled 1 and 2.

Each device includes a total of 8 printed components:
- SpecimenTray1
- SpecimenTray2
- TubeTray
- Body
- CableManager
- Lid
- LEDHolder1
- LEDHolder2


*If uploading your own .STLs, make sure to include copies of duplicate parts for ease-of-print. 


## What the build guide publishes

The build guide at build-vectorcam.org reads this folder automatically and lists every published file as one universal set:

- Everything directly in `stl/Universal/`.
- Interim: the parts in `stl/MotorolaMotoGPlay/` are shown as the universal body parts until the universal versions are uploaded to `stl/Universal/`. The folder-name prefix is removed from their labels on the site.

The following stay in the repository but are not published:

- Files placed directly in `stl/` (outside any folder).
- Every other folder, including `stl/Archive/` and the older phone folders (`stl/SamsungA32/`, `stl/TecnoPop20/`).
- Anything in a subfolder, for example `stl/Universal/Archive/`.
- README and other Markdown files.

To retire an old part without deleting it, move it into an `Archive` folder.
