# Functionality of Security Archive

The Security Archive Project has a lot of backend workings that a random visitor may not get to see. Here I lay it out.

## Registration

We all can see the login and registration forms, so to keep it quick, I'll just point out the encryption of passwords. To keep your information secure in the event of a leak or breach, nobody has access to reading your password.
We store your password in an encrypted state, and there is never a moment it would be visible in plaintext. 


## Profile and Company

For a majority of users, you will only have access to two main pages other than the home page. These are your profile, and company pages. At the profile page, it just shows your associated company, username, and Email. To change this information, you must contact info@securityarchive.net and request an admin to make the changes.

![image](https://github.com/DerekHaber/securityarchive.net/assets/144399414/5df20955-27f2-49dc-bf4b-209e3665816c)


The more important area for our clients, is the company page. This page is not available for those who have not yet been assigned to a company. For those who have been assigned to a company, here you can access any files that have been uploaded to your company's account.
![image](https://github.com/DerekHaber/securityarchive.net/assets/144399414/174bb02e-4f9a-4b33-a609-a65cab63bdb2)


## Admin Panel

The moment you've all been waiting for, our admin panel. The admin panel was crafted in a way that even admins are locked down from seeing passwords, as well as company files. From the main admin page, the administrator can create a company, choose a user account to manage, and go to the file upload manager.
![image](https://github.com/DerekHaber/securityarchive.net/assets/144399414/735f73a4-a95c-45cf-a770-9a7548e28bb1)

## User management

When a user is selected, the administrator is brought to the following page. This page allows them to change the user's username, password, email, assigned company, and Admin status.

![image](https://github.com/DerekHaber/securityarchive.net/assets/144399414/07b1957f-1c3c-4bb2-8d70-a8f2963fa409)


## File Upload

Finally, the file upload. This page lists out all the companies in the database, with a file upload form attached to each. This file upload form is limited to PDFs only. If we determine other filetypes will eventually be needed, we may open up that rule a bit, but to limit the ability of malicious code or files being uploaded, it is currently limited.

![image](https://github.com/DerekHaber/securityarchive.net/assets/144399414/9af2b98b-0279-4a12-a086-9768f0393167)

