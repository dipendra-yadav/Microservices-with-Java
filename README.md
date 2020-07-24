# Microservices-with-Java
Microservices with Java




Lets discuss what is a Microservice first? and what is this new fuss about Microservices.

Monothilic application vs Microservice

In a monolithic architecture, an application is delivered as a single deployable artifact. All the(user interface), business,and database access logic are packaged together into a as single application artifact(JAR/WAR) and deployed to an application server.

when multiple development teams working on the application,each team have their application(part) they are working on, some might be working on UI team, some might be working on dataware house team,few can be working on integration, This makes the monotlithic applications force multiple development teams to sync their delivery because their code needs to be build/test/deployed as a entire unit.

The problem rises even more when the size and complexity of such molotithic applications grow vs the communications & cordination costs of teams. (we know how communication happens right :))as not everthing scales up accordingly hence a small change of code leades to build/test/deploy the entire application.

so the concept of microservice came in response to solve the challenges of trying to scale both technically and organizationally large, monolithic applications.Therefore, a microservice is a small, loosely coupled, distributed service. Microservices allow you to take a large application and decompose it into easy-to manage components with very well thought-out defined responsibilities.
