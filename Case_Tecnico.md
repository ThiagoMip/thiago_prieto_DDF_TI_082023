<br />

<h1 align="center"><strong>Analista de suporte Júnior<strong/></h1>

### Case 1:
Para implementar uma análise de dados eficiente para estar em contato constante com a satisfação do cliente e a eficiência da equipe de suporte da plataforma Dadosfera, eu utilizaria a ferramenta Zendesk para a coleta e análise de dados importantes como o feedback dos clientes, para que a equipe de suporte tenha acesso a satisfação dos clientes referentes ao atendimento. Também seria importante coletar informações sobre quais problemas são recorrentes e necessitam de uma verificação.

### Case 3:
A gestão de acesso é algo crucial para que as contas dos clientes e até funcionários fiquem seguras, para a plataforma da Dadosfera eu sugeriria a utilização de Autenticação de dois fatores, este método vem sendo utilizado por diversas empresas no mundo, pois este modelo de verificação sempre solicitara um código que será enviado por SMS ou gerado por um aplicativo de autenticação (Authenticator, Google Authenticator). Aumentando significativamente a segurança para o usuário. Também pode ser utilizada uma política de senha forte, no qual o usuário deverá criar a senha utilizando uma combinação de letras maiúsculas e minúsculas, números, caracteres especiais e até um tamanho mínimo de 10 caracteres.

### Case 5:
``` sh
SELECT * FROM users_emails WHERE data_cadastro >= DATE_SUB(NOW(), INTERVAL 30 DAY);
```

#### SELECT * FROM users_emails
* Nesta parte do código selecionaremos todas os campos presentes dentro da tabela [users_emails]()
#### WHERE data_cadastro >=
* Neste trecho do código estamos criando uma condição específica para a busca no qual será usuários que a coluna [data_cadastro] será maior   ou igual a 30 dias.
#### DATE_SUB(NOW(), INTERVAL 30 DAY)
 * No final do código iremos utilizar a função [DATE_SUB] no qual irá subtrair um intervalo específico de tempo, para isso é necessário 2      argumentos, o primerio argumento [NOW()] é uma função que retorna a data e hora atual, enquanto o segundo argumento [INTERVAL 30 DAY]       esta sendo utilizado para retirar 30 dias do primeiro argumento.
  
