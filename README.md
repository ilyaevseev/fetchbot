fetchbot
========

### Purpose

Parallel asyncronous requests to multiple URL's.

### Usage
```
Usage: ./fetchbot [args..] urls_file
Args:
    -v, --verbose
    -h, --help
    -D, --delay VALUE
```
Example:
```sh
./fetchbot sample-urls.list
```

### Requirements

* Perl
* standard modules: POSIX, Time::HiRes, Data::Dumper
* [AnyEvent::HTTP](https://metacpan.org/pod/AnyEvent::HTTP) (Debian/Ubuntu: _apt-get install libanyevent-http-perl_)
