# Overview

Adds uninstall target to CMake projects.

# Example

CMakeLists.txt

	FIND_PACKAGE(cmake-uninstall REQUIRED)

Command interpreter

	make uninstall

# Installation

## Gentoo Linux

	$ layman -S
	$ layman -a kaa
	$ emerge dev-util/cmake-uninstall -a

## Yocto

Please use recipe contrib/yocto/cmake-uninstall_git.bb
