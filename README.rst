Motortwit Demo
==============

Example of mongo project using aiohttp_, motor_ and aiohttp_jinja2_ (https://readthedocs.org/projects/aiohttp-jinja2/downloads/pdf/latest/), 
similar to flask one. 

Installation
============

Clone repo and install library::

    $ git clone git@github.com:aio-libs/aiohttp-demos.git
    $ cd aiohttp-demos

Install the app::

   
    $ pip install -e .
    (no need pip install -r req.txt)
Create database for your project::
mongodb
run in pwsh Start-Job -ScriptBlock { mongod --config  ".\sanicmotopronto\db\mongodb.conf" }

cd .\motortwit\

python.exe .\generate_data.py 

Run application::

python.exe .\main.py

Open browser::

    http://127.0.0.1:9001


Requirements
============
* aiohttp_
* motor_
* aiohttp_jinja2_
* running instance of mongodb


.. _Python: https://www.python.org
.. _aiohttp: https://github.com/KeepSafe/aiohttp
.. _motor: https://github.com/mongodb/motor
.. _aiohttp_jinja2: https://github.com/aio-libs/aiohttp_jinja2
.. _MongoDB: https://www.mongodb.com/ 
