# Tape

**Tape** vem do guarani e significa **"caminho"**. Cada dia é um novo trecho do seu caminho de conquistas.

Um app de produtividade pessoal com design gamificado, feito para acompanhar suas atividades diárias organizadas por temas.

## Funcionalidades

### Temas
Organize suas atividades em áreas da vida:
- **Trabalho**, **Saúde**, **Lazer**, **Auto Cuidado**, **Atividades Físicas**, **Tempo de Qualidade**
- Crie temas personalizados com nome, cor e ícone
- Defina em quais dias da semana cada tema está ativo

### Atividades
Cada tema contém atividades que você completa no dia a dia:
- Marque como concluída com um toque
- Horário opcional (fixo ou faixa de horário)
- Configure dias da semana específicos por atividade

### Tela Principal
- Atividades agrupadas por tema (toque para expandir)
- Opção de ver todas as atividades em lista plana
- Ordenação por horário
- Barra de progresso diário

### Celebrações
- Confetti ao completar um tema
- Animação especial ao completar o dia inteiro
- Sistema de badges (Dia Perfeito, Semana de Ouro, Streak, etc.)

### Relatório Semanal
- Taxa de conclusão por tema
- Melhor tema e tema a melhorar
- Dias perfeitos e streaks consecutivos
- Notificação semanal configurável

### Configurações
- Aparência: Claro, Escuro ou Automático (segue o sistema)
- Idioma: Português (BR) e Inglês
- Configuração de início/fim da semana
- Notificações por tema

### Dados e Privacidade
- Login via Google
- Dados salvos no Google Drive (pasta privada do app, invisível ao usuário)
- Funciona offline com sincronização automática
- Sem servidor próprio — seus dados ficam apenas na sua conta Google

## Tecnologias

- React Native + Expo SDK 52
- TypeScript
- Expo Router (navegação)
- Google Drive API (armazenamento)
- AsyncStorage (cache offline)

## Instalação

Baixe o APK da última release na página de [Releases](https://github.com/gustavoeriick/Gus.App.ProdutividadeMax/releases).

1. Baixe o arquivo `.apk`
2. Abra no celular e permita fontes desconhecidas
3. Instale e abra o app

## Releases

### v0.1.0-dev (em desenvolvimento)
- Estrutura base do app com temas e atividades
- Login com Google
- Tela principal com progresso diário
- Relatório semanal
- Dark mode e i18n (pt-BR / en)
- CI/CD com GitHub Actions para build de APK

---

Feito com dedicação por [@gustavoeriick](https://github.com/gustavoeriick)