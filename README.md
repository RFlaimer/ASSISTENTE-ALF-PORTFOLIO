# ASSISTENTE-ALF

Assistente pessoal para **Windows 11**, com processamento local prioritário,
interface centrada na conversa e ferramentas para trabalhar em projetos.

Desenvolvido por [RFlaimer](https://github.com/RFlaimer).

**Estado: em desenvolvimento. Ainda não há instalador público disponível.**
Este repositório apresenta o projeto; não distribui o código privado, dados de
usuários ou credenciais. Não oferece cadastro ou acesso público ao assistente.

## Ideia

Pedir, acompanhar e revisar trabalhos na mesma conversa. A identidade do
assistente, os dados do usuário e os modelos de IA são componentes independentes.
As ferramentas são escolhidas conforme o pedido e suas permissões; não é
necessário ativar uma habilidade manualmente a cada uso.

## Recursos desenvolvidos

- Chat com respostas incrementais, Markdown, histórico e projetos.
- Planejamento, ações e revisão de entregas no contexto da conversa.
- Programação em pastas autorizadas, com execução de testes e evidências.
- Consulta a documentos e procedimentos de referência, sem treinar os pesos.
- Abertura de programas, pastas e pesquisas pelo pedido natural.
- Controle de janelas do Windows sujeito à disponibilidade dos conectores.
- Voz e recursos visuais como componentes separados do modelo de conversa.

Existência de uma ferramenta não garante autonomia em qualquer aplicação ou
resultado correto em qualquer projeto. Tarefas sensíveis exigem permissões e
resultados precisam de conferência.

## Distribuição Windows planejada

Um instalador prepara o aplicativo e seu runtime Python privado e validado.
O usuário não precisará configurar Python ou dependências manualmente.
Modelos e recursos pesados poderão ser baixados depois, conforme o hardware e
as escolhas do usuário. O tamanho final só será divulgado após medir os pacotes.

Cada instalação começa com **memória vazia**, identidade genérica do Alf e
catálogo de capacidades. Conhecer uma ferramenta não concede acesso a arquivos,
contas ou serviços. Não serão incluídos históricos, contatos, permissões ou
conhecimentos pessoais do desenvolvedor.

## Melhorias e atualizações

As melhorias da versão de desenvolvimento poderão chegar às instalações por
versões revisadas e testadas. Atualizações do programa não sincronizam dados
pessoais. Modelos compatíveis já instalados serão reutilizados quando possível.

O gerenciador de instalação e atualização ainda está em preparação. Alterações
locais feitas pelo agente não serão distribuídas automaticamente.

Quando o instalador estiver validado, esta página terá **um único download
destacado da versão estável mais recente**, atualizado junto com cada publicação
aprovada. Não haverá uma seção pública de histórico de atualizações nesta fase.
Enquanto não houver um pacote validado, não será exibido um download fictício.

Está prevista a opção **Configurações → Atualizações → Verificar atualizações**
no aplicativo instalado. Ela permitirá baixar e instalar uma versão compatível,
preservando a memória, os projetos e as configurações do próprio usuário. Recursos
adicionais terão download informado separadamente. Esse atualizador ainda não
está implementado como distribuição pública utilizável.

## Próximas entregas

1. Separar dados pessoais, executáveis, modelos e cache.
2. Preparar um pacote limpo com runtime próprio.
3. Desenvolver a configuração inicial e downloads opcionais verificáveis.
4. Validar em Windows sem Python e sem recursos previamente instalados.
5. Disponibilizar uma versão candidata e registrar suas limitações.

Integrações externas dependem de configuração própria. O canal WhatsApp está
pausado e não integra uma oferta pública pronta. Nenhum serviço na nuvem é
necessário para apresentar este projeto.

## Privacidade

Este portfólio usa somente informações gerais do produto. Não contém bancos de
memória, conversas, fontes pessoais, gravações, credenciais ou arquivos .env.
Processamento local prioritário não significa que todas as ferramentas sejam
offline: recursos online devem identificar seus requisitos e pedir autorização.

## Licenciamento

Repositório de apresentação. A publicação destas informações não concede
licença sobre o código privado ou os modelos de terceiros. As condições de
redistribuição dos componentes serão conferidas antes de uma versão pública.
