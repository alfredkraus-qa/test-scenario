# Aprendendo sobre Cenários de Teste 

### **Olá, pessoal!**

Criei este repositório para documentar o meu aprendizado sobre **cenários de teste**. Espero que vocês achem útil e aproveitem as informações!

## Mas o que é um cenário de teste?

Um cenário de teste é uma **situação geral ou funcionalidade que será testada**. Ele descreve amplamente o que precisa ser avaliado, sem entrar nos detalhes técnicos ou nos passos específicos.

**Exemplo:** Verificar o processo de login de um usuário, desde a entrada das credenciais até o acesso ao sistema.

## Quando devemos criar um cenário de teste?

O cenário de teste deve ser criado **antes dos casos de teste**. Geralmente, ele é desenvolvido logo após a análise dos requisitos ou histórias de usuário, ajudando a conectar o entendimento do que o sistema deve fazer com os testes que serão realizados.

## Como criar um cenário de teste eficiente?

Aqui estão algumas etapas que podem te ajudar:

### 1. Entenda o produto

Estude profundamente o sistema ou produto que será testado.

**Dica:** Analise a documentação do projeto, participe de reuniões de briefing e, se possível, converse com o time de desenvolvimento e stakeholders para esclarecer dúvidas.

**Exemplo:** Para uma tela de cadastro, verifique quais são os requisitos para cadastro, como tipos de credenciais aceitas (e-mail, CPF, etc.), regras de validação (senha obrigatória, limites de caracteres) e fluxos esperados (redirecionamento após login bem-sucedido ou mensagens de erro em caso de falha).

Exemplo prático: [front serverest](https://front.serverest.dev/login)

<img width="737" alt="Screenshot 2025-01-15 at 17 45 33" src="https://github.com/user-attachments/assets/959ef33b-2e02-4f8f-b17d-c0e3488d75bf" />

### 2. Use o sistema

Experimente o sistema na prática. Isso ajuda a identificar funcionalidades críticas e potenciais problemas.

**Exemplo:** Tente fazer um cadastro fictício para verificar como o sistema se comporta.

<img width="472" alt="Screenshot 2025-01-15 at 17 59 33" src="https://github.com/user-attachments/assets/be205e0f-5e4f-437c-8fd1-770d2834bd45" />

### 3. Isole os Requisitos 

Agora use uma ferramenta ou sistema de gestão de teste (Jira, Trello, TestRail) e divida os requisitos em partes menores e bem definidas.

**Exemplo:** Se o requisito é “permitir que o usuário se cadastre”, você pode isolar as condições: verificar o login com credenciais válidas, verificar login com credenciais inválidas, e verificar login com conta bloqueada.

<img width="760" alt="Screenshot 2025-01-15 at 18 55 14" src="https://github.com/user-attachments/assets/fbc0b998-e492-41c2-9c25-50fffd5d4a69" />

### 4. Liste os cenários de teste possíveis

Anote todas as situações que precisam ser avaliadas com base nos requisitos.

**Exemplo:** Para o cenário de login, os cenários podem incluir:

• Usuário insere login e senha corretos.

• Usuário insere senha incorreta.

• Campo de senha está vazio.


<img width="915" alt="Screenshot 2025-01-15 at 18 52 45" src="https://github.com/user-attachments/assets/655dd2b7-a049-4764-a175-c8eed4637d1b" />


### 5. Documente tudo!

Registre os cenários de teste de forma organizada e acessível para a equipe.

**Dica:** Use ferramentas como planilhas ou sistemas de gestão de testes (ex.: TestRail, Jira, Trello) para centralizar as informações.

**Exemplo:** Crie uma tabela com as colunas: ID do cenário, descrição, prioridade e status.

<img width="576" alt="Screenshot 2025-01-15 at 18 13 22" src="https://github.com/user-attachments/assets/713d9263-eeee-4952-9e30-e2fb1f7ba86e" />

## Considerações finais

Criar cenários de teste bem estruturados é um passo fundamental para garantir a qualidade de qualquer produto ou sistema. Além de facilitar o trabalho de QA, essa prática também ajuda no alinhamento com o time e na prevenção de problemas. **Lembre-se:** um bom planejamento hoje pode evitar grandes dores de cabeça no futuro.

Se você tem sugestões ou quer compartilhar sua experiência, fique à vontade para colaborar neste repositório. Bora construir algo incrível juntos! 🪲🚀
