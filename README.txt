This repo contains all dependencies required to build BlueSky Re (https://github.com/uentity/blue-sky-re.git) on Windows.
All you need to do is setup environment variable BLUE_SKY_WINDEPS that points to your local clone of this repo.

NOTE: because of huge size, Boost headers are NOT included. You need to place 'em into `boost/boost` directory by yourself.

Includes following components.
Boost: 1.68
CGAL: 5.0 (header-only)
curl: 7.64.1 modified (patched version from https://github.com/uentity/curl.git that supports NTLM auth with given password hashes, linked with bundled OpenSSL)
HDF5: 1.10.4
loki: 0.1.7
OpenSSL: 1.1.1
tbb: 2019_20181203oss
CAF: 0.17.4
ANN: 1.1
freetype: 2.9.0
Windows CRT: 10.0.17763.0
MSVC libs: 15.9.1