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

**Como o incidente é detectado?**

* O incidente pode ser detectado por meio de relatórios de usuários ou do monitoramento de e-mails suspeitos.

**Após detectado qual o tempo para iniciar o primeiro procedimento?**

* O primeiro procedimento deve ser iniciado imediatamente após a detecção do incidente.

**Quem são as pessoas que irão executar os procedimentos?**

* A equipe de segurança da informação e os administradores de sistemas são responsáveis por executar os procedimentos.

**Qual o primeiro procedimento que precisa ser executado?**

* O primeiro procedimento deve ser alertar os usuários sobre o phishing e orientá-los a não clicar em links suspeitos ou fornecer informações pessoais ou financeiras.

**Quais os demais procedimentos e em que ordem de prioridade precisam ser executados?**

* A equipe deve identificar a fonte do e-mail de phishing e notificar as autoridades competentes, se necessário. Além disso, a equipe deve avaliar a segurança do sistema e implementar medidas adicionais, como filtros de e-mail mais robustos ou treinamento de conscientização de segurança para os usuários.

**Qual o tempo para executar cada procedimento?**

* O tempo para executar cada procedimento depende da gravidade do ataque e da complexidade do ambiente. No entanto, o primeiro procedimento deve ser executado o mais rápido possível, em questão de minutos.

**Se um procedimento não foi efetivo, qual o próximo procedimento a ser executado?**

* Se um procedimento não foi efetivo, a equipe deve revisar o procedimento e identificar o que pode ter falhado. Em seguida, a equipe deve executar o próximo procedimento de acordo com a ordem de prioridade.

**O que fazer depois do incidente ser resolvido?**

* Após o incidente ser resolvido, a equipe deve realizar uma análise pós-incidente para identificar como o incidente ocorreu, como foi resolvido e quais medidas preventivas podem ser tomadas para evitar futuros ataques de phishing.


## DNS Spoofing

Como o incidente é detectado?
É possível identificar casos suspeitos de DNS spoofing antes mesmo de acontecer. Caso um domínio de um site conhecido tem alguma alteração de caráter e você receba espontaneamente de um email esse tipo de link, possivelmente é uma tentativa de ataque por DNS spoofing visto que pode direcionar o usuário a sites maliciosos. DNS spoofing é uma estratégia para que malwares sejam instalados em seu computador, então ele pode ser identificado por scanners de malwares.
Após detectado qual o tempo para iniciar o primeiro procedimento?
Se um link suspeito é identificado, o correto é manter distância dele. Se ele for clicado acidentalmente, o procedimento a ser feito é remover o mais rápido possível o cache de DNS, evitando que arquivos sejam baixados.
Quem são as pessoas que irão executar os procedimentos?
Administradores de sistemas, a equipe de tecnologia da informação e donos de computadores.
Qual o primeiro procedimento que precisa ser executado?
Evitar clicar em links, assim como remover cache de DNS pelo lado servidor e cliente, embora seja difícil ser feito o mesmo procedimento em todos.
Quais os demais procedimentos e em que ordem de prioridade precisam ser executados?
Utilizar o DNSSEC.
Guardar uma lista de respostas para uma determinada requisição por um intervalo de tempo.
Regularmente realizar verificação de malware em seu computador.

Qual o tempo para executar cada procedimento?
Para a maioria dos procedimentos, leva em torno de minutos.
Se um procedimento não foi efetivo, qual o próximo procedimento a ser executado?
DNS spoofing é difícil de ser contornado desde que todos os malwares sejam removidos rapidamente a ponto de não roubar dados a tempo.
O que fazer depois do incidente ser resolvido?
Manter cotidianamente uma verificação por meio de scanners de malwares e sempre suspeitar de links que levem a sites maliciosos.

## Malware

**Como o incidente é detectado?**

* O malware pode ser detectado por meio de alertas de antivírus, monitoramento de rede e comportamento anômalo em dispositivos e sistemas.

**Após detectado qual o tempo para iniciar o primeiro procedimento?**

* O primeiro procedimento deve ser iniciado imediatamente após a detecção do incidente, para impedir que o malware se espalhe e cause danos maiores.

**Quem são as pessoas que irão executar os procedimentos?**

* A equipe de segurança da informação, a equipe de suporte, a equipe de backup e a equipe de gerenciamento de crise são responsáveis por executar os procedimentos.

