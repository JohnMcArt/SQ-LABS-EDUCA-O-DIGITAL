# Informática p/ Internet Itinerante — SQ Labs

O **SQ Labs** é um ambiente educacional interativo para estudar banco de dados, SQL, documentação técnica, Markdown, Git e GitHub.

## Abrir no Windows
1. Baixe o ZIP do projeto e clique com o botão direito nele.
2. Escolha **Extrair Tudo...** e selecione uma pasta.
3. Abra a pasta `SQ-Labs`.
4. Dê dois cliques em `index.html`. Ele abrirá no navegador (Chrome, Edge, Firefox etc.).
5. Para editar o site, abra `index.html` em um editor como Visual Studio Code.

## Abrir no Linux
1. Extraia o ZIP pelo gerenciador de arquivos ou pelo terminal.
2. Abra a pasta `SQ-Labs`.
3. Abra `index.html` no navegador. Também é possível executar:
   ```bash
   xdg-open index.html
   ```
4. Para editar, use seu editor de texto preferido ou Visual Studio Code, se instalado.

O site é estático e não precisa de Node.js, Python, banco de dados ou conexão com a internet para as funcionalidades locais.

## O que existe no site
- Página inicial com identidade gráfica escura, vermelho intenso, formas vetoriais e animações CSS.
- Biblioteca de conteúdo: DDL, DML, filtros, agregações, funções, JOINs, subconsultas, modelagem, README, Markdown, README de perfil e Git/GitHub.
- Atividades com alternativas e feedback explicativo.
- Simulador SQL limitado a consultas SELECT sobre dados fictícios.
- Guias diferentes para Windows (GitHub Desktop) e Linux (Git no terminal).
- Painel personalizável com nome/apelido, meta de aprendizagem, cor de destaque, anotações, checklist, atividades próprias e exportação JSON.

## Dados e privacidade
Preferências, notas, progresso e atividades são guardados no `localStorage` do navegador atual. Não há login nem sincronização entre dispositivos. Se limpar os dados do navegador, as informações locais podem ser apagadas. Use **Exportar meu painel** para salvar uma cópia JSON.

## Limites do simulador SQL
O laboratório não se conecta a MySQL, PostgreSQL nem outro SGBD. Ele interpreta apenas alguns formatos de SELECT sobre dados fictícios. Use um banco real de teste para praticar consultas completas.

## Organização
- `index.html` — site completo (HTML, CSS e JavaScript).
- `README.md` — este guia.

## Conteúdo didático
O conteúdo foi reestruturado e reescrito para o SQ Labs com linguagem direta, exemplos de estudo e observações sobre diferenças entre SGBDs. Alguns comandos SQL têm sintaxe específica de cada sistema; consulte a documentação da ferramenta utilizada em aula.
