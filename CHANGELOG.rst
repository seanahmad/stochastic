Release Changelog
-----------------

0.5.0 (tbd)
~~~~~~~~~~~

* Fixed a bug with missing drift when sampling Brownian motion at specific times (thanks to `MichaelHogervorst <https://github.com/MichaelHogervorst>`_)
* Fixed implementation of fractional Brownian motion (thanks to `Antony Lee <https://github.com/anntzer>`_)

0.4.0 (2018-08-19)
~~~~~~~~~~~~~~~~~~

* Added a MixedPoissonProcess (thanks to `Gabinou <https://github.com/Gabinou>`_)

0.3.0 (2018-07-22)
~~~~~~~~~~~~~~~~~~

* Introduced breaking changes that move the t argument of all processes to the end of the __init__ signature
* Added support for inverse Gaussian process

0.2.0 (2018-07-11)
~~~~~~~~~~~~~~~~~~

* Added support for colored noise processes (generalized power law, violet, blue, white, pink, red/Brownian)
* Added support for multifractional brownian motion
* Added more citations and bibliographical source page to docs

0.1.0 (2018-01-04)
~~~~~~~~~~~~~~~~~~

* First release.
* Support for multiple continuous-time, discrete-time, diffusion, and noise
  processes.
