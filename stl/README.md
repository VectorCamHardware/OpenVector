VectorCam is universal: one set of printed parts fits every compatible phone.

The current model is VectorCam 2.0. Its print files are in `stl/Universal/`. Each file is a print plate; print one of each to build a device:

- `VectorCam-2.0.stl`: the VectorCam body parts (white PETG)
- `TransparentDiffuser-2.0.stl`: the light diffuser (transparent PETG)
- `SpecimenTrayAndTubeTray.stl`: the specimen tray and tube tray (white PETG)

Each device uses approximately 102.1 g of white PETG and 3.1 g of transparent PETG.


## What the build guide publishes

The build guide at build-vectorcam.org reads this folder automatically and lists every file directly in `stl/Universal/` as one universal set.

The following stay in the repository but are not published:

- Files placed directly in `stl/` (outside any folder).
- Every other folder, including `stl/Archive/`.
- Anything in a subfolder, for example `stl/Universal/Archive/`.
- README and other Markdown files.


## Archive

`stl/Archive/` keeps earlier versions for reference. They are not published on the build guide:

- `MotorolaMotoGPlay/`, `TecnoPop20/`, `SamsungA32/`: phone-specific parts from before the universal model.
- `Universal-v1/`: the earlier specimen trays and tube tray.
- `Root-v1/`: older copies of the trays that sat directly in `stl/`.
- `Universal-2.0-rev1/`: the earlier 11-part VectorCam 2.0 plate, replaced on 2026-11-23.

To retire a part without deleting it, move it into `stl/Archive/`.
