# _Cetus_ 

O projeto __Cetus__ foi idealizado para ser um software de gerenciamento empresarial flexível e robusto, fornecendo uma solução para os problemas diários.

## Desenvolvimento (Preparação de ambiente):

No ambiente de desenvolvimento são utilizadas algumas ferramentas em conjunto do sistema `Linux Ubuntu`. 

Preparando o ambiente:

* Instale a ferramenta `Git`, para o gerenciamento de versões
```shell
sudo apt-get install git
```

* Instale `Oh My ZShell`, utilizado como terminal de ajuda para utilização do `Git`
```shell
sudo apt-get install zsh curl && sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

* Instale ferramenta `meld` que realiza a comparação entre arquivos e versões gerenciadas pelo `Git`
```shell
sudo apt-get install meld
```

* Instale o `Java Oracle 8`
```shell
sudo add-apt-repository ppa:webupd8team/java
sudo apt-get update
sudo apt-get install oracle-java8-installer
```

Obs.: Caso necessário reconfigure os links do java utilizando o comando `sudo update-alternatives --config java`, quando houver mais de uma versão de java instalada.

* Instale o Maven, gerenciador de dependências e bibliotecas Java
```shell
sudo apt-get install maven
```

Para finalizar, crie uma pasta no diretório do usuário chamada `Prog`. Dentro da pasta `Prog`, crie uma pasta para a ferramenta [Eclipse IDE - Neon](http://www.eclipse.org/downloads/download.php?file=/technology/epp/downloads/release/neon/3/eclipse-jee-neon-3-linux-gtk-x86_64.tar.gz) e uma segunda pasta chamada `workspace`, local onde será armazenada as configurações do `Eclipse`.

Pelo `terminal`, vá até a pasta `Prog`, através do comando `cd ~/Prog`, e faça um clone do projeto Cetus.

