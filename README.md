# Conecta Proteção

Site estático publicado pelo GitHub Pages.

## Recursos

- Conteúdos de orientação e proteção para crianças, adolescentes, familiares e educadores.
- Biblioteca Conecta com navegação acessível e responsiva.
- VLibras Widget oficial, carregado do domínio `vlibras.gov.br`.
- Interface de conversa do Assistente Conecta.

## Limites da publicação no GitHub Pages

O GitHub Pages publica arquivos estáticos; ele não executa o servidor Python nem o banco SQLite do projeto. Por isso, nesta publicação estática, as solicitações à API de chat não recebem respostas de IA. O chatbot só poderá conversar com um modelo real quando um backend for implantado separadamente e a comunicação entre o site e esse serviço for configurada com HTTPS, validação de origem e credenciais mantidas exclusivamente no servidor.

Não coloque chaves de API, arquivos `.env`, bancos de dados, cadastros ou dados de conversa neste repositório público. Nenhuma conta de usuário é exigida por esta versão.

## VLibras

O widget oficial do VLibras é integrado em `index.html`. Sua disponibilidade e a tradução dos conteúdos dependem dos serviços externos oficiais e de conexão com a internet.