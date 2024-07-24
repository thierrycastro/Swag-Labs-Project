Projeto: Swag Labs

Nome do Caso de Teste: Validação de Login

Descrição: Este caso de teste automatizado verifica a funcionalidade do sistema de autenticação de usuários na aplicação web usando Cypress. O objetivo é garantir que o sistema permita que um usuário existente faça login com credenciais válidas e bloqueie o acesso quando são fornecidas credenciais inválidas.

Tecnologia:

•	Ferramenta de Teste: Cypress

-----

Pré-condições:

•  O usuário deve estar previamente registrado no sistema.

•  O ambiente de teste deve estar configurado e acessível.

•  Cypress deve estar instalado e configurado no projeto.

-----

Passos para a execução do teste:
1.	Abra o terminal e navegue até o diretório do projeto
2.	Execute o Cypress: npx cypress open
3.	No Cypress Test Runner, selecione o teste de login para executá-lo.

 -----
 
Critérios de Aceitação:

•  O usuário deve ser redirecionado para a página inicial (dashboard) após fazer login com credenciais válidas.

•  Uma mensagem de erro "Credenciais inválidas" deve ser exibida quando o usuário tentar fazer login com credenciais inválidas.

•  O sistema deve impedir o acesso a usuários não autenticados.

-----

Resultados Esperados:

•  Teste com credenciais válidas: O usuário é redirecionado para a página inicial e uma mensagem de boas-vindas é exibida.

•  Teste com credenciais inválidas: Uma mensagem de erro "Credenciais inválidas" é exibida.

-----

Notas Adicionais:

•	Verificar se a interface está conforme o design especificado.

•	Testar diferentes navegadores (Google Chrome, Mozilla Firefox) usando o Cypress.

•	Documentar qualquer comportamento inesperado encontrado durante os testes.

-----

Ambiente de Teste:

•	Sistema Operacional: Windows 10.

•	Navegadores: Google Chrome - Versão 125.0.6422.176 (x64 bits), Mozila Firefox - Versão 127.0.1 (x64 bits), Microsoft Edge - Versão 126.0.2592.81 (x64 bits).

•	Versão da Aplicação: 1.0.0

-----

Histórico de Alterações:

•	Data: 11/07/2024

    o	Descrição: Caso de teste inicial criado.
    
    o	Autor: Thierry Castro
    
•	Data: 19/07/2024

    o	Descrição: Adicionadas notas sobre compatibilidade cross-browser.
    
    o	Autor: Thierry Castro

-----

Anexos:

•	Protejo_Swag_Labs.mp4

    
