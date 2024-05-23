# FIAP - 3° Checkpoint - Server-Side Template Injection

## Introdução
Checkpoint realizado com o intuito de colocar em prática todos os conhecimentos sobre vulnerabilidades web na matéria de Web Exploit, ministrada pelo [Professor Rafael Trassi](https://www.linkedin.com/in/rafael-trassi/).

## Feito por

- Matheus Rosa

## Vulnerabilidade

A Server-Side Template Injection ocorre quando um invasor é capaz de usar a sintaxe nativa do modelo para injetar uma carga maliciosa em um modelo, que é então executado no lado do servidor.

Os mecanismos de modelo são projetados para gerar páginas da web combinando modelos fixos com dados voláteis. Ataques de injeção de modelo no servidor podem ocorrer quando a entrada do usuário é concatenada diretamente em um modelo, em vez de ser transmitida como dados. Isso permite que invasores injetem diretivas de modelo arbitrárias para manipular o mecanismo de modelo, muitas vezes permitindo que eles assumam o controle total do servidor. Como o nome sugere, as cargas úteis de injeção de modelo no lado do servidor são entregues e avaliadas no lado do servidor, tornando-as potencialmente muito mais perigosas do que uma injeção típica de modelo no lado do cliente.

### Print da Conta 
* Envie um print da área de detalhes da conta após ter logado
<img src="Imagens/conta.png">
