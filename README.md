tilapia company
# Senha-Facil
atendimento por senhas trabalho de logica ct ano 2025

Um programa em **Python** que gera senhas automáticas para atendimento — inspirado no sistema de senhas do **SUS** — para agilizar o fluxo de pessoas em clínicas, eventos ou repartições públicas.  
O sistema cria senhas com prioridade, salva o histórico e é fácil de usar e expandir.

---

## 👥 Equipe de Desenvolvimento

- **Matheus Reis** — Gerente de Projeto  
- **Vitória** — Designer  
- **Felipe** — Programador

---

## 💡 Funcionalidades

- Geração automática de senhas (ex: `A001`, `P005`)  
- Diferenciação entre **atendimento normal** e **prioritário**  
- Registro de senhas geradas em um arquivo `.csv`  
- Interface de linha de comando simples (CLI)  
- Estrutura pronta para futura interface gráfica (GUI)  

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.8+**  
- Biblioteca padrão (`os`, `csv`, `datetime`)  
- (Opcional) `tkinter` → para interface gráfica  
- (Opcional) `pandas` → para relatórios  
- (Opcional) `pyserial` → para impressora  

---

## 🚀 Como Rodar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/gerador-senhas.git
   cd gerador-senhas
   

##🗂️ Roadmap Passo a Passo – Sistema de Senhas Automáticas

 Planejamento Inicial

Definir objetivo do sistema (senhas automáticas, preferenciais, histórico).

Distribuir funções entre equipe (programador, designer, gerente).
Justificativa: Adicionei como etapa explícita para deixar claro o escopo antes de começar a codar.

 Protótipo de Tela

Criar layout visual inicial (fluxo das telas, botões, exibição de senha).
Justificativa: Mantido como no README; essencial para guiar a implementação.

 Configuração do Projeto

Criar pasta do projeto no VS Code.

Inicializar arquivos: main.py, README.md, ROADMAP.md.

Configurar virtual environment (venv) para Python.
Justificativa: Adicionei o venv para padronizar o ambiente Python, evita erros de biblioteca.

 Implementação da Geração de Senhas

Criar função para gerar senha normal.

Criar função para gerar senha preferencial.

Testar a geração de senhas no terminal.
Justificativa: Separei a geração de senhas normais e preferenciais para facilitar testes individuais.

 Navegação entre Senhas e Histórico

Criar função para exibir "senha atual".

Criar função para ir para "senha anterior" e "senha próxima".

Salvar histórico de senhas em arquivo .csv.
Justificativa: Mantido, mas adicionei explicitamente o “exibir senha atual” para não se perder na navegação.

 Interface Simples no Terminal (Opcional)

Menu básico para selecionar: gerar nova senha, ver senha atual, avançar/voltar, visualizar histórico.
Justificativa: Facilita testes e uso antes de pensar em GUI.

 Testes e Ajustes

Testar todas as funções individualmente.

Corrigir bugs de geração, histórico e navegação.

Validar arquivos .csv (integridade e leitura).
Justificativa: Mantido; essencial para estabilidade.

 Documentação e Preparação Final

Revisar README.md e ROADMAP.md.

Preparar guia rápido de uso para apresentação.

Adicionar comentários no código para melhor entendimento.
Justificativa: Adicionei comentários no código como passo explícito para boas práticas.

 Entrega Final

Programa funcional com geração de senha, histórico e navegação.

Todos os arquivos organizados no projeto.

Preparação para apresentação à turma/escola.
Justificativa: Mantido, etapa final clara.

 Futuras Evoluções (Opcional)

Criar interface gráfica (GUI) usando Tkinter.

Criar versão web simples (Flask ou Streamlit).
Justificativa: Mantido como evolução futura; não atrapalha o desenvolvimento inicial.

💡 **Objetivo final:**  
Ter um **programa funcional e simples**, que gere senhas automáticas (normais e prioritárias), registre histórico e possa futuramente ser adaptado para interface gráfica ou web.
