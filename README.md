bostonlocaltv_data_stylesheets
==============================

these xsl docs are used to put data onto the siteExecutive summary:  this work was done amidst a maelstrom of "where's the data?" chaos.  
e.g.,
# WHDH data in database file named without that moniker but with "BPL" instead;
# WCVB data in two database files, neither named to mention "WCVB," both with identical views and banners beginning "NHF:" but only one named so; 
# CCTV data in a database file named "Programs"
# some databases hosted properly, others on shared drive (hello corruption!)

Ergo, it's easily possible to produce the wrong data or version of it without referring to an authority list of some kind.  

**BEWARE OF FILE/DATABASE LABELS WHEN WORKING WITH THESE STYLESHEETS!**




Specifics:
wgbh database was IMLS_LocalNews_WGBH.fp7 on FMP host

whdh database was IMLS_LocalNews_BPL.fp7 on FMP host

wcvb assignments database for assignments was "IMLS_LocalNews_NHF.fp7" on FMP host

wcvb inventory database was "IMLS_LocalNews_Inventory_final20130211.fp7" on DEPTFS

cctv database "Programs.fp7" on DEPTFS /Volumes/MLA/IMLS_News/CCTV



Each stylesheet is designed to convert these data to a common PBCore2 format, and 
contains comments to help with "where's the data?" in the future, when everything will be neither named nor located so-so predictably.

