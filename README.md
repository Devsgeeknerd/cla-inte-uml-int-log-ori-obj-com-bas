<!-- Título -->
# Interfaces e UML

***Conteúdo da Aula:***

Vamos imaginar a seguinte situação:

* Nós temos uma classe para representar os animais, a classe `Animal`.

* Nós sabemos que, de maneira geral, todos os animais nascem, crescem, reproduzem-se e morrem.

* Este é um comportamento padrão de todos os animais que existem na Terra.

* Sendo assim, precisamos ter uma maneira de forçar que as classes que representem os animais possuam os métodos em questão (`nascer`, `crescer`, `reproduzir` e `morrer`).

* Nós podemos fazer isso criando uma interface, que podemos chamar de `SerVivo`, por exemplo.

* Dessa maneira, a nossa classe `Animal` implementaria a interface `SerVivo`.

Na UML, essa relação entre a interface `SerVivo` e a classe `Animal` poderia ser representada da seguinte maneira:

![Representação](https://d2v0x26thbzlwf.cloudfront.net/prod/13/img/rId16jgrcf2oq.1py.png "Relação entre a interface e a classe")

Perceba que, pelo sentido da seta tracejada (que representa a implementação da interface), indica que a classe `Animal` implementa a interface `SerVivo` e, obrigatoriamente, a classe `Animal` terá os métodos `nascer`, `crescer`, `reproduzir` e `morrer`.

<!-- Informações -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fcla-int-uml-int-log-ori-obj-com-bas&label=Visitantes&labelColor=%23700070&labelStyle=none&countColor=%23000fff&style=plastic&color=%23ffffff "Total de Visitantes")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=800080&color=000fff "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/cla-int-uml-int-log-ori-obj-com-bas?style=p&label=Observadores&labelColor=800080&color=000fff "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/cla-int-uml-int-log-ori-obj-com-bas?style=p&label=Estrelas&labelColor=800080&color=000fff "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/cla-int-uml-int-log-ori-obj-com-bas?style=p&label=Bifurcações&labelColor=800080&color=000fff "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/cla-int-uml-int-log-ori-obj-com-bas?style=p&label=Tamanho&labelColor=800080&color=000fff "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/cla-int-uml-int-log-ori-obj-com-bas?style=p&label=Licença&labelColor=800080&color=000fff "Licença do Repositório")
