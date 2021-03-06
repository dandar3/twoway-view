
Eclipse friendly version of the project.

twoway-view-core
================
Requires libraries:
* [dandar3/android-support-v4](https://github.com/dandar3/android-support-v4)
* [dandar3/android-support-v7-recyclerview](https://github.com/dandar3/android-support-v7-recyclerview)

SVN checkout URL:<br>
https://github.com/dandar3/twoway-view/trunk/core/src/main

twoway-view-layouts
===================
Requires libraries:
* [dandar3/twoway-view-core](https://github.com/dandar3/twoway-view/tree/master/core/src/main) (above)

SVN checkout URL:<br>
https://github.com/dandar3/twoway-view/trunk/layouts/src/main

twoway-view-sample
==================
Requires libraries:
* [dandar3/twoway-view-layouts](https://github.com/dandar3/twoway-view/tree/master/layouts/src/main) (above)
* [dandar3/android-support-v7-appcompat](https://github.com/dandar3/android-support-v7-appcompat)

SVN checkout URL:<br>
https://github.com/dandar3/twoway-view/trunk/sample/src/main

<hr>

TwoWayView
==========

*RecyclerView* made simple.

![](images/sample.png)

Features
========

* A *LayoutManager* base class that greatly simplifies the development of custom layouts for *RecyclerView*
* A collection of feature-complete stock layouts including:
  * List
  * Grid
  * Staggered Grid
  * Spannable Grid
* A collection of stock item decorations including:
  * Item spacing
  * Horizontal/vertical dividers.
* ListView-style pluggable APIs for:
  * Item click and long click support e.g. *OnItemClickListener* and *OnItemLongClickListener*.
  * Item selection (single and multiple) support e.g. *setChoiceMode()*, *setItemChecked(int, boolean)*, etc.

Snapshot
========

The new API is still under heavy development but you can try it now via Maven Central snapshots.

Gradle:
```groovy
repositories {
    maven { url "https://oss.sonatype.org/content/repositories/snapshots/" }
}

dependencies {
    compile 'org.lucasr.twowayview:core:1.0.0-SNAPSHOT@aar'
    compile 'org.lucasr.twowayview:layouts:1.0.0-SNAPSHOT@aar'
}
```

Stable Release
==============

TwoWayView used to be a standalone *AdapterView* implementation. You can grab it here from Maven Central as follows.

Grab via Maven:
```xml
<dependency>
  <groupId>org.lucasr.twowayview</groupId>
  <artifactId>twowayview</artifactId>
  <version>0.1.2</version>
</dependency>
```

Gradle:
```groovy
compile 'org.lucasr.twowayview:twowayview:0.1.2'
```


Want to help?
=============

File new issues to discuss specific aspects of the API and to propose new
features.

License
=======

    Copyright (C) 2013 Lucas Rocha

    TwoWayView's code is based on bits and pieces of Android's
    AbsListView, Listview, and StaggeredGridView.

    Copyright (C) 2012 The Android Open Source Project

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
