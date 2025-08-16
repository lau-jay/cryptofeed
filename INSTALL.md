# Cryptofeed installation
 
The Cryptofeed library is intended for use by Python developers.

Several ways to get/use Cryptofeed:

* Pip - `pip install cryptofeed`
* Git - `git clone https://github.com/lau-jay/cryptofeed`
* Zipped source code - Download [github.com/lau-jay/cryptofeed/archive/master.zip](https://github.com/lau-jay/cryptofeed/archive/master.zip)

## Installation with Pip

The safe way to install and upgrade the Cryptofeed library:

    pip install --user --upgrade cryptofeed

Cryptofeed supports many backends as Redis, ZeroMQ, RabbitMQ, MongoDB, PostgreSQL, Google Cloud and many others.
Cryptofeed is usually used with a subset of the available backends, and installing the dependencies of all backends is not required. 
Thus, to minimize the number of dependencies, the backend dependencies are optional, but easy to install.

See the file [`setup.py`](https://github.com/lau-jay/cryptofeed/blob/master/setup.py#L60)
for the exhaustive list of these *extra* dependencies.

* Install all optional dependencies  
  To install Cryptofeed along with all optional dependencies in one bundle:

        pip install --user --upgrade cryptofeed[all]

* Arctic backend  
  To install Cryptofeed along with [Arctic](https://github.com/man-group/arctic/) in one bundle:

         pip install --user --upgrade cryptofeed[arctic]

* Google Cloud Pub / Sub backend

         pip install --user --upgrade cryptofeed[gcp_pubsub]

* Kafka backend

         pip install --user --upgrade cryptofeed[kafka]

* MongoDB backend

         pip install --user --upgrade cryptofeed[mongo]

* PostgreSQL backend

         pip install --user --upgrade cryptofeed[postgres]

* QuasarDB backend  
  To install Cryptofeed along with [QuasarDB](https://quasar.ai/) in one bundle:

         pip install --user --upgrade cryptofeed[quasardb]

* RabbitMQ backend

         pip install --user --upgrade cryptofeed[rabbit]

* Redis backend

          pip install --user --upgrade cryptofeed[redis]

* ZeroMQ backend

         pip install --user --upgrade cryptofeed[zmq]

