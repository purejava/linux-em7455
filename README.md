# linux-em7455
This builds installable Arch linux kernel 4.5.4 packages that contain a patch for Sierra Wireless EM7455 and MC7455 modems.

The patch is necessary to initialize these modems correctly.

# Build instructions
* Clone this repository
* Import this two keys into your gpg keyring: ABAF11C65A2970B130ABE3C479BE3E4300411886, 647F28654894E3BD457199BE38DBBDC86092693E
* run ```makepkg```
* install packages with ```sudo pacman -U <kernel_packages>```
