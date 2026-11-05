# Ether’s Celestial Atlas

An interactive, self-contained star atlas with all 88 IAU constellations and 5,044 catalogued background stars.

## Open the app

[Open Ether’s Celestial Atlas in your browser](https://tonyparker1964.github.io/Ether-Celestial-Atlas/).

Download `index.html` and open it in a modern browser. The app embeds its star catalogue, line patterns, names, styling, and scripts; no installation or server is required.

## Explore

- Search all 88 constellations or filter by northern/southern label centers and the 12 Nirayana rashis.
- Select a constellation to center its pattern and illuminate its stars.
- Read star names and Bayer/Flamsteed or HIP designations for all 757 unique pattern points.
- Select a star in the detail panel to center and highlight it.
- Drag or use arrow keys to rotate; scroll or use +/− to zoom. Toggle lines, names, and the coordinate grid.
- Explore astronomical descriptions, Nirayana correspondences, and contemporary symbolic reflections.

## Interpretation and projection

Nirayana uses 12 equal 30-degree rashis, distinct from the unequal IAU constellation regions. Lahiri is an interpretive reference convention here; this app does not compute birth charts, planetary positions, or ayanamsa values. Ophiuchus is included as an astronomical constellation, not as a thirteenth rashi. Metaphysical readings are creative reflections, not scientific claims.

The sphere projects catalogue right ascension and declination onto a common radius. It does not represent physical stellar distances or an observer’s local horizon. Star labels may be suppressed to avoid overlap; every pattern point remains listed. Serpens includes both separated parts and counts as one constellation.

## Sources and attribution

Star catalogue, constellation patterns, and star-name data: [Olaf Frohn / d3-celestial](https://github.com/ofrohn/d3-celestial). The upstream BSD license is embedded in the app under **About this atlas & sources → License**. Mira’s identifier (HIP 10826, omicron Ceti) was cross-checked with [SIMBAD](https://simbad.cds.unistra.fr/simbad/sim-id?Ident=Mira).

Astronomical reference: [IAU constellations](https://www.iau.org/IAU/Astronomy-FAQs/Constellations.aspx). Nirayana reference: [India Meteorological Department](https://packolkata.imd.gov.in/panchang/en/explanation).

## Validation

Automated checks cover all 88 selections, line and star-name coverage, the Serpens merge, the 12-rashi filter, search, Ophiuchus treatment, sphere centering, and JavaScript syntax. Full visual browser testing has not been completed.
