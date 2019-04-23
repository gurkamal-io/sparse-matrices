# Sparse Matrices
In numerical analysis, we often come encounter large sparse matrices, where almost all of the elements are 0 or some default value. This behavior is especially common in machine learning applications such as natural language processing, and finding an efficient way to represent this data struture in memory is important. Here is a good simple (but small-scale) example of this behavior:

![Sparse Matrix Example](https://github.com/gurkamalpsc/sparse-matrices/blob/master/sparse_matrix_example.png)
## Real World Applications
#### Representing Sparse Images
Sometimes artwork or even scientific photography can be respresented as a sparse matrix. If most of the pixels of the image are black or some default color, the image's data can be compressed into a sparse-matrix so that redundant data is not stored for the "sparse" pixels.

![Sparse Matrix Images](https://github.com/gurkamalpsc/sparse-matrices/blob/master/sparse_matrix_images.jpg)
#### Application 2
Placeholder Text
## Projects in this Repository
This repository contains 2 versions of the subset sum problem:
* [Sparse Matrix](#)<br />Placeholder Text
* [Sparse Matrix Cloneable](#)<br />Placeholder Text
## Prerequesites
Gradle 5.4 requires [Java 8](https://www.oracle.com/technetwork/java/javaee/downloads/jdk8-downloads-2133151.html) or later to run.
* Mac<br />```$ brew cask install java8```
* Linux<br />```$ sudo apt install oracle-java8-installer```
* Windows<br />```C:\> choco install jdk8```
## Usage
Running both projects:
```
$ git clone https://github.com/gurkamalpsc/sparse-matrices.git && cd sparse-matrices && ./gradlew run
```
## Built With
* [IntelliJ Idea CE](https://www.jetbrains.com/idea/) - Java & Kotlin IDE
* [Gradle 5.4](https://gradle.org/) - Build Tool & Monorepo Management
## License
This project is licensed under the MIT License