**Qual o primeiro procedimento que precisa ser executado?**

* O primeiro procedimento é isolar o dispositivo infectado para impedir que o malware se espalhe para outros dispositivos ou sistemas. Além disso, a equipe deve identificar o tipo de malware e determinar se há backups disponíveis.

**Quais os demais procedimentos e em que ordem de prioridade precisam ser executados?**

* A equipe deve identificar o tipo de malware e determinar sua funcionalidade, quais dados podem ter sido afetados e como o malware se propagou. Em seguida, a equipe deve avaliar o dano causado pelo malware e determinar se há a necessidade de restaurar os dados a partir do backup ou se é possível remover o malware. Além disso, a equipe deve identificar a causa raiz do incidente e tomar medidas para prevenir futuros ataques de malware.

**Qual o tempo para executar cada procedimento?**

* O tempo para executar cada procedimento depende da gravidade do ataque e do número de dispositivos e sistemas infectados. No entanto, o primeiro procedimento deve ser executado o mais rápido possível, em questão de minutos.

**Se um procedimento não foi efetivo, qual o próximo procedimento a ser executado?**

* Se um procedimento não foi efetivo, a equipe deve revisar o procedimento e identificar o que pode ter falhado. Em seguida, a equipe deve executar o próximo procedimento de acordo com a ordem de prioridade.

**O que fazer depois do incidente ser resolvido?**

* Após o incidente ser resolvido, a equipe deve realizar uma análise pós-incidente para identificar como o incidente ocorreu, como foi resolvido e quais medidas preventivas podem ser tomadas para evitar futuros ataques de malware. Além disso, a equipe deve garantir que todos os dispositivos e sistemas infectados sejam corretamente restaurados a partir do backup.

## Engenharia Social

**Como o incidente é detectado?**

* O ataque de engenharia social pode ser detectado por meio de relatos de funcionários ou usuários que receberam solicitações suspeitas de informações confidenciais ou que foram direcionados para sites maliciosos.

**Após detectado qual o tempo para iniciar o primeiro procedimento?**

* O primeiro procedimento deve ser iniciado imediatamente após a detecção do incidente, para impedir que os usuários forneçam informações confidenciais ou que acessem sites maliciosos.

**Quem são as pessoas que irão executar os procedimentos?**

* A equipe de segurança da informação, a equipe de suporte e a equipe de gerenciamento de crise são responsáveis por executar os procedimentos.

**Qual o primeiro procedimento que precisa ser executado?**

* O primeiro procedimento é informar os usuários afetados sobre o incidente e fornecer orientações sobre como evitar serem vítimas de ataques de engenharia social. Além disso, a equipe deve coletar informações sobre o tipo de ataque e determinar se há outros usuários que foram afetados.

**Quais os demais procedimentos e em que ordem de prioridade precisam ser executados?**

* A equipe deve identificar a causa raiz do incidente e tomar medidas para prevenir futuros ataques de engenharia social. Além disso, a equipe deve avaliar se há necessidade de realizar uma investigação mais aprofundada para determinar se houve perda ou acesso não autorizado a dados confidenciais.

**Qual o tempo para executar cada procedimento?**

* O tempo para executar cada procedimento depende da gravidade do ataque e do número de usuários afetados. No entanto, o primeiro procedimento deve ser executado o mais rápido possível, em questão de minutos.

**Se um procedimento não foi efetivo, qual o próximo procedimento a ser executado?**

* Se um procedimento não foi efetivo, a equipe deve revisar o procedimento e identificar o que pode ter falhado. Em seguida, a equipe deve executar o próximo procedimento de acordo com a ordem de prioridade.

**O que fazer depois do incidente ser resolvido?**

* Após o incidente ser resolvido, a equipe deve realizar uma análise pós-incidente para identificar como o incidente ocorreu, como foi resolvido e quais medidas preventivas podem ser tomadas para evitar futuros ataques de engenharia social. Além disso, a equipe deve garantir que os usuários afetados tenham recebido as informações e orientações necessárias para evitar serem vítimas de futuros ataques.

## Força bruta

**Como o incidente é detectado?**

* O incidente pode ser detectado por meio do monitoramento de logs e sistemas de autenticação, que podem alertar quando um grande número de tentativas de login falhas é detectado.

