
## Challenge Number 02
### Single Field Reduction

Use the **QlikView Security Masterclass zip** file which has the required QVW and the QVD files. 

Please note: You need to change the **vRootpath** variable in the QVW file to successfully reload the app.

_________________

### Requirements:
=================

![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")


These are the **sensitive fields** in the data model:

* Salary
* SSN
* Birth Date
* E-mail
* Phone

You need to hide these fields in the data model and also gracefully handle the frontend app (aka QVW) when the respective users open the app. There should not be **ANY** error message on the list boxes. 

**Implement Section Access using the USERID and PASSWORD (Not NTNAME). Feel free to use the INLINE load.**

Here's the ACL:

| User Name     | What are they allowed to see|
| ------------- |:-------------:| 
| user1    | None | 
| user2     | None      | 
| hr | Salary and Birth Date      | 
| manager | Salary    | 
| marketing | E-mail and Phone     | 
| admin | everything      | 

**All other fields which are classified as non-senstivie can be shown to all the users.**


**ALL-THE-BEST!**

