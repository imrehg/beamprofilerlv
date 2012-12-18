# Beamprofiler

The aim is to implement the [original beamprofiler][origin], whis is using Linux and [pydc1394][pydc1394], in Windows and LabView (i.e. IMAQdx for our cameras, [Pointgrey Flea3 FireWire][flea3]).

The initial interface (to see how to actually use IMAQdx) is based on a [script][grabsnap] to continuously grab and manually snap pictures. It will be adapted to our own requirements, eg. by adding the actual analysis part.

[origin]: https://github.com/imrehg/labhardware/tree/master/projects/beamprofile "original beamprofiler on Github"
[pydc1394]: https://github.com/imrehg/pydc1394 "pydc1394 fork"
[flea3]: http://www.ptgrey.com/products/flea3/flea3_firewire_camera.asp "product site"
[grabsnap]: https://decibel.ni.com/content/docs/DOC-9112 "IMAQdx Continuous Grab & User Triggered Snap"
