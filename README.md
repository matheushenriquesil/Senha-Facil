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
   

## 🗂️ Passo a Passo do Desenvolvimento

- [x] **Planejamento Inicial**  
  - Definir objetivo do sistema (senhas automáticas, preferenciais, histórico).  
  - Distribuir funções entre equipe (programador, designer, gerente).  
  *📝 Justificativa:* Etapa adicionada para deixar o escopo claro antes de iniciar a codificação.

- [x] **Protótipo de Tela**  
  - Criar layout visual inicial (fluxo das telas, botões, exibição de senha).  
  *📝 Justificativa:* Mantido como no plano original, essencial para guiar a implementação.

- [ ] **Configuração do Projeto**  
  - Criar pasta do projeto no VS Code.  
  - Inicializar arquivos: `main.py`, `README.md`, `ROADMAP.md`.  
  - Configurar ambiente virtual (`venv`) para Python.  
  *📝 Justificativa:* Adicionada a criação do ambiente virtual para garantir padronização do projeto.

- [ ] **Implementação da Geração de Senhas**  
  - Criar função para gerar senha normal.  
  - Criar função para gerar senha preferencial.  
  - Testar geração de senhas no terminal.  
  *📝 Justificativa:* Separar funções facilita testes e manutenção do código.

- [ ] **Navegação entre Senhas e Histórico**  
  - Criar função para exibir "senha atual".  
  - Criar funções para "senha anterior" e "senha próxima".  
  - Salvar histórico de senhas em arquivo `.csv`.  
  *📝 Justificativa:* Inclui exibição da senha atual para melhor controle na navegação.

- [ ] **Interface Simples no Terminal (Opcional)**  
  - Criar menu para gerar nova senha, ver senha atual, navegar e exibir histórico.  
  *📝 Justificativa:* Facilita testes e uso antes de desenvolver interface gráfica.

- [ ] **Testes e Ajustes**  
  - Testar todas as funções individualmente.  
  - Corrigir possíveis bugs de geração, histórico e navegação.  
  - Verificar integridade do arquivo `.csv`.  
  *📝 Justificativa:* Mantido, essencial para garantir estabilidade e confiabilidade do sistema.

- [ ] **Documentação e Preparação Final**  
  - Revisar `README.md` e `ROADMAP.md`.  
  - Criar guia rápido de uso para apresentação.  
  - Adicionar comentários no código para facilitar entendimento.  
  *📝 Justificativa:* Etapa reforçada para valorizar a clareza e organização da entrega final.

- [ ] **Entrega Final**  
  - Entregar o programa funcional com geração, histórico e navegação de senhas.  
  - Garantir que todos os arquivos estejam organizados e prontos para apresentação.  
  *📝 Justificativa:* Mantido, representa a conclusão do projeto.

- [ ] **Futuras Evoluções (Opcional)**  
  - Criar **interface gráfica (GUI)** com Tkinter.  
  - Criar **versão web simples** usando Flask ou Streamlit.  
  *📝 Justificativa:* Mantido como proposta de expansão futura do projeto.

---


💡 **Objetivo final:**  
Ter um **programa funcional e simples**, que gere senhas automáticas (normais e prioritárias), registre histórico e possa futuramente ser adaptado para interface gráfica ou web.
