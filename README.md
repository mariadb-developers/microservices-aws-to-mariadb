# microservices-aws-to-mariadb
How to create lambda functions that integrate with a MariaDB SkySQL Xpand database

# The video for this demo is located at ... https://www.youtube.com/watch?v=sXg10JP6q4U 

# Navigate to this page, which accompanies the demo

https://aws.amazon.com/getting-started/hands-on/build-web-app-s3-lambda-api-gateway-dynamodb/

# Explanation of Files

index.html is the webapp, which can be used in Module 1 - Create a Web App
lambdaPatientMonitor1.py is the python lambda function
patientSchema.sql can be used from a mariadb client, connecting to SkySQL, for creating the database schema
insertHeartData1.sql can be used for a mariadb client, connecting to SkySQL, for inserting IOT records from a heart monitor

For testing, use the following JSON object:

{
  "serialNumber":"777",
  "heartRate":"180"
}

## Helpful Resources <a name="helpful-resources"></a>


## Support and Contribution <a name="support-contribution"></a>

Please feel free to submit PR's, issues or requests to this project project directly.

If you have any other questions, comments, or looking for more information on MariaDB please check out:

* [MariaDB Developer Hub](https://mariadb.com/developers)
* [MariaDB Community Slack](https://r.mariadb.com/join-community-slack)

Or reach out to us diretly via:

* [developers@mariadb.com](mailto:developers@mariadb.com)
* [MariaDB Twitter](https://twitter.com/mariadb)

## License <a name="license"></a>
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=plastic)](https://opensource.org/licenses/MIT)
