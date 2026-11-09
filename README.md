# Jenkins CI/CD Demo

Pipeline: GitHub push → webhook → ngrok → Jenkins build → WebEx notification

## Files
- `sample_code.py` - simple math functions (add, subtract, multiply, divide)
- `tests/test_sample_code.py` - unit tests (pytest)
- `build.sh` - runs the code and checks PEP 8 style
- `test.sh` - runs the unit tests
