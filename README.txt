***************************************************************************
*                                 Celestia                                *
*                                                                         *
*  A real-time space simulation that lets you experience our universe in  *
*  three dimensions.                                                      *
*                                                                         *
*  Copyright (c) 2001-2020, Celestia Development Team                     *
*                                                                         *
*-------------------------------------------------------------------------*
*  Celestia web site: https://celestia.space/                             *
*                                                                         *
*  Celestia documentation:                                                *
*    https://celestia.space/guides.html                                   *
*    Celestia WikiBook: https://en.wikibooks.org/wiki/Celestia            *
*                                                                         *
*  Celestia forums: https://celestia.space/forum/                         *
*                                                                         *
***************************************************************************

CONTENTS
--------
  License
  Installing in Unix and Linux
  Getting Started
  Mouse, Keyboard & Joystick Controls
  Star & Solar System Browser
  Selecting Objects by Name
  Known Issues
  User Modifiable Elements
  Celestia Resources
  Contributions
  Acknowledgements


LICENSE
-------
This program is free software; you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation; either version 2 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT
ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS
FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more
details, which you should have received along with this program (filename:
COPYING).  If not, request a copy from:
  Free Software Foundation, Inc.
  59 Temple Place - Suite 330
  Boston, MA  02111-1307
  USA


INSTALLING IN UNIX AND LINUX
----------------------------
Type "./configure --help" for a list of options.  The basic commands are shown
below.  For more detailed information, refer to the INSTALL file.

The GTK version is built with...
  ./configure --with-gtk
  make
  make install

The KDE3 version is built with...
  ./configure --with-kde
  make
  make install

  Note: some systems may require configure to be executed with
        --with-qt-includes=/usr/include/qt3

The Gnome version is built with...
  ./configure --with-gnome
  make
  make install

If all else fails, try the gui-less version with...
  ./configure --with-glut
  make
  make install


GETTING STARTED
---------------
Celestia will start up in a window, and if everything is working correctly,
you'll see Earth in front of a field of stars.  Displayed on-screen, is some
information about your target (Earth), your speed, and the current time
(Universal Time, so it'll probably be a few hours off from your computer's
clock).

Right drag the mouse to orbit Earth and you might see the Moon and some
familiar constellations.  Left dragging the mouse changes your orientation
also, but the camera rotates about its center instead of rotating around
Earth.  Rolling the mouse wheel will change your distance to Earth--you can
move light years away, then roll the wheel in the opposite direction to get
back to your starting location.  If your mouse lacks a wheel, you can use the
Home and End keys instead.

When running Celestia, you will usually have some object selected.  Currently,
it's Earth, but it could also be a star, moon, spacecraft, galaxy, or some
other object.  The simplest way to select an object is to click on it.  Try
clicking on a star to select it.  The information about Earth is replaced with
some details about the star.  Press G (or use the Navigation menu), and you'll
zoom through space toward the selected star.  If you press G again, you'll
approach the star even closer.

Press H to select our Sun, and then G to go back to our Sun.  Right click on
the sun to bring up a menu of planets and other objects in the solar system.
After selecting a planet from the menu, hit G again to travel toward it.  Once
there, hold down the right mouse button and drag to orbit the planet.

The Tour Guide is a list of some of the more interesting objects you can visit
in Celestia.  Select the Tour Guide option in the Navigation menu to display
the Tour Guide window.  Choose a destination from the list, click the Goto
button, and you're off.

That covers the very basics.  For a more in-depth look at Celestia and the
controls available to you, download the "Celestia User's Guide" (written by
Frank Gregorio), available in several languages, from:
  https://celestia.space/guides.html
This web page also includes links to the Celestia README file translated into
Japanese.


MOUSE, KEYBOARD & JOYSTICK CONTROLS
-----------------------------------
See the included file: controls.txt OR use the Help menu to display the Controls
list.


STAR & SOLAR SYSTEM BROWSER
-------------------------------------------
The Navigation menu contains 'Solar System Browser' and 'Star Browser'
options.

STAR BROWSER

