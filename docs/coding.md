# Frontend Technical Documentation
The web application can be mainly be divided into two sides: frontend or also known as client-side application, an application that runs inside the browser of the user, backend or also known as server-side application, an application that is connected with a database and provides apis for frontend in order to retrieve data or post data to. This documentation only contains information for frontend as this is made by frontend developer.

## Frontend Pages
All pages for the website can be found under `/pages` folder. As Nextjs is a dynamic framework, all page url will be named automatically based on the folder name or the Js filename. </br>
Other page components such as Navbar or layout can be found under `/components` folder. These components are used by the files in `/pages`

## State
All state information such as userId, cart, etc. are stored in the localStorage. The `store.js` file under `src` folder stores all state's information as well as the logic to update state.

## Component styling
This website is using material-ui v4. See [docs](https://v4.mui.com/getting-started/installation/). Please note that changing to mui-v5 might cause some styling errors as Nextjs prerenders all pages in default in advance instead of doing all in the client side, that is why the style components get conflicted if using mui v5. At the moment, this issue is not fixed yet, therefore, mui v4 was used instead.

