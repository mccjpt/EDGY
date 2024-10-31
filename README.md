An implementation of EDGY as enterprise design langauge for MetaEdit+ (www.metacase.com/download). MetaEdit+ enables collaborative modeling, model checking, publishing and most importantly modification and integration of the EDGY with other languages and generators. 

- .mec file includes the metamodel and example models following EDGY
  - includes support for all facets
  - includes support for showing and hiding facets and metrics
  - includes support for showing and hiding link types as well as their user given names
  - provides reports to show model based on values given for tags and for metrics
  - HTML and Doc generation available from editor toolbar
  - Exporting EDGY model to ArchiMate using its exchange format (covers elements, relationships, tags and metrics and visualization)
- .mxs file includes library symbols

After importing these two files into MetaEdit+ you may apply EDGY. For importing, login to MetaEdit+ and then choose Repository | Import... and start modeling with EDGY. (For import details see https://www.metacase.com/support/55/manuals/meplus/Mp-5_3_2.html) 
The main objective for this implementation is being able to integrate EDGY with other modeling languages, and extend it as needed. Metamodel extensions can be done with MetaEdit+ too and models update accordingly as detailed in https://doi.org/10.1007/s10270-024-01218-5.
