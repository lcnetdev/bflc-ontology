# Overview
Initiated by the Library of Congress, BIBFRAME provides a foundation for the 
future of bibliographic description, both on the web, and in the broader networked 
world that is grounded in Linked Data techniques. A major focus of the initiative 
is to determine a transition path for the MARC 21 formats while preserving a 
robust data exchange that has supported resource sharing and cataloging cost 
savings in recent decades.

## Bibframe Extension Vocabulary
This repository contains the Bibframe Extension Vocabulary [bflc.rdf](bflc.rdf) 

Properties and classes using this namespace are readily identifiable in the data as they begin with "bflc:".  It 
is where LC minted the Hub class while experimenting with it for more than a year before 
promoting it to the main ontology.  LC has minted other properties and classes that it tests with, 
but which LC has not yet determined merit elevation.  It is also where LC creates properties that are 
needed locally but which may never be promoted to the main ontology. Implementers are encouraged to
experiment in a local namespace first if possible.  For example, the University of Chicago might use 
"bfuc:" as a prefix/namespace.

## Change log
A change log can be found [here](dev/README.md)

