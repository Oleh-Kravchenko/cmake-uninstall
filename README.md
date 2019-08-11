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

## Use as git submodule

Add submodule

	git submodule add https://github.com/Oleh-Kravchenko/cmake-uninstall.git 3rdparty/cmake-uninstall

Add into your CMakeLists.txt file

	INCLUDE(3rdparty/cmake-uninstall/cmake/cmake-uninstall.cmake)

## Yocto

Please use recipe contrib/yocto/cmake-uninstall_git.bb
