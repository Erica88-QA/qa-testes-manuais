# qa-testes-manuais
Dia a Dia de um QA: A Prática de Testes Manuais Funcionais

📌 Projeto: O Dia a Dia de um QA — A Prática de Testes Manuais Funcionais
🧠 1. Documentação de Teste
   
👉 Mind Map (Mapa Mental)
O Mind Map ajuda a visualizar os caminhos e componentes principais do que será testado. Pode incluir:

 > Funcionalidades da aplicação
 > Áreas de teste (login, cadastro, pagamentos, etc.)
 > Tipos de teste aplicados (funcional, regressão, integração)

📌 Exemplo visual (pode ser feito no XMind, Draw.io, Whimsical):
# Login
 ├── Campo de usuário
 ├── Campo de senha
 ├── Botão "Entrar"
 └── Mensagens de erro 

👉 Casos de Teste 
Um caso de teste é um conjunto de condições ou variáveis usadas para verificar se uma funcionalidade está funcionando conforme o esperado.

| ID   | Caso de Teste                 | Pré-condição           | Ação                             | Resultado Esperado             |
| ---- | ----------------------------- | ---------------------- | -------------------------------- | ------------------------------ |
| CT01 | Login com credenciais válidas | Estar na tela de login | Informar usuário e senha válidos | Redirecionado para o dashboard |

 👉 Cenários de Teste 
 Os cenários de teste são descrições mais amplas e geralmente em linguagem natural. São úteis para alinhar com o time de produto/negócio.

📄 Exemplo de cenário de teste:
Cenário: Usuário realiza login com sucesso
Dado que o usuário está na página de login
Quando insere seu e-mail e senha válidos
Então deve acessar o sistema com sucesso

📚 2. A Prática da Documentação de Teste > Conceitos e Teoria
Objetivo da documentação: garantir que todos os testes possam ser repetidos e compreendidos por outros membros do time.

* Tipos comuns de documentação de QA:
- Plano de Teste
- Casos de Teste
- Evidências de Teste
- Checklist de Regressão

* Benefícios:
- Rastreabilidade
- Padronização dos testes
- Redução de erros repetitivos

🛠️ 3. A Prática da Documentação de Teste > Aplicando os Conceitos

* casos-de-teste.md

### Casos de Teste - Tela de Login

#### CT01 - Login com sucesso
- **Pré-condição:** Acessar tela de login
- **Passos:**
  1. Preencher usuário válido
  2. Preencher senha válida
  3. Clicar em "Entrar"
- **Resultado esperado:** Usuário redirecionado para a home

#### CT02 - Senha incorreta
- **Passos:**
  1. Preencher usuário válido
  2. Preencher senha inválida
  3. Clicar em "Entrar"
- **Resultado esperado:** Mensagem de erro "Senha inválida"

* cenarios-de-teste.md

### Cenários de Teste - Login

**Cenário 01:** Login bem-sucedido  
Dado que o usuário está na tela de login  
Quando preencher o login e senha corretos  
Então deve ser redirecionado à página principal

**Cenário 02:** Login com senha errada  
Dado que o usuário está na tela de login  
Quando preencher a senha incorretamente  
Então deve ver uma mensagem de erro

