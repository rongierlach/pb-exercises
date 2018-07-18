# Pre-Requisites

Install python 3.5 or above on your machine:

 * Windows: https://www.python.org/ftp/python/3.6.2/python-3.6.2-amd64.exe
 * Mac OS X: https://www.python.org/ftp/python/3.6.2/python-3.6.2-macosx10.6.pkg
 * Linux: see your distro docs

Install pip:

Download this script: https://bootstrap.pypa.io/get-pip.py

Run (you may need to specify python3 if you also have python2 installed)

    $ python get-pip.py

Install git:

https://git-scm.com/downloads

Install nodeenv:

    $ pip install nodeenv

# Download pb-exercises requirements

    $ git clone https://github.com/rongierlach/pb-exercises
    $ cd pb-exercises
    $ nodeenv --requirements=requirements.txt --node=8.11.3 --force .venv

Linux/OSX:

    $ . .venv/bin/activate
    (.venv) $ npm install -g ijavascript
    (.venv) $ ijsinstall

Windows:

    > .venv\Scripts\activate.bat
    > npm install -g ijavascript
    > ijsinstall

# Run jupyter notebook

    (.venv) $ jupyter notebook
