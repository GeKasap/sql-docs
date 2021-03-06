---
title: "Specify Snapshot Format (SQL Server Management Studio) | Microsoft Docs"
ms.custom: ""
ms.date: "03/14/2017"
ms.prod: sql
ms.prod_service: "database-engine"
ms.component: "replication"
ms.reviewer: ""
ms.suite: "sql"
ms.technology: replication
ms.tgt_pltfrm: ""
ms.topic: conceptual
helpviewer_keywords: 
  - "snapshots [SQL Server replication], formats"
  - "snapshot replication [SQL Server], formats"
ms.assetid: 7c95f545-731a-4743-9acb-0b325ef9b98b
caps.latest.revision: 38
author: "MashaMSFT"
ms.author: "mathoma"
manager: craigg
---
# Specify Snapshot Format (SQL Server Management Studio)
[!INCLUDE[appliesto-ss-xxxx-xxxx-xxx-md](../../../includes/appliesto-ss-xxxx-xxxx-xxx-md.md)]
  Specify snapshot format on the **Snapshot** page of the **Publication Properties - \<Publication>** dialog box. For more information about accessing this dialog box, see [View and Modify Publication Properties](../../../relational-databases/replication/publish/view-and-modify-publication-properties.md).  
  
### To specify snapshot format  
  
1.  On the **Snapshot** page of the **Publication Properties - \<Publication>** dialog box, select **Native SQL Server - all Subscribers must be servers running SQL Server** or **Character - required if a Publisher or Subscriber is not running SQL Server**.  
  
    > [!NOTE]  
    >  It is recommended to select the native format unless this publication must support subscriptions to a [!INCLUDE[ssEW](../../../includes/ssew-md.md)] database or a non-[!INCLUDE[ssNoVersion](../../../includes/ssnoversion-md.md)] database.  
  
2.  [!INCLUDE[clickOK](../../../includes/clickok-md.md)]  
  
## See Also  
 [Configure Snapshot Properties &#40;Replication Transact-SQL Programming&#41;](../../../relational-databases/replication/publish/configure-snapshot-properties-replication-transact-sql-programming.md)   
 [Change Publication and Article Properties](../../../relational-databases/replication/publish/change-publication-and-article-properties.md)   
 [Initialize a Subscription with a Snapshot](../../../relational-databases/replication/initialize-a-subscription-with-a-snapshot.md)  
  
  
