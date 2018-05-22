# Introduction

## Project Goals

Voyager 2 is a new mixed-initiative tool that blends manual and automatic chart specification in a unified system. It aims to support smoother gradations between open-ended and more focused phases of analysis. It is a powerful tool that augments traditional visual analysis interfaces with two new partial view specification techniques. Features like wildcards, can allow analysts to precisely vary the properties of a specification to generate multiple charts in parallel, giving them control over sets of views aligned with their analysis goals. Similarly, related views features can automatically recommend charts based on the current user-specified focus view, in which promote the discovery of relevant data fields and alternative ways to summarize or encode the data.

## Interface Overview

![User Interface](.gitbook/assets/ui.png)

This figure shows the Voyager interface, which has the following parts:

* The _top panel_ **\(A\)** provides [bookmark gallery](bookmark-gallery.md) and undo commands.
* The _data panel_ **\(B\)** contains the [data selector](load-data.md), dataset name, data fields **\(C\)**, and [wildcard fields](visualizing-data/wildcard-fields/) **\(D\)**. Wildcard fields let users create multiple views in parallel by serving as "variables" over an enumerated set of fields. Categorical, temporal, and quantitative field wildcards are provided by default, though users can manually author [custom wildcards](visualizing-data/wildcard-fields/custom-wildcard-fields.md) containing desired fields **\(E\)**.
* The [_encoding panel_]() **\(F\)** contains [shelves]() for mapping fields to visual channels via drag-and-drop, and a control for selecting [mark]() type. A [wildcard shelf](visualizing-data/wildcard-fields/wildcard-shelves.md) **\(G\)** lets users add fields without selecting a specific channel, allowing the system to suggest appropriate encodings.
* The [_filter_](visualizing-data/filter.md) panel **\(H\)** shows dynamic query controls for filtering.
* The specified view **\(I\)** displays the currently specified chart.
* [Related views](visualizing-data/related-views/) **\(J\)** show different kinds of recommended plots relevant to the specified view.

