# chalenge


<b>Requirements</b>:
<p>
It should be any app

It connect to translink API

Bus location should be rendered into Maps

Bus location should be live and updating continuously

App should be functional 

Should be well documented
</p>


<b>Addressing the solution:</b>

Lint code with StandardJS. Standard provides a standard JS style and helps to enforce it.

Unit Test code with Jest. Snapshot testing for components should be fine.

Enable modern JS with a pre-configured environment for our purposes. Create-React-App should work fine. Additionally, it includes Jest and React configuration, and bundling of production builds. As well , it provides several pathways for deployment.

I'll use fetch for network calls rather than superagent to reduce dependencies.

I'll use Redux to manage the app's state. Although we could persist the redux store with the service worker bundled in by Create-react-app,i will skip it for this app.

I'll use Redux-Saga to help implement live and continuous updates of bus locations

I'll use react-map-gl for mapping(and map box instead of google map since it’s better for interactivity.It have been used by Uber and have a cheaper option for API calls)



<b>Test Cases:</b>
 The user should see the map

The map should show bus locations

The bus location should be live and continuous updated


<b>My Approach:</b>

  <p>1.Setup Development environment
create-React-App

Linter

Jest

Redux

Redux-saga

React-map-gl
</p>

2.Implement a map

3.Connect to the API

4.Transform responses into the format required

5.Render it onto the map

6.Implement continuous updating of bus locations.

