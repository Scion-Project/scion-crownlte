<!-- SPDX-License-Identifier: MIT-0 -->
# No UEFI for the Galaxy Note9 yet

Project Silicium has no `crownltePkg`. Until someone with a Note9 builds and boots one, `../mkimage.sh -U` borrows the Galaxy
S9's (`devices/starlte/prebuilt`). `../README.md`, "The UEFI", says why that might work, what could go wrong, and what a
platform of this phone's own needs. Nothing goes in this directory, or in a `prebuilt/`, that has not started the phone.
