+++
date = "2015-10-08T09:56:14Z"
title = "Changelog"
[menu.main]
  weight = 55
  pre = "<i class='fa fa-cog'></i>"
+++

## Changelog

Changes between released versions


### 1.3.1

[Full change list](https://jira.mongodb.org/issues/?jql=project%20%3D%20JAVARX%20AND%20fixVersion%20%3D%201.3.1)

  * Fix bug disallowing requesting zero elements [JAVARX-34](https://jira.mongodb.org/browse/JAVARX-33)

### 1.3

[Full change list](https://jira.mongodb.org/issues/?jql=project%20%3D%20JAVARX%20AND%20fixVersion%20%3D%201.3)

  * Updated MongoDB Driver Async to 3.4.0
  * Updated RxJava to 1.2.0 [JAVARX-33](https://jira.mongodb.org/browse/JAVARX-33)
  * Added support for views [JAVARX-32](https://jira.mongodb.org/browse/JAVARX-32)
  * Added Collation support [JAVARX-31](https://jira.mongodb.org/browse/JAVARX-31)
  * Added support for extending handshake metadata [JAVARX-29](https://jira.mongodb.org/browse/JAVARX-29)

### 1.2 

[Full change list](https://jira.mongodb.org/issues/?jql=project%20%3D%20JAVARX%20AND%20fixVersion%20%3D%201.2)

  * Updated MongoDB Driver Async to 3.2.0
    
  * Updated RxJava to 1.0.17
  
  * Added `ObservableAdapter` to allow for custom adapters for `Observable`, such as customizing Scheduler threads.
  
  * Ensured that errors caused when requesting data is passed to the `Observer`.

### 1.1 

[Full change list](https://jira.mongodb.org/issues/?jql=project%20%3D%20JAVARX%20AND%20fixVersion%20%3D%201.1)

  * Updated MongoDB Driver Async to 3.1.0
  
    Simplified the driver by using the new `com.mongodb.async.client.Observable` and mapping to `rx.Observable`
    
  * Updated RxJava to 1.0.14

