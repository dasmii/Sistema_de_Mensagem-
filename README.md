# Projeto P2 – Continuação do Site de Aluguel de Iates

Este projeto é a continuação do **P1 – Site de Aluguel de Iates**.  
O objetivo é implementar uma **API de mensagens** que permita:

- Inserir mensagens enviadas pelo formulário de contato.  
- Criar um ambiente seguro de leitura das mensagens recebidas (apenas por usuários autorizados).  
- Gerenciar mensagens (visualizar, marcar como lidas e excluir).  

## 📌 Funcionalidades

1. **Contato (contato.html)**  
   - Formulário para envio de mensagens.  
   - Uso da função `inserirMensagem(mensagem)` para salvar os dados.  

2. **Admin (admin.html)**  
   - Página de login com e-mail e senha.  
   - Autenticação via `validarUsuario(objLoginSenha)`.  
   - Redirecionamento para `mensagens.html` em caso de login válido.  

3. **Mensagens (mensagens.html)**  
   - Exibição dinâmica das mensagens usando `obterMensagens()`.  
   - Mensagens novas aparecem em **negrito**.  
   - Mensagens visualizadas aparecem em fonte normal.  
   - Armazenamento local das mensagens no navegador.  

4. **Gerenciamento de Mensagens**  
   - Botão **Excluir Mensagem** (com confirmação).  
   - Botão **Mensagem Visualizada** (com confirmação).  

## 🛠 Tecnologias Utilizadas
- HTML5  
- CSS3  
- JavaScript (ES6+)  
- jQuery 3.6.4  
- API.js (funções fornecidas)  

---

✅ Esse projeto garante envio, autenticação e gerenciamento seguro das mensagens recebidas no site de aluguel de iates.