By default, the Star Browser window displays a table of the 100 nearest stars,
along with their Distance, Apparent and Absolute Magnitude, and Type. Clicking
on the column headers will sort the stars.  The table is not continuously
updated, so if you travel to another star, you should press the Refresh button
to update the table for your current position.  The radio buttons beneath the
table let you switch between viewing a list of Nearest, Brightest, or 'With
planets' stars.  As with the solar system browser, clicking on any star name
in the table will select it.  Use this feature along with the Center and Go
To buttons to tour the stars visible from any night sky in the galaxy.

SOLAR SYSTEM BROWSER

The Solar System Browser displays a window with a tree view of all the objects
in the nearest solar system (if there is one within a light year of your current
position.)  Clicking on the name of any object in the window will select it.
You can then use the Center or Go To buttons to display that object in the main
Celestia window.


SELECTING OBJECTS BY NAME
-------------------------
Celestia provides several ways to select an object by name...
  1. Choose 'Select Object' from the Navigation menu, type in the object
     name, and click OK.

  2. Press Enter, type in the entire object name, and press Enter again.

  3. Press Enter, type in the first few characters of the object name,
     press the Tab key to move through the displayed listing until the
     object is highlighted, then press Enter again.

You can use common names, Bayer designations or catalog numbers for stars.
Celestia currently supports the HIP, HD and SAO catalogs. Catalog numbers must
be entered with a space between the prefix and the catalog number.


KNOWN ISSUES
------------
For up-to-the-minute answers to some common problems encountered when running
Celestia, please view either the FAQ in the Help menu or take a look at the
"Celestia User's FAQ" located on the Celestia User's Forum:
https://celestia.space/forum/


USER MODIFIABLE ELEMENTS
------------------------
You can modify how Celestia starts up each time you run it, by defining your
own start-up settings.  Simply open the file "start.cel" in a plain text
editor and follow the in-file instructions.  Also, view the celestia.cfg file
in a plain text editor to see additional settings.

Celestia allows you to easily add real, hypothetical, or fictional objects
by creating new catalog files. It is *not* recommended that you alter the
built-in data files; nearly all desired modifications and additions can be
made by placing new catalog files in Celestia's extras folders. There are three
types of catalog files:
 - ssc (solar system catalog: planets, moons, spacecraft, etc.)
 - stc (star catalog)
 - dsc (deep sky catalog: galaxies, star clusters, and nebulae)
All three types of catalog file are text files that can be updated with your
favorite text editing program.


CELESTIA RESOURCES
------------------
Celestia Web Site:
  https://celestia.space/

Celestia User Forums:
  https://celestia.space/forum/

Selden's List of Resources for Celestia:
  https://www.classe.cornell.edu/~seb/celestia/

Celestia WikiBook:
  https://en.wikibooks.org/wiki/Celestia

Celestial Matters Website and Forums:
  http://www.celestialmatters.org/
  http://forum.celestialmatters.org/

Celestia Motherlode:
  http://www.celestiamotherlode.net/

Celestia Source Code (GitHub.com):
  https://github.com/CelestiaProject/Celestia

Celestia Bug Tracking (GitHub.com):
  https://github.com/CelestiaProject/Celestia/issues

Celestia Feature Requests (GitHub.com):
  https://github.com/CelestiaProject/Celestia/issues

Celestia Discord Server:
  https://discordapp.com/invite/WEWDcJh

Celestia Subreddit:
  https://www.reddit.com/r/Celestiasoftware/

Celestia Archive Repository:
  https://github.com/Anthony-B-Russo10/Celestia-Archive


CONTRIBUTIONS
-------------

Authors
-------
  Chris Laurel        <claurel@gmail.com>
  Clint Weisbrod      <cweisbrod@cogeco.ca>
  Fridger Schrempp    <t00fri@mail.desy.de>
  Bob Ippolito        <bob@redivi.com>
  Christophe Teyssier <chris@teyssier.org>
  Hank Ramsey         <hramsey@users.sourceforge.net>
  Grant Hutchison     <grant.celestia@xemaps.com>
  Pat Suwalski        <pat@suwalski.net>
  Toti
  Da Woon Jung        <dirkpitt2050@users.sf.net>
  Vincent Giangiulio  <vince.gian@free.fr>
  Andrew Tribick
  Hleb Valoshka
  Li Linfeng

