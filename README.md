# AS TÉCNICAS CRIPTOGRÁFICAS, CONCEITOS, USOS E APLICAÇÕES
## Atividades práticas supervisionadas – APS II – Trabalho apresentado como exigência para a avaliação do curso de Ciências da Computação na materia de Introdução a Programação Estruturada da Universidade Paulista sob orientação de professores do semestre.

### Integrantes envolvidos no desenvolvimento da aplicação:
- EMILYN BERTINI
- GABRIEL EDUARDO JOIOSO
- JOÃO VICTOR CAIRES
- PAULO JOSE DE FARIAS
- WELLINGTON JUNIOR CHELES

### Orientador
- Prof. Dr. Karem Daiane Marcomini

### Objetivo
  O objetivo dessa atividade foi desenvolver um algoritimo de criptografia de mensagens utilizando a Programação Estruturada com Python 3.

### Introdução

  Encaminhar uma mensagem de forma segura é uma preocupação que remonta aos primeiros estrategistas que se têm notícia, na Grécia Antiga. Houve época em que soldados tinham mensagens escritas em seu couro cabeludo como estratégia para transpassar uma informação pelas linhas inimigas, bastando chegar ao seu destino e ter sua cabeça raspada. Na Segunda Guerra Mundial, a Alemanha dispunha de um intrincado sistema de informações criptografadas. A base de todo esse sistema era uma máquina eletromecânica conhecida como enigma, capaz de gerar mensagens criptografadas com enorme facilidade. A preocupação com a guarda das informações é à base da criptografia, essencial para o tráfego de informações, especialmente nos dias atuais.

### O que é criptografia?

  Criptografia é a prática de codificar e decodificar dados. Quando os dados são criptografados, é aplicado um algoritmo para codificá-los de modo que eles não tenham mais o formato original e, portanto, não possam ser lidos. Os dados só podem ser decodificados ao formato original com o uso de uma chave de descriptografia específica. As técnicas de codificação constituem uma parte importante da segurança dos dados, pois protegem informações confidenciais de ameaças que incluem exploração por malware e acesso não autorizado por terceiros. A criptografia de dados é uma solução de segurança versátil: pode ser aplicada a um dado específico (como uma senha) ou, mais amplamente, a todos os dados de um arquivo, ou ainda a todos os dados contidos na mídia de armazenamento.
  
  De forma simples, a criptografia é um conjunto de técnicas pensadas para proteger uma informação de modo que apenas emissor e receptor consigam compreendê-la. O protocolo de criptografia pode ser mais ou menos elaborado e técnicas como essas existem desde a antiguidade, com o primeiro sistema de criptografia conhecido tendo surgido no Egito, cerca de 1.900 anos antes de Cristo.
  
  A criptografia tem um apelo especial para assuntos ligados a guerra, mas comerciantes e governantes também podem ver na criptografia uma saída para evitar que pessoas não autorizadas descubram informações sobre suas estratégias, por exemplo. A ideia básica é que este sistema de técnicas cifre uma informação que somente será decifrada por pessoas autorizadas, sem acessos indevidos no caminho.
 
 E entender como a criptografia funciona é simples: o emissor da mensagem utiliza algum protocolo que vai protegê-la, então ela é transmitida até o destinatário, que possui uma chave capaz de “resolver” o problema da criptografia e acessar seu conteúdo.
 
 As técnicas podem variar. Um dos sistemas mais conhecidos de criptografia foi a chamada “Cifra de César”, usada pelo Império Romano para enganar seus inimigos. Ela consistia em escrever frases com o alfabeto normal, mas usando sempre três letras adiante. Ele vigorou por algum tempo, mas perdeu a utilidade após ser “quebrado”.

Com o surgimento dos meios digitais, como rádio, telefone e, posteriormente, a internet, os métodos de criptografia precisaram se tornar mais avançados a fim de serem mais eficazes. A base da criptografia moderna são as chaves, usadas tanto para criptografar quanto para descriptografar um conteúdo.

### A história da criptografia.

