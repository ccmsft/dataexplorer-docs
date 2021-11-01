---
title: The .delete auto delete policy command - Azure Data Explorer | Microsoft Docs
description: This article describes the .delete auto delete policy command in Azure Data Explorer.
services: data-explorer
author: orspod
ms.author: orspodek
ms.reviewer: yifats
ms.service: data-explorer
ms.topic: reference
ms.date: 09/26/2021
---
# .delete auto delete policy

Deletes the auto delete policy of a table. For more information, see [auto delete policy](auto-delete-policy.md).

## Syntax

`.delete` `table` *TableName* `policy` `auto_delete`

## Arguments

*TableName* - Specify the name of the table. 

## Example

```kusto
.delete table [table_name] policy auto_delete
```