**Após detectado qual o tempo para iniciar o primeiro procedimento?**

* O primeiro procedimento deve ser iniciado imediatamente após a detecção do incidente.

**Quem são as pessoas que irão executar os procedimentos?**

* A equipe de segurança da informação e os administradores de sistemas são responsáveis por executar os procedimentos.

**Qual o primeiro procedimento que precisa ser executado?**

* O primeiro procedimento deve ser bloquear o endereço IP ou intervalo de endereços IPs do atacante, a fim de evitar mais tentativas de login.

**Quais os demais procedimentos e em que ordem de prioridade precisam ser executados?**

* Em seguida, a equipe deve investigar os logs para identificar a origem do ataque e determinar se houve sucesso no login. Se houver, a equipe deve imediatamente alterar as senhas comprometidas e alertar os usuários afetados. Além disso, a equipe deve avaliar a segurança do sistema e implementar medidas adicionais, como políticas de senha mais fortes ou a implementação de autenticação multifator.

**Qual o tempo para executar cada procedimento?**

* O tempo para executar cada procedimento depende da gravidade do ataque e da complexidade do ambiente. No entanto, o primeiro procedimento deve ser executado o mais rápido possível, em questão de minutos.

**Se um procedimento não foi efetivo, qual o próximo procedimento a ser executado?**

* Se um procedimento não foi efetivo, a equipe deve revisar o procedimento e identificar o que pode ter falhado. Em seguida, a equipe deve executar o próximo procedimento de acordo com a ordem de prioridade.

**O que fazer depois do incidente ser resolvido?**

* Após o incidente ser resolvido, a equipe deve realizar uma análise pós-incidente para identificar como o incidente ocorreu, como foi resolvido e quais medidas preventivas podem ser tomadas para evitar futuros ataques de força bruta.

## Cross-Site Scripting (XSS)

**Como o incidente é detectado?**

* O ataque de Cross-Site Scripting pode ser detectado por meio de análise de logs de servidor e de aplicativos, observando se há entradas suspeitas de caracteres ou solicitações de dados incomuns. Além disso, a equipe de segurança pode ser alertada por meio de sistemas de detecção de intrusões ou relatos de usuários sobre falhas ou comportamentos estranhos em um aplicativo.

**Após detectado qual o tempo para iniciar o primeiro procedimento?**

* O primeiro procedimento deve ser iniciado imediatamente após a detecção do incidente, para impedir que o invasor execute outras atividades maliciosas ou obtenha informações confidenciais dos usuários.

**Quem são as pessoas que irão executar os procedimentos?**

* A equipe de segurança da informação, equipe de desenvolvimento de aplicativos e a equipe de suporte ao usuário são responsáveis por executar os procedimentos.

**Qual o primeiro procedimento que precisa ser executado?**

* O primeiro procedimento é identificar e isolar as páginas ou os aplicativos comprometidos que estão exibindo conteúdo malicioso. Em seguida, a equipe deve identificar a extensão do ataque, quais dados foram comprometidos e quais usuários podem ter sido afetados.

**Quais os demais procedimentos e em que ordem de prioridade precisam ser executados?**

* A equipe deve corrigir a vulnerabilidade, remover o código malicioso do aplicativo ou da página e validar todos os dados de entrada e saída para evitar futuros ataques. Além disso, a equipe deve notificar os usuários afetados e fornecer orientações sobre como proteger suas informações. Por fim, a equipe deve revisar todos os códigos do aplicativo em busca de outras vulnerabilidades de XSS.

**Qual o tempo para executar cada procedimento?**

* O tempo para executar cada procedimento depende da gravidade do ataque e da extensão do comprometimento. No entanto, o primeiro procedimento deve ser executado o mais rápido possível, em questão de minutos.

**Se um procedimento não foi efetivo, qual o próximo procedimento a ser executado?**

* Se um procedimento não foi efetivo, a equipe deve revisar o procedimento e identificar o que pode ter falhado. Em seguida, a equipe deve executar o próximo procedimento de acordo com a ordem de prioridade.

**O que fazer depois do incidente ser resolvido?**