A criptografia, ciência de escrever códigos e cifras para comunicação segura, é um dos elementos mais importantes para a criação das criptomoedas e das blockchains modernas. As técnicas criptográficas usadas hoje, no entanto, são resultado de uma longa história de desenvolvimento. Desde os tempos antigos, as pessoas usam criptografia para transmitir informações de maneira segura. A seguir, está a fascinante história da criptografia, que resultou nos métodos avançados e sofisticados usados na criptografia digital moderna.

### As antigas raizes da criptografia.

Sabemos que técnicas primitivas de criptografia existiram nos tempos antigos, e a maioria das civilizações antigas parece ter usado algum nível de criptografia. A substituição de símbolos - a forma mais básica de criptografia- aparece tanto nos antigos escritos egípcios, quanto nos mesopotâmicos. O mais antigo exemplo conhecido desse tipo de criptografia foi encontrado no túmulo de um nobre egípcio chamado Khnumhotep II, que viveu há aproximadamente 3.900 anos.

O objetivo da substituição dos símbolos na inscrição de Knhumhotep, não era ocultar informações, mas sim aperfeiçoar seu apelo linguístico. O exemplo mais antigo conhecido de criptografia sendo usada para proteger informações sensíveis ocorreu por volta de 3.900 anos atrás, quando um escriba da Mesopotâmia empregou a criptografia para esconder uma fórmula de esmalte de cerâmica, usado em tabuletas de argila.

Após a antiguidade, a criptografia foi amplamente usada para proteger informações militares importantes, propósito que serve até hoje. Na cidade-estado grega de Esparta, as mensagens eram encriptadas, sendo escritas em pergaminhos colocados sobre um cilindro de tamanho específico. A mensagem só era decifrada quando colocada dentro de um cilindro de tamanho semelhante pelo destinatário. De forma parecida, sabe-se que espiões da antiga Índia usaram mensagens codificadas já no século II a.C.

Talvez, a criptografia mais avançada do mundo antigo tenha sido desenvolvida pelos romanos. Um exemplo proeminente da criptografia romana, a cifra de César, envolvia a substituição das letras de uma mensagem por outras letras que se encontravam algumas posições abaixo na sequência do alfabeto latino. Conhecendo esse sistema e o número de posições a serem deslocadas, o destinatário poderia decodificar a mensagem ilegível.

### Desenvolvimentos na idade média e no renascimento.

Ao longo da Idade Média, a criptografia tornou-se cada vez mais importante, mas as cifras de substituição, das quais a cifra de César é um exemplo, permaneceram como padrão. A criptoanálise, ciência responsável por quebrar códigos e cifras, começou a alcançar a ainda relativamente recente ciência da criptografia. Al-Kindi, um famoso matemático árabe, desenvolveu por volta de 800 d.C., uma técnica conhecida como análise de frequência, que tornou as cifras de substituição vulneráveis à decodificação. Pela primeira vez, as pessoas que tentavam decifrar mensagens criptografadas tiveram acesso a um método sistemático para fazê-lo, tornando necessário que a criptografia avançasse ainda mais para continuar sendo útil.

Em 1465, Leone Alberti desenvolveu a cifra poli alfabética, que é considerada a solução contra a técnica de análise de frequência de Al-Kindi. Em uma cifra poli alfabética, uma mensagem é codificada usando dois alfabetos distintos. Um é o alfabeto no qual a mensagem original é escrita, enquanto o segundo, é um alfabeto totalmente diferente, no qual a mensagem aparece depois de ser codificada. Combinado com as cifras de substituição tradicionais, as cifras poli alfabéticas aumentaram muito a segurança de informações codificadas. A menos que um leitor soubesse o alfabeto no qual a mensagem foi originalmente escrita, a técnica de análise de frequência não teria qualquer utilidade. 

Novos métodos de codificação da informação também foram desenvolvidos no período da Renascença, incluindo um popular método antigo de codificação binária, desenvolvido em 1623, pelo famoso filósofo e cientista Sir Francis Bacon.

### Avanços nos séculos mais recentes.

A ciência da criptografia continuou a avançar progressivamente ao longo dos séculos. Um grande avanço na criptografia foi descrito, embora talvez nunca construído, por Thomas Jefferson na década de 1790. Sua invenção, conhecida como cipher wheel (roda cifrada), consistia de 36 anéis de letras em rodas móveis que podiam ser usados para obter uma codificação complexa. Esse conceito era tão avançado que serviu como base para a criptografia militar americana até a Segunda Guerra Mundial.

