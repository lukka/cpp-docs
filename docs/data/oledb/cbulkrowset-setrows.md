---
title: "CBulkRowset::SetRows | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.technology: ["cpp-data"]
ms.topic: "reference"
f1_keywords: ["ATL.CBulkRowset.SetRows", "CBulkRowset::SetRows", "CBulkRowset<TAccessor>.SetRows", "ATL.CBulkRowset<TAccessor>.SetRows", "CBulkRowset<TAccessor>::SetRows", "ATL::CBulkRowset<TAccessor>::SetRows", "ATL::CBulkRowset::SetRows", "CBulkRowset.SetRows", "SetRows"]
dev_langs: ["C++"]
helpviewer_keywords: ["SetRows method"]
ms.assetid: 7e92312a-bfd0-4c24-a799-62bef663f28e
author: "mikeblome"
ms.author: "mblome"
ms.workload: ["cplusplus", "data-storage"]
---
# CBulkRowset::SetRows
Sets the number of row handles retrieved by each call.  
  
## Syntax  
  
```cpp
      void SetRows(DBROWCOUNT nRows) throw();  
```  
  
#### Parameters  
 `nRows`  
 [in] The new size of the rowset (number of rows).  
  
## Remarks  
 If you call this function, it must be before the rowset is opened.  
  
## Requirements  
 **Header:** atldbcli.h  
  
## See Also  
 [CBulkRowset Class](../../data/oledb/cbulkrowset-class.md)