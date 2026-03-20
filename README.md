# moscow-geocoder-docker

Educational geocoding project for Moscow addresses with containerized runtime.

## Repository Contents

- `src/normalize.py` - address normalization logic.
- `src/geocode_basic.py` - baseline geocoding pipeline.
- `src/geocode_improved.py` - extended geocoding pipeline.
- `src/data_loader.py` - input data loading.
- `src/evaluate.py` - evaluation routines.
- `src/api.py` - API layer.
- `src/config.py` - configuration parameters.
- `scripts/run_basic_cli.py` - CLI run for baseline pipeline.
- `scripts/run_improved_cli.py` - CLI run for improved pipeline.
- `scripts/run_evaluate.py` - evaluation script.
- `docker-compose.yml` and `Dockerfile.txt` - container setup files.

## Implemented Functionality

The codebase includes:

- address normalization,
- baseline and improved geocoding flows,
- API-based invocation,
- evaluation script for output quality checks,
- Docker-based execution environment.