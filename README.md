# serverless-example

You can try the serverless chamaileon email editor plugin with the `serverless-editor-demo.html` file, provided in this repository.

In the demo application please copy yor API key to get an accessToken, then you can initialize Chamaileon SDK and open and use the email editor.

## Installation

### Remote host
Please upload the demo html to your server. Please note that your API access is limited to domains specified in your environment in order to ensure the authorized usage.


### Local comupter
To use the demo application from your local computer, you need to run the html file from the `localhost`, e. g. with a [static-server](https://www.npmjs.com/package/static-server). Please, use ports given in your environment, if not specified, use the default port 50511.

```console
$ npm -g install static-server
$ static-server -p 50511 -i serverless-editor-demo.html
```

