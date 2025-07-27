# Logica-JS2

# <body>
  <h1>Resolução dos Desafios do Curso de Lógica de Programação 💡</h1>

  <p>Praticar a lógica de programação, incluindo conceitos como <strong>variáveis</strong>, <strong>condicionais (if-else)</strong>, <strong>loops (while)</strong> e <strong>interações com o usuário (alert, prompt)</strong>, é essencial para sua carreira de desenvolvimento de software.</p>
  <p>Esses fundamentos fornecem a base para <em>resolver problemas de forma estruturada</em>, <em>tomar decisões no código</em>, <em>criar iterações controladas</em> e <em>interagir eficazmente com os usuários</em>.</p>
  <p>Compreender esses conceitos não apenas facilita o aprendizado de novas linguagens e tecnologias, mas também capacita você a <strong>criar soluções inovadoras</strong>, <strong>depurar eficientemente</strong> e <strong>manter a qualidade</strong> ao longo do ciclo de vida do software.</p>
  <p>Portanto, investir tempo nesses princípios desde cedo é fundamental para <strong>construir uma base sólida e bem-sucedida</strong> no campo da programação.</p>

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Desafios com While</title>
</head>
<body>
  <h1>Desafios com Loop While</h1>

  <h2>1️⃣ Contador de 1 até 10</h2>
  <button onclick="contadorUmAteDez()">Iniciar</button>

  <h2>2️⃣ Contador de 10 até 0</h2>
  <button onclick="contadorDezAteZero()">Iniciar</button>

  <h2>3️⃣ Contagem regressiva personalizada</h2>
  <button onclick="contagemRegressiva()">Iniciar</button>

  <h2>4️⃣ Contagem progressiva personalizada</h2>
  <button onclick="contagemProgressiva()">Iniciar</button>

  <script>
    function contadorUmAteDez() {
      let contador = 1;
      while (contador <= 10) {
        console.log(contador);
        contador++;
      }
    }

    function contadorDezAteZero() {
      let contador = 10;
      while (contador >= 0) {
        console.log(contador);
        contador--;
      }
    }

    function contagemRegressiva() {
      let numero = parseInt(prompt("Digite um número para a contagem regressiva:"));
      while (numero >= 0) {
        console.log(numero);
        numero--;
      }
    }

    function contagemProgressiva() {
      let numero = parseInt(prompt("Digite um número para a contagem progressiva:"));
      let contador = 0;
      while (contador <= numero) {
        console.log(contador);
        contador++;
      }
    }
  </script>
</body>
</html>
