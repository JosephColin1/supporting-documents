This repository contains a library of reaction networks for alkene transformations on acidic zeolites. The construction, automated generation, and characteristics of the reaction networks is extensively described in the paper: “Catalytic conversion of alkenes on acidic zeolites: Automated generation of reaction mechanisms and lumping technique” (authors: Elsa Koninckx, Joseph G. Colin, Linda J. Broadbelt and Sergio Vernuccio).

The networks of the library are catalogued in three broad groups:

(i)                 Oligomerization

(ii)                Alkylation

(iii)               Cyclization and Aromatization

Each network has been indicated by using the expression Ci  Rj where Ci represents the carbon termination criterion (the maximum carbon number of the species allowed to react), and Rj represents the rank termination criterion (the maximum rank of the species allowed to react).

Each folder contains the following files:

  - Components.0_R0: A list of all molecular species and protonated intermediates included in the network
  - Reactions.txt:  A list of all reactions occurring in the network including reactants, products, reaction enthalpy, and reaction family

Most folders contains the following files (exceptions are found for considerably large networks in which visual network generation was deemed unneccesary and the Components.0_R0 and Reactions.txt files suffice):

  - Network.cys: A visual reaction network that can be opened via the software Cytoscape (https://cytoscape.org/).

All documents should be downloaded for use. 
