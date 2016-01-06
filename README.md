# tinyurl-python
Python module to create short links from tinyurl.com

# Installation
```sh
git clone https://github.com/daxeel/TinyURL-Python.git
```
```sh
cd TinyURL-Python
```
```sh
python setup.py install
```

# Usage
```py
>>> import tinyurl
```
```py
>>> print tinyurl.shorten("www.abc.com", "xyz")
>>> http://www.abc.com/xyz
```
```py
>>> print tinyurl.shorten("www.abc.com", "")
>>> http://www.abc.com/wxghf
```
<p>Here, tinyurl has shorten function which takes two parameters. First is URL which you want to short and second one is custome name.</p>
<p>Leave blank second argument if you want random alias.</p>