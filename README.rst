Usage
===============

Start Flask Server
---------------------

.. code-block:: bash

    ~$ python app.py

Access http://0.0.0.0:8080/ to see the webside
    
===============

Build with Dokcer container
--------------------------------

.. code-block:: bash

    ~$ docker build -t aavail-ml .


Run the container to test that it is working
----------------------------------------------    

.. code-block:: bash

    ~$ docker run -p 4000:8080 aavail-ml

Go to http://0.0.0.0:4000/ and you will see a basic website that can be customtized for a project.



