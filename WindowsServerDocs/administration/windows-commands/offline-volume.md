---
title: offline volume
description: "Windows Commands topic for **** - "
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: manage-windows-commands
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: b8f7192f-ea38-47d0-9d4e-58ef68336ae6
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016
---
# offline volume

>Applies To: Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Takes the online volume with focus to the offline state.  
  
> [!IMPORTANT]  
> This DiskPart command is not available in any edition of Windows Vista.  
  
## Syntax  
  
```  
offline volume [noerr]  
```  
  
## Parameters  
  
|Parameter|Description|  
|-------|--------|  
|noerr|for scripting only. When an error is encountered, DiskPart continues to process commands as if the error did not occur. Without this parameter, an error causes DiskPart to exit with an error code.|  
  
## remarks  
  
-   A volume must be selected for this to succeed. Use the **select volume** command to select a disk and shift the focus to it.  
  
## <a name="BKMK_examples"></a>Examples  
To take the disk with focus offline, type:  
  
```  
offline volume  
```  
  
#### additional references  
[Command-Line Syntax Key](command-line-syntax-key.md)  
  

  

