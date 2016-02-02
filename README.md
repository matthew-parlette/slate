slate
=====

Overview
--------

Container to host a [slate](https://github.com/tripit/slate) site.

Usage
-----

In your source documentation folder (which looks like the [source](https://github.com/tripit/slate/tree/master/source) from tripit/slate).

Pull this container and map the documentation folder to `/app/source`:

    $ docker run mattparlette/slate -v /path/to/docs:/app/source

Go to `http://localhost:4567/` and you will see your new beautiful API documentation.

You can also change the port (to port 8000, for example) with:

    $ docker run mattparlette/slate -p 8000:4567
