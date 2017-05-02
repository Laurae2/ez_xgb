<img src=https://raw.githubusercontent.com/dmlc/dmlc.github.io/master/img/logo-m/xgboost.png width=135/>  eXtreme Gradient Boosting (easy R installation maintained separately by Laurae)
===========

This is a version of xgboost **maintained by Laurae** for easy installation for R users. No recursive stuff!

**Install in R easily in ONE command**:

```r
devtools::install_github("Laurae2/ez_xgb/R-package@2017-05-02-v2")
```

---

[Documentation](https://xgboost.readthedocs.org) |
[Resources](demo/README.md) |
[Installation](https://xgboost.readthedocs.org/en/latest/build.html) |
[Release Notes](NEWS.md) |
[RoadMap](https://github.com/dmlc/xgboost/issues/873)

XGBoost is an optimized distributed gradient boosting library designed to be highly ***efficient***, ***flexible*** and ***portable***.
It implements machine learning algorithms under the [Gradient Boosting](https://en.wikipedia.org/wiki/Gradient_boosting) framework.
XGBoost provides a parallel tree boosting (also known as GBDT, GBM) that solve many data science problems in a fast and accurate way.
The same code runs on major distributed environment (Hadoop, SGE, MPI) and can solve problems beyond billions of examples.

What's New
----------
* [XGBoost GPU support with fast histogram algorithm](https://github.com/dmlc/xgboost/tree/master/plugin/updater_gpu)
* [XGBoost4J: Portable Distributed XGboost in Spark, Flink and Dataflow](http://dmlc.ml/2016/03/14/xgboost4j-portable-distributed-xgboost-in-spark-flink-and-dataflow.html), see [JVM-Package](https://github.com/dmlc/xgboost/tree/master/jvm-packages)
* [Story and Lessons Behind the Evolution of XGBoost](http://homes.cs.washington.edu/~tqchen/2016/03/10/story-and-lessons-behind-the-evolution-of-xgboost.html)
* [Tutorial: Distributed XGBoost on AWS with YARN](https://xgboost.readthedocs.io/en/latest/tutorials/aws_yarn.html)
* [XGBoost brick](NEWS.md) Release

Ask a Question
--------------
* For reporting bugs please use the [xgboost/issues](https://github.com/dmlc/xgboost/issues) page.
* For generic questions or to share your experience using XGBoost please use the [XGBoost User Group](https://groups.google.com/forum/#!forum/xgboost-user/)

Help to Make XGBoost Better
---------------------------
XGBoost has been developed and used by a group of active community members. Your help is very valuable to make the package better for everyone.
- Check out [call for contributions](https://github.com/dmlc/xgboost/issues?q=is%3Aissue+label%3Acall-for-contribution+is%3Aopen) and [Roadmap](https://github.com/dmlc/xgboost/issues/873) to see what can be improved, or open an issue if you want something.
- Contribute to the [documents and examples](https://github.com/dmlc/xgboost/blob/master/doc/) to share your experience with other users.
- Add your stories and experience to [Awesome XGBoost](demo/README.md).
- Please add your name to [CONTRIBUTORS.md](CONTRIBUTORS.md) and after your patch has been merged.
  - Please also update [NEWS.md](NEWS.md) on changes and improvements in API and docs.

License
-------
© Contributors, 2016. Licensed under an [Apache-2](https://github.com/dmlc/xgboost/blob/master/LICENSE) license.

Reference
---------
- Tianqi Chen and Carlos Guestrin. [XGBoost: A Scalable Tree Boosting System](http://arxiv.org/abs/1603.02754). In 22nd SIGKDD Conference on Knowledge Discovery and Data Mining, 2016 
- XGBoost originates from research project at University of Washington, see also the [Project Page at UW](http://dmlc.cs.washington.edu/xgboost.html).
