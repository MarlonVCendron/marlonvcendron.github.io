## Ataques

- [Phishing](#phishing)
- [DNS Spoofing](#dns-spoofing)
- [Malware](#malware)
- [Engenharia Social](#engenharia-social)
- [Força bruta](#força-bruta)
- [Cross-Site Scripting (XSS)](#cross-site-scripting-xss)
- [Ransomware](#ransomware)
- [Man-in-the-Middle (MITM)](#man-in-the-middle-mitm)
- [Injeção SQL](#injeção-sql-sql-injection)
- [Zero day exploit](#zero-day-exploit)
- [Trojan horse](#trojan-horse)
- [Keylogger](#keylogger)

## Phishing

*O que faz:*
Se baseia na engenharia social para roubar informações pessoais, financeiras ou confidenciais das vítimas. Ocorre por meio de um e-mail falso ou uma página web falsa que imita uma instituição legítima (banco, comércio, uma rede social e outros).
O objetivo é induzir a vítima a fornecer informações pessoais ou realizar uma ação que permita que o atacante ganhe acesso aos seus dados ou sistemas.

*Operacionalização:*
Preparação e criação da mensagem: O atacante pesquisa e seleciona um alvo (pessoa ou organização) e coleta informações relevantes, como endereço de e-mail, nome, cargo, interesses e comportamentos na internet, e cria a mensagem usando essas informações com base.
Contato: O atacante envia um e-mail falso ou cria uma página web falsa que imita a identidade visual e o conteúdo de uma instituição legítima. A mensagem pode conter um link, arquivo anexado ou página pedindo login que solicita informações.

*Engajamento:*
A vítima recebe o e-mail ou acessa a página web falsa sendo persuadida a realizar a ação pretendida pelo atacante. A persuasão pode ser baseada em várias técnicas (urgência, medo ou incentivos).
Captura: O atacante recebe as informações fornecidas pela vítima e as usa para acessar suas contas, roubar dinheiro, realizar fraudes, comprometer sistemas ou espalhar o ataque. Identificar o Phishing pode ser difícil, pois os e-mails ou páginas web falsas podem ser muito bem elaborados e se parecerem muito com os originais.

*Como funciona:*
Seu funcionamento se dá pelas fases de "contato" e "captura" citados, envolvendo a enganação, mais engenharia social do que conhecimento técnico de fato, onde é criada a mensagem falsa e captura é quando de fato a pessoa caiu no golpe.

*Como identificar:*

- Conferir o endereço de e-mail do remetente é legítimo, atacantes tentam usar emails semelhantes;
- Prestar atenção na mensagem, se houver algum erro de ortografia ou formatação, a mensagem pode ser falsa;
- Analise links e anexos, antes de realmente clicar em algo ou abrir um arquivo;
- Desconfie de mensagens que soam urgentes ou ameaçadoras;
- As mensagens podem seguir um padrão, veja se ninguém online não sofreu algo similar.
  Contramedidas preventivas:
- Conscientização dos usuários: demonstrar porque não clicar em links suspeitos ou fornecer informações pessoais em sites que parecem suspeitos;
- Uso de filtros de e-mail: excluindo spam e e-mails suspeitos, podendo habilitar nas em sua conta de e-mail;
- Uso de antivírus, mantendo softwares atualizados, inclusive navegadores;
- Verificar emails e sites, para excluir suspeitas de que é legítimo;
- Uso de autenticação de dois fatores.
  Contramedidas reativas:
- Alterar senha imediatamente;
- Tentar notificar pessoas importantes de que foi atacado;
- Remover qualquer software malicioso com programas.

## DNS Spoofing

*O que faz:*
DNS Spoofing é um ataque que tem como objetivo manipular o sistema de resolução de nomes de domínio (DNS) para redirecionar os usuários a sites maliciosos em vez dos legítimos que eles querem acessar, ou seja, a alteração do redirecionamento do site, direcionando o tráfego de rede para um endereço IP diferente do pretendido pelo usuário. Isso permite que o invasor possa interceptar e manipular o tráfego da rede, resultando em possíveis ataques de phishing, roubo de dados ou monitoramento de atividades.

*Operacionalização:*
O invasor geralmente usa uma técnica de redirecionamento de tráfego para falsificar as informações do DNS e cria uma resposta falsa que é armazenada no cache DNS do sistema alvo. O invasor pode utilizar várias técnicas para manipular o cache DNS (uso de malware ou a exploração de vulnerabilidades).
Quando o usuário tenta acessar o site legítimo, seu computador consulta o servidor DNS para obter o endereço IP correspondente ao nome de domínio. Se a resposta falsa do DNS Spoofing estiver presente no cache DNS do sistema, o usuário será redirecionado para um endereço IP diferente, que pode ser controlado pelo invasor. O usuário acreditará que está acessando o site legítimo, mas na verdade estará acessando o site falso criado pelo invasor.

*Como funciona:*
Para realizar esse ataque, o invasor usa técnicas para falsificar o endereço IP de um site legítimo e força o usuário a acessar o site falso. Isso é feito por meio da manipulação dos registros DNS da vítima (armazenados em cache nos servidores DNS, roteadores ou dispositivos de rede intermediários).
A técnica mais comum de DNS Spoofing é o ataque Man-in-the-Middle (MITM): intercepta a comunicação entre a vítima e o servidor DNS. Uma vez que o atacante consegue redirecionar a vítima para o site malicioso, ele pode capturar informações confidenciais, como nome de usuário, senha e outras informações pessoais.

*Como identificar:*

- Sites legítimos redirecionado para páginas falsas;
- Mensagens de erro em um site mesmo que seus status sejam de online;
- Certificados SSL inválidos/inexistentes;
- Nome de domínio não correspondendo ao conteúdo do site acessado.
  Contramedidas preventivas:
- Atualização regular de softwares;
- Uso do DNSSEC (extensão de segurança para protocolo DNS) que evita ataques, adicionando uma camada de autenticação aos dados para garantir que respostas DNS recebidas sejam autênticas;
- Uso de VPN, pois a conexão é criptografada e pacotes de dados são enviados de forma mais segura;
- Boa configuração de firewalls e roteadores;
- Uso de antivírus e conscientização dos usuários.
  Contramedidas reativas:
- Limpe o cache do DNS;
- Analisar configurações de rede, se o endereço IP e servidor DNS são corretos;
- Atualizar o software do roteador (firmware);
- Usar servidores DNS seguros que criptografam as consultas DNS
- Contate o provedor de serviços de internet.

## Malware

*O que faz:*
É um termo genérico usado para descrever vários tipos de programas maliciosos projetados para prejudicar ativos. Os malwares podem executar roubo de informações pessoais ou financeiras, interrupção ou destruição de sistemas, controle remoto, criptografia de arquivos e outros:
Vírus: programas que se replicam e infectam outros arquivos no computador;
Worms: se replicam e se espalham por uma rede;
Trojans: se disfarçam como um software legítimo e enganam os usuários para que os instalem;
Spyware: rastreiam as atividades do usuário e coletam informações pessoais;
Ransomware: criptografa os arquivos do usuário e exige um resgate em troca da chave de descriptografia.
A operação de um malware varia dependendo do tipo dele e objetivo do atacante. Quando o usuário executa o programa infectado, o malware pode se instalar no sistema.

*Operacionalização:*
Ela varia dependendo do tipo específico de malware, mas pode envolver algumas das seguintes etapas:
Infecção: A infecção é o processo de introduzir o malware no sistema alvo. O malware entra em um sistema por meio de uma vulnerabilidade (email de phishing, download malicioso ou uma conexão de rede não segura). Para evitar a detecção, o malware pode disfarçar como um arquivo legítimo.
Instalação: O malware é instalado no sistema, permitindo que execute a criação de arquivos ou pastas maliciosas, alteração de arquivos existentes, ou modificações em configurações do sistema.
Comunicação: O malware pode tentar se comunicar com um servidor remoto para receber instruções ou enviar dados coletados do sistema infectado.
Propagação: Alguns malwares são projetados para se espalhar para outros sistemas na mesma rede ou na internet.

*Como funciona:*
Os malwares podem se propagar de diversas maneiras, como anexos de e-mails, downloads de sites infectados, softwares pirateados e vulnerabilidades de segurança. Uma vez que um malware é executado em um computador, ele pode começar a realizar suas atividades maliciosas.
Cada tipo de malware tem suas próprias características e métodos de propagação.
O funcionamento específico de um malware pode variar de acordo com o seu tipo e objetivo, mas em geral, eles têm a capacidade de se instalar em um sistema e se esconder de detecções.

*Como identificar:*

- Lentidão ou travamento do sistema;
- Pop-ups e anúncios inesperados;
- Alterações não autorizadas em configurações do sistema;
- Uso excessivo de recursos do sistema (hardware);
- Comportamento inesperado do sistema.

Contramedidas preventivas:

- Manter sistema operacional e software atualizados;
- Fazer backup de dados importantes;
- Verificar origem de arquivos e uso de antivírus.
  Contramedidas ativas:
- Desconecte imediatamente o sistema da rede;
- Caso seja grave, formatar o sistema operacional pode se fazer necessário;
- Restaurar backups recentes para recuperar dados;
- Análise forense, analisando o tipo do malware e atividades feitas por ele.

## Engenharia social

Um ataque por engenharia social é um tipo de ataque cibernético que utiliza a manipulação psicológica para obter informações confidenciais ou acesso não autorizado a sistemas ou redes de computadores. O objetivo é fazer com que a vítima acredite que está agindo de forma legítima, quando na verdade está fornecendo informações valiosas ou executando ações maliciosas.

Um exemplo simples de uma situação em que um atacante faz uso de engenharia social é o atacante fazer uma ligação telefônica para alguém que tenha acesso ao sistema, se passando por uma pessoa de confiança e a convencendo a lhe passar as credenciais do sistema por conta de uma urgência, ou qualquer mentira que convença a vítima.

O ataque por engenharia social pode afetar diversos recursos e ativos, como sistemas de computadores, redes, dispositivos móveis, aplicativos e informações confidenciais armazenadas em servidores ou bancos de dados. Além disso, o ataque também pode prejudicar a imagem e a reputação de indivíduos e empresas, bem como causar prejuízos financeiros.

A operacionalização do ataque por engenharia social envolve várias etapas. O primeiro passo é a identificação da vítima potencial e a obtenção de informações sobre ela, como nome, endereço de e-mail, telefone, cargo e informações profissionais. Em seguida, o atacante cria um cenário convincente para a vítima, utilizando técnicas de persuasão para obter sua confiança.

O ataque por engenharia social pode ser realizado de várias maneiras, como por meio de phishing, onde o atacante cria um e-mail ou site falso para enganar a vítima e fazer com que ela revele informações confidenciais ou faça o download de um malware. Outra técnica comum é o pretexting, onde o atacante se faz passar por outra pessoa ou autoridade para obter informações confidenciais ou acesso a sistemas. Outra técnica existente, conhecida por sextorsion, é quando o atacante ameaça revelar fotos íntimas, existentes ou não, exigindo o que quiser da vítima posta em uma situação vulnerável. O atacante também pode se infiltrar em um ambiente restrito de uma empresa ao se passar por um colega quando, por exemplo, um funcionário deixa a porta aberta para o atacante por gentileza. Outra técnica comum consiste em procurar informações sensíveis no lixo da vítima.

O ataque por engenharia social funciona explorando a confiança e a boa-fé da vítima, que muitas vezes não percebe que está sendo enganada. Com a crescente sofisticação dos ataques cibernéticos, é essencial que indivíduos e empresas estejam cientes dos riscos da engenharia social e tomem medidas preventivas, como treinamento de segurança cibernética, políticas de segurança rigorosas e medidas de autenticação de dois fatores.

Um exemplo recente foi quando, em 2020, um grupo de atacantes conseguiu acesso a contas de funcionários do Twitter por meio de engenharia social. Diversas contas famosas do Twitter, como de Joe Biden, Elon Musk, Barack Obama etc. tuitaram que transações de bitcoin para uma carteira específica teriam seu valor dobrado e retornado para o indivíduo. No fim, a carteira recebeu mais de 100 mil dólares de vítimas.

<div width="100%" style="display: flex; justify-content: center">
  <img src="/img/scam.png" />
</div>

Fontes:

1: https://www.nytimes.com/2020/07/15/technology/twitter-hack-bill-gates-elon-musk.html

2: https://www.kaspersky.com/resource-center/definitions/what-is-social-engineering

3: https://stefanini.com/pt-br/insights/artigos/tipos-de-ataques-de-engenharia-social

## Força bruta

Um ataque por força bruta é um método utilizado por hackers para tentar adivinhar senhas ou chaves de criptografia por meio de tentativa e erro. Ele funciona por meio da utilização de programas de computador que testam todas as combinações possíveis de caracteres em uma tentativa de descobrir a senha correta.

O ataque por força bruta pode afetar qualquer recurso ou ativo que tenha uma senha ou chave de criptografia, como sistemas, máquinas, dispositivos de armazenamento, contas de e-mail e redes de computadores.

O ataque por força bruta pode ser operacionalizado de várias maneiras. Uma abordagem comum é a utilização de um programa de computador que gera todas as possíveis combinações de caracteres e as testa para adivinhar a senha correta. Além disso, alguns hackers utilizam botnets, que são redes de computadores comprometidos controladas remotamente, para realizar ataques por força bruta em larga escala.

Os ataques por força bruta podem ser extremamente demorados e trabalhosos, especialmente se a senha for longa e complexa. No entanto, com o poder de processamento dos computadores modernos, é possível quebrar senhas comuns em um período de tempo relativamente curto. Para uma senha totalmente aleatória com 8 letras maiúsculas e minúsculas e números, estima-se por volta de uma hora para adivinhá-la por força bruta.

Para realizar um ataque por força bruta, o hacker normalmente utiliza programas específicos, conhecidos como cracking tools ou password cracking software, que testam uma grande quantidade de possíveis senhas em um curto período de tempo. Esses programas podem utilizar diferentes abordagens para realizar o ataque, como o uso de dicionários de palavras comuns, tentativas sequenciais de combinações de caracteres, entre outros.

Além disso, os atacantes podem usar técnicas adicionais para aumentar a eficácia do ataque, como o uso de processamento distribuído, onde várias máquinas trabalham em conjunto para realizar o ataque, ou o uso de técnicas de geração de senhas, onde o programa tenta criar senhas a partir de informações específicas, como nome, data de nascimento, entre outras.

É importante ressaltar que existem bancos de senhas conhecidas disponíveis na internet, que são compostos por senhas vazadas de sistemas comprometidos em diferentes incidentes de segurança. Esses bancos de senhas podem ser utilizados por atacantes em ataques por força bruta, já que muitas pessoas reutilizam senhas em diferentes serviços e sistemas.

As senhas armazenadas nos bancos de senhas conhecidas podem estar criptografadas com diferentes algoritmos, como MD5, SHA-1, SHA-2, entre outros. No entanto, muitos desses algoritmos de criptografia já foram quebrados e  não são mais considerados seguros para proteger senhas. Por isso é importante utilizar algoritmos de criptografia mais recentes, como o SHA-512.

Em 2020, a Canadian Revenue Agency (CRA) sofreu um ataque de força bruta que comprometeu por volta de 11 mil contas.

Fontes:

1: https://www.komando.com/security-privacy/check-your-password-strength/783192/

2: https://www.makeuseof.com/brute-force/

## Cross-Site Scripting (XSS)

Cross-site scripting (XSS) é um tipo de ataque que visa explorar vulnerabilidades em sites da web para injetar código malicioso e executá-lo nos navegadores dos usuários. Esse tipo de ataque pode ser altamente prejudicial, permitindo que invasores roubem dados do usuário, espionem suas atividades na web ou redirecionem o usuário para sites falsos ou maliciosos.

O objetivo do ataque de XSS é basicamente injetar código malicioso em um site da web e enganar o navegador do usuário para executá-lo. Os atacantes usam várias técnicas para alcançar esse objetivo, geralmente explorando vulnerabilidades em formulários, scripts e outros recursos da web.

Uma vez que o código malicioso é executado, o atacante pode potencialmente ter acesso a informações confidenciais do usuário, como senhas, números de cartão de crédito ou outras informações pessoais. O ataque de XSS pode afetar vários recursos ou ativos, como sites, navegadores ed ispositivos móveis.

O ataque de XSS pode ser operacionalizado por meio de diferentes técnicas, como a injeção de código malicioso javascript em um formulário de comentários de um blog, por exemplo. O atacante pode inserir um script malicioso em um campo de comentários, que é executado automaticamente quando o usuário carrega a página do blog. Uma vez que o código é executado, ele pode fazer qualquer coisa que o atacante quiser, como coletar informações pessoais do usuário e enviá-las para o atacante ou redirecionar o usuário para um site malicioso.

A forma mais comum de XSS ocorre quando o site não trata o input de um usuário de forma segura e acaba apenas embutindo-o no HTML. Em um comentário de blog, por exemplo, o atacante pode escrever uma tag de `<script>` e injetar qualquer código javascript que quiser. Caso o input não seja tratado corretamente pelo blog (escapando caracteres como os colchetes angulares), quando outro usuário acessar a seção de comentários ao invés de aparecer apenas o texto de comentário do atacante, o site tratará a tag de script como sendo uma tag HTML normal e executará o código javascript no lado do usuário.

Em 2014, um usuário do Twitter explorou uma vulnerabilidade no TweetDeck, em que a aplicação não fazia o tratamento correto dos tuítes digitados pelos usuários: tuítes que terminassem com um emoji eram tratados como HTML. O simples tuíte consistia em uma tag script que automaticamente clicava e confirmava o retuíte. Dessa forma, qualquer usuário que carregasse esse tuíte automaticamente o retuitava. Hoje, esse tuíte tem 61 mil retuítes.

<div width="100%" style="display: flex; justify-content: center">
  <img src="/img/xss.png" />
</div>

Fontes:

1: https://www.theguardian.com/technology/2014/jun/12/tweetdeck-vulnerability-teen-code-emoji-heart

2: https://twitter.com/derGeruhn/status/476764918763749376

3: https://owasp.org/www-community/attacks/xss

## Ransomware

Ransomware é um tipo de malware que criptografa os arquivos de um sistema ou dispositivo, tornando-os inacessíveis ao usuário, e exige o pagamento de um resgate em troca da chave de descriptografia. O objetivo do ransomware é extorquir dinheiro dos usuários afetados.

Existem diversas formas de execução do ransomware. Uma delas é por meio do phishing, que é uma técnica de engenharia social que usa e-mails falsos para induzir os usuários a clicarem em links ou baixarem arquivos maliciosos. Outra forma é por meio de vulnerabilidades de segurança em sistemas ou dispositivos, que permitem que o ransomware seja instalado sem a necessidade de interação do usuário.

Uma vez instalado no sistema, o ransomware começa a criptografar os arquivos e, em seguida, exibe uma mensagem exigindo o pagamento do resgate para que a chave de descriptografia seja fornecida. Geralmente, o pagamento é exigido em criptomoedas, que são difíceis de rastrear.

O exemplo mais famoso de ataque de ransomware foi o WannaCry, que aconteceu em maio de 2017. O WannaCry afetou milhares de computadores em todo o mundo, incluindo sistemas de grandes empresas, hospitais e governos.

O WannaCry foi disseminado por meio de uma vulnerabilidade de segurança do Windows, que havia sido corrigida pela Microsoft alguns meses antes, mas muitos usuários ainda não haviam instalado a atualização de segurança.

O ransomware criptografou os arquivos dos usuários e exigiu o pagamento de um resgate em bitcoin para que a chave de descriptografia fosse fornecida. O ataque causou grandes prejuízos financeiros e colocou em risco a privacidade e a segurança de muitos usuários.

O WannaCry foi um exemplo importante de como os ataques de ransomware podem ser devastadores e como é importante manter os sistemas atualizados e seguros para prevenir esses tipos de ameaças.

Outro ataque famoso, trazendo para ares mais próximos, foi o ataque ao site das lojas Renner aconteceu no dia 19 de agosto de 2021, onde, segundo a entidade pró-consumidor (Procon-SP), “a varejista discriminou os controles e ferramentas implementados para tais processos.”. Onde os clientes além de serem obrigados a informar dados pessoais para compras.

Não se sabe ao certo, porém informações supostamente vazadas dizem que foi pago 20 milhões de dólares aos golpistas, que teriam provavelmente se aproveitado de uma falha. Porém em notas a lojista diz ter apenas pego um backup das informações e feito algum tipo de recuperação de dados.

É importante lembrar que, mesmo que o usuário pague o resgate, não há garantia de que a chave de descriptografia será fornecida. Além disso, ceder às exigências dos criminosos pode incentivar ainda mais ataques de ransomware. A melhor forma de prevenir o ransomware é manter o sistema e os programas atualizados, ter um antivírus instalado e fazer backups regulares dos arquivos importantes.

Fontes:

1: https://exame.com/tecnologia/renner-sofre-ataque-de-ransomware-e-sistemas-da-empresa-ficam-fora-do-ar/

2: https://tecnoblog.net/noticias/2021/10/01/renner-explica-impactos-do-ataque-de-ransomware-a-pedido-do-procon-sp/

## Man-in-the-Middle (MITM)

O Ataque de Man-in-the-Middle (ou Ataque MITM) é um tipo de ataque em que um invasor intercepta a comunicação entre duas partes que estão se comunicando, como um cliente e um servidor, e pode monitorar, modificar ou até mesmo injetar novas informações na comunicação. O objetivo do ataque MITM é obter informações confidenciais, como senhas, números de cartão de crédito, dados bancários e outras informações pessoais.

O ataque MITM é executado por meio da interceptação das comunicações entre as duas partes, sem que elas percebam que estão sendo monitoradas. O invasor pode usar diversas técnicas para executar o ataque, como:

Spoofing de ARP: o invasor pode enviar pacotes ARP falsificados para a rede, direcionando o tráfego para um dispositivo controlado por ele. Essa é uma técnica que pode além de interceptar os pacotes do destinatário, consegue clonar um IP, podendo assim fazendo até mesmo uma negação de serviço.

Redirecionamento de DNS: o invasor pode interceptar a comunicação de DNS e redirecionar o tráfego para um servidor controlado por ele. Em alguns casos ele pode estar inclusive no broadCast primário da rede.Para  esses dois primeiros temos um tutorial em [1] que explica como executá-los com o queridinho do mundo da segurança ofensiva, o kali linux.

Ataque de phishing: o invasor pode criar um site falso e enviar um e-mail com um link para o usuário acessar o site. Quando o usuário acessa o site falso, o invasor pode interceptar a comunicação e roubar as informações.

Intercepção de Wi-Fi: o invasor pode interceptar a comunicação sem fio entre um dispositivo e um ponto de acesso Wi-Fi e monitorar a comunicação. Esse exemplo é o mais comum, ele é bastante aplicado em redes wireless falsas de hotéis, onde a vítima se conecta a rede achando que a mesma pertence ao estabelecimento quando na verdade é uma rede feita por golpistas para adquirir senhas e informações para os golpistas.

Uma vez que o invasor obtém o controle da comunicação, ele pode monitorar as informações que estão sendo trocadas e, se necessário, modificar ou injetar novas informações na comunicação. Isso pode permitir que o invasor roube informações confidenciais, realize fraudes ou execute outros tipos de ataques. Para prevenir o ataque MITM, é importante usar conexões seguras, como HTTPS, VPN ou criptografia de ponta a ponta, e não confiar em redes Wi-Fi públicas ou não confiáveis.

Fontes:

1: https://acervolima.com/ataque-mitm-man-in-the-middle-usando-envenenamento-arp/(tutorial)

2: https://br.claranet.com/blog/man-in-the-middle-o-que-e

## Injeção SQL (SQL Injection)

Ataque de Injeção SQL é uma técnica de ataque cibernético que explora vulnerabilidades em aplicações web que interagem com bancos de dados. O objetivo do ataque é manipular o banco de dados subjacente ao aplicativo, permitindo que o invasor acesse, altere ou exclua dados confidenciais, como senhas, informações de cartão de crédito ou outras informações pessoais.

Para podermos fazer um ataque de injeção SQL temos que primeiramente identificar uma falha no serviço web o qual vamos atacar que permita um comando SQL, o qual é o que nomeia todo o ataque a injeção do script sql, ali você insere um script de sua preferência, que pode ser desde uma simples consulta até um drop de todo o database, o mais comum nesses casos é o criminoso inserir um script de Ransomware e sequestrar todos os dados conforme aconteceu com a renner que já foi citado.Um tutorial de como ele funciona explorando uma falha antiga do PHP está em [1]

O melhor jeito de prevenção desse tipo de ataque aos seus sistemas é tentar manter a versão mais atual possível da ferramenta usada na aplicação web e sempre ficar atento a falhas que são divulgadas quase que diariamente sobre os compiladores/interpretadores e suas linguagens. Também é importante ter um time (red-team) de segurança ofensiva se possível.

Ataques desse estilo são relativamente comuns por falta de manutenção, cuidado e investimento por parte das equipes de desenvolvimento e das empresas. Um ataque que ficou conhecido e ganhou destaque no Brasil um tempo atrás foi um executado por um famoso que era dono de um blog o CID DO NÃO SALVO onde um fã enviou um tutorial de como se aproveitar de uma falha desse estilo para colocar uma notícia no site oficial do santos futebol clube, na época a falha já era bastante conhecida entre a comunidade, porém por falta de conhecimento e de investimento em TI o clube acabou passando por isso[2].

Fontes:

1: https://rmauro.dev/sql-injection-na-pratica/

2: https://youtu.be/lwRLRURxvAs?t=9681

## Zero day exploit

*O que faz/ o que é:* trata-se de um ataque que acontece quando uma vulnerabilidade é descoberta por atacantes antes mesmo de desenvolvedores descobrirem, e no momento que descobrem, tem um tempo de aviso prévio de “zero dias” para contornar a vulnerabilidades antes que ataques aconteçam. Este tipo de ataque ocorre sempre que uma aplicação nova é lançada em produção, por meios de vulnerabilidades encontradas. Nesse instante, desenvolvedores detêm de zero dias para contornar o ataque. Normalmente este tipo de ataque ocorre com maior frequência em sistemas que testes para encontrar falhas de segurança não ocorrem ou são falhos.

*Como funciona:* quando a vulnerabilidade é encontrada, o que atacantes fazem é primeiramente analisar as brechas, posteriormente criar e distribuir códigos malwares por meio delas. O malware, se usado/executado, prejudica e explora os dispositivos com o intuito de roubo de dados para que criminosos o utilizem para obter ganhos financeiros.

*Operacionalização:* a primeira etapa é identificar softwares que foram recentemente lançados para encontrar vulnerabilidades e por meio delas espalhar malwares. Encontrado um software com vulnerabilidades, a segunda etapa é explorar o que é possível ser feito por meio dela, como injetar scripts de códigos malwares. Se possível então, os criminosos injetam malwares nestes softwares, e nisso usuários do softwares podem executar os scripts que permitirão que os criminosos possam roubar informações.

*Recursos/ativos afetados:* como o zero day exploit funciona através de malwares injetados em softwares, então o principal ativo afetado são dados dos usuários que existem em seus dispositivos, com o intuito de os utilizar para obter ganhos financeiros.

Fontes:

1: https://acaditi.com.br/o-que-e-um-ataque-de-dia-zero-ou-zero-day-exploit/

## Trojan horse

*O que faz/ o que é:* inspirado na guerra de Tróia, o cavalo de tróia atua como um disseminador de malwares, no qual utilizam de engenharia social para enganar os utilizadores a utilizar os softwares por justa causa de que se trata de um software benigno, mas na verdade oculta suas funcionalidades maliciosas, uma analogia ao cavalo de madeira deixado supostamente como “rendição” pelos gregos aos troianos, mas que na verdade dentro Ulisses e seus homens estavam escondidos para contra atacar de dentro das muralhas os troianos.   

*Como funciona:* cavalo de tróia é projetado pelos agentes maliciosos com o intuito de disseminar ameaças, podendo ser ransomware para extorquir dinheiro e a criptografia de dados e sistemas, bem como spywares, para roubar dados, por meio de softwares crackeados (jogos, aplicações proprietárias), arquivos de músicas, anúncios de navegadores que são executados, podem levar a infecção por trojans. Softwares crackeados e que dizem gerar chaves de ativação quando são executados são casos comuns de ataques de trojans, bem como anexos infectados podem se prover de engenharia social com a intenção de persuadir usuários a clicar no arquivo infectado. 

*Operacionalização:* a primeira etapa da operacionalização é montar um script que de alguma forma roube e até mesmo criptografe dados de dispositivos de usuários. Na sequência, esse script é adicionado a um software amplamente conhecido. Pode ser ele algum software proprietário a ser crackeado, um jogo crackeado, algum anexo que por meio de engenharia social estimule o usuário a clicar nele. Trojan Horse está intimamente ligado à engenharia social, pois normalmente ocorrem com usuários que querem ferramentas proprietárias por meio de ferramentas crackeadas, ou por documentos que estimulem usuários a clicar neles.

*Recursos/ativos afetados:* considerando que cavalo de tróia usa em sumo malwares como spyware e ransomware, que tem como foco o roubo de dados, exigir pagamentos para receber de volta seus dados que foram criptografados, ou que sistemas sejam criptografados, os ativos e recursos afetados são os dados, usados para obter ganhos financeiros, o comprometimento de integridade de sistemas por meio da criptografia dos mesmos, dinheiro no caso em que pessoas julgam ser necessário para ter novamente acesso aos dados nos casos de ransomware.

Fontes:

1: https://pt.malwarebytes.com/trojan/

## Keylogger

*O que faz/ o que é:* keylogger se trata de um spyware em que um adversário monitora todo o registro de teclas digitadas por dispositivos sem o devido conhecimento do usuário do dispositivo, ou seja, de maneira imperceptível. No geral, serve para o adversário observar digitação de usuários, a fim de descobrir credenciais, dados sensíveis que possibilitam quebrar privacidade de usuários. 

*Como funciona:* keylogger basicamente informa ao hacker toda e qualquer tecla digitada pelo usuário em seu dispositivo. Entretanto, esse tipo de ataque evoluiu tanto que já pode gravar tela, ações de mouse, copiar o que existe na área de transferência e afins, e o hacker simplesmente visualizar. Então, esse tipo de spyware não se trata apenas de um informador de teclas digitadas, mas todo e qualquer meio de espionar o que usuários fazem em seus dispositivos.

*Operacionalização:* pode infiltrar dispositivos por meio de meios físicos ou sem fio, como pen drives, outros periféricos com ou sem fio, dispositivos podem ser infectados por download de softwares e apps, acesso de sites duvidosos que sugerem cliques que infectam seus dispositivos, e-mails maliciosos, SMSs com links suspeitos.  

*Recursos/ativos afetados:* os ativos e recursos afetados são as informações sensíveis, credenciais e dados pessoais que permitem a hackers mal intencionados usarem deles para obterem ganhos financeiros, assim como para infringir princípios de autenticidade, autorização e privacidade para fazer alguma ação mal intencionada.


Fontes:

1: https://blog.betrybe.com/tecnologia/tudo-sobre-keylogger/

