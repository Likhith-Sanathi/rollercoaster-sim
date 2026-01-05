# rollercoaster-sim

Simple roller coaster simulation project used for learning and experimentation. The repository contains several iterations of the simulation as separate Python scripts.

## Contents

- `iteration1.py` — initial prototype
- `iteration2_1.py` — second iteration (variant 1)
- `iteration2_2.py` — second iteration (variant 2)
- `iteration3_1.py` — third iteration (variant 1)
- `iteration3_2.py` — third iteration (variant 2)

## Requirements

- Python 3.8 or newer
- Optional: any libraries used by specific iterations (e.g., `numpy`, `matplotlib`) — if present, they should be listed in a `requirements.txt` file.

## Installation (Windows / PowerShell)

1. Open PowerShell and create a virtual environment:

```powershell
python -m venv venv
.\\venv\\Scripts\\Activate.ps1
```

2. If the project has dependencies, install them:

```powershell
pip install -r requirements.txt
# If there is no requirements.txt, skip this step
```

## Running

Run any iteration script directly from the activated virtual environment. Examples:

```powershell
python iteration1.py
python iteration2_1.py
python iteration2_2.py
python iteration3_1.py
python iteration3_2.py
```

If a script requires additional arguments or produces plots, consult the top of the script for usage notes or open the file to see how it's invoked.

## Development notes

- Keep each experimental change in its own `iteration*.py` file for clarity.
- If you add dependencies, add them to `requirements.txt` with pinned versions.

## Contributing

PRs and issues are welcome. Prefer small, focused changes and include short descriptions of the behavior you changed or added.

## License

Add a license file if you plan to publish or share this project publicly.


![image_alt](https://github.com/PixelManiac-Droid/rollercoaster_sim/blob/da3bf46f4278926d70e33c3a8aa884d832264e09/Screenshot%202025-04-09%20151351.png)
