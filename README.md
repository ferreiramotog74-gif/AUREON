🛠️ Aureon — Plataforma de Conexão de Prestação de Serviços
License: MIT | Status: PRs Welcome

A Aureon é uma solução digital (Web Marketplace) desenvolvida para conectar trabalhadores autônomos e freelancers a clientes finais que buscam soluções rápidas, confiáveis e acessíveis para suas demandas do dia a dia.

📌 Sumário
🚨 O Problema

💡 A Solução

🚀 Principais Funcionalidades

🏗️ Arquitetura e Tecnologias

📂 Estrutura do Projeto

💻 Como Executar o Projeto

📄 Documentação de Requisitos

👥 Contribuição

📝 Licença

🚨 O Problema
Trabalhadores autônomos e prestadores de serviços informais frequentemente enfrentam grande inconstância financeira e dificuldade para expandir suas carteiras de clientes. A falta de uma ferramenta acessível gera os seguintes impactos operacionais e econômicos:

Dependência do "Boca a Boca": O profissional fica limitado à sua rede imediata de contatos, o que resulta em longos períodos sem demandas de trabalho.

Insegurança e Falta de Credibilidade: Sem um histórico visível de serviços prestados ou depoimentos reais de clientes anteriores, profissionais qualificados perdem oportunidades para concorrentes informais.

Desperdício de Tempo e Custos de Divulgação: Divulgar serviços de forma não direcionada (ex: panfletos, grupos informais em redes sociais) gera alto custo de tempo e baixo retorno de conversão.

Insegurança para o Contratante: Clientes que precisam de um serviço urgente não possuem um canal confiável para verificar reputação, pontualidade e histórico dos profissionais que contratam.

💡 A Solução
A Aureon surge para resolver esses gargalos criando uma ponte direta, transparente e ágil entre a demanda e a oferta de serviços autônomos:

Visibilidade Direcionada: Permite que o prestador crie um perfil profissional completo com portfólio de fotos e áreas de atuação, sendo encontrado por clientes da sua própria região.

Reputação Auditada: Sistema transparente de avaliações por estrelas e depoimentos em texto, permitindo que os profissionais construam sua autoridade com base na qualidade do trabalho entregue.

Central de Orçamentos Ágil: Permite aos clientes descreverem suas necessidades (com suporte a envio de fotos do problema) e solicitarem cotações de forma padronizada.

Democratização do Trabalho: Proporciona uma ferramenta gratuita/acessível de gestão e prospecção de clientes para profissionais de qualquer segmento (manutenção residencial, tecnologia, beleza, aulas, etc.).

🚀 Principais Funcionalidades
👷‍♂️ Para o Prestador de Serviços
Cadastro e Gestão de Perfil: Atualização de biografia, foto de perfil, categorias de atendimento e dados de contato.

Portfólio de Galeria: Upload de fotos de trabalhos recentes realizados.

Gestão de Solicitações: Painel para visualizar e responder a orçamentos recebidos.

👤 Para o Cliente Contratante
Busca Avançada com Filtros: Pesquisa por palavra-chave, categoria de serviço, cidade e média de avaliação.

Solicitação de Orçamento: Formulário para detalhamento do serviço desejado e anexo de imagens.

Sistema de Avaliação: Atribuição de notas (1 a 5 estrelas) e envio de feedbacks após a conclusão do atendimento.

🏗️ Arquitetura e Tecnologias
A plataforma foi planejada seguindo boas práticas de arquitetura de software, garantindo alta usabilidade, responsividade e tempos de resposta ágeis.

Frontend: HTML5, CSS3 / Tailwind CSS, JavaScript (React / Vue.js)

Backend: Node.js / Python (RESTful API)

Banco de Dados: PostgreSQL / MySQL

Autenticação & Segurança: JWT (JSON Web Tokens), criptografia de senhas com bcrypt, conformidade com a LGPD

Hospedagem / Storage: Cloud Storage para fotos de portfólio (ex: AWS S3 ou Cloudinary)

📂 Estrutura do Projeto
Plaintext
aureon/
├── docs/                 # Documentos do projeto (Visão, Requisitos, Histórias de Usuário)
├── public/               # Arquivos estáticos
├── src/
│   ├── assets/           # Imagens e estilos globais
│   ├── components/       # Componentes reutilizáveis de interface
│   ├── controllers/      # Lógica das rotas de API
│   ├── models/           # Mapeamento do Banco de Dados
│   ├── routes/           # Definição de endpoints da aplicação
│   └── services/         # Regras de negócio e integrações
├── .gitignore
├── package.json
└── README.md
💻 Como Executar o Projeto
Pré-requisitos
Antes de começar, você precisará ter instalado em sua máquina:

Git

Node.js (v18 ou superior)

Banco de Dados PostgreSQL instalado ou container Docker

Passo a Passo
Bash
# 1. Clonar o repositório
$ git clone https://github.com/aureon/aureon.git

# 2. Entrar na pasta do projeto
$ cd aureon

# 3. Instalar as dependências
$ npm install

# 4. Configurar as variáveis de ambiente (.env)
$ cp .env.example .env

# 5. Executar as migrações do banco de dados
$ npm run migrate

# 6. Iniciar a aplicação no modo de desenvolvimento
$ npm run dev
A aplicação estará acessível em http://localhost:3000.

📄 Documentação de Requisitos
A documentação detalhada da engenharia de software da Aureon está disponível na pasta /docs:

📄 Documento de Visão de Produto

📋 Roteiro de Entrevista para Requisitos

📜 Especificação de Requisitos (RF / RNF / RN)

📑 Histórias de Usuário e Backlog MoSCoW

👥 Contribuição
Contribuições são sempre bem-vindas! Se você deseja colaborar com o desenvolvimento da Aureon:

Faça um Fork do projeto.

Crie uma nova branch com a sua funcionalidade: git checkout -b feature/minha-funcionalidade.

Salve suas alterações e faça o commit: git commit -m 'feat: adiciona nova funcionalidade'.

Envie para o repositório remoto: git push origin feature/minha-funcionalidade.

Abra um Pull Request.

📝 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
