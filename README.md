# aws-generate-session-token
Generate session token AWS and insert it into some profile of the credential file.

## TO USE
npm run generate TOKEN_CODE

## .env file
Specific the following information:

PROFILE_CONNECT=<<profile in credential file to connect aws>>
PROFILE_GENERATE=<<new profile to save the session token>>
DEVICE_MFA=arn:aws:iam::{acountid}:mfa/{username}
  
  

