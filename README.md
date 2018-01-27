# sudodj
A visual DJ for concerts

## How To Use
1. In the Overview section of the Firebase console, click 'Add Firebase to your web app' and replace the contents of the file `src/main/webapp/WEB-INF/view/firebase_config.jspf` with that code snippet.
2. Ensure that the following environmental variables are defined:
  * `GOOGLE_CLOUD_SDK_HOME` points to the Google Cloud SDK
  * `GOOGLE_APPLICATION_CREDENTIALS` points to a service account key JSON file
3. Deploy:
```sh
mvn appengine:run # to run a local server
mvn appengine:deploy # to deploy to GAE
```
