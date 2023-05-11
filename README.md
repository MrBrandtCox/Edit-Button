# Edit-Button

## `Description`
_Edit-Button_ is a text editor that runs in the browser with the capability of functioning offline as well. </br>
* This application is deployed using [Heroku](https://www.heroku.com/).
</br></br>

## `User Story`
**AS A** developer </br>
**I WANT** to create notes or code snippets with or without an internet connection </br>
**SO THAT** I can reliably retrieve them for later use.
</br></br>

## `Acceptance Criteria`
**GIVEN** a text editor web application, </br>

1. **WHEN** I open my application in my editor
    - **THEN** I should see a client server folder structure.
2. **WHEN** I run `npm run start` from the root directory
    - **THEN** I find that my application should start up the backend and serve the client.
3. **WHEN** I run the text editor application from my terminal
    - **THEN** I find that my JavaScript files have been bundled using webpack.
4. **WHEN** I run my webpack plugins
    - **THEN** I find that I have a generated HTML file, service worker, and a manifest file.
5. **WHEN** I use next-gen JavaScript in my application
    - **THEN** I find that the text editor still functions in the browser without errors.
6. **WHEN** I open the text editor
    - **THEN** I find that IndexedDB has immediately created a database storage.
7. **WHEN** I enter content and subsequently click off of the DOM window
    - **THEN** I find that the content in the text editor has been saved with IndexedDB.
8. **WHEN** I reopen the text editor after closing it
    - **THEN** I find that the content in the text editor has been retrieved from our IndexedDB.
9. **WHEN** I click on the Install button
    - **THEN** I download my web application as an icon on my desktop.
10. **WHEN** I load my web application
    - **THEN** I should have a registered service worker using workbox.
11. **WHEN** I register a service worker
    - **THEN** I should have my static assets pre cached upon loading along with subsequent pages and static assets.
12. **WHEN** I deploy to Heroku
    - **THEN** I should have proper build scripts for a webpack application.
</br></br>

## `Mock-up`
[Edit-Button Mock-up](/Users/brandtcox/Desktop/Edit-Button/Develop/client/src/images/editbutton1.png)
[](/Users/brandtcox/Desktop/Edit-Button/Develop/client/src/images/editbutton2.png)
[](/Users/brandtcox/Desktop/Edit-Button/Develop/client/src/images/editbutton3.png)

## `Deployed Application`
[Edit-Button]()
## `License`
[MIT](https://github.com/MrBrandtCox/Edit-Button/blob/main/LICENSE)


