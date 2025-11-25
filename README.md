# hipSPARSELt-gentoo-ebuild
This is a hacked-together ebuild for hipSPARSELt based on official Gentoo
ebuilds for other ROCm software, targeting 7.1.0 which is not available in the
Gentoo repositories.  I can understand why, because this thing was a pain to
build.

Based on ebuilds and patches from here:

https://github.com/gentoo/gentoo/tree/master/sci-libs/hipBLASLt

https://github.com/gentoo/gentoo/tree/master/sci-libs/hipSPARSE

https://github.com/gentoo/gentoo/blob/master/eclass/rocm.eclass

# Caution
I am not terribly familiar with ebuilds, so this is very much hacked together.
Use at your own risk.  But it does seem to work for me on x86-64.  I'm sharing
it here in the hopes of saving you the pain I had to go through trying to get
this darn library to build so pyTorch would work correctly with ROCm 7.1.0.
