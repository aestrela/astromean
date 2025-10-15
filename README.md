# astromean

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
------------------
# 🌌 Astromean

**Astromean** é um aplicativo educacional desenvolvido em **Flutter**, que combina **conteúdo interativo**, **leitura guiada** e **quizzes** sobre astrologia.  
Inspirado na usabilidade de apps como *Duolingo* e *Sololearn*, o projeto oferece uma jornada de aprendizado gamificada, moderna e acessível.

---

## ✨ Objetivo

Criar uma experiência de **aprendizado envolvente e acessível**, onde o usuário possa:
- Ler textos curtos e ilustrados sobre astrologia;
- Realizar quizzes interativos ao final de cada módulo;
- (Plano Plus 💫) Destacar trechos e salvar suas anotações como um "marca-texto digital";
- Acompanhar seu progresso e explorar conteúdos exclusivos.

---

## 🧱 Stack Tecnológica

| Camada | Tecnologia | Função |
|--------|-------------|--------|
| **Frontend** | Flutter | Interface multiplataforma (Android, iOS, Web) |
| **Backend** | Firebase | Autenticação, Firestore, Storage e Cloud Functions |
| **Banco de Dados** | Firestore | Armazenamento em tempo real |
| **Pagamentos** | RevenueCat (via Google/Apple IAP) | Gerenciamento do plano Plus |
| **Controle de Versão** | Git + GitHub | Versionamento e colaboração |

---

## 🗂️ Estrutura de Pastas

astromean/
├── android/ # Código nativo Android
├── ios/ # Código nativo iOS
├── web/ # Versão web do app
├── lib/ # Código principal em Flutter
│ ├── core/ # Constantes, temas e utilitários
│ │ ├── constants/
│ │ └── themes/
│ ├── models/ # Modelos de dados (usuário, quiz, etc.)
│ ├── services/ # Firebase, Auth, RevenueCat, etc.
│ ├── screens/ # Telas principais do app
│ ├── widgets/ # Componentes reutilizáveis
│ └── data/ # Conteúdos estáticos (textos, quizzes básicos)
├── assets/ # Imagens, ícones e fontes
│ ├── images/
│ ├── icons/
│ └── fonts/
├── pubspec.yaml # Configurações de dependências e assets
├── README.md # Documentação do projeto
└── .gitignore # Arquivos ignorados pelo Git


---

## 🚀 Como executar o projeto

### Pré-requisitos
- Flutter instalado ([Guia oficial](https://docs.flutter.dev/get-started/install))
- Android SDK configurado
- Emulador Android ou Chrome (para Web)
- VS Code ou Android Studio

### Passos
```bash
# Clone o repositório
git clone https://github.com/SEU-USUARIO/astromean.git

# Entre na pasta do projeto
cd astromean

# Baixe as dependências
flutter pub get

# Execute no navegador ou emulador
flutter run
💳 Plano Plus (futuro)

O Astromean Plus oferecerá recursos adicionais:

Marcação e salvamento de trechos importantes

Acesso a conteúdos avançados

Estatísticas de progresso

Experiência sem anúncios

🎨 Identidade Visual

Tema: moderno com nostalgia anos 80/90/2000
Paleta base: Laranja vibrante #FF7A00 + Roxo #6C1FFF + Azul ou Rosa secundário
Tipografia: fontes retrô, com inspiração “MTV era 90s”
Estilo: limpo, contrastado e cativante

🧭 Roadmap
Fase	Descrição	Status
Fase 1	MVP com leitura e quizzes básicos	🟢 Em andamento
Fase 2	Adição do sistema de marca-texto (Plus)	⏳ Planejado
Fase 3	Publicação nas lojas e integração com assinaturas	🔜 Futuro
🤝 Contribuições

Pull requests são bem-vindos!
Sinta-se à vontade para abrir issues e sugerir melhorias.

🪐 Licença

Este projeto está licenciado sob a MIT License — veja o arquivo LICENSE
 para mais detalhes.

💬 “Astromean nasceu da ideia de unir aprendizado, tecnologia e astrologia — com design vibrante e conteúdo envolvente.”