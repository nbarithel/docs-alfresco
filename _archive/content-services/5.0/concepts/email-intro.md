---
author: [Alfresco Documentation, Alfresco Documentation]
audience: 
category: Customization
---

# Configuring email

The email subsystem allows you to configure the outbound and inbound SMTP email settings to interact with Alfresco.

You can run the Alfresco email server by running the email server process in the same JVM context as the repository.

There are two methods of running Alfresco email server:

-   Running the email server process in the same JVM context as the repository
-   Running the email server remotely and communicate with the repository using Remote Method Invocation \(RMI\)

-   **[Admin Console: Managing inbound emails](../tasks/adminconsole-inboundemail.md)**  
Set these inbound email properties to activate sending and receiving site invites, and also for receiving activity notification emails.
-   **[Admin Console: Managing outbound emails](../tasks/adminconsole-outboundemail.md)**  
Set these outbound email properties to manage all emails sent from Alfresco to users such as site invitations, activity notifications, and workflow tasks.
-   **[OutboundSMTP configuration properties](../concepts/email-outboundsmtp-props.md)**  
The following properties can be configured for the OutboundSMTP subsystem type.
-   **[InboundSMTP configuration properties](../concepts/email-inboundsmtp-props.md)**  
The InboundSMTP email subsystem type allows you to configure the behavior of the email server and service.
-   **[Handling messages by target node type](../concepts/email-target-node.md)**  
This section describes the default behaviors for incoming email to different types of referenced nodes.
-   **[Groups and permissions for email](../concepts/email-groupspermissions.md)**  
An email arriving at the Alfresco email server is unauthenticated. An authentication group, `EMAIL_CONTRIBUTORS`, must exist to allow permissions to be handled at a high level by the administrator.

**Parent topic:**[Configuring Alfresco](../concepts/ch-configuration.md)

