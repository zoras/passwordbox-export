# Export for PasswordBox Chrome plugin
To cover for the lack of an export function in PasswordBox, here is a "hack" you're welcome to use if you want to export your passwords to another password manager. Developed by [klingenm](https://github.com/klingenm/passwordbox-export).

[![Watch Video](http://img.youtube.com/vi/1A9aIu8puMQ/0.jpg)](https://www.youtube.com/watch?v=1A9aIu8puMQ)

## Usage
1. Install [Chrome Apps & Extensions Developer Tool](https://chrome.google.com/webstore/detail/chrome-apps-extensions-de/ohmmkhmmmpcnpikjeljgnaoabkaalbgc?hl=en)
2. Login with your credentials to the PasswordBox extension
3. Right click anywhere in the PasswordBox popup and click "Inspect Element"
4. In the "Developer Tools" window that opens select the "Console" tab
6. Paste the entire contents of *export2.js* into it and press enter. You can scroll down to see the progress. Wait patiently if you have a lot of passwords. **Don't navigate to a different page or you'll have to start over.**
8. Once all passwords are loaded you will be prompted to save the csv file. Save this somewhere very safe. Encrypt it, do whatever you need to do. Just keep in mind that it has all your passwords and should be treated as highly confidential.

## Replacement Services

Now that PasswordBox is dead, you'll need something to replace it with. Here are some ideas.

### LastPass

An ideal drop-in replacement for PasswordBox. Similar functionality and supports direct import of the output of our *passwordbox-export*.

1. Sign up for your free trial at [cat5.tv/lastpass](https://cat5.tv/lastpass)
2. Enter your LastPass Vault and choose *More Options->Advanced->Import*
3. Choose *Generic CSV File* from the drop down and paste the content of your CSV output
