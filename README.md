# slack-auth

`<slack-auth>` Polymer element for authenticating with Slack RTM API

[API Docs and Demo](https://heka-house-slack-demo.firebaseapp.com/auth)

[Source](http://github.com/hekahouse/slack-auth/)

## Install

    bower install --save HekaHouse/slack-auth

## Example
    <slack-auth
      path="DISPLAY-ROUTE"
      team="SLACK-TEAM"
      callback="OAUTH-CALLBACK-URL"
      client-id-path="PATH-TO-ID-ON-FIREBASE"
      client-secret-path="PATH-TO-SECRET-ON-FIREBASE"></slack-auth>

In the above example replace:

DISPLAY-ROUTE - the route used to display this element

SLACK-TEAM - the team you want to connect to

OAUTH-CALLBACK-URL - the OAuth callback you configured for your Slack app (should be full URL of DISPLAY-ROUTE)

PATH-TO-ID-ON-FIREBASE - the Firebase path to Slack client id

PATH-TO-SECRET-ON-FIREBASE - the Firebase path to Slack client secret

## Note

Make sure you have appropriate Firebase rules and authentication set for Slack client id and secret

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

slack-auth depends only on Google polymer components, they include:

[firebase-element](https://github.com/GoogleWebComponents/firebase-element)

[app-route](https://github.com/PolymerElements/app-route)

[iron-signals](https://github.com/PolymerElements/iron-signals)

[iron-ajax](https://github.com/PolymerElements/iron-ajax)

## Related
