# Treeversity
Information visualization tool for comparing two trees.

![Treeversity screeshot](http://www.cs.umd.edu/hcil/treeversity/img/2012_03_30_fake_budget_with_labels_and_scatter_plot.png)

TreeVersity is a research prototype that visually compares two trees by node values and created and deleted nodes. It was created by [John Alexis Guerra Gómez](http://johnguerra.co), [Audra Buck-Coleman](http://www.art.umd.edu/faculty/abuck/), [Catherine Plaisant](http://hcil.umd.edu/catherine-plaisant/) and [Ben Shneiderman](https://www.cs.umd.edu/users/ben/) from the [Human Computer Interaction Lab](http://hcil.cs.umd.edu/) and the [CATT Lab](http://www.cattlab.umd.edu/) from the [University of Maryland](http://umd.edu)

 You can find more information about the project on the [Treeversity project homepage](http://www.cs.umd.edu/hcil/treeversity/)

 ## Usage

 Download the jar file and execute it using JRE 1.7 or compatible

 `
 java -jar TreeVersity-1.6.jar
 `

 Then open one of the provided example datasets (from the 2012 US Federal Budget outlays report). *Data files should be in the treeml data format [sample treeml](https://github.com/prefuse/Prefuse/blob/master/data/treeml-sample.xml)*

 The file will contain several trees, one for each year, then drag the trees from the table to the corresponding comparison panels on the top right of the window

![Demo loading data](TreeVersity-1.6-loading_data.gif)