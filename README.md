# SparkCAD
SparkCAD (Spark Caching Anomalies Detector): Logical plan visualization and caching anomalies detection tool.

* Current version: 1.0
* Contents:
  1. Overview
  2. Requirements
  3. Orgenization

---
### OVERVIEW ###

SparkCAD is an interactive decision support tool that visualizes the logical plan of Spark applications and detects caching anomalies. 
It parses the execution logs of Spark (thse same ones that Spark's History Server parses without additional metadata).


### Requirements ###
 * [Jupyter](https://jupyter.org/)
 * [Graphviz](https://graphviz.readthedocs.io/en/stable/manual.html)

### Orgenization ###

Samples of 130 execution logs could be found in "logs" folder.
The produced logical plans are stored by default in "Spark-DAGs".
The default configuration is stored in "config.ini". The user can change it or overwrite the default configuration values during using the notebook.
