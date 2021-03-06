---
author: [Alfresco Documentation, Alfresco Documentation]
audience: 
category: Alfresco Share
option: [extending, Share, Document library, EXIF renderer source code]
---

# Configuring Share user name and password

This section describes how to change the Share user name and password.

1.  Open the file <web-extension\>/share-config-custom.xml.

2.  Search for the text "username". You will see the following configuration:

    ```
    
                
       <config evaluator="string-compare" condition="Users">
          <users>
             <!-- minimum length for username and password -->
             <username-min-length>2</username-min-length>
             <password-min-length>3</password-min-length>
          </users>
       </config>            
                
              
    ```

    You can change the minimum length required for the user name and password.


**Parent topic:**[Configuring Alfresco Share](../concepts/share-configuring-intro.md)

