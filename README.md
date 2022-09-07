# ICD 9/10 Converter

If you are like me and have to work with medical data, more than likely you have run into the issue of legacy data being coded in ICD9 and needs to be in ICD10 for your current apps. 

The python file here contains a dictionary that converts each ICD9 code to ICD10. Please note that ICD10 tends to be more specific so there is the potential that an ICD9 code COULD map to multiple ICD10 codes, but in general this should work. 

Note - I did not create thesee mappings, simply converted them from a spreadsheet to a python dictionary so that it can easily be incorporated into a script through an import. The original mapping was taken from https://www.nber.org/research/data/icd-9-cm-and-icd-10-cm-and-icd-10-pcs-crosswalk-or-general-equivalence-mappings
