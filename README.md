# Pabx Ip Free - Versão Nuclear
![Getting Started](images/erix_logo.png)

# O que é
PbxErix - Versão Nuclear é  baseado em Software Livre que tem funções simples para atendimento telefônico  de qualquer pequena, media ou grande empresa

Conheça mais no site do PbxErix: www.pbxerix.com.br

# Procedimentos de instalação da iso

A instalação está baseado em Linux Debian, versão 9(stretch), sendo assim o procedimento é simples com algumas perguntas no decorrer da instalação como senha de root nome de usuário.
Alguns detalhes importantes na instalação, na tela de configuração do phpmyadmim selecione **apache** e na próxima selecione a opção **no** como mostrado abaixo.

**Selecione a opção **apache****



![Phpmyadmin apache](images/phpmyadmin1.jpg)


**Selecione a opção **no****

![Phpmyadmin common](images/phpmyadmin2.jpg)


# Senhas
PbxErix Nuclear está configurado inicialemnte com a mesma senha no mysql e na interface Web. A senha padrão é : **asterisknuclear** com lodas as letras minúsculas.

**Alterando a senha de root**
Acesse o putty com a senha de root cadastrada na instalação e digite: mysqladmin -u root -p password **'nova-senha'**
A senha padrao será solicitada digite: asterisknuclear , feito isso sua senha já foi alterada.

**Alterando a senha Web**
Acesse pelo seu navegador preferido o Ip do PbxErix, será apresentado uma tela solicitando usuário e senha, digite:
Usuário: admin
Senha: asterisknuclear
Logo após uma tela de redefinição de senha será apresentada, digite e confirme a nova senha que deseja utilizar.


![Erix Login](images/login_web.jpg)
