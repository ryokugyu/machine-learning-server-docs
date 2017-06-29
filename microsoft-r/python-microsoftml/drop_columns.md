--- 
 
# required metadata 
title: "Drops columns from the dataset" 
description: "Specified columns to drop from the dataset." 
keywords: "transform" 
author: "Microsoft Corporation Microsoft Technical Support" 
manager: "" 
ms.date: "" 
ms.topic: "reference" 
ms.prod: "microsoft-r" 
ms.service: "" 
ms.assetid: "" 
 
# optional metadata 
ROBOTS: "" 
audience: "" 
ms.devlang: "" 
ms.reviewer: "" 
ms.suite: "" 
ms.tgt_pltfrm: "" 
ms.technology: "r-server" 
ms.custom: "" 
 
---

## drop_columns


*Applies to:* SQL Server 2017, Machine Learning Services 9.3


### Usage



```
microsoftml.modules.schema_manipulation.drop_columns(cols: (<class ‘list’>, <class ‘str’>), **kargs)
```




### Description

Specified columns to drop from the dataset.


### Arguments


##### cols

A character vector or list of the names of the variables to drop.


### Returns

A ``maml`` object defining the transform.


### Author

Microsoft Corporation [Microsoft Technical Support](https://go.microsoft.com/fwlink/?LinkID=698556&clcid=0x409.md)