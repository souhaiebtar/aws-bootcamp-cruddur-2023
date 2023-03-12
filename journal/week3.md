# Week 3 — Decentralized Authentication

mainly what i did is to watch and rewatch the video and all things worked properly on my code

### setup Cognito User pool

![setupCognitoUserPool][setupCognitoUserPool]

then i run 

`aws cognito-idp admin-set-user-password --username tsouhaieb --password Testing123! --user-pool-id eu-west-1_F9oM510Yj --permanent`

![userConfirmed][userConfirmed]

than i login

![loginSuccessufllyWithDatainConsole][loginSuccessufllyWithDatainConsole]

### Implement Custom Signup Page
### Implement Custom Confirmation Page

i did watch the video and i tried to apply what they did contain
![customConfirmationPage][customConfirmationPage]

![loginAfterConfirmation][loginAfterConfirmation]

### Implement Custom Recovery Page

![recoverPassword][recoverPassword]
![receiveRecoveryPassword][receiveRecoveryPassword]


[setupCognitoUserPool]: assets/3-setupCognitoUserPool.png
[userConfirmed]: assets/3-userConfirmed.png
[loginSuccessufllyWithDatainConsole]: assets/3-loginSuccessufllyWithDatainConsole.png
[customConfirmationPage]: assets/3-customConfirmationPage.png
[loginAfterConfirmation]: assets/3-loginAfterConfirmation.png
[recoverPassword]: assets/3-recoverPassword.png
[receiveRecoveryPassword]: assets/3-receiveRecoveryPassword.png