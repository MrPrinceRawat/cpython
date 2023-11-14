Extended CPython 3.12
========================

.. contents::

Overview
========================

This repository contains the implementation of a new feature for CPython. The feature aims to address a commonly requested enhancement, offering potential improvements to the Python programming experience.

Installation
^^^^^^^^^^^^
Download the binary file from the releases page.

`Check Releases <https://github.com/MrPrinceRawat/cpython-extended/releases>`__ (opens in new tab/window)


Feature Description
^^^^^^^^^^^^^^^^^^^

The implemented feature addresses specific user needs, providing a practical addition to the Python language. The purpose is to enhance functionality which you never thought you needed until now. The feature is described in detail below.

Feature: Introducing the '???' Token
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

We are thrilled to introduce the '???' token, a novel addition to CPython that simplifies global variable handling. The '???' token is designed for situations where you don't want to worry about specifying the type of a global variable explicitly.

Usage Example:

.. code-block:: python
    
    global_variable = ???  # Python will handle the type for you!


The '???' token is a placeholder for the type of the global variable. It is a special token that instructs the Python interpreter to infer the type of the global variable automatically. The '???' token is a convenient way to avoid specifying the type of a global variable explicitly.


Contributing
^^^^^^^^^^^^

Follow these instructions to set up the project on your local machine for development and testing purposes.

Prerequisites
^^^^^^^^^^^^^

Ensure you have the necessary prerequisites installed before getting started.

- Python 3.x
- Virtualenv (optional but recommended)
- Other required dependencies...

Running Tests
^^^^^^^^^^^^^

Execute tests to verify the correct functionality of the implemented feature.

.. code-block:: bash

Example command to run tests

python -m unittest discover tests/

Contributing

Follow these steps to contribute to the project:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`
3. Make your changes and commit them: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature-name`
5. Open a pull request with a clear title and description.

Code Style

Adhere to the coding style guide specified in PEP 8. Consistent code style is encouraged for readability.

License

This project is licensed under the `MIT License <LICENSE>`\_. Your contributions are appreciated.

Acknowledgments

Recognition to resources, libraries, and community support that contributed to the development of this feature.
