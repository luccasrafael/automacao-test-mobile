# Lojinha API Automação
Automação de testes Mobile de um software denominado Lojinha. Os sub-tópicos abaixo descrevem algumas decisões tomadas na estruturação do projeto.


## 🛰️ Tecnologias Utilizadas   
- [Java](https://www.oracle.com/br/java/technologies/javase-jdk11-downloads.html)
  
- [JUnit](https://mvnrepository.com/artifact/org.junit.jupiter/junit-jupiter-engine/5.7.1)

- [Appium java-client](https://mvnrepository.com/artifact/io.appium/java-client)
  
- [Appium](https://appium.io/)
  
- [Maven](https://maven.apache.org/)

- [IntelliJ IDEA](https://www.jetbrains.com/idea/)

## 🤖 Testes Automatizados
Testes para validar as partições de equivalência relacionadas ao valor do produto na Lojinha, que estão vinculados diretamente a regra de negócio que diz que o valor do produto deve estar entre R$ 0,01 e R$ 7.000,00.

## 📝 Notas Gerais

- Nesse projeto fazemos uso do JUnit 5, o que nos dá a possibilidade de usar a anotação DisplayName para dar descrições em português para nossos testes



> 👍 Automação desenvolvida durante o Programa de Testes e Qualidade de Software de [Julio de Lima](https://www.juliodelima.com.br)