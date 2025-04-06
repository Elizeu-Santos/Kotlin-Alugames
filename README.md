 <h1>AluGames 🎮</h1>
  <p>
    Este é o projeto da minha <strong>primeira aplicação em Kotlin</strong>, desenvolvido durante o curso da 
    <a href="https://www.alura.com.br/" target="_blank">Alura</a>.
    A aplicação foi construída com o objetivo de praticar os conceitos de Kotlin e entender o funcionamento de uma
    aplicação orientada a objetos com uso de listas, leitura de arquivos e consumo de APIs.
  </p>

  <hr>

  <h2>📋 Índice</h2>
  <ul>
    <li><a href="#sobre">Sobre o Projeto</a></li>
    <li><a href="#tecnologias">Tecnologias Utilizadas</a></li>
    <li><a href="#estrutura">Estrutura do Projeto</a></li>
    <li><a href="#pre-requisitos">Pré-requisitos</a></li>
    <li><a href="#execucao">Passo a Passo para Executar</a></li>
    <li><a href="#testes">Executar os Testes</a></li>
    <li><a href="#autor">Autor</a></li>
  </ul>

  <hr>

  <h2 id="sobre">📦 Sobre o Projeto</h2>
  <p>
    O <code>AluGames</code> é uma aplicação de linha de comando que simula o gerenciamento de jogos com base em dados fornecidos via arquivos ou APIs.
    O projeto tem como foco o aprendizado prático de Kotlin, explorando desde os fundamentos da linguagem até o uso de bibliotecas como o Gson para manipulação de JSON.
  </p>

  <hr>

  <h2 id="tecnologias">🚀 Tecnologias Utilizadas</h2>
  <ul>
    <li><a href="https://kotlinlang.org/" target="_blank">Kotlin</a></li>
    <li><a href="https://maven.apache.org/" target="_blank">Maven</a></li>
    <li><a href="https://junit.org/junit5/" target="_blank">JUnit 5</a></li>
    <li><a href="https://github.com/google/gson" target="_blank">Gson</a></li>
  </ul>

  <hr>

  <h2 id="estrutura">⚙️ Estrutura do Projeto</h2>
  <pre><code>
AluGames/
├── src/
│   ├── main/
│   │   └── kotlin/        # Código-fonte
│   └── test/
│       └── kotlin/        # Testes automatizados
├── pom.xml                # Configurações do Maven
└── .gitignore             # Arquivos ignorados pelo Git
  </code></pre>

  <hr>

  <h2 id="pre-requisitos">📋 Pré-requisitos</h2>
  <p>Antes de rodar o projeto, é necessário ter as seguintes ferramentas instaladas:</p>
  <ul>
    <li><a href="https://www.oracle.com/java/technologies/javase-jdk11-downloads.html" target="_blank">Java JDK 11+</a></li>
    <li><a href="https://maven.apache.org/install.html" target="_blank">Apache Maven</a></li>
    <li><a href="https://git-scm.com/" target="_blank">Git</a></li>
  </ul>

  <p><strong>Dica:</strong> Verifique se estão instalados com os comandos:</p>
  <pre><code>java -version
mvn -v</code></pre>

  <hr>

  <h2 id="execucao">🧭 Passo a Passo para Executar</h2>
  <ol>
    <li>
      <strong>Clone o repositório</strong>
      <pre><code>git clone https://github.com/seu-usuario/AluGames.git
cd AluGames</code></pre>
    </li>
    <li>
      <strong>Compile o projeto</strong>
      <pre><code>mvn clean compile</code></pre>
    </li>
    <li>
      <strong>Execute a aplicação</strong>
      <pre><code>mvn exec:java</code></pre>
    </li>
  </ol>

  <hr>

  <h2 id="testes">🧪 Executar os Testes</h2>
  <p>Para rodar os testes automatizados com JUnit 5:</p>
  <pre><code>mvn test</code></pre>

  <hr>

  <h2 id="autor">✍️ Autor</h2>
  <p>Desenvolvido por <strong>Elizeu Santos</strong> como parte do curso da <a href="https://www.alura.com.br/" target="_blank">Alura</a>.</p>

  <p>Entre em contato:</p>
  <ul>
    <li><a href="https://www.linkedin.com/in/elizeusantoss/" target="_blank">LinkedIn</a></li>
  </ul>

  <hr>

  <p><em>📝 Este projeto é educacional e foi desenvolvido como parte da minha jornada de aprendizado em Kotlin.</em></p>

</body>
</html>