* Após o incidente ser resolvido, a equipe deve realizar uma análise pós-incidente para identificar como a vulnerabilidade de XSS ocorreu, como foi resolvida e quais medidas preventivas podem ser tomadas para evitar futuros ataques. Além disso, a equipe deve garantir que os usuários afetados tenham recebido as informações e orientações necessárias para proteger suas informações e evitar futuros ataques.

## Ransomware

**Como o incidente é detectado?**

* O incidente pode ser detectado por meio de alertas de antivírus ou por usuários que notificam a equipe de segurança da

informação sobre a criptografia de seus arquivos.

**Após detectado qual o tempo para iniciar o primeiro procedimento?**

* O primeiro procedimento deve ser iniciado imediatamente após a detecção do incidente.

**Quem são as pessoas que irão executar os procedimentos?**

* A equipe de segurança da informação e os administradores de sistemas são responsáveis por executar os procedimentos.

**Qual o primeiro procedimento que precisa ser executado?**

* O primeiro procedimento deve ser isolar a máquina infectada da rede para impedir a propagação do ransomware. A equipe também deve notificar as autoridades competentes, se necessário.

**Quais os demais procedimentos e em que ordem de prioridade precisam ser executados?**

* A equipe deve avaliar a extensão do dano e identificar se há backups disponíveis para restaurar os arquivos criptografados. Se houver backups, a equipe deve restaurá-los. Se não houver backups, a equipe deve avaliar se é possível descriptografar os arquivos. Se não for possível descriptografar os arquivos, a equipe deve avaliar se é viável pagar o resgate para obter a chave de descriptografia.

**Qual o tempo para executar cada procedimento?**

* O tempo para executar cada procedimento depende da gravidade do ataque e da complexidade do ambiente. No entanto, o primeiro procedimento deve ser executado o mais rápido possível, em questão de minutos.

**Se um procedimento não foi efetivo, qual o próximo procedimento a ser executado?**

* Se um procedimento não foi efetivo, a equipe deve revisar o procedimento e identificar o que pode ter falhado. Em seguida, a equipe deve executar o próximo procedimento de acordo com a ordem de prioridade.

**O que fazer depois do incidente ser resolvido?**

* Após o incidente ser resolvido, a equipe deve realizar uma análise pós-incidente para identificar como o incidente ocorreu, como foi resolvido e quais medidas preventivas podem ser tomadas para evitar futuros ataques de ransomware. Além disso, a equipe deve garantir que todos os sistemas afetados sejam corretamente protegidos e atualizados para prevenir novas infecções.


## Man-in-the-Middle (MITM)

**Como o incidente é detectado?**

* O ataque Man in the Middle pode ser detectado por meio de análises de tráfego de rede, observando se há alterações no tráfego normal. Além disso, os usuários podem relatar problemas de conexão ou erros de certificado ao acessar sites ou aplicativos.

**Após detectado qual o tempo para iniciar o primeiro procedimento?**

* O primeiro procedimento deve ser iniciado imediatamente após a detecção do incidente, para impedir que o invasor obtenha informações confidenciais ou realize outras atividades maliciosas.

**Quem são as pessoas que irão executar os procedimentos?**

* A equipe de segurança da informação e a equipe de rede são responsáveis por executar os procedimentos.

**Qual o primeiro procedimento que precisa ser executado?**

* O primeiro procedimento é identificar os pontos de acesso da rede em que o ataque está ocorrendo. A equipe deve usar ferramentas de monitoramento de rede para identificar os nós envolvidos no ataque Man in the Middle.

**Quais os demais procedimentos e em que ordem de prioridade precisam ser executados?**

* Em seguida, a equipe deve tomar medidas para impedir o ataque, como bloquear os endereços IP dos nós maliciosos e atualizar os filtros de segurança da rede. Além disso, a equipe deve notificar os usuários afetados sobre o incidente e fornecer orientações sobre como evitar serem vítimas de ataques Man in the Middle.

**Qual o tempo para executar cada procedimento?**

* O tempo para executar cada procedimento depende da gravidade do ataque e do número de nós envolvidos. No entanto, o primeiro procedimento deve ser executado o mais rápido possível, em questão de minutos.

**Se um procedimento não foi efetivo, qual o próximo procedimento a ser executado?**

* Se um procedimento não foi efetivo, a equipe deve revisar o procedimento e identificar o que pode ter falhado. Em seguida, a equipe deve executar o próximo procedimento de acordo com a ordem de prioridade.

