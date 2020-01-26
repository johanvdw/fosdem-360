# FOSDEM 360 viewer

This is the code for the viewer which currently sits at: https://gisky.be/viewer

It is based on https://derekeder.github.io/csv-to-html-table/ and https://pannellum.org/

## Usage

Open the viewer at:
https://gisky.be/viewer/

Click the name of the photo twice (or fix my crappy script) and you will see it.

Adjust the data file https://github.com/johanvdw/fosdem-360/edit/master/data/files.csv for changes. I will give you access if you like.

Please commit often. Better tell on IRC #fosdem-nav where you will start so we don't change twice the same thing.

For columns: don't change the photo. Room should be the slug in c3nav of the room. We should add slugs for hallways etc.
POI: is a link to the point in c3nav. I have not made proper pois, We can later do this in bulk. Finally add a comment when the room name is insufficient.
