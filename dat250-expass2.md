## Software Technology Experiment Assignment 2

The first few points in the installation went quite smoothly, but I encountered some problems with Derby however. I especially had some difficulties with the following error:  
>Exception in thread "main" javax.persistence.PersistenceException: No Persistence provider for EntityManager named todo
>at javax.persistence.Persistence.createEntityManagerFactory(Persistence.java:84)
>at javax.persistence.Persistence.createEntityManagerFactory(Persistence.java:54)
>at de.vogella.jpa.simple.main.Main.main(Main.java:17)
 
The problem got solved after downloading the maven repository and going from there. Here is the code from Experiement 2:
https://github.com/jonashaneborg/EXP2

Here is a screenshot of the database tables that were created after doing Experiement 2:  
https://imgur.com/a/4yooYYO
