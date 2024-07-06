# Jogo de Adivinhar o Número Secreto

<p>Este projeto é um jogo interativo do Número Secreto, onde o objetivo do jogador é adivinhar um número secreto gerado aleatoriamente. O jogo é enriquecido com a funcionalidade de um assistente de voz que orienta o jogador, fornecendo dicas e feedback em tempo real através de comandos de voz. Este projeto é construído utilizando HTML, CSS e JavaScript.</p>

## Funcionalidades Principais
<ul>
  <li>
    <strong>Geração de Número Secreto:</strong>
    <ul>
      <li>O jogo gera um número secreto aleatório dentro de um intervalo especificado (por exemplo, de 1 a 10).</li>
    </ul>
  </li>
  <li>
    <strong>Interação com o Jogador:</strong>
    <ul>
      <li>O jogador insere suas tentativas de adivinhar o número através de um campo de input.</li>
      <li>O assistente de voz confirma a tentativa do jogador e fornece feedback, indicando se o número secreto é maior ou menor que a tentativa atual.</li>
    </ul>
  </li>
  <li>
    <strong>Assistente de Voz:</strong>
    <ul>
      <li>Utiliza a Web Speech API para reconhecimento e síntese de voz.</li>
      <li>O assistente de voz oferece instruções iniciais ao jogador.</li>
      <li>Responde às tentativas do jogador com dicas (ex.: "Tente um número maior" ou "Tente um número menor").</li>
      <li>Anuncia quando o jogador adivinha o número correto e congratula-o.</li>
    </ul>
  </li>
  <li>
    <strong>Interface do Usuário:</strong>
    <ul>
      <li>Uma interface de usuário intuitiva e responsiva construída com HTML e CSS.</li>
      <li>Elementos visuais atraentes que indicam o progresso do jogador, como um contador de tentativas e um histórico de palpites.</li>
      <li>Feedback visual para complementar o feedback auditivo fornecido pelo assistente de voz.</li>
    </ul>
  </li>
</ul>

## Tecnologias Utilizadas
<ul>
  <li>
    <strong>HTML:</strong>
    <ul>
      <li>Estruturação da página do jogo, incluindo o campo de input para tentativas, botões de controle e áreas de feedback.</li>
    </ul>
  </li>
  <li>
    <strong>CSS:</strong>
    <ul>
      <li>Estilização da interface do jogo para torná-la visualmente atraente e responsiva.</li>
      <li>Utilização de flexbox e grid para layout, cores vibrantes e animações leves para feedback visual.</li>
    </ul>
  </li>
  <li>
    <strong>JavaScript:</strong>
    <ul>
      <li>Lógica do jogo, incluindo a geração de números aleatórios, verificação de tentativas do jogador e controle do fluxo do jogo.</li>
      <li>Implementação da Web Speech API para reconhecimento de voz e síntese de voz do assistente.</li>
      <li>Manipulação do DOM para atualizar a interface do usuário com feedback em tempo real.</li>
    </ul>
  </li>
</ul>

## Fluxo do Jogo
<ol>
  <li>O jogador acessa a página do jogo e é saudado pelo assistente de voz, que explica as regras.</li>
  <li>O jogador faz sua primeira tentativa inserindo um número no campo de input e clicando no botão "Enviar" ou dizendo o número.</li>
  <li>O assistente de voz confirma a tentativa e dá feedback auditivo e visual, sugerindo se o número secreto é maior ou menor.</li>
  <li>O jogador continua a adivinhar até acertar o número secreto.</li>
  <li>Quando o jogador acerta, o assistente de voz parabeniza-o e oferece a opção de jogar novamente.</li>
</ol>

## Conclusão
<p>Este projeto foi realizado em conjunto a Alura e combina a lógica interativa de um jogo clássico com a inovação de um assistente de voz, proporcionando uma experiência de usuário única e envolvente. Utilizando HTML, CSS e JavaScript, o jogo é acessível e divertido, incentivando a prática de habilidades de programação e design web.</p>

<p><a href="https://jogo-numero-secreto-taupe-seven.vercel.app/">Acesse o Jogo</a></p>
