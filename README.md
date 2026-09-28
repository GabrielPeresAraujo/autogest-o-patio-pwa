[readme.md](https://github.com/user-attachments/files/32774519/readme.md)
# autogestao-patio-pwa

```text
autogestao-patio-pwa/
├── .github/
│   ├── workflows/
│   │   └── ci.yml                 # Pipeline de CI (Build, Linter e Testes)
│   └── PULL_REQUEST_TEMPLATE.md   # Template formal para Pull Requests
├── lib/                           # Código-fonte da aplicação (MVC Pattern)
│   ├── controllers/              # Regras de negócio e gerenciamento de estado
│   ├── models/                   # Entidades de dados (Veículo, Status, Usuário)
│   ├── views/                    # Telas PWA (Login, Catálogo/Pátio, Lead WhatsApp)
│   └── services/                 # Integrações (Hive Local Storage, Supabase, API)
├── test/                          # Suíte de testes automatizados
│   ├── unit/                     # Testes unitários de validação e formatação
│   └── integration/              # Testes de integração de fluxos e cache
├── .gitignore                     # Arquivos ignorados pelo Git
├── README.md                      # Documentação técnica e instruções do projeto
└── pubspec.yaml                   # Gerenciador de dependências e scripts do projeto
```
