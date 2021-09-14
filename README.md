# LocationTextField Add-on for Vaadin 19+

LocationTextField is an UI component add-on for Vaadin that geocodes addresses using a configurable geocoder.
Any class implementing org.vaadin.addons.locationtextfield.LocationProvider can be used with LocationTextField.
There are currently two LocationProvider implementations provided; one using Google's geocoder and the other using
OpenStreetMap's Nominatim. Adding new implementations is trivial. Results for the geocoded address are available to
choose from in a drop-down menu.

## Download release

Official releases of this add-on are available at Vaadin Directory. For Maven instructions, download and reviews, go to http://vaadin.com/addon/locationtextfield

## License & Author

Add-on is distributed under Apache License 2.0. For license terms, see LICENSE.txt.

LocationTextField is written by Mark Thomas and updated to Vaadin 19+ by Magnus Ahlden
