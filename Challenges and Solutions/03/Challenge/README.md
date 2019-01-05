
## Challenge Number 03
### Multiple Field Reduction

Use the following files:
1. Challenge_03_MultiField_SA.XLS (Section Access Authorization Matrix/Table)
2. 03. Multi Field Reduction - Challenge.QVW (Use the project folder structure)

Please note: You need to change the **vRootpath** variable in the QVW file to successfully reload the app.

_________________

### Requirements:
=================

Following table is created using:

Dimension: Supplier Name

Measure: Sum([Order Amount])

![alt text](https://github.com/iamdv/QlikView-Security-Masterclass/blob/master/Assets/OrderAmount%20by%20Supplier.png "Order Amount by Supplier")

You need to use the USERID and PASSWORD (test) for each supplier. So, suppliers can login with their respective and passwords to see the sales data. You should **NEVER** allow suppliers to view each other's sales information. This will be a security flaw!

**Implement Section Access using the USERID and PASSWORD (Not NTNAME). Feel free to use the INLINE load.**

**Make sure the administrator account [APPADMIN] has access to all the data**


**ALL-THE-BEST!**

