# TFS-Collection-Level-Permissions-18
Team Foundation Server (#Collection Level Permissions)
## You guys can also find the  referebce in this website::
https://roadtoalm.com/2014/07/28/add-permissions-with-tfssecuritythe-ultimate-reference/
## Refer the CSV File to frame all those permissions

## 
Collections==>NameSpace==>Access Control Lists===>Token===>Access Control Entry
##
Permissions wil be only

Allow
Deny
Explicit Allow
Explicit Deny
##
For getting Inherited Allow and Inherited Deny

Inherited Allow=(Explicit Allow)-(Allow)
Inherited Deny=(Explicit Deny)-(Deny).
