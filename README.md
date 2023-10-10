# bulk_RNA_nanostring
analysis scripts used in analysing RNA data from Nanostring nCounter 

Input data: 
Conditions matrix for DE analysis
Recist_response: 
complete response (CR), partial response (PR), stable disease (SD), and progressive disease (PD).

Clinical activity (end point): 
Y: activity 
N: no-activity

TTPR time to progression ratio
TTPR=TTP2/TTP1
TTP1: time takes previous treatment to control the cancer 
TTP2: time takes this drug tildrakizumab to control the cancer
TTPR lower bound is 1.3 to be significant improve

TTP2m: Time to process in month if the patient was on this drug more than 6 months. 
TTP2n: Time to process in month if the patient was on this drug more than 3 months. 

for TTP1=NA means the drug which the patient previously had did not reliable. 

Pet_response: SUV_max indicates the postive response within the signal not the size, 6 patients showed the positive response in SUVmax-> worth looking at the transcription profile

