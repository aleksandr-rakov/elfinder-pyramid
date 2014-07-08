connector.py
------------
This is conector for elfinder file manager, written for pyramid framework.
Based on original https://github.com/Studio-42/elfinder-python/blob/master/connector.py
For work you also need https://github.com/Studio-42/elfinder-python/blob/master/elFinder.py

How to try it:
-------------
In your virtualenv run:
```
git clone git://github.com/aleksandr-rakov/elfinder-pyramid.git
cd elfinder-pyramid/elfinder_pyramid_example/
../../bin/python setup.py develop
../../bin/pserve development.ini
```

And open http://127.0.0.1:6543/ in your browser.
Done!

Notes:
-------------
- This connector support only v.1 protocol
- requires PIL or PILLOW for thumbnail generation
