# Capone

# Tech Stack
* Facebook App
* Facebook webhook
    - Webhooks are user defined HTTP callbacks.  They are usually triggered by some event.  When that event 
        occurs, the source site makes an HTTP request to the URL configured for the webhook.  Since they use
        HTTP, they can be integrated into web services without adding additional new infrastructure.
* Facebook Messenger
* Heroku
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

