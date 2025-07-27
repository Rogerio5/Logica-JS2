# Logica-JS2

# <body>
  <h1>Resolução dos Desafios do Curso de Lógica de Programação 💡</h1>

  <p>Praticar a lógica de programação, incluindo conceitos como <strong>variáveis</strong>, <strong>condicionais (if-else)</strong>, <strong>loops (while)</strong> e <strong>interações com o usuário (alert, prompt)</strong>, é essencial para sua carreira de desenvolvimento de software.</p>
  <p>Esses fundamentos fornecem a base para <em>resolver problemas de forma estruturada</em>, <em>tomar decisões no código</em>, <em>criar iterações controladas</em> e <em>interagir eficazmente com os usuários</em>.</p>
  <p>Compreender esses conceitos não apenas facilita o aprendizado de novas linguagens e tecnologias, mas também capacita você a <strong>criar soluções inovadoras</strong>, <strong>depurar eficientemente</strong> e <strong>manter a qualidade</strong> ao longo do ciclo de vida do software.</p>
  <p>Portanto, investir tempo nesses princípios desde cedo é fundamental para <strong>construir uma base sólida e bem-sucedida</strong> no campo da programação.</p>

<body>

  <h1>Desafios com Loop While</h1>

  <div class="desafio">
    <h2>Desafio 1 — Contador de 1 até 10</h2>
    <div class="enunciado">Crie um contador que comece em 1 e vá até 10 usando um loop while. Mostre cada número.</div>
    <pre>
function contadorUmAteDez() {
  let contador = 1;
  while (contador <= 10) {
    console.log(contador);
    contador++;
  }
}
    </pre>
    <div class="resposta">🟢 Exemplo de resposta: O console exibirá os números de 1 a 10, um por linha.</div>
  </div>

  <div class="desafio">
    <h2>Desafio 2 — Contador de 10 até 0</h2>
    <div class="enunciado">Crie um contador que começa em 10 e vá até 0 usando um loop while. Mostre cada número.</div>
    <pre>
function contadorDezAteZero() {
  let contador = 10;
  while (contador >= 0) {
    console.log(contador);
    contador--;
  }
}
    </pre>
    <div class="resposta">🟢 Exemplo de resposta: O console exibirá os números de 10 até 0, um por linha.</div>
  </div>

  <div class="desafio">
    <h2>Desafio 3 — Contagem regressiva personalizada</h2>
    <div class="enunciado">Crie um programa de contagem regressiva. Peça um número e conte deste número até 0, usando um loop while no console do navegador.</div>
    <pre>
function contagemRegressiva() {
  let numero = parseInt(prompt("Digite um número para a contagem regressiva:"));
  while (numero >= 0) {
    console.log(numero);
    numero--;
  }
}
    </pre>
    <div class="resposta">🟢 Exemplo de resposta: Se o usuário digitar "5", o console exibirá: 5, 4, 3, 2, 1, 0.</div>
  </div>

  <div class="desafio">
    <h2>Desafio 4 — Contagem progressiva personalizada</h2>
    <div class="enunciado">Crie um programa de contagem progressiva. Peça um número e conte de 0 até esse número, usando um loop while no console do navegador.</div>
    <pre>
function contagemProgressiva() {
  let numero = parseInt(prompt("Digite um número para a contagem progressiva:"));
  let contador = 0;
  while (contador <= numero) {
    console.log(contador);
    contador++;
  }
}
    </pre>
    <div class="resposta">🟢 Exemplo de resposta: Se o usuário digitar "5", o console exibirá: 0, 1, 2, 3, 4, 5.</div>
  </div>

</body>
</html>


