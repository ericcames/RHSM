# Red Hat Subscription Management (RHSM)

**Red Hat Subscription Managment what is it? Why should my organization use it?**  
- [Red Hat Subscription Management](https://access.redhat.com/products/red-hat-subscription-management#whats-new "RHSM")  

**Login in to:**  
- [Red Hat Customer Portal](https://access.redhat.com/management/ "Red Hat Customer Portal")

**Register servers with RHSM**  
- [Red Hat Subscription Management (RHSM) ansible playbook](https://github.com/ericcames/RHSM/blob/main/rhsmregistration.yml "RHSM ansible playbook")  
- This playbook requires a username and password to be input at runtime.  This can be done using a survey via the Anisble Automation Platform web interface.  The credentials are the credentials used for access to access.redhat.com.
- In the web interface find the template that you will use to subscribe your servers to RHSM and create a survey with the two input variables needed to subscribe the servers to RHSM.  Make sure your variables names in the playbook and the survey match.

![alt text](https://github.com/ericcames/RHSM/blob/main/images/survey1.png "Logo Title Text 1")
![alt text](https://github.com/ericcames/RHSM/blob/main/images/survey2.png "Logo Title Text 1")
