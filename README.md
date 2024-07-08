#Overview

sb, the SCO Breaker, generates serial numbers, activation keys and
registration keys for SCO products, such as UnixWare 7.1.4.

It still works for versions released after SCO was acquired by Xinuos.
Products made by Xinuos themselves (namely OpenServer 10) do not employ any
kind of DRM.

THIS PROGRAM IS NOT MADE BY ME I'VE FOUND THIS ONLINE
# License
MIT License
# Installation

```
$ make
$ install -s sb /usr/local/bin
$ install -m 0644 doc/sb.1 /usr/local/man/man1
```

The install step is optional; sb does not depend on any files and can thus be
run from any directory.

# Usage and Documentation

See doc/sb.1 for using sb and doc/drm.ms for a description of the DRM
mechanisms employed by SCO.

For those with no access to troff implementation, a PDF version of the
documents have been included.
