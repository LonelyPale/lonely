# lonely
tools

```
python3 -m pip install --upgrade pip

python3 setup.py --help
python3 setup.py sdist
python3 setup.py bdist_wheel
python3 setup.py sdist bdist_wheel

pip3 install twine
python3 -m twine --version
pip3 show --files twine
twine upload dist/*

pip3 install lonely
pip3 show --files lonely
python3 -m lonely version

https://pypi.org/project/lonely
```
