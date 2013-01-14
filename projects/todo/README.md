todo
====

A basic todo app. It lets you add tasks, (un)mark them as complete, delete them, and filter the listing by "all", "done", or "active". Pretty standard todo app. It highlights a few different areas of Alloy:

* Data binding is the main highlight in this app.
  * More specifically, collection binding where we assign a collection to the main TableView's **dataCollection** property so that a row is created for each model in that collection.
  * Collection binding filtering with the **dataFilter** attribute and transformations with the **dataTransform** attribute.
    * There's detailed comments in the controller code for these
  * Show how to use the curly brace notation in your repeated UI element's markup to bind model properties, like **{item}** in [row.xml](https://github.com/tonylukasavage/alloy_demos/blob/master/projects/todo/app/views/row.xml).
  * Alloy handles all of the changes to your collections and its models automatically, no need to manage updating the table yourself.
* Other notable Alloy techniques
  * Usage of Backbone.js techniques for adding, modifying, and deleting models on a collection
  * Using platform-specific markup to use a TabbedBar to filter on iOS, a menu to filter on Android
  * Event handlers created from XML markup

Requirements
------------

* Titanium SDK 3.0.0.GA
* Alloy 0.3.4
* Platforms: Depends what adapter you use. It uses the sql adapter by default, which supports Android and iOS so that's your best bet.
