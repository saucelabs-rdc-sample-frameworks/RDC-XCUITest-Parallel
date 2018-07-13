## RDC-XCUITest-Parallel

>This code is presented as an example only, since your tests and testing environments may require specialized scripting. This information should be taken only as an
>illustration of how one would set up tests with Sauce Labs, and any modifications will not be supported. For questions regarding Sauce Labs integration, please see 
>our documentation at https://wiki.saucelabs.com/.

### Environment Setup

1. Global Dependencies
    * Make sure you have Java 8 installed on your local machine.

2. Project Dependencies
	* Download the latest version of the Sauce Labs Runner [here](https://wiki.saucelabs.com/display/DOCS/Using+XCUITest+for+Real+Device+Testing)
	* Add the runner file to the RDC-XCUITest-Parallel directory. 
	* Ensure your Sauce Labs Real Device account has access to the devices specified in the config.yml file. 

3.  Real Device Application Credential
    * Export your application API key to authenticate to the Sauce Labs Real Device Cloud
    ```
    $ export SAUCE_RDC_API_KEY=<your_api_key>
    ```
    
### Running Tests
```
$ ./runner.sh
```

### Resources

##### [Sauce Labs Documentation](https://wiki.saucelabs.com/)

##### [Stack Overflow](http://stackoverflow.com/)
* A great resource to search for issues not explicitly covered by documentation.