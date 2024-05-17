# Arquitetura de Sistemas de Software Populares - Spotify <img src="https://upload.wikimedia.org/wikipedia/commons/1/19/Spotify_logo_without_text.svg" align="right" width="50">

### Engenharia de Software - PUC Minas
![Spotify Logo](https://upload.wikimedia.org/wikipedia/commons/1/19/Spotify_logo_without_text.svg)

## Integrantes 👩🏻‍💻

- **Integrante 1**: [Arthur Jansen Oliveira](https://github.com/artjansentec)
- **Integrante 2**: [Bárbara Mattioly Andrade](https://github.com/barbaraMattioly)
- **Integrante 3**: [⁠Bruno Pontes Duarte](https://github.com/brunopdt)
- **Integrante 4**: [Laura Enísia Rodrigues Melo](https://github.com/lauramelo28)
- **Integrante 5**: [Samuel Marques Sousa Leal](https://github.com/SamLeal)

## Profesora 👨‍🏫
- [Aline Norberta de Brito](https://github.com/alinebrito)

# Sumário
- [Introdução](#introdução)
- [Funcionalidades e Segurança](#funcionalidades-e-segurança)
- [Arquitetura Organizacional](#arquitetura-organizacional)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Descrição da Arquitetura](#descrição-da-arquitetura)
- [Curiosidades](#curiosidades)
- [Conclusão](#conclusão)
- [Referências Bibliográficas](#referências-bibliográficas)

## Introdução

O Spotify é o serviço de assinatura de streaming de áudio mais popular do mundo com cerca de 615 milhões de usuários, incluindo 239 milhões de assinantes. Foi lançado em 2008 para revolucionar a forma de ouvir músicas e segundo dados oficiais do próprio Spotify, conta hoje com mais de 100 milhões de faixas de músicas, 6 milhões de podcasts, 350.000 audiolivros e mais de 2 bilhões de playlists.

É um serviço digital que dá acesso instantâneo a esses milhões de músicas, podcasts, vídeos e outros conteúdos de criadores no mundo todo. Sua principal funcionalidade de reprodução de músicas é gratuita, conta com anúncios ao longo das músicas, mas permite aos usuários consumirem esse conteúdo sem a necessidade de serem assinantes. O serviço premium do Spotify (Spotify Premium) permite que os usuários desfrutem de todo o conteúdo de áudio sem interrupção e limitações.

O Spotify foi desenvolvido de forma a trazer uma experiência única para cada usuário, coletando os dados de uso de cada um e dessa forma trazendo recomendações com base nos gostos pessoais, montando coleções de músicas e podcasts voltadas a esses gostos.

É um serviço que possui compatibilidade com vários dispositivos, incluindo computadores, celulares, alto-falantes, televisões, carros e sistemas operacionais, como Android e IOS.

Para dar suporte a todos esses usuários, serviços de áudio e funcionalidades ele possui uma infraestrutura bem consolidada, além de contar com recursos de segurança para lidar com os dados sensíveis de cada usuário, como alguns dados pessoais e dados bancários.

## Funcionalidades e Segurança


### **Funcionalidades**

### **Requisitos de Segurança**

## Arquitetura Organizacional

O spotify é uma plataforma que está em constante crescimento, número de usuários diários, de serviços de áudio no catalogo, número de nós no backend que alimentam o serviço, número de plataforma de hardware em que seus clientes operam, número de aplicativos externos que hospedam na plataforma e o número de equipes de desenvolvimento que atuam nos produtos.

Para lidar com todo esse crescimento e garantir a velocidade de entega de novas funcionalidades, correções e ajustes, a arquitetura organizacional do spotiify é pensada de forma a eliminar ao máximo possível as dependências entre equipes e remover a complexidade na arquitetura do sistema.

As equipes (também chamadas de Squads) no Spotify são equipes autônomas que conseguem fazer entregas e se mover independentemente de outras squads, permitindo assim a realização de entregas constantes.

Todo o código do Spotify está disponível para todos os desenvolvedores de forma transparente, ou seja o código no cliente Spotify, no backend do Spotify e na infraestrutura do Spotify está disponível para todos os desenvolvedores do Spotify para lerem ou modificarem.


## Tecnologias Utilizadas
As principais linguagens utilizadas pelo sistema Spotify são: Python, Java, JavaScript e C++. A linguagem Java é utilizada com o foco para o serviços de backend devido à sua robustez e escalabilidade. O python é utilizado principalmente na área de machine learning, data analysis e alguns componentes do backend. Dessa forma, utiliza-se desse grande recurso juntamente com a inteligência artificial para recomendar músicas, playlists e podcasts para seus usuários.  O C++ é usado para componentes de alto desempenho como codecs de áudio.

Além disso, também são utilizadas outras ferramentas como *kubernetes* (para a orquestração de conteineres, permitindo a implantação e gestão de aplicações em escala), *docker* (para conteinerização de aplicações, facilitando a portabilidade e consistência entre diferentes ambientes), *apache kafka* (para o processamento de fluxo de dados em tempo real, facilitando na comunicação entre diferentes serviços), *elasticSearch* para pesquisa e análise de dados em tempo real.

Por fim, algumas práticas de desenvolvimento principalmente utilizadas no Spotify são a arquitetura baseada em microsserviços, com a integração e entrega contínua (CI/CD) para agilizar o processo de desenvolvimento e implantação, e o Machine Learning para a personalização e recomendações de playlists. 

É válido ressaltar também que o Spotify é compatível com uma ampla gama de sistemas operacionais e plataformas de modo que permite aos usuários acessarem serviços de qualquer dispositivo seja celulares, tablets, televisões, computadores e entre outros. Ele apresenta suporte para os sistemas operacionais iOS, Android, Windows, macOS e Linux. Isso torna


## Descrição da Arquitetura

Todas as equipes compartilham um mesmo servidor centralizado de git, onde cada repositório git tem um proprietário de sistema dedicado que cuida do código e garante sua qualidade. O modelo de código transparente que o Spotify proporciona garante que todos tenham acesso ao código de todos, garantindo uma padronização de código e avanço o tempo todo.

![Spotify Logo](./assets/arquitetura.png)

## Curiosidades

## Conclusão

## Referências Bibliográficas

* [Decoding Software Architecture Of Spotify: How Microservices Empowers Spotify](https://www.techaheadcorp.com/blog/decoding-software-architecture-of-spotify-how-microservices-empowers-spotify/)
* [Backend infrastructure at Spotify](https://engineering.atspotify.com/2013/03/backend-infrastructure-at-spotify/)
* [O que é o Spotify?](https://support.spotify.com/br-pt/article/what-is-spotify/)
* [Spotify anuncia recurso que utiliza inteligência artificial para recomendar músicas; entenda](https://www.cnnbrasil.com.br/economia/spotify-anuncia-recurso-que-utiliza-inteligencia-artificial-para-recomendar-musicas-entenda/)
* [Como o Spotify usa Ciência de Dados para engajar usuários](https://medium.com/somos-tera/como-o-spotify-usa-ci%C3%AAncia-de-dados-para-engajar-usu%C3%A1rios-bc47e3b948af) 
* [Spotify e o poder das métricas](https://pt.k21.global/blog/spotify-e-o-poder-das-metricas?gad_source=1&gclid=Cj0KCQjwgJyyBhCGARIsAK8LVLOYm8cQUeFpoAwgkFN4N8EsCFLIyGEd3-2KqkI8sxpfrQBVitHXCI4aAnfIEALw_wcB )

## Key Components
