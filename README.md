How to make RPM file
---------------------

1\. Clone django source tree.

``` bash
$ git clone git@github.com:django/django.git
```

2\. Change directory into cloned django's directory and run following command.

``` bash
$ python setup.py bdist_rpm --packager="Project Hatohol <hatohol-users@lists.sourceforge.jp>"
```

- See also
  - [Django repository](https://github.com/django/django)
  - [Python document (Creating Built Distributions)](https://docs.python.org/2.7/distutils/builtdist.html)
