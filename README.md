# GreekGods--Dashboard

![x](greekGods.png)


# Background

Compare search results between greek mythology and roman mythology to see which god is most popular.


# Goals

* In ancient Rome, their gods were often counterparts or imports of Greek gods. For example, the Greek god Zeus became in Rome Jupiter via an etymological transformation from Zeus to Zeus Pater ("Father Zeus") to Jupiter (classical Latin lacked a "J" consonant).

* In today's world, are these gods better known by their Roman names or Greek names? To answer this question, your task is to plot the number of search results, of both Roman and Greek names, returned for each god.

* To accomplish this task, you will need to create two traces, one for Roman gods, and another for Greek gods.

* In order to define the data for each plot point in a trace, use the `map()` method on the dataset.

* Examine `data.js` to determine how you will do this.


* Sort the data array of objects by `greekSearchResults`.

* Slice the top 10 objects from the array.

* Create a horizontal bar chart that plots the top 10 greek gods based on their search results in descending order.

