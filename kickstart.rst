#######################
How To Write & Infos
#######################

Es wird hier eine Sprache verwendet, die sich reStructuredText_ nennt
Die Software dahinter Sphinx_

Alternativ ist auch noch Markdown_ möglich und eingerichtet, sollten aber der Einfachheit halber bei reStructuredText_ bleiben

************************************************
Online Code Editoren für reStructuredText
************************************************

* `reStructuredText Viewer`_
* `Online reStructuredText editor`_

Manche Dinge gehen nicht, da hier die Referenzen zwischen den Dateien fehlen

************************************************
Hier ist noch ein schickes `cheat-sheat`_
************************************************

************************************************
Vieles habe ich auch von readthedocs_ kopiert
************************************************

Styleguide for readthedocs http://documentation-style-guide-sphinx.readthedocs.io/en/latest/style-guide.html

Verweise
============

Wenn du auf die Projekt Maßnahmennummer verweisen möchtest musst du hier eingeben:

.. code::

    :ref:`projektMasnahmennummer`.


und mit einer Leerzeile dazwischen über der Überschrift

.. code::

    .. _projektMasnahmennummer:

Sieht dann so aus: Hier in diesem Text wird auf die Maßnahmennummer verwiesen :ref:`projektMasnahmennummer`.

Die Referenzen müssen eindeutig sein, nehmen aber den Namen von der Überschrift darunter an, den "_" nicht vergessen

************************************************
wenn ihr etwas besonders hervorheben wollt
************************************************

.. code::

    .. note:: Eine schöne Bemerkung.

    .. hint:: Oder aber ein Hinweis?.

    .. warning:: Achtung, hier ist eine Warnung.

    .. tip:: Tipp gefällig?.

    .. seealso:: Siehe hier und da und dort.


in Action:

.. note:: Eine schöne Bemerkung.
.. hint:: Oder aber ein Hinweis?.
.. warning:: Achtung, hier ist eine Warnung.
.. tip:: Tipp gefällig?.
.. seealso:: Siehe hier und da und dort.



#. ``#`` with overline
#. ``*`` with overline
#. ``=``
#. ``-``
#. ``^``
#. ``"``

As an example:

.. code-block:: rst

  ##################
  H1: document title
  ##################

  Introduction text.


  *********
  Sample H2
  *********

  Sample content.


  **********
  Another H2
  **********

  Sample H3
  =========

  Sample H4
  ---------

  Sample H5
  ^^^^^^^^^

  Sample H6
  """""""""

  And some text.

Die Zeichen müssen mindestens so lange sein wie die Überschrift selbst


Die Dokumentation aus dem aktuellen Glossar habe ich unter Alt geschmissen; alles was kopiert wurde kann direkt gelöscht werden, das sollte dann über die Zeit verschwinden
