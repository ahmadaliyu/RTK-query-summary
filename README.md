# TABLE OF CONTENT

#### Prerequisites [redux-toolkit](https://redux-toolkit.js.org/introduction/getting-started) and [understanding of redux concept and terms](https://redux.js.org/tutorials/fundamentals/part-2-concepts-data-flow)

### [What is rtk query](https://github.com/goodmanfreeman/RTK-query-summary/README.md#what-is-rtk-query-1)
### [Setting up the store](https://github.com/goodmanfreeman/RTK-query-summary/README.md#setting-up-the-store-1)
### [createApi](https://github.com/goodmanfreeman/RTK-query-summary/README.md#create-api)
### [Conclusion](https://github.com/goodmanfreeman/RTK-query-summary/README.md#conclusion)



## What is rtk query
RTK Query is an advanced data fetching and caching tool, designed to simplify common cases for loading data in a web application. It stands for redux toolkit query, it simplifies and take care of all logics that you don't need to write all in one go in simple steps.
## Setting up the store
## 1 The store
## ![setting-up-store](https://user-images.githubusercontent.com/32324434/161045348-2afa18db-97be-4f19-9e74-9f3379c726df.png)
 ## 2 The api service
## ![api-service](https://user-images.githubusercontent.com/32324434/161045485-4e3a427e-d1f5-4e92-abd0-1178d3d6763d.png)
  Wrap your app in a Provider
## Create Api
The createApi in rtk query exposes methods like the reducerPath, baseQuery having the fetchBaseQuery method where you define your base url, the endpoints for your endpoints definitions that has the query method that returns a string which will be appended to the baseUrl in your fetchBaseQuery, it also has headers and prepareHeaders to set your header params for authention and authorisation.
Importing create api from @reduxjs/toolkit/query/react means hooks will be auto-generated for you to use in your components
## Conclusion
Use your hooks in your component like this
## ![component](https://user-images.githubusercontent.com/32324434/161047875-7c8837bd-ac8f-4e78-8cd3-5aa64462fdff.png)

