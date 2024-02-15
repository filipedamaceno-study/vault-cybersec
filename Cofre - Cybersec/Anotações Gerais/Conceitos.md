---
Date: 01-02-2024
Type: summary
Theme:
Summary: "Resumo de alguns conceitos gerais"
---
#  [[Conceitos]]
## Spoofing:
Também conhecido como ataque de falsificação. É uma situação em que uma pessoa ou programa se identifica com sucesso como outro falsificando dados, para obter uma vantagem. Um exemplo seria o sequestro de um navegador, redirecionando o usuário de um site legitimo para um fraudulento de aparência semelhante. Também conhecido como spoofing de IP, que diferente do spoofing de e-mails, tem como alvo uma rede. O invasor tenta obter acesso não autorizado a um sistema, enviando mensagens com um endereço IP falso ou “disfarçado” para parecer que a mensagem veio de uma fonte confiável. Para fazer isso, é utilizado um endereço IP de um host legítimo e são alterados alguns cabeçalhos dos pacotes enviados. Já o spoofing de e-mail muitas vezes envolve itens como solicitações de dados pessoais ou transações financeiras. Parecem ser de remetentes confiáveis, como clientes, colegas de trabalho ou gerentes, mas foram enviados por criminosos. Além disso, muitas vezes podem conter anexos que, quando abertos, instalam malware como cavalos de troia ou vírus. Em muitos casos, o malware é projetado para ir além da infecção do computador, espalhando-se em toda sua rede.

## Sniffing: 
Corresponde ao roubo ou interceptação de dados capturando o tráfego de rede usando um aplicativo para tal, conhecido como sniffer. Quando os dados são transmitidos pelas redes, se os pacotes não forem criptografados, os dados contidos no pacote de rede poderão ser lidos pelo aplicativo. Assim, um invasor pode analisar a rede e obter informações para eventualmente causa o travamento ou a corrupção da rede ou até ler as comunicações que estão trafegando. Podem ser comparados com os grampos telefônicos. Os invasores podem detectar informações de uma rede, incluindo tráfego de e-mail (SMTP, POP, tráfego IMAP), tráfego da Web (HTTP), tráfego FTP (autenticação Telnet, senhas FTP, SMB, NFS) e muito mais. Para se prevenir contra ataques de sniffing, as organizações devem ficar longe de aplicativos que usam protocolos não seguros e preferir protocolos como HTTPS, SFTP e SSH. Caso seja necessário usar qualquer protocolo não seguro, toda transmissão de dados deve ser criptografada.

## Active Sniffing: 
Nos ataques de Active Sniffing, o invasor rouba pacotes de dados manipulando redes switch-based. A maioria das redes hoje usa um switch, que é uma ferramenta conectando dois endpoints de uma rede. O pacote de dados é enviado por switches para uma porta especifica como um MAC Address. Os invasores exploram isso injetando trafego na LAN. Exemplos comuns de Active Sniffing são MAC flooding, DNS spoofing, ARP spoofing, etc.

## Passive Sniffing: 
Acontece a partir de hubs e redes sem fio, onde os atacantes usam o MAC Address para ler a porta de destino do pacote de dados. Não é feito nenhuma tipo de comunicação direta com o alvo. A maioria dos programas sniffers são difíceis de serem detectados exatamente por serem passivos.

## Phishing: 
Uma ameaça que consiste em mensagens falsas enviadas por hackers que se passam por empresas ou pessoas confiáveis. A forma mais comum é por meio de e-mails, se utilizando de domínios parecidos com e-mails verdadeiros. Geralmente se usam de tons alarmantes para atrair a atenção da vítima.

## Baiting: 
Mais uma técnica que se utiliza de engenharia social, dessa vez prometendo algum tipo de recompensa para a vítima para que ela acesse um site ou baixe algo malicioso. Também pode ser utilizado offline a partir de pen drives, provocando uma curiosidade da vítima a utilizar um pen drive achado. Baiting é considerado eficiente exatamente por explorar a natureza humana, geralmente a ganancia e a curiosidade da vítima.

## Vishing:
Phishing por meio de chamadas telefônicas (voice phishing). Usando de técnicas de engenharia social, buscam convencer vitimas com mensagens automáticas ou se passando por alguém que precisa confirmar dados pessoais.

## Smishing: 
Phishing realizado por sms ou mensagem para celular. Geralmente redirecionam para algum site que faz coleta de informações com uma desculpa de atualização cadastral e focam dados como _nome, endereço, cpf, redes sociais_ e afins.