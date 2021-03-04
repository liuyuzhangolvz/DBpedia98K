# DBpedia98K

DBpedia98K consisting of 98,022 entities, 294 relations and 596,797 triples is a novel dataset we built by the following steps:  
(1) Randomly select some relational triples from DBpedia.   
(2) Collect the entity types through the $rdfs:domain$ and $rdfs:range$ domains of relations contained in the triples selected.   
(3) Split the selected triples into training set, valid set and test set.
