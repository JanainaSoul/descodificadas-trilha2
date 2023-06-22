

## Tecnologias utilizadas durante o curso
* JavaScript

## Tecnologias utilizadas no projeto
* HTML
* CSS


## Conteúdo
Orientações para a apresentação
Quando iniciamos a Trilha 2, você já tinha um site em HTML, CSS e um pouco de JavaScript, com os requisitos a seguir:

Logotipo
Menu
Título destacado sobre o assunto do site com imagem do fundo
Trecho de texto com plano de fundo colorido
Botão com link interno ou externo
Imagens com descrições
Vídeo
Mapa de localização
Formulário para coletar cadastro
Rodapé com a frase criado por seunome

Ao longo da Trilha 2, você foi incorporando novas funcionalidades em seu código enquanto aprofundou os conhecimentos em HTML, CSS e JS.

Por isso, para a entrega final do código e a apresentação do seu site aprimorado, você deve ter:

Usado metatags e tags semânticas
Feito menu dropdown ou sidebar
Usado pelo menos um card
Utilizado botões de link interno ou externo com efeitos (transições ou animações)
Adicionado imagens com carrossel
Usado grid e flexbox para posicionamento dos elementos do site
Usado um iframe
Deixado o site responsivo (usando media queries)
Usado o JavaScript para deixar o site interativo (envio de mensagens, execução de alguma tarefa etc.)


Para a apresentação


Tempo de apresentação: 10 minutos


Tópicos da apresentação:

Apresentação pessoal
Falar um pouco sobre o tema do site
Apresentar os itens obrigatórios:
Metatags e tags semânticas
Menu dropdown ou sidebar
Card
Transições ou animações
Carrossel
Grid e flexbox 
Iframe
Responsividade (media queries)
Interatividade

Compartilhar como foi para você incrementar o site e aprofundar os estudos na trilha 2

## Para saber mais:

Para saber mais: lidando com inputs

Durante essa aula lidamos com alguns tipos de input. É importante entender a função deles e de outros existentes:

![image](https://user-images.githubusercontent.com/104031152/223828858-fb8c175f-d1e4-4f9a-85bc-2b791a0a99ac.png)

Além disso, você pode aprender mais sobre lidar com dados do usuário no artigo “Recebendo dados de usuário na Web com inputs - https://www.alura.com.br/artigos/recebendo-dados-usuario-na-web-com-inputs” do instrutor Luan Alves.

Para saber mais: digito verificador

Quando estamos construindo um sistema que requer a criação de contas como o MoniBank, devemos validar os dados em que há essa possibilidade. Usando JavaScript nativamente, sem o uso de bibliotecas, iremos precisar fazer algumas validações manualmente, como a validação do CPF.

Vamos atuar em cima de um CPF base que será: 451.055.040-54. A fórmula do cálculo dos ultimos digitos verificadores de um CPF é dividida em:

Primeiro dígito
Para descobrir o primeiro dígito você precisará recolher os 9 primeiros dígitos do CPF e multiplicar por números de 10 a 2, sequencialmente.

![image](https://user-images.githubusercontent.com/104031152/223851519-97bc729b-5d89-4d1a-9c70-c1ccc049030c.png)

Depois, precisamos somar todos os valores gerados nas multiplicações entre eles. Nesse caso, a soma resultou em 160. Em seguida, será necessário multiplicar essa soma por 10, que gerou o número 1600. Por fim, devemos considerar o módulo da divisão desse número com 11: 5.

Antes de decidirmos que esse é o primeiro dígito verificador, precisamos testar uma condição: Se o resultado for 10 ou 11, precisaremos zera-lo. Como não é o caso, podemos confirmar que 5 realmente é o primeiro dígito verificador do CPF base.

Segundo dígito
Para descobrir o segundo dígito você precisará recolher os 10 primeiros dígitos do CPF e multiplicar por números de 11 a 2, sequencialmente.

![image](https://user-images.githubusercontent.com/104031152/223851635-5e8d4186-5929-41c3-a5a1-4a08861757da.png)

Em seguida, será necessário somar todos os valores resultados pela multiplicação novamente, e essa soma resultou em 194. Depois, multiplicamos essa soma por 10, para encontrar o valor 1940. Ao final, chegamos na etapa de encontrar o módulo da divisão por 11: o número 4.

Novamente, precisamos verificar para caso o resultado for 10 ou 11, será necessário zera-lo. Como novamente não foi o caso, o número 4 realmente é o segundo dígito verificador do CPF base.

Para Saber Mais: localStorage e DOM

Durante o projeto selecionamos elementos do HTML para pegar seus valores, para criar novas validações, para inserir textos, entre outros casos. Para conseguir realizar essas ações, estamos interagindo com o Document Object Model (DOM). Isso é algo que abordamos em vários projetos mas temos um curso em específico pra te ajudar nesse assunto: JavaScript: manipulando o DOM -> https://cursos.alura.com.br/course/javascript-manipulando-dom, não deixe de dar uma passadinha por lá.

Para armazenamento dos dados do formulário foi utilizado o localStorage. O objeto localStorage permite salvar pares de chave/valor no navegador sem data de expiração, ou seja, os dados não são excluídos quando o navegador é fechado e ficam disponíveis para navegação futura. Você pode se aprofundar mais no assunto com o treinamento JavaScript na Web: armazenando dados no navegador do instrutor Pedro Marins -> https://cursos.alura.com.br/course/javascript-web-armazenando-dados-navegador e com o artigo "Armazenadores de dados do navegador" do Luan Alves -> https://www.alura.com.br/artigos/armazenadores-de-dados-do-navegador?utm_source=gnarus&utm_medium=timeline.

## Links
https://www.4devs.com.br/gerador_de_cpf 

https://cursos.alura.com.br/formacao-vuejs3

https://cursos.alura.com.br/dashboard

https://cursos.alura.com.br/formacao-svelte

https://cursos.alura.com.br/formacao-react-javascript 

