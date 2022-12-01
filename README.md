# APT-Files
Collection of APT Files for the Giant Planet Observations.

## Jupiter System 1373

We have brought together a large and diverse community in the US and Europe to observe the jovian system, with the following scientific goals:
* Characterize Jupiter’s cloud layers, winds, composition, auroral activity, and temperature structure;
* Produce maps of the atmosphere and surface of volcanically-active Io and icy satellite Ganymede to constrain their thermal and atmospheric structure, and search for plumes;
* Characterize the ring structure, and its sources, sinks and evolution.

Our program will thus demonstrate the capabilities of JWST’s instruments on one of the largest and brightest sources in the Solar System and on very faint targets next to it. We will also observe weak emission/absorption bands on strong continua, and with NIRIS/AMI we will maximize the Strehl ratio on unresolved features, such as Io’s volcanoes.

We will deliver a number of science enabling products that will facilitate community science, including, e.g.: i) characterizing Jupiter’s scattered light in the context of scientific observations, ii) resolve point sources with AMI in a crowded field (Io’s volcanoes), and compare this to classical observations,  iii) develop tools to mosaic/visualize spectral datacubes using MIRI and NIRSpec on Jupiter.
Finally, our program will also set a first temporal benchmark to study time variations in the jovian system and any interconnectivity (e.g., through its magnetic field) during JWST’s lifetime.


### Jupiter - MIRI
(2-4) Jupiter South Pole - MIRI MRS 4.9–28.5 micron

Timing/constraints: Avoid moons or their shadows blocking the target. Maintain fixed pointing at 75 deg south as the planet rotates, to build up longitude coverage (three separate MIRI exposures). Do sky background scan up to 5 hours before science observation. Sequence with NIRSpec to observe south polar region within a single Jupiter rotation. Central Meridian Longitude (CML) constraint: First MIRI observation starts with CML in (-80, -12), so that final NIRSpec observation will finish with CML in (+63, +129).


### Jupiter - NIRSpec
(5) Jupiter GRS - NIRSpec IFU High Res 1.7-5.3 micron (G395H, G235H)

Timing/constraints: Mosaic (2x3) is centered on planetographic target JUPITER-GRS, which tracks the estimated position of the Great Red Spot. Target must remain inside 6" of Jupiter's limb during the observation, so within 41-46 deg of the CML. We will work with schedulers at STScI to make sure observation will occur close in time to GTO observations of the GRS with MIRI. 

(25) Jupiter South Pole - NIRSpec IFU High Res 2.9-5.3 micron (G395H)
(26) Jupiter South Pole - NIRSpec IFU High Res 1.7-3.2 micron (G235H)

Timing/constraints: Observations sequence immediately after MIRI South Pole spectra, giving estimated CMLs (+22, +103) for the long wavelengths (including start time uncertainty) and (+63, +129) for the short wavelengths. Mosaic size is 2x3 for long wavelengths, 1x3 for short wavelengths. Mosaics will track a point (at +75 W) on the southern auroral oval as it rotates. Avoid moons or their shadows blocking the target. 


### Jupiter - NIRCAM
(6) Jupiter 1 - NIRCAM SUB640 (F164N / F360M)
(7) Jupiter 2 - NIRCAM SUB640 (F164N / F405N)
(8) Jupiter 1 - NIRCAM Full Module B (F212N / F335M)
(9) Jupiter 2 - NIRCAM Full Module B (F212N / F335M)

Timing/constraints: Jupiter 2 (SUB640 + FULL) follows Jupiter within three Jupiter rotations for to observe temporal evolution of storm systems. For Obs. 6, use a "PHASE" special timing requirement to ensure the GRS is on the face of the planet, but track planet center with JWST. Calculation of the PHASE constraint is described in Obs. 6 comments. Obs. 7-9 have no specific constraint to position the GRS, relying only on the SEQUENCE and AFTER constraints. SUB640 observations use a 4-point INTRAMODULEBOX dither to cover detector gap. FULL observations offset from Bs aperture to B3 aperture avoid detector edge gaps. B1, B2, or B4 apertures are just as good, so we could switch if observatory verification finds one of these apertures to be better for imaging. Restrict V3 to 241-250 deg to ensure mosaic axis is aligned with planet spin axis for the 2022A epoch (JWST-leading). Avoid moons or their shadows blocking the disk.


### Rings - NIRCAM (F212N / F150W2 / F250M / F322W2)
(10) Ring System Leading 1 - NIRCAM Full Module B
(11) Main Ring Ansa - NIRCAM SUB400P
(12) Ring System Leading 2 - NIRCAM Full Module B
(13) Ring System Trailing 1 - NIRCAM Full Module B
(14) Ring System Trailing 2 - NIRCAM Full Module B 

