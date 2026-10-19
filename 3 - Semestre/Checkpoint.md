
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
Vue.js, Ant Design Vue, Java, Spring Boot, PostgreSQL, Docker, Figma.
