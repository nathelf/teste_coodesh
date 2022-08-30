# teste_coodesh

-- Apontamentos de chamadas API estão ocorrendo corretamente
-- Responsividade Mobile/Desktop 

Obrigatório 2 - Navegar pela página de login no menu superior;

-- Ao selecioanar acesso via conta Google, é realizada a chamada: Solicitar URL: https://accounts.youtube.com/_/AccountsDomainCookiesCheckConnectionHttp/cspreport
 origin: https://accounts.youtube.com 
 referrer: "https://accounts.google.com/"

404. That’s an error.
The requested URL /_/AccountsDomainCookiesCheckConnectionHttp/cspreport was not found on this server. That’s all we know.

Obrigatório 3 - Agora deverá criar uma conta para o perfil de pessoas candidatas;
-- Criar perfil 
-- Preenchimento de todos os campos obrigatórios 
-- Validações de responsividade

Obrigatório 4 - Ao criar a conta você será direcionado ao sistema para o preenchimento do perfil e deverá testar os formulários que estarão em cada etapa do preenchimento do perfil;
-- Opção Feedback: message: "Reação atualizada"
-- Permite realizar o avanço dos testes sem preencher/selecionar nenhuma alternativa 

Obrigatório 5 - Um vez na tela de vagas, terá que buscar por uma empresa onde terá um ou mais resultados de vagas;
-- Ao dar scroll na listagem de vagas, a mesma fica atualizando as chamadas mesmo que a página não foi atualizada. 

Deferencial - Você poderá documentar testes para a criação de contas com redes sociais (github, linkedin e google)
-- Linkdin: Bad Request
-- Github
For request 'POST /platform-telemetry/li/apfcDf' [HTTP header is larger than 8192 bytes.]
-- Google: 404. That’s an error.
The requested URL /_/AccountsDomainCookiesCheckConnectionHttp/cspreport was not found on this server. That’s all we know.
<p>The requested URL <code>/_/AccountsDomainCookiesCheckConnectionHttp/cspreport</code> was not found on this server.  <ins>That’s all we know.</ins>
