# FineRTS
Select regression tests more precisely by reasoning about semantics-modifying changes.
Based on [Ekstazi](https://github.com/gliga/ekstazi), we implemented [FineEkstazi](https://github.com/EngineeringSoftware/fine-ekstazi)
Based on [STARTS](https://github.com/TestingResearchIllinois/starts), we implemented [FineSTARTS](https://github.com/EngineeringSoftware/fine-starts)


## Content of this repository

### insights-of-class-level
Contains the manual inspection results for the 5 projects. The file,
"insightclass.json" puts them together in one place.

### change-levels
Contains the automatically generated classification of change levels
in the 23 evaluation projects.

### cmp-tools
Contains the execution results (including intermediate data) of
Ekstazi, FineEkstazi<sup>F</sup>, FineEkstazi, STARTS,
FineSTARTS<sup>F</sup>, FineSTARTS, and HyRTS.

### shas-with-java-files-change
Contains the SHAs used in evaluation on 23 projects.

### predictiverts-results
Contains the ML models prediction results.

### appendix.pdf
Contains the appendix of the paper.

## Citation
If you have used FineRTS in a research project, please cite the research paper in any related publication:

Title: [More Precise Regression Test Selection
via Reasoning about Semantics-Modifying Changes](https://dl.acm.org/doi/abs/10.1145/3597926.3598086)

Authors: [Yu Liu](https://sweetstreet.github.io/), [Jiyang Zhang](https://jiyangzhang.github.io/), [Pengyu Nie](https://pengyunie.github.io/), [Milos Gligoric](http://users.ece.utexas.edu/~gligoric/), [Owolabi Legunsen](https://mir.cs.illinois.edu/legunsen/)

```bibtex
@inproceedings{liu2023more,
  title={More precise regression test selection via reasoning about semantics-modifying changes},
  author={Liu, Yu and Zhang, Jiyang and Nie, Pengyu and Gligoric, Milos and Legunsen, Owolabi},
  booktitle={Proceedings of the 32nd ACM SIGSOFT International Symposium on Software Testing and Analysis},
  pages={664--676},
  year={2023}
}
```