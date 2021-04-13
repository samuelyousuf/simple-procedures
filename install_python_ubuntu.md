# Installing Python on Ubuntu

Use this procedure to install Python on your Ubuntu system.

1. Download the latest version of Python from the [official website](https://www.python.org/).

2. Open a terminal window and then log in with the `root` account.

3. Navigate to the downloaded package.

4. To extract the contents of the package, type `tar -xf [name of the package]` and then press `enter`.

    ````shellscript
    tar -xf Python-3.9.4.tar.xz
    ````

5. Navigate to the extracted folder.

6. Type `./configure` and then press `enter`.

    ````shellscript
    ./configure
    ````

7. Type `make` and then press `enter`.

    ````shellscript
    make
    ````

8. Type `make install` and then press `enter`.

    ````shellscript
    make install
    ````

9. To confirm that Python was installed, type `python3 --version` and then press `enter`.

    ````shellscript
    python3 --version
    ````

The installed version of Python will appear.

````shellscript
    Python 3.9.4
````
