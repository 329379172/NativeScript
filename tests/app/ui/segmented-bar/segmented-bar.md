---
nav-title: "SegmentedBar How-To"
title: "segmented-bar"
description: "Examples for using SegmentedBar"
previous_url: /ApiReference/ui/segmented-bar/HOW-TO
---
# SegmentedBar
Using a SegmentedBar requires the "ui/segmented-bar" module.
<snippet id='article-require-segmentedbar-module'/>
## Creating a SegmentedBar
<snippet id='article-create-segmentedbar'/>
``` XML
<SegmentedBar>
  <SegmentedBar.items>
    <SegmentedBarItem title="Item 1" />
    <SegmentedBarItem title="Item 2" />
    <SegmentedBarItem title="Item 3" />
  </SegmentedBar.items>
</SegmentedBar>
```
### Creating segmentedBar.items
It is important that an items array gets created and filled with
items first and then assigned to the segmented bar.
<snippet id='article-creating-segmentedbar-items'/>
### Selecting an item programmatically
<snippet id='artcile-selecting-item'/>
