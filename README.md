[![CVE reports](https://img.shields.io/badge/Release--contents-CVE%20Reports-blue?labelColor=grey&color=green)](https://gnome.pages.gitlab.gnome.org/gnome-build-meta/release-contents.html)

## Disclaimer (part I added for this repo)

Wanted to experiment with some Flatpak apps on my MuseBook but could not find the Gnome runtime anywhere for riscv64. So here it is, maybe it will save someone a little bit of time.

### How to download/install

The repo is hosted on a Cloudflare bucket. You can add it with:
```
flatpak remote-add flatpak-repo-riscv64 https://flatpak.ambatunat.buzz/repo/nico359-riscv64.flatpakrepo
```
Alternatively you can just download the .flatpakrepo file and add it with the graphical app of your choice (e.g. Gnome Software, KDE Discover, etc.):  
https://flatpak.ambatunat.buzz/repo/nico359-riscv64.flatpakrepo  

You can also check what is included in the repo with the following command (assuming you named it like in the step above):  
```
flatpak remote-ls flatpak-repo-riscv64
```
You might have to specify --arch=riscv64 after remote-ls if you are not running it on a riscv device.


# GNOME Build Metadata

The GNOME Build Metadata repository is where the GNOME release team manages build metadata for building the GNOME Flatpak runtime, GNOME OS, and GNOME OCI images.

## Getting started

If you'd like to **use** GNOME OS, please see the [installation guide](https://gnome.pages.gitlab.gnome.org/gnome-build-meta/docs/install.html) and the [user guide](https://gnome.pages.gitlab.gnome.org/gnome-build-meta/docs/using.html). For an overview of the project, visit the [GNOME OS website](https://os.gnome.org/).

To **contribute** to the GNOME Flatpak runtime, GNOME OS or GNOME OCI images, see the [contribution guide](https://gnome.pages.gitlab.gnome.org/gnome-build-meta/docs/contributing.html) to get started, and the [debugging guide](https://gnome.pages.gitlab.gnome.org/gnome-build-meta/docs/debugging.html) for common troubleshooting steps.

You can also read the markdown source of the documentation in [docs](./docs/)
