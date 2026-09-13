<h1 align="center">Olá! Eu sou Victor Hugo 👋</h1>
<h3 align="center">Desenvolvedor Full Stack</h3>
<h4 align="center">Java · TypeScript · Node.js · NestJS · Next.js · React · Vue.js · Angular · AWS | Clean Architecture e APIs Escaláveis</h4>

<p align="center">
Construo e evoluo sistemas full stack com foco em performance, APIs REST bem desenhadas, processamento assíncrono e interfaces integradas ao backend. Meu trabalho é fazer o sistema aguentar volume sem virar gargalo quando o dado cresce — e garantir visibilidade sobre ele em produção.<br><br>
Aplico <b>Clean Architecture</b>, <b>Clean Code</b> e princípios <b>SOLID</b> no dia a dia, com decisões técnicas sustentadas por trade-offs claros.<br><br>
📍 Goiânia, Goiás · Brasil
</p>

<div align="center">
<a href="https://www.linkedin.com/in/victorhugoaguiarporfiro/" target="_blank">
<img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="linkedin logo" />
</a>
<a href="mailto:vhaporfiro@gmail.com" target="_blank">
<img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="gmail logo" />
</a>
</div>
<br/>

<h3 align="center">💼 Sobre Mim</h3>
<p align="center">
Desenvolvedor full stack com foco em Java/Spring Boot e TypeScript/NestJS no backend, e Next.js, Vue.js, React e Angular no frontend. Trabalho com APIs REST, processamento assíncrono e otimização de performance — reduzi em <b>82,9%</b> o tempo de resposta de rotas críticas com cache em memória e derrubei consultas de dashboards de <b>6,7s para 1,2s</b>. Aplico Clean Architecture e SOLID no dia a dia, com atenção a testes unitários e Code Review.
</p>
<p align="center">
Tenho base sólida em Java e Orientação a Objetos, e trabalho com mensageria (Kafka, SQS), sistemas distribuídos e AWS. Atualmente também atuo com observabilidade de software — logs, métricas e monitoramento para garantir a saúde das aplicações em produção. Familiarizado com Docker, CI/CD e ambientes ágeis (Scrum), transito entre backend e frontend integrando times multidisciplinares de ponta a ponta.
</p>
<br/>

<h3 align="center">🚀 Experiência Profissional</h3>

<p align="center"><b>🏢 New Line Tecnologia em Segurança</b> · Desenvolvedor Full Stack · <i>Set/2026 – atual</i></p>

Atuo como desenvolvedor full stack, com foco também em observabilidade de software.
Implemento práticas de monitoramento, logs e métricas para garantir a saúde e o desempenho das aplicações em produção.
Trabalho com banco de dados Oracle, além da stack full stack já consolidada em projetos anteriores.

<br/>

<p align="center"><b>🏢 MadeinWeb</b> · Desenvolvedor Full Stack · <i>Set/2025 – Ago/2026</i></p>

Implementei cache em memória em 4 pontos críticos do sistema, reduzindo o tempo de resposta dessas rotas em 82,9% e aliviando a carga de leitura no banco em consultas de alta frequência.
Otimizei queries MySQL do módulo de timer, reduzindo o tempo de resposta dos dashboards gerenciais de 6,7s para 1,2s e eliminando inconsistências nos relatórios.
Construí do zero o módulo de autenticação e autorização via API Key, habilitando a integração segura entre dois sistemas internos, com controle de acesso granular por endpoint e armazenamento da chave em hash.
Projetei e implementei APIs REST em TypeScript/NestJS, participando das decisões de arquitetura junto ao time, além de desenvolver interfaces frontend consumindo essas APIs.
Entreguei features críticas do produto (comentários, histórico de alterações, hierarquia de projetos e recuperação de senha) aplicando Clean Architecture por domínio, o que reduziu o acoplamento entre módulos.
Escrevi testes unitários cobrindo os fluxos críticos do backend, com média de 92,3% de cobertura nos módulos que desenvolvi.

<br/>

<p align="center"><b>🏢 QaCoders</b> · Desenvolvedor Back-End · Estágio · <i>Mai/2025 – Set/2025</i></p>

Desenvolvi módulos acadêmicos e financeiros de um ERP escolar em TypeScript/NestJS, integrando dois domínios de negócio distintos.
Entreguei em sprints quinzenais, do refinamento ao deploy, participando de 10 sprints completas em sistema já em produção.
Criei coleções de teste automatizado no Postman, cobrindo casos esperados e de borda, o que passou a detectar regressões antes do QA.
Documentei os endpoints no Swagger, estabelecendo contratos claros entre backend e time de QA.
Padronizei código legado do sistema em produção, reduzindo inconsistências de estilo e facilitando a manutenção pelo time.

<br/>

<h3 align="center">📂 Projetos em Destaque</h3>
<p align="center"><b>Processamento Assíncrono de Importação de Leads</b></p>
<p align="center">
Backend assíncrono para importação em massa de leads via CSV, capaz de processar arquivos de 10 mil linhas sem estourar a memória. Upload direto ao S3 por pre-signed URL, processamento em worker Spring Boot consumindo fila SQS e notificação via SNS. Streaming do CSV linha a linha com persistência em batch, mantendo uso de memória constante, e idempotência para a semântica at-least-once do SQS.<br>
<i>Java 21 · Spring Boot · AWS (S3, SQS, SNS, IAM) · MySQL · Flyway · Docker</i>
</p>
<br/>

