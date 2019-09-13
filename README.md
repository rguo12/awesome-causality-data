# awesome-causality-data
An index of datasets that can be used for learning causality.

Please cite our survey if this data index helps your research.

@article{guo2018survey,</br>
  title={A Survey of Learning Causality with Data: Problems and Methods},</br>
  author={Guo, Ruocheng and Cheng, Lu and Li, Jundong and Hahn, P. Richard and Liu, Huan}, </br>
  journal={arXiv preprint arXiv:1809.09337}, </br>
  year={2018}</br>
}

*Updates coming soon* 

## Datasets for Learning Causal Effects (Causal Inference)
### With Back-door Criterion

#### Standard Datasets for Causal Inference
Standard datasets for learning causal effects comes with each instance in the format of (**x**,d,y).

[IHDP1](https://github.com/AMLab-Amsterdam/CEVAE/tree/master/datasets/IHDP)

[How is IHDP1 (setting A) simulated](https://github.com/vdorie/npci/tree/master/examples/ihdp_sim)

[IHDP2](https://math.la.asu.edu/~prhahn/)

[Twins](https://github.com/AMLab-Amsterdam/CEVAE/tree/master/datasets/TWINS)

[Job Training](http://users.nber.org/~rdehejia/data/nswdata2.html) (Lalonde 1986)

[ACIC Benchmark](https://github.com/vdorie/aciccomp/tree/master/2016)

#### Non-i.i.d. Datasets for Causal Inference

[Amazon](https://drive.google.com/drive/u/1/folders/1Ff_GdfjhrDFbZiRW0z81lGJW-cUrYmo1)

### Without Back-door Criterion
#### Datasets with instrumental Variables (IV)
Standard datasets for learning causal effects, each instance has the format of (i,**x**,d,y).

[1980 Census Extract](https://economics.mit.edu/faculty/angrist/data1/data/angkru95)

[CPS Extract](https://economics.mit.edu/faculty/angrist/data1/data/angkru95)

#### Datasets for Regression Discontinuity Design

[Population Threshold RDD Datasets](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/PGXO5O)

## Datasets for Learning Causal Relationships (Causal Discovery)

#### Distinguishing Cause from Effect
[Database with cause-effect pairs (Tbingen  Cause-Effect  Pairs)](http://webdav.tuebingen.mpg.de/cause-effect/)

[AntiCD3/CD28](https://science.sciencemag.org/content/308/5721/523)

[Pittsburgh Bridges](http://archive.ics.uci.edu/ml)

[Abalone](http://archive.ics.uci.edu/ml)

[Lung Cancer Simple Set (LUCAS)](http://www.causality.inf.ethz.ch/data/LUCAS.html)

## Datasets for Connections to Machine Learning
### Datasets with randomized test set for recommendation systems
|Name|Paper|URL|
|---|---|---|
|Coat|Schnabel, Tobias, Adith Swaminathan, Ashudeep Singh, Navin Chandak, and Thorsten Joachims. "Recommendations as treatments: Debiasing learning and evaluation." arXiv preprint arXiv:1602.05352 (2016).|[download](http://www.cs.cornell.edu/~schnabts/mnar/index.html)|
|Yahoo! R3|   |[download](https://webscope.sandbox.yahoo.com/catalog.php?datatype=r)|
