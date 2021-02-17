Cache of packages for gpg4win build. Used to make full rebuild of gpg4win more
reliable, since without this the source of each endpoint must be online for a
build to complete.

See
[gpg4win/packages](http://git.gnupg.org/cgi-bin/gitweb.cgi?p=gpg4win.git;a=tree;f=packages;hb=HEAD)
for more info.

To update the packages, run the
[download.sh](http://git.gnupg.org/cgi-bin/gitweb.cgi?p=gpg4win.git;a=blob;f=packages/download.sh;hb=HEAD)
and copy the downloaded files to packages in this repo.
