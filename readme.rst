=======
F-Lymph
=======
F-Lymph replaces the native werkzeug wsgi application interface in lymph web-api flask.
So with flymph you get all the benifits of a flask and still access the lymph.* api's.

------------
Installation
------------

    pip install flymph  # as flask and lymph are dependencies, this will install both flask and lymph

-------------------
Hello World Program
-------------------

    wget link.tar.gz
    tar -xvf link.tar.gz
    cd link
    virtualenv .venv --python=python3
    source activate ./.venv/bin/activate
    pip install flymph
    lymph node

that's it now the hello world microservice is alive, you can test it with,

    curl localhost:6060
    curl localhost:6061
