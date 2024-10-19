# Automation_Testing

1. Set Git credentials
   
   ```bash
   git config --global user.name "ajoejoseph"
   ```
   ```bash
   git config --global user.email "ajoejoseph99@gmail.com"
   ```
   
2. Confirm Credentials
   
    ```bash
     git config --list
     ```
3. Create a workspace folder in your documents folder
     ```bash
     Automation Testing Workshop
     ```
     
4. Open terminal inside VSCode
    ```bash
    npm init -y
    ```
     ```bash
     npm init wdio
     ```
     ```bash
     npm install
     ```
     --run this command only if it was not run by the script already!

   Optionals
   ```bash
   npm install @wdio/spec-reporter --save-dev
   ```

   Add the spec reporter under the reporters section:
   ```bash
   reporters: ['spec'],
   ```
        
5. Open the package.json file
   
    ```bash
      "wdio": "wdio run ./wdio.conf.js"
     ```
    Add this line under the "scripts" section right under the "tests"

6. For on prepare hookerror:

   ```bash
   npm install typescript@latest ts-node@latest
   ```
