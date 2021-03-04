# DBpedia98K

DBpedia98K consists of 98,022 entities, 294 relations, 596,797 triples and 91 entity types. It was built by the following steps:  
</br>
(1) Randomly select some relational triples from DBpedia.   
</br>
(2) Collect the entity types through the *rdfs:domain* and *rdfs:range* domains of relations contained in the triples selected.  
</br>
(3) Split the selected triples into training set, valid set and test set.
</br>
## Citation

```
@misc{  
  TransET,  
  title={TransET: Knowledge Graph Embedding with Entity Types},  
  author={Jing Zhou, Yuzhang Liu, Peng Wang},  
  year={2020},  
  publisher={GitHub},
  howpublished={\url{https://github.com/liuyuzhangolvz/DBpedia98K}},
}  
```

