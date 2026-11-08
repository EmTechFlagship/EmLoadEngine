# EmLoadEngine

EmLoad's backend engine. The macOS app (`gui-macos`) runs this package.

```bash
git clone https://github.com/EmTechFlagship/EmLoadEngine.git
cd EmLoadEngine
python3 -m venv .venv
.venv/bin/python -m pip install -e .
.venv/bin/python -m EmLoadEngine setup
.venv/bin/python -m EmLoadEngine doctor
```

Stay in `EmLoadEngine` for those commands. Build and open the Mac app from the EmLoad checkout that contains `gui-macos/`.
