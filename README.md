Documentação do Projeto PinhAu
Equipe:
 Katia Dhaem
 Curso: Gestão da Tecnologia da Informação – IFPR Câmpus Pinhais

1. Identificação
a. Identidade visual do projeto
O projeto PinhAu possui identidade visual baseada em cores suaves e amigáveis, com predominância do amarelo (Bootstrap – bg-warning), transmitindo acolhimento e proximidade com o público-alvo. A interface prioriza simplicidade, clareza e fácil navegação.

b. Redes sociais do projeto
Atualmente o projeto encontra-se em fase acadêmica e está hospedado no GitHub como repositório de desenvolvimento.

c. Organização da Equipe
Responsável: Katia Dhaem


Função: Desenvolvimento backend, frontend, modelagem de banco de dados e documentação.


Forma de comunicação: WhatsApp (Daily), GitHub (versionamento) e Trello (organização Kanban).


d. Data de criação do projeto
2024 – Projeto Interdisciplinar I – IFPR Câmpus Pinhais
2026 – Projeto Interdisciplinar II – IFPR Câmpus Pinhais

2. Concepção
a. Descrição da visão geral do projeto
O projeto PinhAu consiste em uma plataforma web desenvolvida para facilitar a adoção responsável de cães no município de Pinhais.
O sistema conecta tutores que desejam disponibilizar cães para adoção e adotantes interessados em oferecer um novo lar aos animais.
A aplicação foi refatorada e reorganizada estruturalmente, visando maior manutenibilidade, organização modular e segurança.
b. Objetivo do projeto
Desenvolver uma plataforma digital simples e funcional que:
Permita o cadastro de tutores e adotantes;


Possibilite o cadastro e gerenciamento de cães;


Facilite a visualização pública dos animais disponíveis;


Promova a adoção responsável.


c. Escopo do produto
Descrição do produto:
 Sistema web desenvolvido em PHP e MySQL que permite gerenciamento de cães para adoção, autenticação de usuários e controle de perfil de tutor.
Principais entregas implementadas:
Sistema de cadastro e login com sessão;


CRUD completo de cães (inserção, alteração e remoção);


Perfil do tutor com gerenciamento de seus próprios animais;


Listagem pública de cães;


Organização modular do código em pastas separadas.


Critérios de aceite:
Usuário consegue cadastrar-se e realizar login;


Tutor consegue cadastrar e gerenciar seus cães;


Visitante consegue visualizar cães disponíveis;


Sistema mantém controle de acesso por sessão.


d. Matriz de Riscos
Id
Descrição
Impacto
Probabilidade
Resposta
R1
Falhas de segurança no login
Alto
Médio
Uso de sessões e prepared statements
R2
Inconsistência no banco de dados
Médio
Médio
Uso de chaves estrangeiras
R3
Código difícil de manter
Alto
Alto
Refatoração estrutural do projeto
R4
Falhas de autenticação
Alto
Médio
Validação de sessão em todas as telas restritas


3. Design do Software
a. Design Centrado no Usuário
O sistema foi desenvolvido priorizando simplicidade e facilidade de uso, com foco na navegação intuitiva e acesso rápido às principais funcionalidades.
b. Personas e mapa de empatia
Persona principal:
 Tutor que deseja disponibilizar um cão para adoção.
Persona secundária:
 Adotante que busca um animal para adoção responsável.
c. Storyboard (contexto de uso)
Usuário acessa a página inicial;


Visualiza cães disponíveis;


Realiza cadastro/login;


Tutor cadastra novo cão;


Tutor gerencia seus próprios registros.


d. UI Design (guia de estilo)
Interface baseada em Bootstrap;


Layout responsivo;


Uso de cards para organização de informações;


Separação de componentes (header e footer reutilizáveis).


e. Protótipação do MVP
O MVP contempla:
Autenticação funcional;


CRUD de cães;


Perfil do tutor;


Listagem pública.


4. Desenvolvimento
a. Processo de software
Metodologia utilizada:
 Kanban com organização em:
To Do


Doing


Done


Sprints quinzenais para desenvolvimento incremental.
b. Recursos utilizados
Frontend: HTML5, CSS3, Bootstrap
 Backend: PHP
 Banco de Dados: MySQL
 Controle de versão: GitHub
 Scripts: JavaScript (AJAX para gerenciamento de cães)
c. Resultados esperados
Plataforma funcional para adoção responsável;


Código organizado e modular;


Base estruturada para evolução futura.


d. Instruções para download e execução
Clonar o repositório:


git clone https://github.com/seuusuario/pinhau.git
Importar o script SQL disponível em:


banco_de_dados/script.sql
Configurar a conexão em:


conex_banco/conexao.php
Executar via XAMPP (htdocs).


e. Licença de uso e distribuição
Projeto acadêmico desenvolvido para fins educacionais no IFPR Câmpus Pinhais.
5. Estratégia de Marketing Digital
Como projeto acadêmico, a estratégia contempla:
Divulgação em redes sociais;


Parcerias futuras com ONGs locais;


Produção de conteúdo educativo sobre adoção responsável.


6. Gestão do Projeto
1. Backlog do Projeto
Principais funcionalidades priorizadas:
Sistema de autenticação


CRUD de cães


Perfil do tutor


Listagem pública


Melhorias de segurança


2. Métricas de acompanhamento
Número de funcionalidades entregues por sprint;


Registro de dailys;


Revisão quinzenal (Review).


3. Lições aprendidas
Importância da organização modular;


Necessidade de segurança em autenticação;


Relevância do versionamento contínuo.


7. Relatório Técnico
O sistema foi estruturado com:
Separação por camadas;


Controle de acesso por sessão;


Uso de prepared statements;


Estrutura organizada em pastas (autenticação, telas, componentes, banco_de_dados, etc.).


8. Plano de Negócio
Como projeto acadêmico, o plano prevê futura expansão com:
Upload de imagens reais;


Integração com API WhatsApp;


Sistema formal de solicitação de adoção;


Painel administrativo.


9. Artigo
O projeto contribui para a conscientização sobre adoção responsável, oferecendo uma solução digital que facilita a conexão entre tutores e adotantes.
10. Extras
a. Modelagem UML
Diagrama de casos de uso, classes e relacionamento entre entidades.
b. Modelagem de banco de dados
DER estruturado com chaves primárias e estrangeiras.
c. Resultados da Entrevista
Usuários indicaram necessidade de sistema simples, rápido e intuitivo.
d. Termo de Consentimento
Aplicável caso haja coleta de dados formal para extensão.
11. Pasta Extensão
Contempla documentação de ações futuras de extensão e aplicação prática do sistema na comunidade.
