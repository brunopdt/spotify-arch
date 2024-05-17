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

## Descrição da Arquitetura

Todas as equipes compartilham um mesmo servidor centralizado de git, onde cada repositório git tem um proprietário de sistema dedicado que cuida do código e garante sua qualidade. O modelo de código transparente que o Spotify proporciona garante que todos tenham acesso ao código de todos, garantindo uma padronização de código e avanço o tempo todo.

![Spotify Logo](./assets/arquitetura.png)

## Curiosidades

## Conclusão

## Referências Bibliográficas

* [Decoding Software Architecture Of Spotify: How Microservices Empowers Spotify](https://www.techaheadcorp.com/blog/decoding-software-architecture-of-spotify-how-microservices-empowers-spotify/)
* [Backend infrastructure at Spotify](https://engineering.atspotify.com/2013/03/backend-infrastructure-at-spotify/)
* [O que é o Spotify?](https://support.spotify.com/br-pt/article/what-is-spotify/)


## Key Components