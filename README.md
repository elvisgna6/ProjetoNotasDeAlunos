# ProjetoNotasDeAlunos
Visão geral do projeto
Você está desenvolvendo um aplicativo de Notas de Alunos que automatiza o cálculo das notas atuais de cada aluno de uma classe. 
Os parâmetros do aplicativo são os seguintes:

Você recebe uma pequena lista de quatro alunos com as notas das cinco tarefas que eles realizaram.
Cada nota é expressa como um valor inteiro de 0 a 100, em que 100 representa 100% de acerto.
A pontuação final é calculada pela média das cinco notas de tarefas.
O aplicativo precisa executar operações matemáticas básicas para calcular as notas finais de cada aluno.
Seu aplicativo precisa gerar como resultado/exibir o nome e a pontuação final de cada aluno.
Atualmente, o livro de notas dos professores mostra as tarefas avaliadas de cada aluno da seguinte maneira:

Sophia: 93, 87, 98, 95, 100

Nicolas: 80, 83, 82, 88, 85

Zahirah:   84, 96, 73, 85, 79

Jeong:  90, 92, 98, 100, 97

O professor exige que as notas calculadas de cada aluno sejam exibidas da seguinte maneira:

Student     Grade
Sophia      94.6  A
Nicolas     83.6  B
Zahirah     83.4  B
Jeong       95.4  A

Instalação
Use as seguintes etapas para se preparar para o desenvolvimento do projeto:

Abra o ambiente de codificação do Editor do .NET.

Copie e cole o código a seguir no Editor do .NET. Esses valores representam as tarefas avaliadas de cada aluno.

//inicializar variáveis - tarefas analisadas
int tarefasAtuais = 5;

int sophia1 = 93;
int sophia2 = 87;
int sophia3 = 98;
int sophia4 = 95;
int sophia5 = 100;

int nicolas1 = 80;
int nicolas2 = 83;
int nicolas3 = 82;
int nicolas4 = 88;
int nicolas5 = 85;

int zahirah1 = 84;
int zahirah2 = 96;
int zahirah3 = 73;
int zahirah4 = 85;
int zahirah5 = 79;

int jeong1 = 90;
int jeong2 = 92;
int jeong3 = 98;
int jeong4 = 100;
int jeong5 = 97;

Calcular a soma das notas de tarefa de cada aluno

você usará as notas de tarefa de cada aluno para calcular a nota atual na classe. 
Para executar esse cálculo, primeiro você somará os valores de notas de tarefa deles e depois calculará a média (nota atual deles). 

Criar variáveis para armazenar a soma

você criará uma variável para cada aluno que representará a soma das notas de tarefa deles. 
Você também exibirá a soma do aluno junto com o nome deles na saída do console. Como as notas de tarefa são representadas como Integers, 
você criará variáveis Integer para armazenar as somas.

Verifique se o Editor do .NET está aberto e se ele tem as variáveis instanciadas com as notas de tarefa de cada aluno.

Na unidade Prepare-se deste módulo de projeto guiado, as instruções de preparação fazem você copiar as notas de tarefa dos alunos para o editor. 
Se necessário, volte e siga as instruções de preparação.

Role para baixo até a parte inferior do código e crie uma linha de código em branco.

Para declarar uma variável Integer para cada aluno que você pode usar para somar as notas deles, insira o seguinte código:
int somarNotasSophia = 0;
int somarNotasNicolas = 0;
int somarNotasZanirah = 0;
int somarNotasJeong = 0;

0 é atribuído às variáveis como parte da instrução de declaração. Em outras palavras, as variáveis são inicializadas como 0. 
Embora a atribuição de valor não seja necessária ao declarar variáveis, ela pode deixar seu código mais eficiente. 
A próxima etapa é exibir a saída e, como essa saída incluirá uma referência a essas variáveis, elas devem ser inicializadas.

Para criar instruções Console.WriteLine() que exibem o nome do aluno e o valor das notas de tarefa somadas, insira o seguinte código:

Console.WriteLine("Sophia: " + somarNotasSophia);
Console.WriteLine("Nicolas: " + somarNotasNicolas);
Console.WriteLine("Zahirah: " + somarNotasZanirah);
Console.WriteLine("Jeong: " + somarNotasJeong);

Por fim, é interessante exibir a nota geral atual do aluno. Contudo, por enquanto, vamos usar essas instruções Console.WriteLine() 
para exibir o valor dos cálculos de soma. Dessa forma, você pode verificar se o código está funcionando corretamente em cada fase do 
processo de desenvolvimento.