<p align="center"><b>TeeStore · Plataforma de Pedidos Orientada a Eventos</b></p>
<p align="center">
Plataforma de pedidos com arquitetura orientada a eventos, integrando três serviços desacoplados por mensageria. Fluxo de eventos <code>order.created</code> e <code>order.status.updated</code> em Apache Kafka com 3 brokers e consumer groups independentes por domínio, autenticação JWT com refresh token e blacklist em Redis, e serviço de notificação assíncrono entregando via WebSocket e SMTP.<br>
<i>Java 21 · Spring Boot 3.x · Apache Kafka · PostgreSQL · Redis · React 19 · Vite · Docker Compose</i>
</p>
<br/>

<h3 align="center">🛠️ Tech Stack</h3>

<p align="center"><b>Linguagens</b></p>
<div align="center">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="45" alt="java logo" title="Java" />
<img width="12" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="45" alt="typescript logo" title="TypeScript" />
<img width="12" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="45" alt="javascript logo" title="JavaScript" />
</div>
<br/>

<p align="center"><b>Frameworks & Runtimes — Backend</b></p>
<div align="center">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nestjs/nestjs-original.svg" height="45" alt="nestjs logo" title="NestJS" />
<img width="12" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="45" alt="nodejs logo" title="Node.js" />
<img width="12" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" height="45" alt="spring logo" title="Spring Boot" />
<img width="12" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/hibernate/hibernate-original.svg" height="45" alt="hibernate logo" title="Hibernate / JPA" />
</div>
<br/>

<p align="center"><b>Frameworks — Frontend</b></p>
<div align="center">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="45" alt="react logo" title="React" />
<img width="12" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" height="45" alt="nextjs logo" title="Next.js" />
<img width="12" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg" height="45" alt="vuejs logo" title="Vue.js" />
<img width="12" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg" height="45" alt="angular logo" title="Angular" />
</div>
<br/>

<p align="center"><b>Bancos de Dados & Cache</b></p>
<div align="center">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="45" alt="mysql logo" title="MySQL" />
<img width="12" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="45" alt="postgresql logo" title="PostgreSQL" />
<img width="12" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" height="45" alt="mongodb logo" title="MongoDB" />
<img width="12" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" height="45" alt="redis logo" title="Redis" />
</div>
<br/>

<p align="center"><b>Cloud & DevOps</b></p>
<div align="center">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" height="45" alt="aws logo" title="AWS" />
<img width="12" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="45" alt="docker logo" title="Docker" />
<img width="12" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" height="45" alt="linux logo" title="Linux" />
<img width="12" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apachekafka/apachekafka-original.svg" height="45" alt="kafka logo" title="Apache Kafka" />
</div>
<br/>

<p align="center"><b>Ferramentas</b></p>
<div align="center">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="45" alt="git logo" title="Git" />
<img width="12" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="45" alt="github logo" title="GitHub" />
<img width="12" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postman/postman-original.svg" height="45" alt="postman logo" title="Postman" />
<img width="12" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/swagger/swagger-original.svg" height="45" alt="swagger logo" title="Swagger" />
</div>
<br/>

<p align="center">
<b>☁️ Serviços AWS:</b> S3 · SQS · SNS · RDS · IAM · Lambda
</p>
<br/>

<h3 align="center">📜 Certificações</h3>
<p align="center">
✅ <b>AWS Certified Cloud Practitioner</b> — Amazon Web Services (Mar/2026 – Mar/2029)<br>
✅ <b>JavaScript e TypeScript do Básico ao Avançado</b> — Udemy<br>
✅ <b>Java Completo: Programação Orientada a Objetos + Projetos</b> — Udemy<br>
✅ <b>Fundamentos do Spring Boot</b> — Rocketseat
</p>
<br/>

<h3 align="center">🎓 Formação Acadêmica</h3>
<p align="center">
<b>Pontifícia Universidade Católica de Goiás (PUC-GO)</b><br>
Análise e Desenvolvimento de Sistemas · <i>2024 – 2026</i>
</p>
<br/>

<h3 align="center">📊 GitHub Stats</h3>
<div align="center">
<img src="https://github-stats-extended.vercel.app/api?username=VHAPorfirium&show_icons=true&theme=nightowl&locale=pt-br&hide_border=false&cache_seconds=21600" height="170" alt="stats graph" />
<img src="https://github-stats-extended.vercel.app/api/top-langs?username=VHAPorfirium&layout=compact&card_width=320&langs_count=8&theme=nightowl&hide_border=false&locale=pt-br&cache_seconds=21600" height="170" alt="languages graph" />
</div>
<div align="center">
<img src="https://streak-stats.demolab.com?user=VHAPorfirium&theme=nightowl&hide_border=false&locale=pt_BR" height="170" alt="streak graph" />
</div>
<div align="center">
<img src="https://raw.githubusercontent.com/VHAPorfirium/VHAPorfirium/output/activity-graph.svg" width="800" alt="activity-graph graph" />
</div>
<br/>

<p align="center">
⭐ <b>Sinta-se à vontade para explorar meus repositórios e entrar em contato!</b>
</p>
