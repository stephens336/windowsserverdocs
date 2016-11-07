---
title: Using the disable-Server Command
description: "Windows Commands topic for **** - "
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: manage-windows-commands
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: b69fcfe0-b744-4794-bc75-2c9218c0ba66
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016
---
# Using the disable-Server Command

>Applies To: Windows Server&reg; 2016, Windows Server&reg; 2012 R2, Windows Server&reg; 2012

Disables all services for a Windows Deployment Services server.  
  
## Syntax  
  
```  
wdsutil [Options] /Disable-Server [/Server:<Server name>]  
```  
  
## Parameters  
  
|Parameter|Description|  
|-------|--------|  
|[/Server:<Server name>]|Specifies the name of the server. This can be either the NetBIOS name or the fully qualified domain name (FQDN). if no server name is specified, the local server will be used.|  
  
## <a name="BKMK_examples"></a>Examples  
To disable the server, run one of the following:  
  
```  
wdsutil /Disable-Server  
wdsutil /verbose /Disable-Server /Server:MyWDSServer  
```  
  
#### additional references  
[Command-Line Syntax Key](command-line-syntax-key.md)  
  
[Using the enable-Server Command]()  
  
[Using the get-Server Command]()  
  
[Using the Initialize-Server Command]()  
  
[Subcommand: set-Server]()  
  
[Subcommand: start-Server]()  
  
[Subcommand: stop-Server]()  
  
[The uninitialize-Server Option]()  
  
