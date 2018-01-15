***********
SNFcocktail
***********

Maskininl�rning, Bayesiansk statistik och lite fysik
===========================================================
:Author: Christian Forssen (christian.forssen@chalmers.se)

Detta repo inneh�ller den pythonkod som anv�ndes f�r en presentation
p� SNF cocktail party 2018-01-18. Publiken var studenter p� Chalmers
program i Teknisk fysik och Teknisk matematik.

Min f�rhoppning �r att materialet kan vara intressev�ckande och jag
vill uppmana de intresserade att sj�lva installera python och de
moduler som beh�vs f�r att sedan kunna testa de exempel som visades.

Nedan installationsinstruktioner med mera p� engelska.

Installation
------------

Download the repo from github::

    git clone https://github.com/cforssen/SNFcocktail.git

The scripts depend on several scientific modules (see
environment.yml) and require a python3.5 installation. 

Dependencies are best installed using ``conda`` by creating
a virtual environment:: 

    conda env create
    source activate SNF-env

To deactivate virtual environment::

    source deactivate


Code overview
-------------

``SNF_presentation.ipynb`` ......... Presentation as a jupyter ipython
notebook

``SNF_presentation_extra.ipynb`` ......... Some extra material,
figures, etc.

``environment.yml`` ... Package dependencies

``LICENCE.txt`` .............. MIT License

``README.rst`` .......... This.


Support
-------

For questions regarding this software, feel free to e-mail the main author.

