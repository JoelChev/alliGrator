# alliGrator
A Java based search engine aggregator that outputs JSON formatted results for Google, Yahoo and Bing queries.

To use this application:
1. Fork the repository
2. Navigate to the target folder of the project on your system.
3. In the terminal or in the command line write the following: (you are in ../target) java -jar alliGrator-0.0.1.jar
4. Through the Spring.io API the Spring Boot will now launch a Server on your machine. Make sure to close this server when
you are done with it!
(Perform the next steps in the order you desire/are able to) :
5. In the terminal (UNIX based systems) write: curl http://localhost8080/search to get the default query output in JSON.
If you would like to see variable query results, write: curl http://localhost8080/search?query=****, where **** is the query
you want to obtain.
6. To see a browser representation of the results, go to http://localhost8080/search (or http://localhost8080/search?query=****)
for a default or variable JSON result output respectively.

Thank you!