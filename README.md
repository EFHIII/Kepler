# Kepler

A Discord Bot for astronomical curiosity

Named After Johannes Kepler because Kepler took Tycho Brahe's observations after his death for his own research, which is what I thought of when considering that this bot takes others' observations and compiles them for my own selfish curiosity.

# TODO:

## picture of the day:

-   <https://api.nasa.gov/planetary/apod?api_key=DEMO_KEY&count=1>
-   <https://api.nasa.gov/planetary/apod?api_key=DEMO_KEY&date=2017-07-15>

## get coordinates and radius based an arbitrary name

-   based on arbitrary name, identify if it's a solar system object/galactic/extragalactic/unknown

### NED (Nasa extragalactic Database):

-   <https://ned.ipac.caltech.edu/byname>
-   <https://ned.ipac.caltech.edu/srs/ObjectLookup?name=><name>

### SIMBAD

-   <http://simbad.u-strasbg.fr/simbad/sim-help?Page=sim-url>

### Sesame

-   <http://vizier.u-strasbg.fr/vizier/doc/sesame.htx>

## is outside solar system, give photo cropped to radius from:

### Pan-STARRS:

-   <http://ps1images.stsci.edu/cgi-bin/ps1filenames.py?>
       ra = <degrees> &
      dec = <degrees>
-   <https://ps1images.stsci.edu/cgi-bin/fitscut.cgi?>
       ra = <degrees> &
      dec = <degrees> &
     blue = <image url> &
    green = <image url> &
      red = <image url> &
     size = <resolution>

### DSS:

-   <https://irsa.ipac.caltech.edu/data/DSS/>
-   <http://archive.stsci.edu/cgi-bin/dss_form>
-   <http://archive.stsci.edu/cgi-bin/dss_search?>
    r = <degrees> &
    d = <degrees> &
    h = <arc min> &
    w = <arc min> &
    f = GIF & v = 3

### SDSS:

-   <https://dr12.sdss.org/fields>

### Skyview? (many wavelengths in one place):

-   <https://skyview.gsfc.nasa.gov/current/cgi/titlepage.pl>
-   <https://skyview.gsfc.nasa.gov/current/docs/>

### Hubble?:

-   <https://hla.stsci.edu/hlaview.html>
-   <http://hla.stsci.edu/fitscutcgi_interface.html>

### viewer:

-   <http://archive.eso.org/scienceportal/home>

## Inside solar system:

### JPL Horizons:

-   <https://ssd.jpl.nasa.gov/?horizons_doc>
    file:///C:/Users/efhii/Downloads/Horizons_doc.pdf

### JPL mission design:

-   <https://ssd-api.jpl.nasa.gov/doc/mdesign.html>

### JPL API:

-   <https://ssd-api.jpl.nasa.gov/>
-   <https://ssd-api.jpl.nasa.gov/doc/index.php>

### JPL SPICE:

-   <https://naif.jpl.nasa.gov/naif/tutorials.html>
