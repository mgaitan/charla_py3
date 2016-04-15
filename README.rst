========================
Python 3 para escépticos
========================



:autor: Martín Gaitán

.. image:: http://mgaitan.github.com/curso-django/slides/static/img/cc_by_sa-3.png
   :align: center


`Ver presentación <https://nbviewer.jupyter.org/format/slides/github/mgaitan/charla_py3/blob/master/py3.ipynb#/>`_

Introducción
============

Tu próximo proyecto debe ser con Python 3. La razón, simple y potente, es un manojo importante de
funcionalidades y mejoras que te estarías perdiendo si seguís usando Python 2. Echemos un
vistazo rápido a esas perlitas que el mito de que “todavía no vale la pena el esfuerzo” te hizo ignorar.

Sobre el autor
==============

Martín Gaitán es Ing. Comp. por la UNC. Pythonista desde hace una década, es especialista
en el framework web Django, en el stack de herramientas científicas basadas en Python y,
desde algunos meses, en cambiar pañales con una mano.
Actualmente trabaja en Onapsis, donde se codea con el borde de su escritorio y con muy buenos programadores. Suele ser orador en eventos
sobre software libre y arador en su perpetuo intento de huerta. Hincha
de Boca y fundamentalista del locro (ambas pasiones, incluso en verano).

Presentaciones
==============

:evento: Python Meetup Córdoba
:lugar: The Tech Pub, Córdoba, Argentina
:fecha: 18 de Marzo de 2016

----

:evento: PyDay Loja
:lugar: Loja, Ecuador  (via teleconferencia)
:fecha: 1 de Abril de 2016


Instalación para presentación **en vivo**
==========================================

La presentación se basa en un `jupyter notebook <http://jupyter-notebook-beginner-guide.readthedocs.org/en/latest/what_is_jupyter.html>`_,
(ejecutado con **kernel Python 3.5**) con la correspondiente metainformación en cada "celda" para visualizarse como diapositivas.

Si este documento se ejecuta en Jupyter con el plugin `RISE <https://github.com/damianavila/RISE>`_, las diapositivas se pueden
ver "en vivo", permitiendo modificar los ejemplos en tiempo real.

::

  mkvirtualenv -p /usr/bin/python3.5 charla_py3
  git clone https://github.com/mgaitan/charla_py3.git .
  pip install -r requirements.txt
  wget https://github.com/damianavila/RISE/archive/master.zip; unzip master.zip; python RISE-master/setup.py
  jupyter notebook py3.ipynb


Agradecimiento
==============

`Onapsis <http://onapsis.com>`_ me permitió dedicar algunas horas laborales para la preparacmión
de esta charla.