Timing/constraints: Ring System Portraits are in pairs, separated by 1-3 hrs or 5-7 hrs, to avoid orbital longitude aliasing by the moons Adrestea and Metis (whose periods are 8 hrs). Pairs also have 10 +/- 1 deg roll angle separations to enable scattered light background subtraction. Separation between epochs (Leading and Trailing JWST around the Sun) is ideal for detecting spiral density waves. Major moons are required to be outside the ring area. Solar System Target Windows are set to exclude the smaller moons from the SUB400P FOV area, using orbital longitude constraints. 


### Io - MIRI, NIRSpec
(15) Io Leading Hemisphere - MIRI MRS 4.9–28.5 micron
(16) Io in Eclipse - NIRSpec IFU High Res 0.97–1.89 micron (G140H/F100LP)
(24) Io in Eclipse - NIRSpec IFU High Res 1.66–5.3 micron (G235H/F170LP, G395H/F290LP)

Timing/constraints: For MIRI, use Central Meridian Longitude constraint to ensure leading hemisphere is observed, and ensure separation from planet is large. We use a 2-point dither to nod the target on-detector, rather than acquiring a separate background frame. Group these observations with other Io and Jupiter observations to save on major slew overheads. NIRSpec eclipse observations must happen while Io is in full umbral eclipse; this happens only 24 times per epoch, so we did not try to bundle the eclipse observation with other jovian system observations. Due to the limited duration of Io eclipse events, break the NIRSpec spectrum into separate short-wavelength and long-wavelength observations, to be conducted during separate eclipses.


### Io - NIRISS AMI
(17) Io near elongation from Jupiter - NIRISS NRM/F430M (AMI)

Timing/constraints: Use Central Meridian Longitude constraint to ensure leading hemisphere is observed by NIRISS, and ensure separation from planet is large. Do NIRISS PSF calibrator observation within 5 hours of science observation. Group these observations with other Io and Jupiter observations to save on major slew overheads. PSF calibrator star is chosen to be close to target in the 2022A timeframe; use alternate calibration star if timing changes again due to additional launch delay(s).


### Ganymede - MIRI, NIRSpec
(18) Ganymede Leading Hemisphere - MIRI MRS 4.9–28.5 micron
(19) Ganymede Leading Hemisphere - NIRSpec IFU High Res 2.9–5.3 micron (F395H/F290LP)
(20) Ganymede in Eclipse - NIRSpec IFU Low Res 0.6–5.3 micron (PRISM)

Timing/constraints: Use Central Meridian Longitude constraint to ensure leading hemisphere is observed by NIRSpec and MIRI and ensure separation from planet is large. Do MIRI background observation within 5 hours of science observation. Group non-eclipse observations with other Jupiter and rings observations to save on major slew overheads. NIRSpec eclipse observation must happen while Ganymede is in full umbral eclipse; this happens only 7 times per epoch.


### Calibrations
(1,22) MIRI Backgrounds

Test of MIRI sky background standard procedure, using parameters for bright objects. Backgrounds used for Jupiter and Ganymede observations. Same background target used (90 arcsec N of Jupiter). Jupiter observations use 4 group/int just like GTO program; so GTO and ERS can be done around the same time, one program may eliminate a background.

(23) NIRISS PSF

Not known until post-launch whether PSF stability requires these extra calibration PSF observations. But we are prepared. PSF star is far from Io so another 1800-sec slew overhead is charged.

## Jupiter 1246 - Great Red Spot

Jupiter’s extended disk and significant brightness present an extreme test for JWST capabilities. We will use MIRI/MRS spatio-spectral imaging to create a 3-point mosaic of the Great Red Spot (GRS) and its environs in the 6-11 μm range to determine the 3-dimensional temperature, composition, and aerosol distribution.  We will explore moist convective activity surrounding the GRS via the ammonia, phosphine, and condensed ices detectable in this spectral range. We will also search spectra for chemical products that may be unique to the GRS region as a by-product of the production of the poorly-understood red chromophores. We will use methane emission to study stratospheric effects of the underlying GRS and moist-convective plumes.

### Notes
Three-point mosaic of Jupiter's Great Red Spot and its environs in 5-11 µm (longer wavelengths will saturate).

Jupiter's angular size varies from 37-43" during FoR windows.

1.  MOSAIC OF ROTATING TARGET:  Given the difficulties of specifying a true MIRI mosaic of a rotating target, we have specified three seperate pointings (one for the GRS centre, one for the region to the east, and one for the west).  These should be executed consecutively, or as close together in time as possible.  Note that the GRS moves in longitude, so the precise longitudes of these three footprints can only be specified in the weeks prior to execution.  The longitudes currently provided should be considered as dummy variables.

