
---

## 1. Descrição do Projeto

No terceiro semestre o time desenvolveu um **Sistema de Registro de Movimentações** voltado para a gestão de controle de acesso de colaboradores terceirizados. A aplicação foi concebida em parceria com a empresa **Altave**, para automatizar o controle de acesso de colaboradores terceirizados em zonas de manutenção naval. O desafio era substituir o controle manual analógico por uma plataforma digital inteligente, conteinerizada e capaz de exportar análises gerenciais seguras de fluxo e frequência de funcionários

---

## 2. Contribuição para o Projeto

Com foco de atuação direcionado à camada de **Front-end**, assumi a responsabilidade pelo desenvolvimento de módulos críticos da interface, garantindo a comunicação fluida com os serviços de *back-end*. Minhas principais contribuições incluíram:
Desenvolvi todo o módulo de cadastro e a Tabela Dinâmica de Registros, onde o grande desafio foi receber dados brutos e timestamps do servidor e formatá-los para uma exibição intuitiva para o usuário final, acoplando a funcionalidade de edição de usuários direto da tabela via chamadas HTTP.

O momento de maior complexidade técnica, no entanto, foi o desenvolvimento do Subsistema de Exportação em Lote (.csv). Para evitar que o navegador do usuário travasse ao processar históricos gigantescos, implementei conceitos de paginação do lado do servidor (server-side pagination) e manipulação inteligente de buffers em JavaScript, gerando arquivos pesados para download de maneira otimizada e invisível para o usuário.

---

## 4. Lições Aprendidas (Soft Skills & Hard Skills)

### Soft Skills

* **Comunicação:** Precisei práticar e comunicar diáriamente na exposição de ideias e alinhamento técnico com toda a equipe, o que era possível ser feito, especialmente com minha experiencia com Vue.js, facilitando a identificação precoce de impedimentos no desenvolvimento.

* **Trabalho em Equipe e Cultura Ágil:** Exercitei a proatividade e automação no acompanhamento das tarefas do kanban, colaborando ativamente com os membros, um dos pontos importantes foi identificar os limites no meu conhecimento e buscar orientação com membros mais experientes do time sempre que necessário em boas práticas de programação.

### Hard Skills

* **Vue.js & Axios:** Foi necessário aprender o conceito de paginas, router e comunicação entre backend e frontend, desenvolvi e integrei páginas, criei componentes e consumi APIs REST de forma assíncrona, foi muito importante em minha jornada para conhecer na prática o conceito do funcionamento de paginas web.
* **Estilização e CSS/SASS:** Támbem utilizei o CSS e SASS para estilizar layouts e adoção do pré-processador SASS para reaproveitamento de código e aplicação de práticas de código limpo.
* **Fundamentos de Java (Back-end):** Pratiquei conceitos de Programação Orientada a Objetos (POO), tratamento de exceções, boas práticas de Código Limpo e manipulação de fluxos com a API de *Streams*.
* **SQL/PostgreSQL:** Precisei escrever consultas estruturadas, modelar entidades do banco, fazer os relacionamentos (DER) e aplicar regras como as formas normais no banco.
* **Docker:** Fui introduzido ao conceito de conteinerização, manipulação de imagens e gerenciamento de contêineres de desenvolvimento.

### Tecnologias Utilizadas: 

#### Frontend


[![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)](https://github.com/vuejs/vue)
[![Vue Router](https://img.shields.io/badge/Vue_Router-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D)](https://github.com/vuejs/router)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://github.com/vitejs/vite)
[![Ant Design Vue](https://img.shields.io/badge/Ant_Design_Vue-0170FE?style=for-the-badge&logo=ant-design&logoColor=white)](https://github.com/vueComponent/ant-design-vue)
[![MirageJS](https://img.shields.io/badge/MirageJS-FF6D70?style=for-the-badge&logo=javascript&logoColor=black)](https://github.com/miragejs/miragejs)
[![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)](https://github.com/axios/axios)
[![Pinia](https://img.shields.io/badge/Pinia-FFD859?style=for-the-badge&logo=pinia&logoColor=black)](https://github.com/vuejs/pinia)
[![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)](https://github.com/sass/sass)
[![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)](https://github.com/eslint/eslint)

#### Backend

[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)](https://www.oracle.com/java/)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)](https://swagger.io/)

