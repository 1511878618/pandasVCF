pandasVCF
=========
VCF parser using the Python pandas library for interactive analysis


<h3>Update: February 12 2015</h3>
pandasVCFmulti now handles both multi-sample and single-sample VCF files. pdVCFsingle.py is now depracated and will be removed in the near future.  Command line support will be added in the near future. 

<h3>Update: Nov 10 2014</h3>
pdVCFsingle.py can now parse a dataframe with a single individual, either from a multi-sample VCF or a single-sample VCF.  Missing genotype calls maked with '.' are dropped when add_variant_annotations are called.  100,000 variants are parsed in ~10sec.  


