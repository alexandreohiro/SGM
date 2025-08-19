SGM - Sistema de Gerenciamento de Malote - B Adm QGEx

📦 Sistema de Gerenciamento de Malotes – Mark I

É um núcleo inteligente de tráfego de informações, preparado para evoluir em camadas: do simples CRUD até um hub de inteligência artificial e segurança militar digital.
Modular, escalável e transparente.
Cada parte é uma tropa, cada módulo é uma unidade. O todo é mais forte que a soma das partes.

🧩 Arquitetura Modular
sistema-malote/
│── docs/                  # Documentação e diagramas
│── frontend/              # Interface do usuário (HTML/JS/React)
│   ├── public/            # Assets globais
│   ├── views/             # Páginas e templates
│   └── js/                # Scripts (Chart.js, DataTables, Ajax)
│
│── backend/               # Núcleo do sistema
│   ├── api/               # Endpoints REST
│   │   ├── php/           # PHP (CRUD, relatórios, autenticação)
│   │   └── python/        # Python (IA, NLP, OCR, previsões)
│   ├── c_cpp/             # Módulos críticos em C/C++ (performance/segurança)
│   ├── core/              # Regras de negócio e fluxo de documentos
│   └── utils/             # Logs, criptografia, validações
│
│── database/              # Banco de dados
│   ├── migrations/        # Alterações de esquema
│   ├── seeds/             # Dados iniciais (tipos de doc, OMS, perfis)
│   └── schema.sql         # Estrutura principal
│
│── ia/                    # Inteligência Artificial
│   ├── nlp/               # Busca em linguagem natural
│   ├── ocr/               # Reconhecimento de texto em documentos
│   ├── anomaly/           # Detecção de anomalias
│   └── forecasting/       # Previsão de fluxo
│
│── tests/                 # Testes unitários e integração
│── config/                # Configurações (env, php.ini, settings.json)
│── scripts/               # Scripts auxiliares (setup, backup, deploy)
│── .gitignore             # Arquivos ignorados
│── README.md              # Este documento
└── LICENSE                # Licença

⚙️ Tecnologias

Frontend: HTML5, CSS3, JS (Chart.js, DataTables, Ajax) → futuramente React + Tailwind.

Backend:

PHP (via XAMPP) → CRUD e relatórios.

Python (FastAPI/Flask) → serviços de IA.

C/C++ → módulos críticos (performance, criptografia).

Banco de Dados: MySQL/MariaDB.

IA: NLP (pesquisa semântica), OCR, detecção de anomalias, previsão de fluxo.

🚀 Roadmap (Mark I → Mark III)
🔹 Fase 1 – MVP

Login e controle de perfis.

CRUD de documentos.

Dashboard básico com contadores.

Relatórios e exportações (CSV, Excel, PDF).

🔹 Fase 2 – Administração e Segurança

Cadastro de OMS, seções e usuários.

Perfis RBAC (Admin, Supervisor, Atendente, Auditor).

Logs e auditoria.

Criptografia e autenticação com JWT.

🔹 Fase 3 – IA e Automação

Busca em linguagem natural (NLP).

Sugestão automática no cadastro.

OCR para leitura de documentos digitalizados.

Anomalias e previsões de fluxo.

Integração com assinatura digital (ITI).

📊 Fluxo Operacional

Documento é cadastrado → vinculado a OMS/Seção.

Sistema gera linha do tempo (entrada, retirada, entrega, devolução).

Painel mostra indicadores e SLA em tempo real.

IA apoia com busca inteligente, sugestões e alertas.

Toda ação fica registrada em log de auditoria.

🛡️ Segurança

Perfis de acesso por função.

Autenticação JWT + opção 2FA.

Tráfego HTTPS/TLS.

Logs imutáveis de auditoria.

Conformidade com LGPD.

📖 Filosofia

Modularidade: cada parte pode ser trocada sem afetar o todo.

Clareza: tudo documentado, nada escondido.

Escalabilidade: pronto para crescer com mais IA e automação.

Impacto real: menos burocracia, mais rastreabilidade, mais eficiência.

📌 Status

Mark I (Em construção): estrutura modular e CRUD básico.

Mark II (Planejado): administração avançada e segurança.

Mark III (Visão): IA integrada, previsões e automação total.