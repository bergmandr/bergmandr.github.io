---
title: "Telescope Array"
excerpt: "Telescope Array (TA) is the largest cosmic ray detector in the northern hemisphere."
collection: portfolio
---

Telescope Array (TA) is the largest cosmic ray detector in the northern hemisphere, located just to the west of Delta, UT. It detects cosmic-ray-induced extensive air shiowers for cosmic rays with energies above about 1 EeV (a sixth of Joule). The detector has two main components: an array of 500 surface detectors spaced every 1.2 km and covering 700 km2 of the desert floor, and three sets of air-fluorescence telescopes which view the atmosphere above the surface array. The two detectors work together to produce a very accurate reconstruction of the air-shower geometry and size.

My specialty has always been the reconstruction of extensive air showers using the fluorescence telescopes. The reconstruction of the shower geometry and paramteres can be done with just one set of telescopes (monocular reconstruction), two sets of telescopes (stereo reconstruction) or using fluorescence telescopes together with the surface array (hybrid reconstruction). Monocular reconstruction has significantly porrer geometrical resolution than the other techniques, but can often be used to reconstruct much lower energy showers, down to 0.2 EeV.

In all three types of reconstruction it is important to simulate the response of the fluorescence telescopes to a variety of showers. This allows us to determine the area over which the detector will work at any given energy, and thus calculate the size (aperture) of the detector as a function of cosmic ray energy. My group produced the code which simulates the fluorescence detector response and calcaultes the instantaneous apperture. It is called TRUMP (Ta Reconfigurable and Updateable Monte carlo Program; also a play on the fact that Donald Trump has a casino like the one at Monte Carlo). TRUMP produces fake data in the same format as the real data from the detectors, so we can use the same analysis to find the aperture and to reconstruct our acctual measurements.
