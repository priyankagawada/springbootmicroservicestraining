To access properties from spring cloud configuration server application
------------------------------------------------------------------------------------------------
1. Create a folder named config and a sub folder in it named native
   config --> native

2. Create a folder named currency-conversion-service inside native folder and copy all application.properties files from the project into this folder

\SpringClouMicroservicesJuly21\config\native\currency-conversion-service
    - application.properties
    - application-dev.properties
    - application-test.properties

3. Test accessing properties from native - 

http://localhost:8888/currency-conversion-service/default
http://localhost:8888/currency-conversion-service/dev