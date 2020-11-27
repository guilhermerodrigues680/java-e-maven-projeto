# Projeto Java com Maven

---

### Artigos

Artigo sobre java e maven:

[mkyong.com/maven/how-to-create-a-java-project-with-maven](https://mkyong.com/maven/how-to-create-a-java-project-with-maven/)

[giuliana-bezerra.medium.com/gerenciando-dependencias-com-o-mavem-em-projetos-java-6703fce91fb6](https://giuliana-bezerra.medium.com/gerenciando-dependencias-com-o-mavem-em-projetos-java-6703fce91fb6)

Como pular teste do maven:

[stackoverflow.com/a/19838914](https://stackoverflow.com/a/19838914)

---

### Download do maven

Site oficial: [https://maven.apache.org/](https://maven.apache.org/)

**Mac:** *apache-maven-3.6.3-bin.tar.gz*
**Windows:** *apache-maven-3.6.3-bin.zip*

```sh
tar -xzf apache-maven-3.6.3-bin.tar.gz
```

### Gerando FAT JAR

```sh
./mvnw clean package
java -jar target/projeto-1.0-SNAPSHOT.jar
```

---
