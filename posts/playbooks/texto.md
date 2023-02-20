## Ataques

- [Ataque de força bruta](#ataque-de-força-bruta): Este tipo de ataque envolve a tentativa de adivinhar uma senha ou chave de criptografia por meio de tentativas repetidas e automatizadas de diferentes combinações de caracteres.
- [Ataque DDoS (Distributed Denial of Service)](#ataque-ddos-distributed-denial-of-service): Os atacantes usam uma rede de computadores comprometidos para enviar uma grande quantidade de tráfego para um servidor, tornando-o inacessível para os usuários legítimos.
- [Ataque de Phishing](#ataque-de-phishing): Os atacantes enviam e-mails ou mensagens de texto que parecem legítimos para enganar as pessoas a revelar informações pessoais, como senhas, informações de cartão de crédito e dados bancários.
- [Ransomware](#ransomware): Os atacantes criptografam os dados do usuário, tornando-os inacessíveis e exigindo um pagamento em dinheiro para desbloqueá-los.
- [Malware](#malware): Este termo genérico refere-se a qualquer tipo de software malicioso que é projetado para prejudicar computadores ou dispositivos móveis.
- [Ataque de Engenharia Social](#ataque-de-engenharia-social): Este tipo de ataque envolve a manipulação psicológica das pessoas para obter informações confidenciais ou acesso a sistemas de computador.
- [Ataque de Man-in-the-Middle (MITM)](#ataque-de-man-in-the-middle-mitm):Os atacantes interceptam as comunicações entre dois sistemas, permitindo que eles roubem informações ou injetem dados maliciosos.
- [Ataque de Injeção SQL](#ataque-de-injeça-sql): Os atacantes exploram vulnerabilidades em um site para injetar código SQL malicioso, permitindo que eles acessem ou manipulem o banco de dados do site.
- [Ataque de Cross-Site Scripting (XSS)](#ataque-de-cross-site-scripting-xss): Os atacantes injetam código malicioso em páginas da web para roubar informações dos usuários ou sequestrar sessões do usuário.
- [Ataque de Acesso Remoto](#ataque-de-acesso-remoto): Os atacantes exploram vulnerabilidades em um sistema para obter acesso remoto e controlar o computador sem o conhecimento do usuário.

## Ataque de força bruta

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

## Ataque DDoS (Distributed Denial of Service)

**Como o incidente é detectado?**

* O incidente pode ser detectado por meio do monitoramento de tráfego de rede, que pode alertar quando um grande volume de tráfego malicioso é detectado.

**Após detectado qual o tempo para iniciar o primeiro procedimento?**

* O primeiro procedimento deve ser iniciado imediatamente após a detecção do incidente.

**Quem são as pessoas que irão executar os procedimentos?**

* A equipe de segurança da informação, administradores de rede e provedores de serviços de internet (ISP) são responsáveis por executar os procedimentos.

**Qual o primeiro procedimento que precisa ser executado?**

* O primeiro procedimento deve ser contatar o provedor de serviços de internet (ISP) para solicitar ajuda na mitigação do ataque.

**Quais os demais procedimentos e em que ordem de prioridade precisam ser executados?**

* A equipe deve implementar medidas para mitigar o impacto do ataque, como bloquear o tráfego malicioso e limitar o acesso ao sistema. Além disso, a equipe deve tentar identificar a origem do ataque e notificar as autoridades competentes, se necessário. Se o ataque continuar, a equipe pode recorrer a serviços de mitigação de DDoS de terceiros para ajudar a aliviar a carga.

**Qual o tempo para executar cada procedimento?**

* O tempo para executar cada procedimento depende da gravidade do ataque e da complexidade do ambiente. No entanto, o primeiro procedimento deve ser executado o mais rápido possível, em questão de minutos.

**Se um procedimento não foi efetivo, qual o próximo procedimento a ser executado?**

* Se um procedimento não foi efetivo, a equipe deve revisar o procedimento e identificar o que pode ter falhado. Em seguida, a equipe deve executar o próximo procedimento de acordo com a ordem de prioridade.

**O que fazer depois do incidente ser resolvido?**

* Após o incidente ser resolvido, a equipe deve realizar uma análise pós-incidente para identificar como o incidente ocorreu, como foi resolvido e quais medidas preventivas podem ser tomadas para evitar futuros ataques DDoS.

## Ataque de Phishing

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

## Ataque de Engenharia Social

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

## Ataque de Man-in-the-Middle (MITM)

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

## Ataque de Injeção SQL

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

## Ataque de Cross-Site Scripting (XSS)

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

## Ataque de Acesso Remoto

**Como o incidente é detectado?**

* O ataque de acesso remoto pode ser detectado por meio de sistemas de detecção de intrusões, análise de logs de servidor e monitoramento de tráfego de rede. Também pode ser detectado por relatos de usuários sobre atividades suspeitas em seus dispositivos.

**Após detectado qual o tempo para iniciar o primeiro procedimento?**

* O primeiro procedimento deve ser iniciado imediatamente após a detecção do incidente, para impedir que o invasor execute outras atividades maliciosas ou obtenha informações confidenciais.

**Quem são as pessoas que irão executar os procedimentos?**

* A equipe de segurança da informação, a equipe de suporte ao usuário e a equipe de TI são responsáveis por executar os procedimentos.

**Qual o primeiro procedimento que precisa ser executado?**

* O primeiro procedimento é desativar o acesso remoto comprometido, seja desativando o serviço ou desconectando o dispositivo do acesso à rede. Em seguida, a equipe deve identificar a extensão do ataque, quais sistemas foram comprometidos e quais dados foram acessados.

**Quais os demais procedimentos e em que ordem de prioridade precisam ser executados?**

* A equipe deve avaliar se houve roubo de dados e notificar as autoridades competentes, se necessário. Além disso, a equipe deve verificar todos os dispositivos de rede e sistemas em busca de outras vulnerabilidades ou dispositivos comprometidos. A equipe também deve implementar medidas de segurança adicionais, como autenticação de dois fatores e criptografia, para impedir futuros ataques.

**Qual o tempo para executar cada procedimento?**

* O tempo para executar cada procedimento depende da gravidade do ataque e da extensão do comprometimento. No entanto, o primeiro procedimento deve ser executado o mais rápido possível, em questão de minutos.

**Se um procedimento não foi efetivo, qual o próximo procedimento a ser executado?**

* Se um procedimento não foi efetivo, a equipe deve revisar o procedimento e identificar o que pode ter falhado. Em seguida, a equipe deve executar o próximo procedimento de acordo com a ordem de prioridade.

**O que fazer depois do incidente ser resolvido?**

* Após o incidente ser resolvido, a equipe deve realizar uma análise pós-incidente para identificar como o acesso remoto foi comprometido, como foi resolvido e quais medidas preventivas podem ser tomadas para evitar futuros ataques. Além disso, a equipe deve garantir que os usuários afetados tenham recebido as informações e orientações necessárias para proteger suas informações e evitar futuros ataques. A equipe também deve revisar e atualizar as políticas de segurança da informação e o plano de resposta a incidentes.
