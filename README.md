# Hospedagens grátis

## Com suporte ao PHP, ao MySQL e cia

Os melhores serviços free que conheço. Se conhece mais algum que não foi listado, por favor me mande um Issue para que eu adicione na lista.

## Atualização
Depois de alguns testes, atualmente a melhor hospedagem free que conheço é o Heroku, que inclkusive usa git para enviar os arquivos para o servidor, que é eficiente e importante em nossos dias.

## Justificativa

Como sempre me deu muito trabalho encontrar uma boa hospedagem free com suporte ao PHP e com MySQL, então resolvi criar este repositório para compartilhar. Sem contar que geralmente tem uma baixa performance. Isso normalmente nos força a usar seus planos comerciais.

## Alerta

As contas free servem apenas para testes e iniciar seu aprendizado, pois todas as que conheço tem diversas restrições e limitações que impedem de se criar um projeto para se colocar em produção.


### Freehostia

Meu preferido - https://www.freehostia.com/

Bom hosting free com suporte ao PHP, MySQL e cia

Pelo gerenciador de arquivos do site podemos enviar arquivos, inclusive compactados, com até 2MB e ele também descompacta

Para arquivos e pastas maiores criar uma conta de FTP. Minha sugestão é usar o Filezilla com SFTP

- Requer que você tenha um domínio para criar e usar a conta (Dica: É bom ter um domínio para testes e estas hospedagens)
- PHP - várias versões, inclusive 7.4 e 8. Configurações no php.ini
- MySQL - 1 banco com até 10MB, com phpMyAdmin e até acesso remoto
- Abrigar até 5 domínios com gerenciamento
- 250MB Disk Space
- 6GB Monthly Traffic
- 3 E-mail Accounts e com webmail
- Instalador com 1 clique: Joomla, WordPress, Laravel e outros
- Diretório web - /home/www


### Freehostingeu

Este foi indicação do colega Jorge Miguel do grupo Laravel Brasil do Facebook

https://www.freehostingeu.com/

A vantagem deste é que nem domínio ele exige. Você recebe um subdomínio. Veja um que tenho lá: http://ribafs.eu3.org/

Recursos

- PHP com MySQL
- Instalação com 1 clique do Joomla, Wordpress, e outros
- Outros recursos. Confira 


### Cloudaccess

Se for free para hospedar um site com Joomla este é o meu preferido

Este é dedicado e especializado nos CMS Joomla e Wordpress

Vocẽ cria a conta e já recebe uma conta e site com o CMS instalado e pronto para usar

Free por 30 dias. Caso queira pode renovar. Eles avisam por e-mail

https://www.cloudaccess.net/joomla/managed-hosting.html

https://www.cloudaccess.net/wordpress/managed-hosting.html

Máquina Virtual com bons recursos, espaço de 500MB e uma IDE web para administração do projeto


### Heroku

https://www.heroku.com/

Este exige conhecimento de git

Heroku runs your app in lightweight, isolated Linux containers called "dynos." The platform offers different dyno types to help you get the best results for your type of app.

Plano free:

- Aplicações não comerciais
- Projetos pessoais
- 512MB
- Custom domain - podemos hospedar lá nosso domínio pessoal

O deploy é feito com git e docker

Uma boa opção de SGBD free é o PostgreSQL ou o SQLite, que pra valer não é um SGBD mas quebra alguns galhos


## Byethost

Este usei muito pouco, mas quando usei funcionou

https://byet.host/free-hosting/

Main FeaturesPHP & MySQL included with every free hosting plan

    1000 MB (one gigabyte!) Disk Space
    FTP account and File Manager
    Control Panel
    PHP
    MySQL databases & PHP Support
    Free tech support
    Addon domain, Parked Domains, Sub-Domains
    Free Community Access (Forums)
    Clustered Servers
    No ads!
    Complete Features
    Account Specification


## 000webhost

Eu tive tantos problemas com este que não vou citar aqui nem indicar, mas pode te servir, como chegou a me servir


## Sites estáticos

Estes são sites que usam apenas HTML, CSS e Javascript. Nada de PHP nem MySQL


### Github Pages - https://github.com

Este é o meu preferido para sites estáticos. Meu site está com ele - https://ribamar.net.br

Criar um repositório e usá-lo para abrigar um site em HTML

Existem várias outras alternativas, como


### 21 opções de hosting free para sites com HTML estático

https://devandgear.com/blog/free-hosting-static-website/


### 10 opções

https://graygrids.com/free-static-html-hosting-providers/


## Domínio free

Aaproveitando temos também uma opção de domínio free. Não é aceito em toda hospedagem mas pode ser vir em algumas.

https://www.freenom.com/

Freenom World is a fast and anonymous Public DNS resolver

https://my.freenom.com/clientarea.php?action=domaindetails

Seus nameserver são

80.80.80.80
80.80.81.81


## Domínios comerciais

Caso queira contratar um domínio pago a minha sugestão é o registro.br. Porque? 

Lembrando: não ganho nada do registro.br. Eles nem sabem que existe. Aqui meu compromisso é apenas o de prestar uma boa informação, que me serviu bem.

Eles cobram geralmente a mesma taxa anual a cada ano. Diferente de muitas hospedagens que quando você vai renovar ela cobra o dobro ou mais do que você pagou no primeiro ano.

Outra grande, enorme vantagem é que você mesmo gerencia tudo do seu domínio: nameservers, registros, etc na administração web do registro.br. Não precisará ficar pedindo ao suporte da hospedagem que faça por você e esperar dias para que façam. É verdade que isso exige mais conhecimento mas isso é algo que precisamos ter em nossa área, não podemos ficar dependendo de outros.

Gosto do registro.br principalmente por dois motivos: quando for renovar o domínio não terá a horrível surpresa de pagar o dobro ou até mais e outra que agiliza muito o gerenciamento domínio, que é a interface de administração deles, que te oferece todos os recursos que precisamos para nossos domínios, que são os nameservers e os registros. Você não irá perder tempo pedindo que o suporte faça isso por você e ter que esperar pela nada ágil resposta, como acontece com alguns. Eu tenho um domínio numa destas e estarei abandonando, pois a renovação será 70, mais que o dobro.

## Explicando um pouco

Um domínio é um apelido para um IP que facilita memorizar

- Primeiro contratamos um serviço, como o registro.br
- Depois configuramos os dados recebidos do registro.br numa hospedagem. Exemplo: Digital Ocean
- Então aguardamos um certo tempo para que o domínio propague (que pode variar de minutos até a horas  e até 3 dias)


## Ferramentas para checar a proapgação do DNS

Mostra em que regiões já propagou e também pelos registros do DNS

https://www.whatsmydns.net/

https://www.intodns.com/
