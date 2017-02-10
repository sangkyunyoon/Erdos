# Erdos
a modular and modern Graph theoretic algorithms framework
### Dependencies
* none

## How to use

Option 1: Jitpack

Add Jitpack in your root build.gradle at the end of repositories:
```groovy
allprojects {
    repositories {
        ...
        maven { url "https://jitpack.io" }
    }
}
```

Add to your dependencies:

```groovy
dependencies {
    compile 'tbd'
}
```

Option 2: Simply fork or download the project, you can also download and create `.jar` file yourself, with

```bash
git clone https://github.com/Erdos-Graph-Framework/Erdos.git erdos
cd erdos
./gradlew build
ls -l build/libs
```

Option 3: grab the latest released jar

[https://github.com/Erdos-Graph-Framework/Erdos/releases](https://github.com/Erdos-Graph-Framework/Erdos/releases)

```bash

```

## Notable technical features
* compatible with `Java 7`
* compose your graph by features and engine. modular design.
* production proved code. Used in a commercial project.

## Supported graphs
* simple graph, directed and undirected
* multi edge graph, directed and undirected
* pseudo graph
* custom graph, configure by self-loops, multi-edges and a graph engine.

## builtin algorithms
Erdos is a framework to easily help you design graph algorithms
with the correct abstractions and utilities. The builtin algorithms are:
* search algorithms
    * [BFS](https://en.wikipedia.org/wiki/Breadth-first_search) - Breadth First Search
    * [DFS](https://en.wikipedia.org/wiki/Depth-first_search) - Depth First Search
* sorting
    * [Topological sorting](https://en.wikipedia.org/wiki/Topological_sorting)
* structure
    * [Strongly Connected Components](https://en.wikipedia.org/wiki/Strongly_connected_component)
* minimum spanning tree
    * [Prim's algorithm](https://en.wikipedia.org/wiki/Prim's_algorithm)
    * [Kruskal's algorithm](https://en.wikipedia.org/wiki/Kruskal's_algorithm)
* single source shortest path
    * [Bellman–Ford algorithm](https://en.wikipedia.org/wiki/Bellman%E2%80%93Ford_algorithm)
    * [Dijkstra's algorithm](https://en.wikipedia.org/wiki/Dijkstra's_algorithm)
    * Directed acyclic graph algorithm
* all pairs shortest path
    * [Floyd–Warshall algorithm](https://en.wikipedia.org/wiki/Floyd%E2%80%93Warshall_algorithm)
    * [Johnson's algorithm](https://en.wikipedia.org/wiki/Johnson's_algorithm)
* minimum spanning tree
    * [Prim's algorithm](https://en.wikipedia.org/wiki/Prim's_algorithm)
    * [Kruskal's algorithm](hhttps://en.wikipedia.org/wiki/Kruskal's_algorithm)
* transformations
    * Square of a graph
    * transitive closure of a graph
    * transpose of a graph

## builtin graph engines
* **Adjacency** and **Incidence** list based graph engine <br/>designed for optimal complexity for algorithms that require more than a moderate edge queries.

### Instructions
#### 1. create XML layouts
blah
```java
```

#### 2. Implement a View renderer
```java

```

### Contributions
contributions are most welcomed, please consult [`CONTRIBUTING.MD`](CONTRIBUTING.MD)

### License
If you like it -> star or share it with others

```
Copyright (C) 2016 Tomer Shalev (https://github.com/HendrixString)

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
```

### Contact Author
* [tomer.shalev@gmail.com](tomer.shalev@gmail.com)
* [Google+ TomershalevMan](https://plus.google.com/+TomershalevMan/about)
* [Facebook - HendrixString](https://www.facebook.com/HendrixString)
