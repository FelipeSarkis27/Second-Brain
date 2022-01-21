# Segurança da Informação
## Conceitos que já caíram no Concurso da banca da Cesgranrio
- ISO 27000: 2018 e 27002: 2013
- E-mail: Phishing, trojan proxy, Worm
- Ataque passivo
- Controle de acesso
- Criptoanálise
- Ataque DDos
- Gestão de continuidade do negócio
- Engenharia social
- Chaves secretas (de criptografia) e chaves públicas

### ISO
- A ISO 27000 define os sistemas de segurança da informação eo vocabulário utilizado. 
- Confidenciabilidade pertence ao domínio de "controle de acesso".
- Criticidade pertence ao domínio de "Gerenciamento de continuidade de negócios", que tem a ver com realizar procedimentos de cópia de segurança, proteger o acesso, evitar a divulgação de informações.
- Prazo de retenção ao domínio de "Organização da segurança da informação"	

### Ataques
#### Ataque passivo
- É uma forma de ataque que você irá acessar as informações sem que o usuário/sistema perceba que está sendo invadido.
#### Ataque DDos
-  Distributed Denial of service, ou ataque distribuído de negação de serviço, vários dispositivos (zumbis controlados por um hacker) acessam um servidor fazendo com que ele caia ficando sobrecarregado ou não aceite novos dispositivos.
#### Engenharia Social
- São técnicas que se utiliza para convencer uma pessoa a entregar informações, por senso de urgência, submissão, autoridade, falsidade de identidade.
#### Phishing
- Se joga uma ísca enviada por uma mensagem e quando o usuário clica nesse link ele acaba fornecendo suas informações para o outro usuário.
#### Trojan
- Cavalo de tróia, se entrega um "presente" para o usuário, que pode ser um vídeo, e quando o arquivo é executado o trojan é ativado. Ele desativa as defesas do PC (antivírus; antimalware e firewall) e abre as portas TCP do PC para que o hacker possa entrar.
##### Tipos de Trojan
- Trojan Downloader: Instala outros códigos maliciosos obtidos através de sites da internet.
- Trojan Dropper: Instala outros códigos maliciosos, embutidos no próprio código do trojan.
- Trojan Backdoor: Inclui backdoors, possibilitando o acesso remoto no próprio código do trojan.
- Trojan DoS: Instala ferramentas de negação de serviço e as utiliza para desferir ataques.
- Trojan destrutivo: Semelhante a vírus, altera/apaga dados, formata disco, pode deixar o pc fora de operação.
- Trojan clicker: redireciona a navegação do usuário para sites específicos, com o objetivo de aumentar a quantidade de acessos a esses sites ou paresentar propagandas.
- Trojan proxy: Instala um servidor de proxy, possibilitando que o computador seja utilizado para navegação anônima e para envio de Spam.
- Trojan Spy: Instala programa spyware e os utiliza para coletar informações sensíveis, como senhas e números de cartão de crédito, e enviá-las ao atacante.
- **Trojan Banker ou bancos: Coleta dados bancários do usuário, através da instalação de programas spyware que são ativados quando sites de internet banking são acessados. É similar ao Trojan spy mas com objetivos mais específicos. **
#### Worms
- São vermes que infectam dispositivos e se propagam para outros dispositivos trabalhando de forma autônoma, se replicando sem a interferência de um usuário.

### Criptografias
- É um embaralhamento de informações para as proteger criando um resumo com as informações que servem para decodificar e para isso é necessário realizar a criptoanálise, que é justamente a tentativa de descoberta do texto cifrado e/ou a lógica utilizada em sua encriptação (chave). 
- Para decodificar uma informação é necessária uma chave, que são secretas, e podem ser públicas, divulgadas pela autoridade certificadora e que valida essas chaves, ou privadas, que são campartilhadas entre cada um dos usuários e deve ser mantida em sigilo.
![[Pasted image 20210816210902.png]] 

## referências 
- https://www.youtube.com/watch?v=gwwlUrD7Qdo