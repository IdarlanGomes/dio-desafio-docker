
Docker: Utilização prática no cenário de Microsserviços
Denilson Bonatti, Instrutor - Digital Innovation One

Muito se tem falado de containers e consequentemente do Docker no ambiente de desenvolvimento. Mas qual a real função de um container no cenários de microsserviços? Qual a real função e quais exemplos práticos podem ser aplicados no dia a dia? 

Microsserviços são um tipo inovador de arquitetura de software, que consiste em construir aplicações desmembrando-as em serviços independentes. Estes serviços se comunicam entre si usando APIs e promovem grande agilidade em times de desenvolvimento.
Hoje, gigantes do mercado como Netflix e Spotify, divulgam a receita do sucesso ao transformar suas aplicações monolíticas em mais de 500 microsserviços.

Quando quebramos uma aplicação monolítica em várias pequenas partes, conseguimos escalá-las de forma separada. Supondo que um serviço de autenticação seja chamado várias vezes durante a sessão de um usuário, com certeza o stress sobre ele é maior.

Com microsserviços, podemos escalar apenas uma parte, ao invés de ter que escalar a aplicação como um todo, como ocorre em uma arquitetura monolítica.

Os microsserviços não necessariamente precisam ser escritos usando a mesma linguagem de programação.

O Swarm é um recurso do Docker que fornece funcionalidades de orquestração de contêiner, incluindo clustering nativo de hosts do Docker e agendamento de cargas de trabalho de contêineres. Um grupo de hosts do Docker formam um cluster "Swarm".

Um cluster (do inglês cluster : 'grupo, aglomerado') consiste em computadores ligados que trabalham em conjunto, de modo que, em muitos aspectos, podem ser considerados como um único sistema. Computadores em cluster executam a mesma tarefa, controlado e programado por software.
Cada computador presente em cluster é conhecido como nó (node).

