# Guia de Contribuição – SEMCULT

Bem-vindo(a) ao espaço digital da **Secretaria Municipal de Cultura e Turismo de Belém (SEMCULT)**.  
Este guia estabelece as regras e boas práticas para colaboração nos repositórios oficiais da organização.

---

## 📌 Quem pode contribuir
- Apenas membros autorizados do **Departamento de Tecnologia da Informação (DTI)** podem realizar contribuições.  
- Contribuições externas não são aceitas neste momento.  
- Todas as alterações devem passar por revisão antes de serem integradas ao código principal.

---

## 🔄 Fluxo de Trabalho
1. **Criação de branch**  
   - Sempre crie uma nova branch a partir de `main`.  
   - Use uma convenção clara no nome, por exemplo:  
     - `feature/nome-da-funcionalidade`  
     - `bugfix/correcao-especifica`  
     - `hotfix/ajuste-critico`  

2. **Commits**  
   - Mensagens de commit devem ser objetivas e descrever a mudança feita.  
   - Exemplo:  
     - `fix: corrigido erro de autenticação no login`  
     - `feat: adicionada integração com API de eventos`  

3. **Pull Requests (PRs)**  
   - Toda alteração deve ser enviada via Pull Request.  
   - O PR deve conter:  
     - Descrição clara do que foi alterado.  
     - Issue relacionada (se houver).  
     - Checklist de testes básicos.  
   - Pelo menos **1 aprovação de revisor** (Thiago ou Aiua) é obrigatória antes do merge.  

---

## 🐛 Abertura de Issues
- Sempre que identificar um problema, abra uma **Issue**.  
- Use labels (ex.: `bug`, `enhancement`, `infra`, `documentação`).  
- Descreva de forma clara o problema, passos para reprodução (quando aplicável) e sugestões de solução.

---

## ✅ Boas Práticas
- Código deve seguir padrões definidos pela equipe (linters, formatação e convenções internas).  
- Manter o repositório organizado: nada de arquivos temporários ou credenciais sensíveis.  
- Documentar mudanças relevantes no README ou na Wiki do projeto.  
- Revisar sempre as configurações de segurança (tokens, secrets, etc.).

---

## 🔒 Governança e Segurança
- **Main branch protegida** → não é permitido push direto na `main`.  
- Todo código passa por revisão obrigatória.  
- Logs e histórico de commits devem ser preservados.  
- Informações sensíveis (senhas, chaves, tokens) **nunca** devem ser incluídas no repositório.

---

## 👥 Responsáveis pela Revisão
- **Thiago Alberto Cruz dos Santos (DTI – Diretor)**  
- **Aiua Reis Queiroz (Superintendente)**  

O estagiário Edgar poderá submeter contribuições via Pull Requests, mas somente sob revisão e aprovação de um dos responsáveis acima.
