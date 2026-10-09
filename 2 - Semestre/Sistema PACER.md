
---
## Descrição do Projeto
Neste projeto, desenvolvemos um Sistema Desktop de Avaliação baseado na Metodologia PACER, voltado para a gestão de desempenho e avaliação de soft skills entre colegas de equipe. O grande problema que resolvemos foi automatizar e centralizar um processo de coleta de notas que era manual, disperso e propenso a erros, fornecendo um dashboard analítico rápido e seguro para os professores.

### Contribuição para o Projeto

Atuando de ponta a ponta (Full-Stack), minha prioridade foi garantir a integridade das informações, do banco de dados até a tela do usuário. O maior desafio arquitetural que assumi foi o Subsistema de Ingestão e Processamento de CSV. Projetei todo o pipeline no back-end (em Java) não apenas para ler arquivos, também realizando validações sintáticas, garantindo que dados mal formatados não corrompessem nosso banco relacional MySQL.

Na camada de negócios, desenvolvi o mecanismo estatístico que computava a média aritmética ponderada das notas e implementei travas de segurança para impedir que um usuário submetesse avaliações duplicadas. Com esses dados seguros, criei o Painel Dinâmico de Monitoramento em JavaFX, que permitia aos professores renderizar as médias consolidadas de qualquer equipe em tempo real, realizando consultas pesadas de forma otimizada.

### Soft Skills

Esse projeto exigiu forte Colaboração. Como a aplicação envolvia regras de negócio complexas, precisei alinhar constantemente as interfaces técnicas com o time, garantindo que o fluxo das telas que eu construía conversasse perfeitamente com os controladores dos outros desenvolvedores. Isso fortaleceu minha Adaptabilidade, pois integramos requisitos técnicos iterativamente sem perder o ritmo das entregas.