Contributors
------------
  Deon Ramsey ........... Original GTK1 interface
  Christopher Andre ..... Eclipse Finder
  Colin Walters ......... Endianness fixes
  Peter Chapman ......... Orbit path rendering changes
  James Holmes ..........
  Harald Schmidt ........ Lua scripting enhancements, bug fixes
  Nils Larsson .......... Various enhancements and bug fixes

Documentation
-------------
  Frank Gregorio ........ Celestia User's Guide
  Hitoshi Suzuki ........ Japanese README translation
  Christophe Teyssier ... DocBook and HTML conversion of User's Guide
  Diego Rodriguez ....... Acrobat conversion of User's Guide
  Don Goyette ........... CEL Scripting Guide
  Harald Schmidt ........ Celx/Lua Scripting Guide


Scientific Data Base
--------------------

# Grant Hutchison
    Supplied the correct orientations for the major planets, their moons, and a
    number of asteroids and also worked on these data files:
	Solarsys.ssc, nearstars.stc, extrasolar.ssc, extrasolar.stc, earth_locs.ssc

# Fridger Schrempp
    Complete NGC/IC galaxy database + local group galaxies (galaxies.dsc)
    
	Data base on globular clusters (globulars.dsc)
    
	Data base on visual and spectroscopic binaries (visualbins.stc, 
    
	spectbins.stc)
    
	World-capitals.ssc

    Asterisms.dat

# Andrew Tribick
    Significant update of the star.dat base based on new HIP Reduction of the
    Raw data, Floor van Leeuwen, 2007.
    
	CHARM2 stellar radii (charm2.stc)

Note on content from JPL
------------------------
Some content in Celestia, including texture maps and models, comes from JPL
websites. That content is subject to the JPL Image Use Policy, a copy of which
appears below (as captured on 2020-July-13). The latest version of this policy
can be found at https://www.jpl.nasa.gov/imagepolicy/. Also refer to
https://space.jpl.nasa.gov/faq.html for clarity on how textures/models are
covered.

# JPL Image Use Policy
# Unless otherwise noted, images and video on JPL public web sites (public
# sites ending with a jpl.nasa.gov address) may be used for any purpose
# without prior permission, subject to the special cases noted below.
# Publishers who wish to have authorization may print this page and
# retain it for their records; JPL does not issue image permissions on an
# image by image basis.
#
# By electing to download the material from this web site the user agrees:
# 1. that Caltech makes no representations or warranties with respect to
# ownership of copyrights in the images, and does not represent others who
# may claim to be authors or owners of copyright of any of the images, and
# makes no warranties as to the quality of the images. Caltech shall not be
# responsible for any loss or expenses resulting from the use of the images,
# and you release and hold Caltech harmless from all liability arising from
# such use.
#
# 2. to use a credit line in connection with images. Unless otherwise noted
# in the caption information for an image, the credit line should be
# "Courtesy NASA/JPL-Caltech."
#
# 3. that the endorsement of any product or service by Caltech, JPL or NASA
# must not be claimed or implied.
#
# Special Cases:
# * Prior written approval must be obtained to use the NASA insignia logo
# (the blue "meatball" insignia), the NASA logotype (the red "worm" logo)
# and the NASA seal. These images may not be used by persons who are not
# NASA employees or on products (including Web pages) that are not NASA
# sponsored. In addition, no image may be used to explicitly or implicitly
# suggest endorsement by NASA, JPL or Caltech of commercial goods or
# services. Requests to use NASA logos may be directed to Bert Ulrich, Public
# Services Division, NASA Headquarters, Code POS, Washington, DC 20546,
# telephone (202) 358-1713, fax (202) 358-4331, email bert.ulrich@hq.nasa.gov.
#
# * Prior written approval must be obtained to use the JPL logo (stylized JPL
# letters in red or other colors). Requests to use the JPL logo may be
# directed to the Institutional Communications Office, email
# instcomm@jpl.nasa.gov.
#
# * If an image includes an identifiable person, using the image for
# commercial purposes may infringe that person's right of privacy or publicity,
# and permission should be obtained from the person. NASA and JPL generally do
# not permit likenesses of current employees to appear on commercial products.
# For more information, consult the NASA and JPL points of contact listed above.
#
# * JPL/Caltech contractors and vendors who wish to use JPL images in
# advertising or public relation materials should direct requests to the
# Institutional Communications Office, email instcomm@jpl.nasa.gov.
#
# * Some image and video materials on JPL public web sites are owned by
# organizations other than JPL or NASA. These owners have agreed to make their
# images and video available for journalistic, educational and personal uses,
# but restrictions are placed on commercial uses. To obtain permission for
# commercial use, contact the copyright owner listed in each image caption.
# Ownership of images and video by parties other than JPL and NASA is noted in
# the caption material with each image.