2.  DITHER: A 4-point dither has been assumed to optimise imaging quality across Channels 1-2, but as we hope to optimise over the full field of view, only small dither steps are required (large 1" dither steps would not work, as this would render only a small area of the FOV optimised).  

3.  GROUPS:  As some regions of the spectrum (particularly those beyond 11 µm) are likely to saturate in the second group, we have set ngroups=4 and used sufficient iterations to build up our signal-to-noise.  For the brightest regions, this will allow us to subsample the exposure time to create sharper images (Jupiter's rotation will cause blur during the science exposures).

4.  BACKGROUND:  A single background frame (an offset to sky, 90" away from Jupiter) should be acquired to chararacterise any anomalous slopes or contributions.  This should be executed as near as possible to the science frames.

5.  SCHEDULING:  We require the Great Red Spot (and the other longitudes of interest) to be near the central meridian of the planet during the observation.  We attempted to use a Central Meridian target window constraint, but this prevented the visit planner from running correctly.

## Saturn System 1247

Reconnaissance of the Saturn system with NIRCam will test the capacity of JWST to detect faint moons around bright planets, via comparison to the faint targets already detected by Cassini, which will be useful for ERS and GO observers of other planetary systems.  Furthermore, the NIRCam images should be sensitive to discovering new moons significantly fainter than any that Cassini has discovered.  Any such newly discovered moons would be important dynamical tracers of the current operations and past history of Saturn's planetary system.  The NIRCam observations will also establish a baseline for continuing time-domain observations of the planet, rings, and satellites following the 2017 conclusion of the Cassini orbiter mission. 

Deep spectra of selected small moons of Saturn (Epimetheus, Pandora, Pallene, and Telesto) with NIRSpec IFU will test the capacity of JWST to take deep spectra of faint targets near bright planets, which will be useful for ERS and GO observers of other planetary systems.  The NIRSpec IFU spectra will enable cross-calibration with Cassini VIMS, and may improve on its signal-to-noise and spectral resolution (which would enable searches for finer spectral features). 

Spectra of Saturn's main rings with MIRI MRS will test the capacity of JWST to take spatially resolved thermal spectra of icy ring systems, will enable cross-calibration with Cassini VIMS and CIRS, will fill a wavelength gap between those two instruments, and may improve on Cassini's signal-to-noise and spectral resolution. 

A mosaic of Saturn’s north polar region using MIRI spectro-spatial imaging (5-16 µm) will explore the continued evolution of the polar temperatures, aerosols, and composition, including (i) the expected growth of a wide, hot summer vortex in the stratosphere; (ii) variability within the polar cyclones associated with ammonia, phosphine and aerosols; and (iii) identification of any unique polar chemicals/haze species inaccessible to Cassini in the 5.5-7.5 µm region.  These observations will establish a baseline for continuing time-domain observations of Saturn’s seasonal atmosphere following the 2017 conclusion of the Cassini orbiter mission at northern summer solstice.

### Notes:

1. MIRI Saturn Scan:  three overlapping footprints (based on the smallest MRS FOV) targetting the northern summer hemisphere.  Top priority is a direct view of the northern summer pole and hexagon; secondary priority is to step along the prime meridian towards the equator.  We originally intended for this to be a mosaic, but given that each MIRI disperser (SHORT/MEDIUM/LONG) would be seperated by too long for each tile, we had to specify each tile as a separate observation without interuption.  The TORUS technique is used to ensure that the observations are pointing at the central meridian.

2.  MIRI Saturation:  The SHORT detectors (Channel 1 and 2) only saturate with ngroups>4, so we have specified 4 groups.  For the LONG detectors (Channels 3 and 4), saturation can only be avoided with 2 groups.  

3.  MIRI dithering:  A 4-point dither pattern has been used based on advice from STScI, but this should be optimised for image sampling in Channels 1 and 2, where the observations are least likely to saturate.  

4.  MIRI background:  A single background exposure will be performed 90" to the north of Saturn, ensuring that no planetary satellites are present within the field of view.

5.  Observations 301 (System NIRCam 1) and 341 (System NIRCam 2) would be best if a few hours apart.  A natural way to do this is for the NIRSpec observations to be between them.

6.  We want Titan to be far out of the FOV for the NIRCam and MIRI observations, thus the Orbital Longitude constraints. 

7.  We want all the bright moons to be at least 7 arcsec (in the case of Titan, 15 arcsec) from the FOV for the NIRSpec observations, thus the Separation constraints.

## Uranus 1248

We will investigate the influence of Uranus' extreme seasonal tilt on the circulation and chemistry of this ice giant. Spatially-resolved global spectroscopic maps will reveal contrasts in atmospheric temperatures and chemical tracers (e.g., the myriad hydrocarbons produced via methane photochemistry), as well as a full chemical inventory of this ice giant. MIRI observations will be executed near-simultaneously with NIRSpec observations of uranian H3+, allowing us to understand the coupling between the upper, middle and lower atmospheric regimes for the first time.  Each instrument will sample thtee longitudes to generate a global map.

### Notes
Uranus global spatial-spectral map using NIRSpec and MIRI, sampling three longitudes with each instrument to span 360 degrees.
Uranus rotates in 17 hours, 14 minutes.  The time between adjacent sets (MIRI or NIRSPEC) should therefore be 5.7hours.

1.  SCHEDULING:  Each longitude has been defined seperately to allow the visits to be seperated if necessary, but it makes most sense to execute all observations during one 17-hour rotation of Uranus, reducing the need for major slews.  If time is unused between the targetted observations, we would welcome extended integration times for these low-signal observations.

2.  PRECISE LONGITUDES ARE FLEXIBLE:  As long as there is 120 degrees between each MIRI frame, and 120 degrees between each NIRSPEC frame, then we still sample all 360 degrees of longitude.  Indeed, science would be optimised if MIRI and NIRSPEC observations were executed consecutively for a particular longitude.  Instead of using longitude constraints, we therefore use a "time after" grouping to capture the three different longitudes.

3.  DITHERING:  MIRI assumes a 4-point dither pattern to optimise the imaging of this 3.7" diameter disc.  Large 1" dither offsets should be avoided, as the purpose is to improve spatial sampling for ALL of the MIRI channels.  NIRSPEC assumed a 4-point dither pattern for the same purpose.

4.  BACKGROUND:  Both MIRI and NIRSPEC observations assume a single offset to a background region of sky (20" is acceptable, provided no Uranian satellites are in the field of view).  This would be best scheduled immediately before or after one of the science exposures.

5.  SATURATION: Comparison to the MIRI sensitivity model and the ETC suggest Uranus Channels 1-4 will not saturate even with 100 groups, so this was split into multiple integrations of 10 groups to achieve ~5 minute exposure per observation.  If there is a way to further optimise this, please let us know.

## Neptune 1249

We propose to explore the middle atmospheric circulation of this archetypal ice giant world using spatially-resolved global maps of atmospheric temperatures and tracers of dynamics and chemistry (e.g., hydrocarbon species). With simultaneous multi-wavelength (5-29 μm) spectral imaging, we will: (i) reveal the unusual environmental conditions within Neptune’s summer south polar vortex; (ii) search for evidence of vertical coupling between tropospheric storm systems/wind fields and stratospheric dynamics; and (iii) search for evidence of tropical vertical oscillation patterns. JWST results for Neptune and Uranus will be intercompared to understand the similarities and differences between the two ice giants.

### Notes
Neptune global spatial-spectral map using MIRI and NIRSPEC, sampling two opposite hemispheres of the planet, 180 degrees apart.
Neptune rotates in 16 hours, 6 minutes.  The time between adjacent observations should therefore be ~8 hours.

1.  SCHEDULING:  Each longitude has been defined seperately to allow the visits to be seperated if necessary, but it makes most sense to execute all observations during one 16-hour rotation of Neptune, reducing the need for major slews.  

2.  PRECISE LONGITUDES ARE FLEXIBLE:  As long as there is 180 degrees between each MIRI frame, then we still sample all 360 degrees of longitude.  A "time after" constraint has been used to enforce this.

3.  DITHERING:  MIRI assumes a 4-point dither pattern to optimise the imaging of this 2.3" diameter disc.  Large 1" dither offsets should be avoided, as the purpose is to improve spatial sampling for ALL of the MIRI channels.  NIRSPEC also assumes a 4-point dither pattern.

4.  BACKGROUND:  MIRI and NIRSPEC observations assume a single offset to a background region of sky (20" is acceptable, provided no Neptunian satellites are in the field of view).  This would be best scheduled immediately before or after one of the science exposures.

5.  SATURATION:  The SHORT detector (channels 1 and 2) show no sign of saturating for 10 groups in the methane band at 7.66 µm (the brightest spectral point from 5-11 µm).  The LONG detector (channels 3 and 4) saturate in the 5th group near C2H2 emission at 13.7 µm, so we selected 5 groups (the minimum recommended).


