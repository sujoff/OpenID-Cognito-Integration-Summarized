## About 

Hello! This is short overview of how i integrated OpenID Connect (OIDC) with AWS Cognito, configured authentication rules for different user groups for a Fintech Company from India.

## Projects

### 1. OIDC Integration with AWS Cognito

I have successfully implemented OpenID Connect (OIDC) integration for unique AWS Cognito user pools. This project involved:

- **Setup and Configuration**: 
  - Created multiple AWS Cognito user pools to manage different sets of users.
  - Configured OIDC settings for authentication process.
  
- **Authentication Rules**:
  - Defined and configured authentication rules for each user group (e.g., admins, regular user i.e branch manager, front staffs, loan manager etc).
  - Implemented MFA (Cognito > MFA & Verification Process > Make MFA required > Configured TOTP).
  -  Applied password policies for better security (that means ).
 
- ## IAM role for SMS (Optional) :


  `{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Effect": "Allow",
      "Action": "sns:Publish",
      "Resource": "*"
    }
  ]
}

`

##Overall Architecture

![image](https://github.com/sujoff/OpenID-Cognito-Summarized/assets/91075040/2a9c8422-a43b-45f1-bbda-4d9aa7f52a16)

  
Thank you for reading!