Texture maps
------------

# Most of the planet maps are from David Seal's site:
    http://maps.jpl.nasa.gov/.
  A few of these maps were modified by me, with fictional terrain added to fill
  in gaps. The model of the Galileo spacecraft is also from David Seal's site
  (though it was converted from Inventor to 3DS format.)

# The Mars, Neptune, and Uranus textures and Mars bump maps are all from James 
  Hastings-Trew's collection. His maps may be found here: 
    http://gw.marketingden.com/planets/planets.html

# Grant Hutchison

   Saturn's rings were built by Grant Hutchison from Cassini imaging, with
   transparency information derived from stellar transit data obtained from:
     http://pds-rings.arc.nasa.gov/ringocc/ringocc.html

   The Eros map is a shaded relief generated from the NEAR laser rangefinder 
   shape model at:
     http://pdssbn.astro.umd.edu/NEARdb/nlr/#shape

# Jens Meyer

   Dione and Rhea are USGS maps colored and modified by Jens Meyer.

   The Moon map is based on data from PDS Map-A-Planet at
   http://pdsmaps.wr.usgs.gov/maps.html with colors from Mark Robinson at
   http://www.earth.northwestern.edu/research/robinson/MOON/clem_color.html.

# Fridger Schrempp

   'Available data' Pluto and Charon textures using maps created by Marc Buie
   at Lowell Observatory.  Buie's maps were generated from photometric data
   gathered during six years of mutual occultations of Pluto and Charon.

   Titan's cloud texture in natural colors and its surface map at near-infrared 
   wavelength. They are based on resources available from the imaging site 
   (Ciclops) of the Cassini mission  
   (http://ciclops.lpl.arizona.edu/index.php)

   The Phoebe base texture was created from the cylindrical map published by
   the Cassini imaging team
   (http://photojournal.jpl.nasa.gov/catalog/PIA07775)

   The Tethys textures are based on the Oct 2008 Ciclops map
   (http://photojournal.jpl.nasa.gov/catalog/PIA11116)

   The Iapetus texture was created from the Oct 2008 Ciclops map
   (http://photojournal.jpl.nasa.gov/catalog/PIA11116)

   The Lunar topography and bump maps, using Clementine laser altimeter data,
   merged in the polar regions with topographic data  from Clementine 750 nm 
   oblique and nadir images 
   (ftp://ftpflag.wr.usgs.gov/dist/pigpen/moon/usgs/topo/global/)

   The Mercury map was created from a combination of Mariner 10 imaging
   with recent MESSENGER WAC images from the first two flybys, as collected 
   and reprojected by Steve Albers: 
   See http://laps.noaa.gov/albers/sos/sos.html.
    
# Phil Stooke

   Proteus, Janus, Prometheus and Epimetheus maps are from Phil Stooke.

   The Ida and Gaspra photomosaic maps are by Phil Stooke.

# Venus's clouds and the textures for Ganymede, Callisto and Saturn are from
  Björn Jónsson. His site at http://www.mmedia.is/~bjj/ is an excellent
  resource for solar system rendering.

# Venus's surface is a copyright-free NASA image, prepared from Magellan radar
  data. The original is available at
    http://www.solarviews.com/cap/venus/venmap.htm

# The Earth texture was created by NASA using data from the MODIS instrument
  aboard the Terra satellite.  Further information is available from:
    http://earthobservatory.nasa.gov/Newsroom/BlueMarble/

# Steve Albers 
   The Io and Europa maps are by Steve Albers. His planetary maps are at:
   http://laps.noaa.gov/albers/sos/sos.html

# The textures for the Uranian satellites were created by Ivan Rivera from JPL
  data. His Celestia page is: http://bruckner.homelinux.net/celestia.html

# The Hyperion map is a photomosaic assembled by Phil Stooke and
  colored by Jens Meyer.

# Amalthea is a shaded relief map by Phil Stooke, colored by Wm. Robert Johnston
  (http://www.johnstonsarchive.net/spaceart/cylmaps.html), and further modified
  by Jens Meyer and Grant Hutchison.

# The asteroid.jpg texture was created by Paul Roberts.

# The textures for the five classes of extrasolar giant planet were created by
  Andrew Tribick.

# CICLOPS

  The map of Enceladus is derived from the December 2008 CICLOPS map:
  http://ciclops.org/view/5447/Map_of_Enceladus_December_2008


3D Models
---------

# Models of Mars Global Surveyor and Mars Odyssey were created by Shrox:
    http://www.shrox.com/
  They are included under the Creative Commons Attribution 4.0 International
  License (CC BY 4.0):
    https://creativecommons.org/licenses/by/4.0/

# The Cassini and Huygens models are by Jack Higgins:
    http://homepage.eircom.net/~jackcelestia/

# The 3D model of ISS is a deconstruction of Andrew Farnaby's
  complete ISS model with textures by Bob Hundley. The model
  represents the ISS as of June 2008 and is a modification of
  the model that can be found here:
    http://www.celestiamotherlode.net/catalog/show_addon_details.php?addon_id=1199
   ISS model of June 2008 (with Kibo) by krisci3 (modified and
   converted in order to work with JPG by Ulrich Dickmann, a.k.a.
   Adirondack)

# 3D asteroid models of Toutatis, Kleopatra, Geographos, 1998 KY26, Bacchus,
  Castalia and Golevka are courtesy of Scott Hudson, Washington State
  University.  His site is:
    http://www.eecs.wsu.edu/~hudson/Research/Asteroids/models.html
  On August 20, 2020, Scott Hudson waived the commercial use restrictions on
  these models, permitting unrestricted use of them.

# 3D models of Phobos, Deimos, Amalthea, Janus, Epimetheus, Prometheus, Pandora,
  Hyperion, Larissa, Proteus, Vesta, Ida, Gaspra and Halley are derived from
  Phil Stooke's Cartography of Non-Spherical Worlds at:
    http://publish.uwo.ca/~pjstooke/plancart.htm
  and optical shape model dataset at:
  http://pdssbn.astro.umd.edu/SBNast/holdings/EAR-A-5-DDR-STOOKE-SHAPE-MODELS-
  V1.0.html

# The 3D model of Eros was prepared from the NEAR laser rangefinder shape model
  at: http://pdssbn.astro.umd.edu/NEARdb/nlr/#shape

# The Phoebe mesh was designed by Jerry Gardner aka Jestr, jestr@ntlworld.com,
  based on Phoebe's bumpy topography display from Cassini,
  http://photojournal.jpl.nasa.gov/catalog/PIA06070


Libraries
---------

# This software is based in part on the work of the Independent JPEG Group.

# Some versions of Celestia may use the SPICE system for spacecraft and
  planetary information, developed by Caltech/JPL under contract to NASA.

# Many cylindrical projections of photographs were performed by Fridger
  Schrempp with Matthew Arcus 'mmps' software,
    http://www.users.globalnet.co.uk/~arcus/mmps/

# The lower resolution textures were all converted from their higher resolution
  versions using Gimp.

# The star database (stars.dat) was derived from the ESA's HIPPARCOS data set.

# Constellation boundaries are drawn from Davenhall & Leggett's "Catalogue of
  Constellation Boundary Data":
    http://cdsweb.u-strasbg.fr/viz-bin/ftp-index?/ftp/cats/VI/49


Other work
----------

# Selden Ball deserves a special mention for suffering more prerelease versions
 finding more bugs, and giving more feedback than anyone else.

# Christophe Campos aka ElChristou created the splash screen for Celestia.

# The MacOS X icon was designed by Chris Alford: http://www.chrisalford.com/

# The txf font format used by Celestia was devised by Mark Kilgard.


ACKNOWLEDGEMENTS
----------------

A very big thank you for creating Celestia goes to Chris Laurel who started this
program in the year 2001.
  <claurel@gmail.com>
  https://celestia.space/

Special thanks go to all Celestia users who submit bug reports, suggestions, and
fixes. Celestia wouldn't be the program it is today, without their help.




The Celestia Development Team
