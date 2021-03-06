# Dependency Brown clustering
## Data and experimental details for:

Simon Šuster and Gertjan van Noord (2014) [From neighborhood to parenthood: the advantages of dependency representation over bigrams in Brown clustering.][] COLING.

  [From neighborhood to parenthood: the advantages of dependency representation over bigrams in Brown clustering.]: http://www.let.rug.nl/suster/publications/DepBrown.pdf

The following clusters were induced with [dep-brown-cluster](http://github.com/rug-compling/dep-brown-cluster). If you use dependency Brown clusters (DepBrown), please cite the above paper.




### Standard and dependency Brown clusters for Dutch

- 1000 clusters, frequency cutoff 3: [DepBrown](dep/paths_dlm_1000_min3), [Brown](standard/paths_root_1000_min3)
- 1000 clusters, frequency cutoff 5: [DepBrown](dep/paths_dlm_1000_min5), [Brown](standard/paths_root_1000_min5)
- 1000 clusters, frequency cutoff 10: [DepBrown](dep/paths_dlm_1000_min10), [Brown](standard/paths_root_1000_min10)
- 1000 clusters, frequency cutoff 20: [DepBrown](dep/paths_dlm_1000_min20), [Brown](standard/paths_root_1000_min20)
- 1000 clusters, frequency cutoff 30: [DepBrown](dep/paths_dlm_1000_min30), [Brown](standard/paths_root_1000_min30), [DepBrownHTML][]
- 1000 clusters, frequency cutoff 50: [DepBrown](dep/paths_dlm_1000_min50), [Brown](standard/paths_root_1000_min50)
- 3200 clusters, frequency cutoff 50: [DepBrown](dep/paths_dlm_3200_min50), [Brown](standard/paths_3200_min50)
- 200 clusters, frequency cutoff 10: [DepBrown](dep/paths_dlm_200_min10), [Brown](standard/paths_200_min10)
- 400 clusters, frequency cutoff 10: [DepBrown](dep/paths_dlm_400_min10), [Brown](standard/paths_400_min10)
- 600 clusters, frequency cutoff 10: [DepBrown](dep/paths_dlm_600_min10), [Brown](standard/paths_600_min10)
- 800 clusters, frequency cutoff 10: [DepBrown](dep/paths_dlm_800_min10), [Brown](standard/paths_800_min10)

[DepBrownHTML]: http://www.let.rug.nl/suster/clusters/dependency/1000/view_dep_1000_30.html

### Standard and dependency Brown clusters for English (not in the paper)

- 1000 clusters, frequency cutoff 1: [DepBrown](en/dep/paths_1000_min1), [Brown](en/standard/paths_1000_min1)
- 1000 clusters, frequency cutoff 3: [DepBrown](en/dep/paths_1000_min3), [Brown](en/standard/paths_1000_min3)
- 1000 clusters, frequency cutoff 50: [DepBrown](en/dep/paths_1000_min50), [Brown](en/standard/paths_1000_min50), [EnDepBrownHTML][]
- 3200 clusters, frequency cutoff 3: [DepBrown](en/dep/paths_3200_min3), [Brown](en/standard/paths_3200_min3)
- 3200 clusters, frequency cutoff 50: [DepBrown](en/dep/paths_3200_min50), [Brown](en/standard/paths_3200_min50)

[EnDepBrownHTML]: http://www.let.rug.nl/suster/clusters/english/standard/1000/view_base_1000_50.html

### Standard and dependency Brown clusters for Dutch: varying amount of data

1000 clusters, frequency cutoff 3.

- 10k sentences: [DepBrown](learning_curve_dep/paths_10k_1000_min3), [Brown](learning_curve/paths_10k_1000_min3)
- 50k sentences: [DepBrown](learning_curve_dep/paths_50k_1000_min3), [Brown](learning_curve/paths_50k_1000_min3)
- 100k sentences: [DepBrown](learning_curve_dep/paths_100k_1000_min3), [Brown](learning_curve/paths_100k_1000_min3)
- 200k sentences: [DepBrown](learning_curve_dep/paths_200k_1000_min3), [Brown](learning_curve/paths_200k_1000_min3)
- 400k sentences: [DepBrown](learning_curve_dep/paths_400k_1000_min3), [Brown](learning_curve/paths_400k_1000_min3)
- 600k sentences: [DepBrown](learning_curve_dep/paths_600k_1000_min3), [Brown](learning_curve/paths_600k_1000_min3)
- 800k sentences: [DepBrown](learning_curve_dep/paths_800k_1000_min3), [Brown](learning_curve/paths_800k_1000_min3)
- 1000k sentences: [DepBrown](learning_curve_dep/paths_1000k_1000_min3), [Brown](learning_curve/paths_1000k_1000_min3)
- 1200k sentences: [DepBrown](learning_curve_dep/paths_1200k_1000_min3), [Brown](learning_curve/paths_1200k_1000_min3)
- 1400k sentences: [DepBrown](learning_curve_dep/paths_1400k_1000_min3), [Brown](learning_curve/paths_1400k_1000_min3)
- 1600k sentences: [DepBrown](learning_curve_dep/paths_1600k_1000_min3), [Brown](learning_curve/paths_1600k_1000_min3)
- 1800k sentences: [DepBrown](learning_curve_dep/paths_1800k_1000_min3), [Brown](learning_curve/paths_1800k_1000_min3)
- 2000k sentences: [DepBrown](learning_curve_dep/paths_2000k_1000_min3), [Brown](learning_curve/paths_2000k_1000_min3)
- 2200k sentences: [DepBrown](learning_curve_dep/paths_2200k_1000_min3), [Brown](learning_curve/paths_2200k_1000_min3)
- 2400k sentences: [DepBrown](learning_curve_dep/paths_2400k_1000_min3), [Brown](learning_curve/paths_2400k_1000_min3)
- 2600k sentences: [DepBrown](learning_curve_dep/paths_2600k_1000_min3), [Brown](learning_curve/paths_2600k_1000_min3)


### Relation-specific dependency Brown clusters for Dutch

1000 clusters, frequency cutoff 3.

1st order:

- [LD](dep/paths_dep35_hd-ld_1000_3)
- [OBJ1](dep/paths_dep35_hd-obj1_1000_3)
- [SU](dep/paths_dep35_hd-su_1000_3)
- [SU+OBJ1](dep/paths_dep35-hd-obj1.dep35-hd-su_1000_3)

2nd order:

- [OBJ2](dep/paths_hdpp_hd-obj2_1000_3)
- [PC](dep/paths_hdpp_hd-pc_1000_3)
- [LD](dep/paths_hdpp_hd-ld_1000_3)


### Input data

Clusters were induced on the data sample from the SoNaR corpus: [sentence ids](ids/SONAR_random4000000.ids.full.zip).

### Data preparation

To obtain the root forms of words, use the Alpino lexical analyzer with the following setting:

```
cat text | Alpino -notk batch_command=lex_all
```

`text` is sentences extracted from the SoNaR corpus based on the given sentence ids.

Dependency tuples are generated by Alpino in this way:

```
cat sentence_ids | xargs Alpino -treebank_dep_features 
```

Obtaining/removing second-order dependency tuples:

Simply query the tuples for lines beginning with `hdpp`, which stands for a 2nd-order relation (`dep35` denotes a 1st-order relation).

### Dependency-relation selection results

See the [full list](dep/results_full_perrel) of results per dependency relation.

### Questions?

Further experimental details and evaluation scripts available from the authors upon request.
