Entry 3 (Third Place)
=====================

.. figure:: entry3.png

Authors
-------
 - Jake Vanderplas
 - Zeljko Ivezic
 - Andrew Connolly

This figure is based on data presented in figures 3-4 of Parker &
Ivezic et al (2008). A similar figure appears in the book "Statistics,
Data Mining, and Machine Learning in Astronomy", by Ivezic, Connolly,
Vanderplas, and Gray (2013).

Running this code requires astroML, a lightweight python package which
can be quickly installed using `pip install astroML`.  See
`<http://astroML.github.com>`_ for more information.  AstroML will
automatically download and cache the required dataset to
`$HOME/astroML_data`.

Figure Caption
--------------

These panels visualize a 4-dimensional correlation between orbits and
surface color for about 35,000 main-belt asteroids (found between Mars
and Jupiter) observed by the Sloan Digital Sky Survey. The left panel
quantifies the variation of the asteroid surface chemistry using two
measured colors: a* is an optical color (as would be seen by
e.g. human eyes) and i-z is a near-infrared color (as would be seen by
e.g. snake eyes). The dots corresponding to individual objects are
color-coded according to the object's position in this diagram. Blue
shades are representative of carbonaceous surfaces, and orange and
green shades correspond to silicate surfaces. The right panel is
constructed with two orbital parameters: semi-major axis a (AU stands
for astronomical unit, equal to Sun-Earth distance) and sine of the
orbital inclination i. The vertical dashed lines mark the so-called
Kirkwood gaps, where no objects are found because of resonant
gravitational scattering due to Jupiter.  These gaps define the three
main-belt zones. The easily discernible clusters of points correspond
to the so-called orbital families of asteroids, believed to be smaller
remnants of larger objects destroyed in collisions. The dots
corresponding to individual objects are color-coded according to the
two-dimensional color palette from the left panel and the measured
surface colors. The vividly demonstrated fact that orbitally related
asteroids also have similar colors (and therefore similar surface
chemistry) is evidence that asteroids in these families share a common
origin.

Products
--------

- :download:`PDF <asteroids.pdf>`

Source
------

.. literalinclude:: entry3.py
    :language: python

- :download:`Python source <entry3.py>`
