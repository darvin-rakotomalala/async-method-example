## Spring Boot - @Async Annotation

Dans ce repo, un exemple d'exécution asynchrone dans Spring ou Spring Boot à l'aide de l'annotation `@Async`.
Nous annoterons une méthode d'un bean avec `@Async` qui fera s'exécuter dans un thread séparé, c'est-à-dire l'appel
n'attendra pas la fin de la méthode appelée.
L'annotation `@EnableAsync` active la capacité de Spring à exécuter des méthodes @Async dans un pool de threads
d'arrière-plan.