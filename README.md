# Back-End-Development-Pictures

Flask REST API completed from the IBM Skills Network template. Supports health, count, list, item lookup, POST, PUT, DELETE, duplicate detection and missing-ID errors. All 11 provided pytest tests pass.

## Environment Setup
- Repository created from the provided template.
- Course setup script: bin/setup.sh (original Python 3.9 environment).
- Verified in an isolated capstone-env environment using Python 3.10 in IBM Skills Network Labs, and Python 3.14 locally.
- Install: python -m pip install -r requirements.txt
- Test: python -m pytest -v
- Run: flask --app backend run --host 0.0.0.0 --port 3000
- Container: docker build -t pictures .

Endpoints: GET /health, GET /count, GET/POST /picture, GET/PUT/DELETE /picture/<id>.
Data starts from backend/data/pictures.json; changes are held in process memory as specified by the lab.
