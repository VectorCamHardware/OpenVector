For each device print one complete phone-specific folder and one universal folder.

Duplicate parts are labeled 1 and 2.

Devices Should include a total of 8 printed-components:
- SpecimenTray1 (Universal)
- SpecimenTray2 (Universal)
- TubeHolder (Universal)
- Body (Device-Specific)
- CableManager (Device-Specific)
- Lid (Device-Specific)
- LED Holder1 (Device-Specific)
- LED Holder2 (Device-Specific)


*If uploading your own .STLs, make sure to include copies of duplicate parts for ease-of-print. 


## What the build guide publishes

The build guide at build-vectorcam.org reads this folder automatically. Only the following files appear on the site:

- `stl/Universal/<file>`: shown for every phone, tagged "Universal Compatibility".
- `stl/<PhoneFolder>/<file>`: shown for that phone only. `<PhoneFolder>` must match the phone's catalog id without the `phone-` prefix (for example, `phone-MotorolaMotoGPlay-1` uses `stl/MotorolaMotoGPlay/`).

The following stay in the repository but are not published:

- Files placed directly in `stl/` (outside any folder).
- Anything in `stl/Archive/`.
- Anything in a subfolder of a phone or Universal folder, for example `stl/MotorolaMotoGPlay/Archive/`.
- README and other Markdown files.

To retire an old part without deleting it, move it into an `Archive` folder.
