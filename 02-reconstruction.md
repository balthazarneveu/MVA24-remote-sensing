# 3D reconstruction
### Linear pushbroom camera
*Example of values for Pléiades*
- A single line of pixels in the focal plane.
- Camera center moves at constant speed.
- Internal parameters:
  - Focal length $f$ (12.9m)
  - Position of principal point $y_0$ (15000 pixels)
  - Size of pixel sensor $w$ (13µm)
  - dwell time $\delta_{t}$ (0.07ms)


### Extrinsic parameters

- Orbit altitude (700km)
- Orbit inclination (98°)
- Capture duration $\Delta_{t}$ (3s)
- A satellite flies at 7 km/s.
- Roll $\phi$ , rotation aound the orbit
- Pitch $\psi$
- Yaw $\omega$ ~ around optical center
3rd order polynomials $\phi = P(t)$


### Image formation model
$L : R^{2} , R \rightarrow [-\pi, \pi] , [\frac{\pi}{2},\frac{\pi}{2}]$

$(x, h) \rightarrow \lambda \theta$

Complex projections :facepalm:

:green_circle: For end user: **RPC model** : Rational polynomial camera. *Rational polynomial functions with degree 3*



- Localization function $L$ : image to ground
- Projection $P$ ground to image.
160 coefficients.

Depth model (established around 2000 by a space shuttle.)



# 3D stereo reconstruction