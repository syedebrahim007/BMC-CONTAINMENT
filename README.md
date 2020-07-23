The file contains latitude-longitude information associated with different markers.
You need to find out all of these latitude-longitude pairs, as well as the associated marker id
with these pairs. Create a dataframe out of this, which has three columns - latitude, longitude
and marker id.
For example, the text file will have strings like these:
var marker_9795626cfd584471ab4406d756a00baf = L.marker(
[19.041691972000024, 72.85052482000003],
{}
).addTo(feature_group_ad623471194f451d9f1cf7fc718747c5);
The marker id, here, would be - 9795626cfd584471ab4406d756a00baf
The latitude would be - 19.041691972000024
And the longitude would be - 72.85052482000003
