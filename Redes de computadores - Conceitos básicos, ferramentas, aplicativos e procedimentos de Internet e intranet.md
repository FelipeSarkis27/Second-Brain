# Redes de Computadores
## Diferença entre internet e intranet
- A diferença entre a internet e a intranet é que a Internet representa a rede mundial de todos os computadores e está aberta para o acesso de todos, sem qualquer restrição, enquanto a intranet também é uma forma de internet, mas é usada por um grupo específico de empresas ou pessoas e não está aberto para aqueles que estão fora de um grupo seleto
- O framework que localiza um recurso na internet ou intranet é a URL, Uniform Resource Locator, ou Localizador Uniforme de Recursos. Não existe um navegador específico para internet ou intranet, ambos podem ser usados no mesmo navegador.

## Endereços URL
- URL - Uniform Resouce Locator: Localizador Uniforme de Recursos
- URI - Uniform Resouce Identify: Identificador Uniforme de Recusos
- URN - Uniform Resourse Name: Nome Padrão do Recurso

### Formação da URL
- Uma URL é formada por: protocolo://máquina/caminho/recurso
	- Protocolo: padrão de comunicação
	- Máquina: nome do computador
	- Caminho: pastas no computador
	- Recurso: nome do arquivo acessado

### Formação da URI
- esquema://domínio:porta/caminho/recurso?querystring#fragmento

- Esquema é o protocolo que será usado na transferência
- Domínio é o nome da máquina, o nome do site. O Domínio poderá ser dividido em subdomnínios.
- Dois pontos e porta indica qual porta TCP será usada na transferência.
- Caminho indica as pastas do servidor, que é um computador com muitos arquivos em pastas.
- Recurso é o nome do arquivo que está sendo acessado.
- ?querystring é para transferir um parâmetro de pesquisa, usado especialmente em sites seguros.
- fragmento é para espeficicar qual é a localização da informação dentro do recurso acessado (marcas), não irá começar pelo início e sim por um ponto específico.

![[Pasted image 20210907085654.png]]
- HTTPS é o protocolo seguro, já o HTTP seria um protocolo não seguro, pois o com S no final usa criptografia de informações, e o outro não.
- WWW é uma divisão multimídia do site, como documentos, imagens, músicas e vídeos.
- Cesgranrio é o domínio, o nome da máquina.
- ORG é uma organização não governamental
- BR é no Brasil essa ORG.
- Concursos é o caminho, que indica as pastas do server.
- BancodoBrasil é uma subpasta dentro da pasta concursos.
- edital.pdf é o recurso que estamos acessando, o nome do arquivo propriamente dito.
- ? é o querystring para transferir o parâmetro de pesquisa.
- conteúdo é o acesso ao conteúdo desse edital.

- URN é desde a designação da máquina (o nome do site que seria o domínio) até o final do endereço.
- URL é do protocolo até o final do nome do recurso.
- URI é o endereço todo.

## VPN
![[Pasted image 20210907091253.png]]
- É um túnel que conecta um usuário remeto a uma empresa / universidade / instituição, se um usuário mal intencionado tentar acessar essas informações não conseguirá, pois o ambiente é seguro. A VPN liga essas duas partes dentro de um ambiente inseguro que é a internet.

## Protocolos
### FTP
- FTP: File transfer protocol
- Utiliza duas portas TCP (Transmission Control Protocol - Protocolo de controle de transmissão), é um conjunto de regras padronizadas que permitem que computadores se comuniquem em uma rede como a internet.
- Servidor FTP: disponibiliza arquivos para o cliente FTP, que é um usuário cadastrado e autorizado.

### HTTP
- HTTP: Hyper Text Transfer Protocol
- utiliza a porta 80
- O navegador faz uma requisição e recebe uma resposta, no caso para achar páginas web.

### HTTPS
- HTTPS: Hyper Text Transfer Protocol Secure
- Utiliza a porta 443
- O navegador faz a negociação da criptogracia que será usada para depois ser usada, depois transfere os dados como no HTTP.

## Referências
- https://www.youtube.com/watch?v=-5yj8iEzMYU
- https://www.minhaconexao.com.br/blog/voce-sabe-a-diferenca-entre-a-internet-e-intranet/
- https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjwkoSr7uzyAhWOqJUCHetnAJoQFnoECAoQAw&url=https%3A%2F%2Fwww.avast.com%2Fpt-br%2Fc-what-is-tcp-ip&usg=AOvVaw2IzgCsHu5OY2eUB5auL-Bf