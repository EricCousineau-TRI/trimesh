```sh
python -m venv ./venv
source ./venv/bin/activate
pip install --update pip wheel
pip install -e .[test]

pytest tests/test_obj.py -k test_multi_texture_roundtrip -s
```
