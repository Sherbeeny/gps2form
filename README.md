# gps2form
Detect user's location coordinates (longitude and latitude) and redirect to a pre-filled Google or Tally form containing these coordinates.

To use, simply change "TYPE",  "ABC", and "XYZ" in the following URL
https://sherbeeny.github.io/gps2form?formType=TYPE&formId=ABC&gpsEntry=XYZ&note=ENCODEDNOTE

Where
1. TYPE is either 'google' or 'tally'.
2. ABC is the form ID.
3. XYZ is the where you want the GPS coordinates to be entered in your form.
4. ENCODEDNOTE is URI encoded text if you want to change the text above the buttons.

Google Demo
https://sherbeeny.github.io/gps2form?formType=google&formId=1FAIpQLSe2weLPy-5P5QxoQP0o02hem1wavqLkZqzsTPYOqdueXIibFQ&gpsEntry=272787931&note=You%20are%20going%20to%20a%20Google%20Form%20that%20requests%20your%20current%20location.


Tally Demo
https://sherbeeny.github.io/gps2form?formType=tally&formId=nPp48P&gpsEntry=gmaplink&note=You%20are%20going%20to%20a%20Tally%20Form%20that%20requests%20your%20current%20location.
