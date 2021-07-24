# anapa-dunes-public
Contain Jupyter Notebook 'anapa_structure_lines_detection.ipynb' used for detection of structural lines (crest and toes) of dunes at Anapa bay-bar

Input file must contain cross-shore profiles, represented as set of points (look at sample file 'point_profile_5m_sample.gpkg'). You can easily create such set of points from transects using SAGA GIS module "Profile from lines" (http://www.saga-gis.org/saga_tool_doc/2.2.5/ta_profiles_4.html)

Attribute table must have same structure, as in sample file.

Also contain 'dZ calculation for seeward and landward dune slopes.ipynb', which is used to create map of dynamics of frontal dune cross-shore profile.