**O que fazer depois do incidente ser resolvido?**

* Após o incidente ser resolvido, a equipe deve realizar uma análise pós-incidente para identificar como o ataque ocorreu, como foi resolvido e quais medidas preventivas podem ser tomadas para evitar futuros ataques Man in the Middle. Além disso, a equipe deve garantir que os usuários afetados tenham recebido as informações e orientações necessárias para evitar serem vítimas de futuros ataques.

## Injeção SQL (SQL Injection)

**Como o incidente é detectado?**

* O ataque de Injeção SQL pode ser detectado por meio de análise de logs de servidor e de aplicativos, observando se há entradas suspeitas de caracteres ou solicitações de banco de dados incomuns. Além disso, a equipe de segurança pode ser alertada por meio de sistemas de detecção de intrusões ou relatos de usuários sobre falhas ou comportamentos estranhos em um aplicativo.

**Após detectado qual o tempo para iniciar o primeiro procedimento?**

* O primeiro procedimento deve ser iniciado imediatamente após a detecção do incidente, para impedir que o invasor obtenha informações confidenciais ou execute outras atividades maliciosas.

**Quem são as pessoas que irão executar os procedimentos?**

* A equipe de segurança da informação, equipe de desenvolvimento de aplicativos e a equipe de administração de banco de dados são responsáveis por executar os procedimentos.

**Qual o primeiro procedimento que precisa ser executado?**

* O primeiro procedimento é isolar o aplicativo ou o servidor comprometido para impedir que o invasor continue explorando a vulnerabilidade. Em seguida, a equipe deve identificar a extensão do ataque, quais dados foram comprometidos e quais usuários podem ter sido afetados.

**Quais os demais procedimentos e em que ordem de prioridade precisam ser executados?**

* A equipe deve corrigir a vulnerabilidade e atualizar o aplicativo ou o servidor comprometido. Além disso, a equipe deve revisar todos os códigos do aplicativo e do banco de dados em busca de outras vulnerabilidades de injeção SQL. Por fim, a equipe deve notificar os usuários afetados e fornecer orientações sobre como proteger suas informações.

**Qual o tempo para executar cada procedimento?**

* O tempo para executar cada procedimento depende da gravidade do ataque e da extensão do comprometimento. No entanto, o primeiro procedimento deve ser executado o mais rápido possível, em questão de minutos.

**Se um procedimento não foi efetivo, qual o próximo procedimento a ser executado?**

* Se um procedimento não foi efetivo, a equipe deve revisar o procedimento e identificar o que pode ter falhado. Em seguida, a equipe deve executar o próximo procedimento de acordo com a ordem de prioridade.

**O que fazer depois do incidente ser resolvido?**

* Após o incidente ser resolvido, a equipe deve realizar uma análise pós-incidente para identificar como a vulnerabilidade de injeção SQL ocorreu, como foi resolvida e quais medidas preventivas podem ser tomadas para evitar futuros ataques. Além disso, a equipe deve garantir que os usuários afetados tenham recebido as informações e orientações necessárias para proteger suas informações e evitar futuros ataques.

## Zero day exploit

**Como o incidente é detectado?**

* Normalmente é detectado o ataque no “dia zero” ou nos primeiros dias em que aplicações são colocadas em produção, por meio da indisponibilidade deles. Ou ainda, por meio da identificação de  scripts suspeitos injetados por meio das vulnerabilidades.

**Após detectado qual o tempo para iniciar o primeiro procedimento?**

* Logo aṕos a descoberta do ataque, pois desenvolvedores detêm de zero dias para contornar a situação, ou seja, em questão de minutos.

**Quem são as pessoas que irão executar os procedimentos?**

* Desenvolvedores e administradores de sistemas e o pessoal da equipe de segurança da informação. 

**Qual o primeiro procedimento que precisa ser executado?**

* O primeiro procedimento a ser feito é temporariamente suspender o serviço e encontrar as vulnerabilidades utilizadas e outras possíveis, por meio de uma bateria de testes.

**Quais os demais procedimentos e em que ordem de prioridade precisam ser executados?**

* Recomenda-se que a equipe avise os usuários que baixaram os possíveis malwares e que notifique eles de que devem remover imediatamente tais scripts. Camadas de segurança também devem ser implementadas, no caso em que existem seríssimas vulnerabilidades, pelos desenvolvedores e administradores de sistemas.

