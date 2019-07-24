# How to deal with nested lists in R? Using the purrr, furrr and future packages in practice.

Author: Lidia Kolakowska (Sotrender)

# Description

Cleaning and preparing data for analysis is one of the most time-consuming stages in the analyst's work. This process is further prolonged and can be frightening when data is available as nested lists. An example can be data received for analysis in JSON format, downloaded directly from API or non-relational database such as MongoDB. 

Based on data on political advertisements, provided by Facebook, in my presentation I will show you how to optimize the processing of data nested in lists using publicly available packages. In addition, I will discuss how to easily write anonymous functions, which are to be iterated after each element of the list, as well as two lists simultaneously. An anonymous function (also known as a lambda expression) is a definition of a function that is not associated with an identifier. This means that it is a function that is created and used, but never assigned to a variable. Using the purrr package, it will show you how to define this type of function in a very short way.

By jumping to a higher level with time-consuming code processing, I will show examples of using furrr and future packages, which with minimal editing will allow you to process the same operations in parallel. And all this in a pipe!

Tag words: nested lists, json data format, iterating over two list at same time, dealing with NULLs in nested lists, filtering lists elements, parallel processing, processing in pipelines, joining data from lists without primary keys


main packages: dplyr, purrr, future, furrr, fs, jsonlite
