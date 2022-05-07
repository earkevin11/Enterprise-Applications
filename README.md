# Enterprise-Applications

# What are enterprise applications?
- These are external applications that are offered within Azure AD.
- Azure AD can act as an Identity Provider for other SaaS applications as well.

<strong> <em> Remember, the SaaS enterprise applications must support Azure AD and vice versa. </em> </strong>

Pros of Enterprise applications:
- Eliminate the need for two separate credentials.
- Single Sign-On (SSO)

For example, if you want to use Dropbox, which has Azure AD integration. You can use the same credentials to sign into Dropbox and Azure AD. It also has SSO, where you can authenticate with your user ID via Azure and if you want to go to Dropbox, it will direct you to Dropbox without prompting you to sing in.

IdP passes the SAML credentials to the service provider to allow SSO.


How to use an enterprise application?
- First, create the Enterprise application within Azure AD. It will create an application object, where you use the application object to work with the application's account. 

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167267526-babcbc9d-4da7-4fd9-97ab-5fb844b2cdd1.png" height="85%" width="85%" alt="Enterprise app object"/>

<p/>


How do we access an application that is assigned to a user?

- myapps.microsoft.com - is where a user will see the applications assigne to them.

How do we make an application visible to a user? 
- We assign permissions to them via the application.
- Navigate to the enterpriser application > go to users and groups > assign the user or group 
- Prompt the user to log back into myapps.microsoft.com and they will have access and see the applications that they have access to.


# Navigating to Users and groups within the Enterprise Application (Dropbox)
<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167267758-c6ddcb9f-391b-48b0-8433-a321a96f15ba.png" height="85%" width="85%" alt="Enterprise app object"/>

<p/>

# Assigning the user 

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167267786-3ff68015-6112-4770-bef1-ef1adc55bd63.png" height="85%" width="85%" alt="Enterprise app object"/>

<p/>

# Prompt user to sign into myapplications.microsoft.com and verify if user can view the application

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167268023-4217de62-233b-482d-92a4-5045b7434657.png" height="85%" width="85%" alt="Enterprise app object"/>

<p/>



# Enterprise Self-Service

- Instead of assigning users to access an application, users can request access to an application.
- Enable this by going to the enterprise application > Self Service > Select the group 
- <strong> <em> Remember, the approver assigned will be the owner of the group. </em> </strong>

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167268855-d9357aeb-b6ae-4fab-bb63-85b13baf5468.png" height="85%" width="85%" alt="Enterprise app self-service"/>

<p/>
