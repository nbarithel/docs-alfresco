---
author: [Alfresco Documentation, Alfresco Documentation]
audience: 
category: [Administration, Alfresco Server]
keyword: back up restore
---

# Backing up and restoring

This section describes the process for backing up the Alfresco content repository only. It assumes that components other than the data residing in Alfresco \(operating system, database, JDK, application server, Alfresco binaries and configuration, etc.\) are being backed up independently.

Your backup strategy must be tested end-to-end, including restoration of backups. Ensure that you have adequately tested your backup scripts prior to deploying Alfresco to production.

-   **[Backing up and restoring the repository](../concepts/backup-intro.md)**  
Backing up an Alfresco repository involves backing up the directory pointed to by the `dir.root` setting, the database that Alfresco is configured to use, and the Solr 4 indexes.

**Parent topic:**[Administering](../concepts/ch-administering.md)

