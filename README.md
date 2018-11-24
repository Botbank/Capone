# Capone

# Tech Stack
* Facebook App
* Facebook Graph API 
    - primary way to get data into and out of the Facebook platform.  It is an HTTP based
        API that apps can use to programatically query data, post new stories, manage ads, upload photos,
        and other tasks...
* Facebook webhook
    - Webhooks are user defined HTTP callbacks.  They are usually triggered by some event.  When that event 
        occurs, the source site makes an HTTP request to the URL configured for the webhook.  Since they use
        HTTP, they can be integrated into web services without adding additional new infrastructure.

* Facebook Messenger
    - The Messenger Platform sends events to your webhook to notify your bot when a variety of interactions or      events happen, including when a person sends a message. Webhook events are sent by the Messenger           Platform as POST requests to your webhook.
    - Postback - HTTP POST to the same page that the form is on.  The contents of the form are POSTed back to
        the same URL as the form.  The server then refreshes the same page using the info it has just received.
* Facebook Access Tokens
    - https://developers.facebook.com/docs/facebook-login/access-tokens
* Heroku
    - Procfile - Heroku apps include a Procfile that specifies the commands that are executed by the app’s dynos.  [Procfile](https://devcenter.heroku.com/articles/procfile)
* Dialogflow
* Google Cloud Platform
    * Service Accounts
    - The service account and associated private key are used by Dialogflow for system integration.
    - Service account for Bot-bank app on Heroku: dialogflow-dnfyji@banking-123d5.iam.gserviceaccount.com
* Express
    - routing framework
* Crypto 
    - The `crypto` module provides cryptographic functionality that includes a set of wrappers for OpenSSL's hash, HMAC, cipher, decipher, sign, and verify functions.
* body-parser
    - Returns middleware that only parses json and only looks at requests where the Content-Type header matches the type option. This parser accepts any Unicode encoding of the body and supports automatic inflation of gzip and deflate encodings.  A new body object containing the parsed data is populated on the request object after the middleware (i.e. req.body).
* request
    - Request is designed to be the simplest way possible to make http calls. It supports HTTPS and follows redirects by default.
* uuid
    - generation of RFC4122 UUIDS
* pg
    - Non-blocking PostgreSQL client for Node.js. Pure JavaScript and optional native libpq bindings.
* [ejs](https://ejs.co/)
    - templating language that lets you generate HTML markup with plain JavaScript. 
* passport
    - Passport is Express-compatible authentication middleware for Node.js.  Passport's sole purpose is to authenticate requests, which it does through an extensible set of plugins known as strategies. Passport does not mount routes or assume any particular database schema, which maximizes flexibility and allows application-level decisions to be made by the developer. The API is simple: you provide Passport a request to authenticate, and Passport provides hooks for controlling what occurs when authentication succeeds or fails.
* passport-facebook
    - Passport strategy for authenticating with Facebook using the OAuth 2.0 API.  This module lets you authenticate using Facebook in your Node.js applications. By plugging into Passport, Facebook authentication can be easily and unobtrusively integrated into any application or framework that supports Connect-style middleware, including Express.
* npm express-session
    - 
* 

## app.js
* isEcho - message sent by the same page
