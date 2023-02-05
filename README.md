# SignatureGB_SageMath

DESCRIPTION

A beta version of the SageMath package for computing signature Gröbner bases in the free algebra.

LICENCSE

Distributed under the terms of the GNU General Public License, either version 2 or (at your option) any later version (https://www.gnu.org/licenses/)

REQUIREMENTS

- SageMath 9.1 or later

- The Python library pyahocorasick (https://pyahocorasick.readthedocs.io/en/latest/)

INSTALLATION

Download the source code from this page.

Then install the Python library pyahocorasick as decribed in https://pyahocorasick.readthedocs.io/en/latest/.

After this, the SignatureGB package can be installed. As this package is written mostly in Cython,
it needs to be compiled before it can be used. This can be done by running the command

sage setup.py build_ext --inplace

in the folder SignatureGB.






