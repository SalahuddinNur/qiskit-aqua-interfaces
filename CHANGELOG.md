Changelog
=========

All notable changes to this project will be documented in this file.

The format is based on [Keep a
Changelog](http://keepachangelog.com/en/1.0.0/).

> **Types of changes:**
>
> -   **Added**: for new features.
> -   **Changed**: for changes in existing functionality.
> -   **Deprecated**: for soon-to-be removed features.
> -   **Removed**: for now removed features.
> -   **Fixed**: for any bug fixes.
> -   **Security**: in case of vulnerabilities.


[UNRELEASED](https://github.com/Qiskit/qiskit-aqua-interfaces/compare/0.2.1...HEAD)
===================================================================================

[0.2.1](https://github.com/Qiskit/qiskit-aqua-interfaces/compare/0.2.0...0.2.1) - 2019-12-17
============================================================================================

Changed
-------

-   Application deprecate message (#54)

Fixed
-----

-   Do not create output file on chemistry run (#53)
-   Change start aqua/chemistry process calls to run command line scripts (#52)
-   Open file only return False if file not found (#51)
-   Fix pylint errors, remove operator_mode (#49)



[0.2.0](https://github.com/Qiskit/qiskit-aqua-interfaces/compare/0.1.0...0.2.0) - 2019-08-22
============================================================================================

Added
-----

-   IBMQ v2 support
-   More Information on About box.

Changed
-------

-   Handle single value with different schema types, like array and integer
-   Improve PEP8 conformance
-   Remove qiskit-chemistry library dependency

Fixed
-----

-   Refresh sections panel when removing a section
-   On MacOSX avoid possible matplotlib error in case it is imported by other imported libraries


[0.1.0](https://github.com/Qiskit/qiskit-aqua-interfaces/compare/b1d21f0...0.1.0) - 2019-05-02
=================================================================================

Added
-----

-   Moved Aqua GUI and command line to this repository
-   Moved Chemistry GUI and command line to this repository

Changed
-------

-   Changed package name to dashes in setup.py.
-   Updated qiskit minimum version in setup.py.
-   Fixed links in readme.me.