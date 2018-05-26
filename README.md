# Introduction

## Project Goals

Voyager is a data visualization tool that blends manual and automatic chart specification in a unified system. It aims to support smoother gradations between open-ended exploration and more focused phases of analysis. Voyager augments a traditional drag and drop chart specification interface with two new partial view specification techniques. [Related Views](visualizing-data/related-views.md) automatically recommend charts based on your currently specified view, promoting the discovery of relevant data fields and alternative ways to summarize or encode the data. [Wildcards](visualizing-data/wildcard-fields.md) let you to precisely vary the properties of a specification to generate multiple visualizations in parallel, giving you control over sets of charts aligned with your analysis goals.

## Interface Overview

![](.gitbook/assets/largeui.png)

This figure shows the Voyager interface, which has the following parts:

* The _top panel_ **\(A\)** provides [bookmark gallery](bookmark-gallery.md) and undo commands.
* The _data panel_ **\(B\)** contains the [data selector](load-data.md), dataset name, data fields **\(C\)**, and [wildcard fields](https://data-voyager.gitbook.io/voyager/visualizing-data/wildcard-fields#wildcard-fields) **\(D\)**. Wildcard fields let you create multiple views in parallel by serving as "variables" over an enumerated set of fields. Categorical, temporal, and quantitative field wildcards are provided by default, though you can manually author [custom wildcards](https://data-voyager.gitbook.io/voyager/visualizing-data/wildcard-fields#custom-wildcard-fields) containing desired fields **\(E\)**.
* The _encoding panel_ **\(F\)** contains [shelves](https://data-voyager.gitbook.io/voyager/visualizing-data/specify-visual-encoding#encoding-shelves) for mapping fields to visual channels via drag-and-drop, and a control for selecting [mark](https://data-voyager.gitbook.io/voyager/visualizing-data/specify-visual-encoding#mark-selection) type. A [wildcard shelf](https://data-voyager.gitbook.io/voyager/visualizing-data/wildcard-fields#wildcard-shelves) **\(G\)** lets you add fields without selecting a specific channel, allowing the system to suggest appropriate encodings.
* The [filter](https://data-voyager.gitbook.io/voyager/visualizing-data/specify-visual-encodings#mark-selection) panel **\(H\)** shows dynamic query controls for filtering.
* The specified view **\(I\)** displays the currently specified chart.
* [Related Views](visualizing-data/related-views.md) **\(J\)** shows different kinds of recommended plots relevant to the specified view.

