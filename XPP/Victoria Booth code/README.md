Synaptic Dynamics
==================
Missing synaptic currents (added)
-------------------------
The XPP [.ode file](../booth_bose.ode) for this model [obtained from ModelDB](https://senselab.med.yale.edu/ModelDB/ShowModel.cshtml?model=35358&file=\b04feb12\booth_bose.ode) does not include synaptic dynamics. Specifically, Idendrite, Isynapse, Inmda, and Iampa currents are not included. Description on ModelDB mentions that Victoria Booth may have additional details. We emailed her to see if we can get additional files.

New .ode file incorporating the previously missing currents [can be found here](../booth_bose_syn.ode).

Files from Victoria
-----------------
She replied with email below and we include the [files she attached](../Victoria Booth code).

Hi Sharon and Padraig,

I found a couple different xpp files.

I think the model on ModelDB by Bill Lytton is based on xpp files for a network of 2 coupled PR cells with interneurons that was in the attached paper BoothBose-Network2002.  This is the ode file booth_bose_pinrin.ode and the set files network*_pinrin.set

I also found xpp files for a single PR cell that we used for the attached chapter on somatic-dendritic  ping-pong bursting that is in the book Bursting: The Genesis of Rhythm in the Nervous System edited by Stephen Coombes and Paul Bresslof.  We made some simplifications to a time constant function in the PR model that are made in the  pinrin_simpletau*.ode files.

I haven't tried to run these files.  Let me know if you run into major problems with them.
Hope that helps!  Feel free to make them publically available.

Regards,

Victoria

References:

* BoothBose 2002: "Burst synchrony patterns in hippocampal pyramidal cell model networks." www.ncbi.nlm.nih.gov/pubmed/12061418
* BoseBooth 2005: "BURSTING IN 2-COMPARTMENT NEURONS: A CASE STUDY OF THE PINSKY-RINZEL MODEL" http://www.worldscientific.com/doi/abs/10.1142/9789812703231_0005
