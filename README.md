# RoseBlanc
The online store is now closed. This is a simple site that is used to deliver a message to our customers.

## Author
Dennis Le <br />
(operating partner & software developer at RoseBlanc)

## How to deploy
1. Update to th newset version of firebase tools
```bash
npm install -g firebase-tools
```
2. Logout <br />
This step is very important to prevent any error caused by old token from previous session
```bash
firebase logout
```

3. Login
```bash
firebase login
```
4. Initialise the project
```bash
firebase init
```
5. Deploy the project
```bash
firebase deploy
```