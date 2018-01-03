# CUCM-LUA
Collection of LUA scripts for diverse usage,

1. SIP-FROM_Remove Calling name from FROM.txt
Removes Calling name from the FROM SIP Header.

2. SIP-PAI-PPI_Remove Calling Name.txt
Removes Calling name from the PAI/PPI SIP Header.

3. SIP-SDP_Normalize v1 - Conditional.txt
Deletes specific parts of an SDP to normalize it
for CUCM usage (i originally developed this for calls 
coming into CUCM form various SBCs)

4. SIP-SDP_Normalize v2 - unConditional.txt
Deletes the whole SDP and replaces it with 
G711Alaw and DTMF type = 101

5. SIP-SDP_Remove M Line - Video.txt
Removes video Capability advertisement from SDP