No Editor do .NET, para executar o código, selecione o botão verde Executar.

Você não tem problemas para exibir seus valores inteiros, todos como 0 por enquanto, usando o mesmo método WriteLine() que exibe os literais 
de cadeia de caracteres (nomes de alunos).

O valor numérico atual é recuperado automaticamente referenciando o nome da variável.

Agora que as instruções Console.WriteLine() estão prontas para exibir os resultados, vamos começar a adicionar o código que executa seus cálculos.

 Importante:
Você precisa escrever o código que faz os cálculos em cima do código que exibe a saída.

Localize a linha de código abaixo: int somarNotasSophia = 0;

Você escreverá o código que calcula o valor da soma para cada aluno. Primeiro, você adicionará as notas de tarefa dos alunos e, em seguida, 
atribuirá o valor às variáveis "soma". Vamos começar com Sophia. 

Atualize a linha de código para o seguinte:

int somarNotasSophia = sophia1 + sophia2 + sophia3 + sophia4 + sophia5;

No Editor do .NET, selecione Executar.

Sua saída agora deve mostrar que a soma de Sophia é igual a 473. As outras ainda serão 0. Você adicionará cálculos de soma semelhantes para o 
restante dos alunos.

Começando na linha de código em branco que você acabou de criar, insira o seguinte código:

int somarNotasNicolas = nicolas1 + nicolas2 + nicolas3 + nicolas4 + nicolas5;
int somarNotasZanirah = zahirah1 + zahirah2 + zahirah3 + zahirah4 + zahirah5;
int somarNotasJeong = jeong1 + jeong2 + jeong3 + jeong4 + jeong5;

Verificar seu trabalho
Nesta tarefa, você executará o código e verificará se a saída está correta.

Compare seu código com o seguinte:

//inicializar variáveis - tarefas analisadas
int tarefasAtuais = 5;

int sophia1 = 93;
int sophia2 = 87;
int sophia3 = 98;
int sophia4 = 95;
int sophia5 = 100;

int nicolas1 = 80;
int nicolas2 = 83;
int nicolas3 = 82;
int nicolas4 = 88;
int nicolas5 = 85;

int zahirah1 = 84;
int zahirah2 = 96;
int zahirah3 = 73;
int zahirah4 = 85;
int zahirah5 = 79;

int jeong1 = 90;
int jeong2 = 92;
int jeong3 = 98;
int jeong4 = 100;
int jeong5 = 97;

int somarNotasSophia = sophia1 + sophia2 + sophia3 + sophia4 + sophia5;
int somarNotasNicolas = nicolas1 + nicolas2 + nicolas3 + nicolas4 + nicolas5;
int somarNotasZanirah = zahirah1 + zahirah2 + zahirah3 + zahirah4 + zahirah5;
int somarNotasJeong = jeong1 + jeong2 + jeong3 + jeong4 + jeong5;

Console.WriteLine("Sophia: " + somarNotasSophia);
Console.WriteLine("Nicolas: " + somarNotasNicolas);
Console.WriteLine("Zahirah: " + somarNotasZanirah);
Console.WriteLine("Jeong: " + somarNotasJeong);

No Editor do .NET, selecione Executar.

Examine sua saída e verifique se as somas das notas de tarefa estão corretas:

Output
Sophia: 473
Nicolas: 418
Zahirah: 417
Jeong: 477

Se o código exibir resultados diferentes, você precisará examinar o código para encontrar o erro e fazer atualizações. Execute o código 
novamente para ver se você corrigiu o problema. Continue atualizando e executando o código até que ele produza os resultados esperados.

Calcular a média das pontuações das tarefas do aluno

você calculará e armazenará a média das pontuações das tarefas de cada aluno. Como você sabe o número de tarefas pontuadas de cada aluno, 
a média será calculada dividindo a soma das pontuações das tarefas pelo número de tarefas. Para armazenar as médias, você usará o tipo de 
dados Decimal.

Criar variáveis para armazenar a média
Você criará uma variável para cada aluno que pode ser usada para armazenar a pontuação média de suas tarefas que valem nota.

No Editor do .NET, localize as instruções Console.WriteLine() usadas para exibir as pontuações somadas de cada aluno.

Crie uma linha de código em branco acima das instruções Console.WriteLine().

Na linha de código em branco que você criou, para declarar as variáveis Decimal que serão usadas para as pontuações atuais dos alunos, 
digite o seguinte código:

decimal sophiaScore;
decimal nicolasScore;
decimal zahirahScore;
decimal jeongScore;