A Segunda Guerra Mundial também viu o exemplo perfeito da criptografia analógica, conhecido como a máquina Enigma. De maneira similar a cipher wheel, esse dispositivo, empregado pelas Potências do Eixo, usava anéis rotativos para codificar uma mensagem, tornando praticamente impossível ler a mensagem sem outra máquina Enigma. A tecnologia da computação foi eventualmente usada para ajudar a quebrar a cifra Enigma, e a decodificação bem-sucedida de mensagens enigma ainda é considerada um elemento crítico da eventual vitória dos Aliados.

###	Criptografia na era da computação.

Com a ascensão dos computadores, a criptografia tornou-se muito mais avançada do que na era analógica. A criptografia matemática de 128 bits, muito mais forte que qualquer cifra antiga ou medieval, agora é o padrão para muitos dispositivos sensíveis e sistemas de computação. Começando em 1990, uma forma inteiramente nova de criptografia, apelidada de criptografia quântica, estava em desenvolvimento por cientistas da computação, que buscavam, mais uma vez, elevar o nível de proteção oferecido pela criptografia moderna.

Mais recentemente, técnicas criptográficas também foram usadas para tornar as criptomoedas possíveis. As criptomoedas aproveitam várias técnicas criptográficas avançadas, incluindo funções hash, criptografia de chave pública e assinaturas digitais. Essas técnicas são usadas principalmente para garantir a segurança dos dados armazenados em blockchains e para autenticar transações. Uma forma especializada de criptografia, conhecida como Algoritmo de Assinatura Digital de Curva Elíptica (ECDSA), sustenta o Bitcoin e os sistemas de outras criptomoedas como um meio de fornecer segurança extra e garantir que os fundos só possam ser usados por seus legítimos proprietários.

A criptografia percorreu um longo caminho nos últimos 4.000 anos e provavelmente não irá parar tão cedo. Enquanto dados sensíveis exigirem proteção, a criptografia continuará avançando. Embora os sistemas criptográficos usados nas blockchains das criptomoedas representem hoje algumas das formas mais avançadas dessa ciência, eles também fazem parte de uma tradição que se estendeu por grande parte da história humana.

### Tipos de criptografia, chaves e protocolos.

As chaves podem ser simétricas (quando a mesma chave privada é usada nas duas pontas da transmissão — emissão e recepção) ou assimétricas (quando as chaves de criptografia e descriptografia são distintas, sendo uma pública e a outra privada). Elas são geradas por algoritmos que criam uma sequência de caracteres específica para cada processo. As chaves podem ter tamanhos distintos e, quanto maiores, mais seguras elas se tornam.

Existem inúmeros protocolos de proteção utilizados na atualidade. Eles nos servem a todo instante, como quando você digita nome de usuário e senha para acessar um serviço da web, visita o site do banco ou então realiza uma compra pela internet. Protocolos como 3DES, RC AES, TLS e SSL são alguns dos mais comuns na atualidade.

No caso das Chaves (tanto simétrica quanto assimétrica), o nível de segurança de uma criptografia é medido no número de bits, ou seja, quanto mais bits forem usados, mais difícil será quebrar a criptografia na força bruta.
   
Ex: Se tivermos uma criptografia de 10 bits, existirão apenas 2¹º (ou 1024) chaves, porém, ao usarmos 64 bits, o número de chaves possíveis subirá para aproximadamente 20 x 10^18 chaves, um número alto até mesmo para um computador.

No caso da função Hash, o nível de segurança é dado pela dificuldade de se criar colisões intencionais, evitando que haja sequência iguais para dados diferentes.

### Criptografia hash.

A criptografia hash permite que, através de uma string de qualquer tamanho, seja calculado um identificador digital de tamanho fixo, chamado de valor hash. O valor hash geralmente é formado por 16 bytes (no caso do MD-2, MD-4 e MD- 5) ou 20 bytes (no caso do SHA-1), mas pode se estender, embora não passe de 512 bytes. Seja uma função hash H, e x uma string qualquer, teremos que H(x) será o valor hash para a string x. As características básicas de uma função hash são:

