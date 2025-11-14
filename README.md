# thunderbird-uplift-queries
Script used to gather bugzilla uplift queries.

## Installation

### Using pipx (Recommended)
```bash
pipx install .
```

Or install directly from the repository:
```bash
pipx install git+https://github.com/coreycb/thunderbird-uplift-queries.git
```

### Using pip
```bash
pip install .
```

### Development setup
```bash
python3 -m virtualenv .venv
source .venv/bin/activate
pip3 install -e .
```

Or with development dependencies:
```bash
pip3 install -e ".[dev]"
```

## Uninstallation

If installed with pipx:
```bash
pipx uninstall thunderbird-uplift-queries
```

If installed with pip:
```bash
pip uninstall thunderbird-uplift-queries
```

## Usage

After installation, simply run:
```bash
get-uplift-queries
```

This will:
1. Fetch current Thunderbird version information
2. Generate bugzilla query URLs for uplift candidates
3. Create an HTML file with all queries and open it in your browser
