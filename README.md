# EECS 348 Class Project

[![C/C++ CI](https://github.com/kmdeskin/EECS348-Class-Project/actions/workflows/compiles.yml/badge.svg)](https://github.com/kmdeskin/EECS348-Class-Project/actions/workflows/compiles.yml)

This is a repository for our class project done for EECS348 Software Engineering I at KU for the Fall 2023 semester.

To build the project, run `./macos-build.sh` on macOS, then the expected output is:
```
$ ./macos-build.sh

Building configurations...
Running action 'gmake'...
Done (80ms).
```

Now, to compile the project, run `make`. The expected output is:
```
$ make

==== Building sqlite (debug) ====
==== Building Calculator (debug) ====
==== Building Website (debug) ====
```

Next, change to the directory for the website by running `cd www`. 

In this directory, now run `./Website`.

Open your browser of choice and navigate to the following IP address: `137.184.123.158:3000`.

You should now see the web calculator application on the screen of your device.