-	O valor de entrada da função possui qualquer tamanho;
-	O valor de saída da função possui tamanho fixo;
-	H(x) é relativamente fácil de ser computado, para qualquer valor de x;
-	H(x) é uma função “one-way”;
-	H(x) é livre de colisão.

Uma função hash é dita "one-way” pois uma vez obtido o valor hash h para uma string x, é computacionalmente impossível fazer o processo inverso, ou seja, encontrar um valor x tal que H(x) = h.  

Diz se ainda que H(x) é livre de colisão, significando que as funções hash devem garantir uma probabilidade mínima de que duas strings diferentes acabem por resultar no mesmo valor hash. Qualquer alteração na string original que deu origem ao identificador digital, mesmo que de um único bit, acabará por gerar uma alteração significativa no valor hash final.

### Chaves simétricas.

É o tipo mais simples de criptografia, já que tanto o emissor quanto o receptor da mensagem possuem a mesma chave, ou seja, a mesma chave é usada tanto na codificação quanto na decodificação.

Para ser realizada, basta que o emissor, antes de enviar a mensagem criptografada, envie a chave privada que será utilizada para descriptografá-la.

Porém, a Chave Simétrica apresenta alguns problemas graves, tais como a necessidade da troca constante dessas chaves e a impossibilidade de serem usados com fins de autentificarão (já que a transmissão da chave privada de um para o outro pode não ser segura e acabar caindo em outras mãos), apesar de seus algoritmos serem mais rápidos do que os algoritmos assimétricos.

### Chaves Assimétricas.

Diferentemente do método de Chave Simétrica, esse tipo utiliza 2 chaves, uma pública e uma privada. O sistema funciona da forma que alguém cria uma chave e envia essa chave há quem quiser mandar informações a ela, essa é a chamada chave pública. Com ela é feita a codificação da mensagem. Para decodificação será necessário utilizar uma outra chave que deve ser criada, a chave privada – que é secreta.

Esse esquema de chaves pública e privada atuando em conjunto funciona muito bem, principalmente quando queremos garantir a confiabilidade nos dados, já que somente o proprietário da chave privada será capaz de descriptografar a mensagem e vice-versa (nem mesmo o dono da chave pode descriptar a mensagem que ele encriptou, a não ser que ele possua a outra chave), ou seja, mesma que ela caia em “mãos erradas”, essa pessoa não será capaz de lê-la.

Assim como a Chave Simétrica, a Assimétrica também tem seus problemas. A utilização de algoritmos reversos para desencriptação de mensagens acaba por elevar o tempo computacional dos algoritmos de criptografia assimétrica, tornando inviável o seu uso em uma comunicação intensa.

### Criptografia nas redes sem fio.

As redes wireless abriram uma brecha enorme na segurança dos dados. Isso porque os dados podem ser facilmente interceptados com algum conhecimento técnico.

Isso obrigou o desenvolvimento de técnicas de criptografia para tornar esse tipo de comunicação viável, não só para empresas que decidem conectar seus usuários por meio de redes sem fio, mas também para que os usuários domésticos possam realizar suas transações financeiras com mais segurança e privacidade.

### WEP.

Esta técnica usa uma chave secreta compartilhada e o algoritmo de criptografia RC4. O roteador wireless ou ponto de acesso, bem como todas as estações que se conectam a ele devem usar a mesma chave compartilhada. Para cada pacote de dados enviado em qualquer direção, o transmissor combina o conteúdo do pacote com uma soma de verificação desse pacote. O padrão WEP pede então que o transmissor crie um IV (Initialization Vector, vetor de inicialização) específico para o pacote, que é combinado com a chave e usado para criptografar o pacote. O receptor gera seu próprio pacote correspondente e o usa para decodificar o pacote. Em teoria, essa abordagem é melhor do que a tática óbvia de usar apenas a chave secreta compartilhada, pois inclui um bit de dado específico para o pacote que dificulta sua violação. Entretanto, se uma chave compartilhada estiver comprometida, um invasor poderá bisbilhotar o tráfego de informações ou entrar na rede.

### WPA e WPA2.

