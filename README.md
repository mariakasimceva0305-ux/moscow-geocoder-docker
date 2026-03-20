# moscow-geocoder-docker

Educational geocoding project for Moscow addresses with Docker-based runtime.

## Project Scope

Address normalization, geocoding, and evaluation with script and API entrypoints.

## Repository Structure

- `src/normalize.py`
- `src/geocode_basic.py`
- `src/geocode_improved.py`
- `src/data_loader.py`
- `src/evaluate.py`
- `src/api.py`
- `scripts/run_basic_cli.py`
- `scripts/run_improved_cli.py`
- `scripts/run_evaluate.py`
- `docker-compose.yml`

## Implemented Functionality

- address normalization
- baseline geocoding flow
- improved geocoding flow
- API invocation path
- evaluation script execution