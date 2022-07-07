# LAB 1

## 1. Login to your AWS account
   -  Go to `console.aws.amazon.com`. Since you are not logged in, it will redirect to the login page. 
   - Enter your root credentials and submit

![Login page](/images/aws_login.PNG)

## 2. Activate Multifactor authentication for root user
    - Select IAM from the Services menu
    - If multifactor authentication is currently disabled, an `Add MFA for root user` section would appear as a security recommendation on the IAM dashboard
    -  Click the Add MFA button to be redirected to the Security Credentials page
    - Click the Activate MFA button and select an MFA device

![Add MFA page](/images/add_mfa.PNG)

## 3. Create a user who is an admin for the root user
    - In the sidebar menu, click `Users` under the `Access management` section
    - Click the `Add Users` button. It will trigger a wizard. Fill the first form as desired and click Next
    - Select `Attach existing policies directly` and check `AdministratorAccess` and click Next to add Tags
    - Review the user and policies added then click Create User to wrap this up

![Create Admin user](/images/create_admin.PNG)


