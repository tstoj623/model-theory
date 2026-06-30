# Machine Learning and Model Theory

A short mathematics report (co-authored, Nov 2025) on a single question:

> **Given data, when does a model generalise instead of overfit?**

It frames supervised learning as fitting a hypothesis to a finite sample, then uses
**statistical learning theory** to answer when that hypothesis will also work on unseen data.
The key quantity is the **VC dimension** (how complex a model class is: the largest set of
points it can label in every possible way), which bounds the gap between training and true
error. The report's mathematical twist is connecting this to **model theory** from logic: a
model class has finite VC dimension exactly when its defining formula has the **NIP**
property, so the same boundary that controls overfitting in ML is a known "tameness" line in
logic.

📄 **[Machine_Learning_and_Model_Theory.pdf](Machine_Learning_and_Model_Theory.pdf)**