**Qual o tempo para executar cada procedimento?**

* Depende da gravidade do ataque e da complexidade/tamanho do ecossistema da aplicação. Para o primeiro procedimento, o tempo para executar é imediatamente, o mais rápido possível. Para notificar os usuários que baixaram os malwares, independente da quantidade deles, deve ser o mais rápido possível. A aplicação de camadas de segurança é bem variável, a depender de quantas forem necessárias. 

**Se um procedimento não foi efetivo, qual o próximo procedimento a ser executado?**

* Primeiro deve-se revisar o procedimento e identificar o que pode ter falhado. Na sequência, a equipe deve executar os demais procedimentos de acordo com a ordem de prioridade. 


**O que fazer depois do incidente ser resolvido?**

* O que deve ser feito é uma análise identificando como o incidente ocorreu, como foi resolvido e quais medidas preventivas devem ser tomadas em eventuais eventos de zero day exploit.

## Trojan horse

**Como o incidente é detectado?**

* Normalmente um cavalo de tróia aparece em um sistema por meio da exibição de um erro de DLL, arquivos perdidos, remoção de firewalls ou sistemas falhando.

**Após detectado qual o tempo para iniciar o primeiro procedimento?**

* O primeiro procedimento deve ser iniciado imediatamente.

**Quem são as pessoas que irão executar os procedimentos?**

* Normalmente ataques de cavalo de tróia ocorrem em computadores pessoais ou em computadores empresariais, logo donos de computadores pessoais e técnicos da tecnologia da informação, respectivamente, devem exercer procedimento neles.

**Qual o primeiro procedimento que precisa ser executado?**

* Remover imediatamente o vírus, seja de forma automática por meio de ferramentas antivírus que removam malwares ou remover de forma manual, por mais que seja difícil.

**Quais os demais procedimentos e em que ordem de prioridade precisam ser executados?**

* Quais os demais procedimentos e em que ordem de prioridade precisam ser executados?
É altamente recomendável fazer verificações periódicas com scanner e ferramentas que detectam malwares de trojan horse para ter ciência de que não existem softwares com malwares.

**Qual o tempo para executar cada procedimento?**

* Se feito de maneira manual, depende do tamanho do malware e do conhecimento do agente que fizer a remoção do malware, mas se removido com ferramentas que identifiquem e removam malwares, podem demorar desde minutos até horas.

**Se um procedimento não foi efetivo, qual o próximo procedimento a ser executado?**

* Identificar o porquê os malwares ainda afetam mesmo após terem sido removidos. Entrar em contato com especialistas e até mesmo suporte das ferramentas utilizadas para remover os malwares para solicitar ajuda.

**O que fazer depois do incidente ser resolvido?**

* Periodicamente utilizar scanners para identificar cavalos de tróia e caso necessário fazer uso de ferramentas que removam os malwares.
 
## Keylogger

**Como o incidente é detectado?**

* A dificuldade para detectar keyloggers é complicada, muitos keyloggers permanecem no escuro por muito tempo sem ser identificado por scanners de malwares pois por vezes falham, considerando que keyloggers na maioria das vezes não deixam problemas perceptíveis.

**Após detectado qual o tempo para iniciar o primeiro procedimento?**

* Deve ser iniciado imediatamente.

**Quem são as pessoas que irão executar os procedimentos?**

* Administradores de sistemas e a equipe de tecnologia da informação.

**Qual o primeiro procedimento que precisa ser executado?**

* Remover todos os programas suspeitos instalados.

**Quais os demais procedimentos e em que ordem de prioridade precisam ser executados?**

* Fazer backup de arquivos e reinstalar o sistema.

**Qual o tempo para executar cada procedimento?**

* Dependendo do tamanho do malware, se pequeno se resolve em questão de minutos e em grande tamanho até horas.

**Se um procedimento não foi efetivo, qual o próximo procedimento a ser executado?**

* Se o primeiro procedimento falhar, o procedimento recomendável na sequência é fazer backup de arquivos, posteriormente fazer a instalação de todo o sistema novamente.

**O que fazer depois do incidente ser resolvido?**

* Fazer uso de ferramentas que possibilitem com maior assertividade identificar ataques de keylogger.
