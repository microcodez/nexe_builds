# microcodez/nexe_builds release log

## 0.4.0

* Created on: 2023-12-10
* Nexe version: 4.0.0-rc.2
* Set Linux build to run in version pinned `ghcr.io/urbdyn/centos7-devtoolset8-builder` container which has preinstalled version of `devtoolset-8` package.
* Set Linux build to use Node.js version as defined in `.nvmrc` file.
* Build matrix:
  * OS: `linux`, `macos`, `windows`
  * Node Version: `20.10.0`
  * Node Version: `20.9.0` (added on 24/12/2023)
  * Node version: `20.12.2` (added on 14/07/2024)
  * Node version: `20.15.1` (added on 15/07/2024)
  * Node version: `22.13.1` (added on 15/07/2024)
  * Node version: `22.14.0` (added on 14/04/2025)
  * Node version: `22.16.0` (added on 05/06/2025)
  * Node version: `22.20.0` (added on 14/10/2025)
  * Node version: `22.21.0` (added on 27/10/2025)

## 0.3.0 and below

Go to https://github.com/urbdyn for older version