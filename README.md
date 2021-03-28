# Muddle-LIST-functions

This repository has some useful list processing functions for MUDDLE
.....................................................................
;" LCOPY makes a copy of a list, not just the pointer to
   the LIST, ( !.l ) does not make a copy of the LIST "
   
;" LCAT concatenate two LISTs together. LCAT modifies the first 
   LIST to contain the concatenation of the two LISTs, no
   copying "
   
;" LAPPEND append any object or thing to the end of a LIST 
   LAPPEND modifies the original list so that .OBJ 
   is Appended to its end, no copying "
