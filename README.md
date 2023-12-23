# JenkinsQA_JS_07

**How to start working in our project?**

1. Clone repository to your machine.

2. Navigate to project root folder.

3. Run command ```npm ci``` in terminal VScode.

4. Copy and paste the file ```cypress.env.json.example``` to project root folder. Сhange the file name to ```cypress.env.json```. Put your own credentials for login in json file.

5. After, execute ```npx cypress open```  to run tests.

**Project Coding Convention**

Naming conventions:
We shall use Camelcase for naming conventions: ```camelCase```

Spec names:
student should create the spec containing the name of the userstory (US): ```header.cy.js``` 


**Spec structure:**

- Each block ```describe``` should contain the name of spec file
- Each test (```it```) should contain name of test case (```AT```) 

example:
describe('Header', () => {

    it('Verify logo jenkins is visible on the header', function () {
        ...
    })

    it('Verify logo jenkins is clickable and redirects to homePage', function () {
        ...
    })
})

**Attention!**

Students are not allowed to install any libraries, plugins, etc. to avoid changing configuration files. 

**!!Do not push changed files as:**

```package.json```
```package.lock.json```
```cypress.config.js```
```e2e.js```
```ci.yml```
```cancel.yml```
```globalHooks.js```
```cleanData.js```
