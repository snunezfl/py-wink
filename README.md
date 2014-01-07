py-wink
=======

Python library for interfacing with Wink devices

This library implements the API at: http://docs.wink.apiary.io/

To get started...

1. Copy config.default.cfg to config.cfg and add in your client id and secret
   keys.

2. Run the "login.py" script and provide your Wink account credentials.

3. Run the "test.py" script in interactive mode (`python -i test.py`) so you
   can interact with the Wink servers. All the test script does is fetch a list
   of your Wink devices, and print out the type and id for each.

---

Note that this library requires httplib2 to be installed.

I only have a Nimbus "cloud_clock" and so far have only done a small amount of
testing. Any input, bug reports or additional functionality would be much
appreciated.
