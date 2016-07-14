=======
F-Lymph
=======
F-Lymph replaces the native werkzeug wsgi application interface in lymph web-api flask.
So with flymph you get all the benifits of a flask and still access the lymph.* api's.

please refer to the `helloworld.tar.gz
<https://github.com/eightnoteight/flymph/releases/download/v0.1.3/helloworld.tar.gz>`_ tar file for a demo lymph+flask microservice.

------------
Installation
------------

    pip install flymph  # as flask and lymph are dependencies, this will install both flask and lymph

-------------------
Hello World Program
-------------------

.. code:: bash

    wget 'https://github.com/eightnoteight/flymph/releases/download/v0.1.3/helloworld.tar.gz' -O helloworld.tar.gz
    tar -xvf helloworld.tar.gz
    cd helloworld_flymph
    virtualenv .venv --python=python3
    source ./.venv/bin/activate
    pip install flymph
    export PYTHONPATH=`pwd`
    lymph node


that's it now the hello world microservice is alive, you can test it with,

.. code:: bash

    curl localhost:6060
    curl localhost:6061


