1. Install depndencies using composer
2. To run the test please change USERNAME, BROWSERSTACK_KEY, BROWSER_NAME, BROWSER_VERSION, OS, OS_VERSION in features/bootstrap/FeatureContext.php
3. To run test through tunnel please start the BrowserStackTunnel.jar and specify the value tunnel parameter in behat.yml as true
3. To run this sample test please run following command in root folder of this repository: 
```
./bin/behat --config=behat.yml
```
