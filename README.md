![Cypress JavaScript](/cypress-javascript.png)

# cypress-javascript
[Cypress](https://www.cypress.io/) is an automation web testing tool that's fast, easy, and reliable for testing the things (web components) that run in a browser.
</br>
[JavaScript](https://www.ecma-international.org/publications-and-standards/standards/ecma-262/) is a programming language that conforms to the ECMAScript specification.

## Getting Started
1. Install [NodeJS](https://nodejs.org/en/) LTS
1. Open the root folder using [VS Code](https://code.visualstudio.com/)
   * If you use [GitHub Desktop](https://desktop.github.com/), select the "Open in Visual Studio" button
1. Open the [integrated terminal](https://code.visualstudio.com/docs/editor/integrated-terminal)
1. Run `npm install`

## Run Tests
1. Run `npm run cypress:open`

----

<details>

<summary>Creating the First Test (Historical)</summary>

1. Run `npm init`
   * Hit [Enter] until the project is generated.
1. Run `npm install cypress --save-dev` to install the latest version of Cypress as a dev dependency.
1. Run `npx cypress open`
   * Select "Allow" if prompted
1. Select "Continue"
1. Edit `package.json` to include:
   ```
   {
      "scripts": {
         "cypress:open": "cypress open"
      }
   }
   ```
   * Now you can open Cypress by running `npm run cypress:open`
1. Select "E2E Testing"
1. Select "Continue"
1. Select "Start E2E Testing in Chrome"
1. Select "Create new empty spec"
1. Select "Create spec"
1. Click the "X" to close
1. Open `cypress\e2e\spec.cy.js` and replace the contents with
   ```
   describe('My First Test', () => {
      it('Does not do much!', () => {
         expect(true).to.equal(true)
      })
   })
   ```

</details>
