# Gauguin Library

The idea automate EDA - to create a python based AutoEDA tool similar to the many AutoML frameworks where a user uploads some data, selects a target of interest
and the tool creates thousands of visualizations giving insight into the data ranked by interestingness.

We will start by refactoring the AutoViz and Auto_ViML libraries [https://github.com/AutoViML](https://github.com/AutoViML).

The AutoViz is missing many important EDA plots such as individual conditional expectation (ICE), leave-one-covariance (LOCO), local feature importance, partial dependency plots, tree-based feature importance, standardized coefficient importance, accumulated local effects (ALE) plots and Shapley values.

The AutoViz plots are ugly. An important feature would be to add "themes". That is, design parameters like font, leading, color sets, etc.  There should be themes like "New York Times", "The Economist," etc. which make the plots adhere to a visual style.

The parameters of the theme should be configurable in a JSON file so a user and use custom themes.  

There seems to be no ranking of the plots to show interesting plots first in AutoViz.   

The library needs to be easily extendable.  As new plots get developed in the research aspects of the project they should be able to be added to the library in a standard and easy manner.   

For OPT people, your challenge will be to replicate the clone and analyze the AutoViz to create a design document for the above specs.


