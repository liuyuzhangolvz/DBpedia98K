# DBpedia98K

DBpedia98K consisting of 98,022 entities, 294 relations and 596,797 triples is built by the following steps:
</br>
(1) Randomly select some relational triples from DBpedia.   
</br>
(2) Collect the entity types through the *rdfs:domain* and *rdfs:range* domains of relations contained in the triples selected.  
</br>
(3) Split the selected triples into training set, valid set and test set.