Estes certificados de segurança são baseados no padrão da Wi-Fi Alliance para redes locais sem fio e utilizados por muitas empresas e até em redes domésticas. Eles permitem autenticação mútua para verificação de usuários individuais e criptografia avançada. A WPA fornece criptografia para empresas, e a WPA2 – considerada a próxima geração de segurança Wi-Fi – vem sendo usada por muitos órgãos governamentais em todo o mundo. “O WPA2 com AES é a novidade, tanto para o uso corporativo quanto para o pessoal. Ao usuário residencial, ele garante um excelente padrão de segurança e, aos usuários corporativos, permite agregar um servidor de autenticação para controle dos usuários em conjunto com a criptografia”, avalia Diogo Superbi, engenheiro de vendas da Linksys no Brasil.

### Assinatura digital.

A assinatura digital é uma técnica que utiliza criptografia para conferir segurança e integridade a documentos eletrônicos. Com a expansão da informática, grande parte dos arquivos em diversas áreas do mercado migrou para o ambiente digital. A partir disso, surgiu a necessidade de autenticar todo esse volume de informações, da mesma forma com que as assinaturas validam contratos e outros conteúdos em papel.

### Como funciona uma assinatura digital.

O autógrafo convencional é substituído por um certificado digital e uma chave privada exclusiva do seu proprietário. O certificado digital serve para comprovar que a chave pertence à pessoa. Além da identificação e das informações da chave, ele [o certificado] é assinado por uma Autoridade Certificadora, uma espécie de 'terceiro', uma pessoa em quem signatário e destinatário do arquivo, ou documento, confiam.

Em suma, para conseguir uma assinatura digital é preciso se dirigir até uma destas entidades e requisitar uma chave privada. As ACs (Autoridade Certificadora) são autorizadas pelo Instituto Nacional de Tecnologia da Informação.

### A cifra de cesar.

Em criptografia, a Cifra de César, também conhecida como cifra de troca, código de César ou troca de César, é uma das mais simples e conhecidas técnicas de criptografia. É um tipo de cifra de substituição na qual cada letra do texto é substituída por outra, que se apresenta no alfabeto abaixo dela um número fixo de vezes. Por exemplo, com uma troca de três posições, A seria substituído por D, B se tornaria E, e assim por diante. O nome do método é em homenagem a Júlio César, que o usou para se comunicar com os seus generais.

