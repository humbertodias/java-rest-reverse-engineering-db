# java-rest-reverse-engineering-db



# MySQL

    docker run -d -p 3306:3306 -e MYSQL_ALLOW_EMPTY_PASSWORD=yes -e MYSQL_ROOT_HOST=% percona/percona-server:5.7
    
    
# Entities

    mvn compile exec:java -Dexec.cleanupDaemonThreads=false