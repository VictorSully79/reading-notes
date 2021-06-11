# Cognito
#### notes taken from: https://docs.amplify.aws/lib/auth/getting-started/q/platform/android

### Cognito works behind the scenes to provide authorization to other Amplify categories.

### Configure Auth Category:
- In the command line use `amplify add auth`
- Use `amplify push` to push changes to the cloud

### Install Amplify Libraries:
- `dependencies {
  implementation 'com.amplifyframework:aws-auth-cognito:1.18.0'
  }`
  
### Initialize
- `Amplify.addPlugin(new AWSCognitoAuthPlugin());
  Amplify.configure(getApplicationContext());
  `
  
### Further instruction are detailed in the above named link.