![image](https://user-images.githubusercontent.com/78885438/144442097-ae81f0e8-0ce7-446f-929a-6f63a4e6fb48.png)

### História e uso da cifra de cesar.

A cifra de César foi nomeada em homenagem a Júlio César que, segundo Suetónio, a usava com uma troca de três posições para proteger mensagens de significado militar. Ainda que o uso deste esquema por César tenha sido o primeiro a ser registrado, é sabido que outras cifras de substituições foram utilizadas anteriormente.

É desconhecido o quão efetiva era a cifra de César nesta época, mas é provável que fosse razoavelmente segura, ainda mais porque a maioria dos inimigos de César eram analfabetos e outros presumiam que as mensagens estavam escritas em uma língua estrangeira desconhecida.

### Decifrando a cifra de Cesar.

A cifra de César pode ser facilmente decifrada mesmo em um cenário que se tenha apenas o texto cifrado. Duas situações podem ser consideradas:

1.	Um interceptador conhece (ou adivinha) que algum tipo de cifra de substituição simples foi utilizado, mas não especificamente que é um código de César;

2.	Um interceptador sabe que uma cifra de César foi usada, mas não sabe o valor de troca.

No primeiro caso, a cifra pode ser decifrada usando as mesmas técnicas usadas para resolver qualquer outro tipo de cifra de substituição simples, como a análise de frequência ou verificando os padrões de palavras. Enquanto resolve, é provável que o atacante rapidamente perceba a regularidade da solução e deduza que a cifra de César é o algoritmo específico empregado.

No segundo exemplo, decifrar o esquema é ainda mais fácil. Uma vez que existe apenas um número limitado de rotações possíveis (26 em português, se desconsiderarmos o uso de cedilha e letras acentuadas), cada uma pode ser testada por turno num ataque de força bruta.

### Cifra de vigenère.

A cifra de Vigenère é um método de criptografia que usa uma série de diferentes cifras de César baseadas em letras de uma senha. Trata-se de uma versão simplificada de uma mais geral cifra de substituição poli alfabética, inventada por Leon Battista Alberti cerca de 1465. Esta cifra é muito conhecida por ser fácil, e parecendo, a quem tem pouca prática, que é inquebrável. Consequentemente, muitos programadores implementaram esquemas de criptografia nas suas aplicações que são no essencial cifras de Vigenère, e que são facilmente quebradas por qualquer criptoanalista.

### Descrevendo a cifra de vigenère.

Na cifra de César, cada letra do alfabeto é deslocada da sua posição um número fixo de vezes, por exemplo, se tiver um deslocamento de 3, "A" torna-se "D", "B" fica "E". A cifra de Vigenère consiste no uso de várias cifras de César em sequência, com diferentes deslocamentos ditados por uma "palavra-chave".

Para cifrar, é usada uma tabela de alfabetos que consiste no alfabeto escrito 26 vezes em diferentes linhas, cada um deslocado ciclicamente do anterior por uma posição. As 26 linhas correspondem às 26 possíveis cifras de César. Uma palavra é escolhida como "chave", e cada letra desta palavra vai indicar a linha a ser utilizada para cifrar ou decifrar uma letra da mensagem.

Por exemplo, supondo que se quer criptografar o texto: ATACARBASESUL ("atacar base Sul")

Escolhendo a chave e repetindo-a até ter o comprimento do texto a cifrar, por exemplo, se a chave for "LIMAO":

LIMAOLIMAOLIM

A primeira letra do texto, A, é cifrada usando o alfabeto na linha L, que é a primeira letra da chave. Para a segunda letra do texto, ver a segunda letra da chave: linha I e 
coluna T, que é B, continuando sempre até obter a cifra:

LBMCOCJMSSDCX

### A escolha da cifra de vigenère em nosso algoritmo.

A cifra de vigenère foi escolhida para ser implementada em nosso algoritmo por se tratar de uma cifra de fácil entendimento e manuseio, mas ao mesmo tempo garantir uma grande segurança para o usuário que a utilizar para codificar suas mensagens. Por se tratar de uma sequência de várias cifras de Cesar, temos letras iguais de uma mensagem com valores codificados   diferentes, o que traz grande dificuldade para quem tentar fazer a quebra da mensagem codificada.

![image](https://user-images.githubusercontent.com/78885438/144443064-c5f3b89f-1cdf-4ec8-a489-199e8a82b2cf.png)

A chave será o centro da criptografia pois ela é quem ditara como a mensagem será cifrada, utilizando os caracteres da chave apontaremos para novos caracteres ou no caso do nosso algoritmo, conjuntos de caracteres, que serão responsáveis por representar a mensagem original na mensagem cifrada.

Isso ocorre da seguinte forma, por exemplo: a chave sendo C, será selecionado o alfabeto correspondente a C e dentro do alfabeto C será selecionada a letra correspondente as letras M,G,R,G e D, da mesma forma para a chave H será selecionado o alfabeto H e dentro do alfabeto H será selecionada a letra correspondente ao E,E,I,R e A e assim sucessivamente até o fim da mensagem.

No exemplo também pode ver a aplicação da não repetição de letras codificadas, isso é se compararmos o M que é a primeira letra da mensagem e o M que é a última letra da palavra mensagem, eles terão valores diferentes pois são codificados usando diferentes letras da chave.

### Fluxograma de funcionamento do algoritmo.

![image](https://user-images.githubusercontent.com/78885438/144443176-d9f99949-d887-4a30-8b24-fe6ef11b8991.png)

### O algoritimo.

Para iniciar o algoritmo foram necessárias duas funções, a primeira foi responsável por gerar valores com 5 caracteres aleatórios para todas as letras entre A e Z, maiúsculos, minúsculos e os numerais de 0 a 9:

![image](https://user-images.githubusercontent.com/78885438/144443286-449c2573-38f0-43f6-a3ce-180d719c3cef.png)

O dicionário_pt tem todos os valores armazenados, o código em si faz o sorteio de um índice, esse índice é concatenado em uma variável e vai gerar 70 valores com 5 caracteres em cada. Esse será o nosso primeiro dicionário.

![image](https://user-images.githubusercontent.com/78885438/144443337-3bce2a7c-ea94-4cc7-857b-cd57f27514f8.png)

O valor gerado pelo código acima é adicionado na lista dicionário. E novamente e sorteado indicies aleatórios, mas nesse segundo sorteio os índices não podem se repetir, para isso foi feita uma verificação, se o índice não existe na lista ele é adicionado, se ele já existe na lista, é chamada a função sorteio mis uma vez e por último é verificado novamente.

Cada linha gerada por esse código foi adicionada a nossa matriz, cada linha equivale a um dicionário.

A baixo usaremos uma imagem para explicar o funcionamento da matriz:

A parte da primeira linha grifada em amarelo são as letras representantes da chave, a parte da primeira coluna circulada em vermelho são as letras representantes da mensagem, então por exemplo se a primeira letra da chave for “C” e a primeira letra da mensagem for “E” o valor gerado pela criptografia será o conjunto de caracteres “AsceR”.

![image](https://user-images.githubusercontent.com/78885438/144443441-efbeb878-dbe8-4f7e-9fad-46acb41cd63b.png)

### A função criptografia.

Ela leva como parâmetro a chave e a mensagem. A primeira parte é verificar se o tamanho da mensagem é maior que 128 caracteres (limite proposto), se ela se encaixar nesse limite então a variável texto pronto é zerada (se for a 2 vez que o programa é executado é possível que ela já atenha um valor armazenado) o H representa o índice da mensagem e será executado o tamanho da mensagem. Já o I representa  o índice da chave, e o J ira verificar qual é a letra da chave para poder selecionar o dicionário que será usado, assim que é encontrado o dicionário valor K entra em ação, percorrendo o dicionário original e verificando qual indicie do dicionário tem valor igual ao valor do índice h da mensagem. Assim que terminar todos os laços o programa retorna o valor da mensagem já codificado. 

![image](https://user-images.githubusercontent.com/78885438/144443636-4032ba1a-a098-4a71-8f68-75ce6627d090.png)

### A função descriptografia.

A função Descriptografia é onde podemos colocar uma mensagem já criptografada pela função criptografia do algoritmo e é o caminho inverso da criptografia, a única diferença relevante é a lista itens, onde é utilizado o comando “.split(‘ ‘)”  esse comando vai fazer a separação de todos os espaços, então pôr exemplo no caso da mensagem: ”xgXl7 ON3rg Z60kQ“ será criada uma lista com 3 índices: “itens = [“xgXl7”,“ON3rg“,“Z60kQ”]” na verificação do tamanho da mensagem, foi usado o número de índices já que uma palavra com 10 letras gera um conjunto de caracteres com 50 leras.

![image](https://user-images.githubusercontent.com/78885438/144443766-408aad2e-6823-4bcc-b8bc-c5b0e95e2249.png)

### A função info.

A função info exibe as informações importantes sobre o funcionamento do algoritmo na tela, para o usuário aprender a utilizar o algoritmo e tirar suas dúvidas, e logo após essa leitura, a função info chama a função menu que é centro algoritmo e será explicada a seguir: 

![image](https://user-images.githubusercontent.com/78885438/144443872-e31e7b1d-db54-4e24-8d68-08c39fac9428.png)

### A função menu.

Foi feito um “while” para sempre repetir enquanto o valor de opção for diferente de 4, após isso é verificado se o valor é 1, 2 ou 3 então vai verificar o tamanho da chave e da mensagem, caso a opção for 4, foi preciso usar a função “sys.exit(0)” que foi importado na primeira linha do código, na última linha é chamada a função info para que o usuário já receba as informações assim que o programa é iniciado e logo em seguida é chamado o menu. 

![image](https://user-images.githubusercontent.com/78885438/144443957-16296675-956c-4143-918d-c398eec565e3.png)


<p align="left"><strong>Nota:</strong> 10.0<br>
<strong>Comentário do orientador:</strong><br>
<i>"O texto está bem redigido, aborda o tema solicitado. Só é preciso adequar o padrão de referências bibliográficas."</i></p>

<p align="center"><i>“Não importa o que aconteça, continue a nadar”</i> <br>
(WALTERS; GRAHAM, Procurando Nemo, 2003).</p>

<p align="center">Atividade concluída 23/11/19.</p>
