Introduction:
-------------

TODO

Compilation
------------

TODO

Working with the source code repository
---------------------------------------

dleyna-connector-dbus can be downloaded, compiled and installed as
follows:

   Clone repository
     # git clone git://github.com/01org/dleyna-connector-dbus.git
     # cd dleyna-connector-dbus

   Configure and build
```
     # meson setup build
     # ninja -C build
```

   Final installation
```
     # sudo ninja -C build install
 ```

Configure Options:
------------------

`-Dlog_level`

See logging.txt for more information about logging.
