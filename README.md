# nsVariantsVcfToMySql

Scripts (in python and possibly R) intended to:

1. annotate a vcf file with snpEff (Cinglioni et al 2008) 
2. filter out variants of interest (non-synonymous SNVs) with snpSift 
3. convert this to an sql file with Gemini and ..
3. edit the sql file to be compatible with MySQL format
4. transfer to a MySQL table
