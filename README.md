These are some third party packages for Solus, maintained by me here because Solus is no longer accepting new third party packages, and these packages are not available in another compatible format like snaps.

I haven't gotten far into learning how to properly package for Solus so apologies if these are not up to spec which I suspect they are not - I am mostly just doing this for my own use.  If it helps someone else though, that's cool :)

The original readme text of this forked repo is at the bottom.  But first, real quick, here's how to build and install one of the packages from this repo:

```
sudo eopkg build https://raw.githubusercontent.com/cyberwitch/3rd-party/master/network/download/synology-drive/pspec.xml
sudo eopkg install synology-drive-*-x86_64.eopkg
```

Third Party Apps (DEPRECATED)
=============================

**Note**: This repo will not accept NEW packages as we are replacing the majority of them in Solus with Snaps. After we have Snaps integrated in the Software Center we will begin forceful deprecation of this repository.

This repo contains the build files required to create packages that cannot be redistributed, whether for licensing restrictions or otherwise.

For more information about 3rd party applications in Solus, visit our Help Center page at https://getsol.us/articles/software/third-party/en/.


DO NOT PUSH BINARY PACKAGES. The git history has been reset because it ballooned to nearly 300MB in size. :)
