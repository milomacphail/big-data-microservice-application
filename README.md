Jethro is a Java-based application to read big data files and upload them to a cloud-based database.

The MVP version takes a static, locally-hosted file and shares the data on a PostgreSQL database. The sample file is of over 6 million financial records.

Construction
The system contains an authorization service, Zuul gateway, Eureka discovery server and. The user only interacts directly with either the authorization service which then connects directly to the job running. The data pull is then visible in a highly customizable database.


Links

Data Server: https://github.com/milomacphail/jethro-batch-reader

Auth/Gateway: https://github.com/milomacphail/jethro-discovery-server
