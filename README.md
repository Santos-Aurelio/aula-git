# Biblioteca Digital UniRovuma — protótipo académico

## Como executar
1. Extraia a pasta `biblioteca_digital_unirovuma`.
2. Abra `index.html` num navegador moderno (Chrome, Edge ou Firefox).
3. Para uma experiência de desenvolvimento, abra a pasta no Visual Studio Code e execute com a extensão Live Server.
4. Entre com `admin@unirovuma.ac.mz` e a palavra-passe `admin123` para testar o painel administrativo.
5. Crie uma conta de leitor para testar empréstimos e reservas.

## Funcionalidades demonstrativas
- Catálogo com pesquisa textual, filtros por género/ano/disponibilidade e ordenação.
- Detalhes das obras, cadastro, edição e remoção de livros.
- Perfis de leitor e administrador (demonstração).
- Empréstimo, devolução, prazo demonstrativo de 14 dias e reservas.
- Painel com estatísticas, gestão de utilizadores e exportação CSV.
- Layout responsivo para computador, tablet e telemóvel.
- Registos persistidos no `localStorage` do navegador; sessão no `sessionStorage`.

## Limitações importantes
Esta é uma demonstração front-end, não um sistema institucional seguro. As contas e os registos são guardados no navegador; as palavras-passe de demonstração não são protegidas por hash; não há API, servidor ou base de dados partilhada. Não utilize dados pessoais reais nem publique esta versão como serviço de produção.

Para cumprir integralmente a arquitectura descrita na monografia, a próxima etapa deve implementar back-end (por exemplo, Spring Boot ou PHP), API REST, base de dados relacional (por exemplo, MySQL), autenticação segura com hash de senhas e sessões/tokens, autorização por perfil, validação no servidor, upload controlado de PDF/EPUB e protecção contra CSRF/XSS/SQL injection. Os requisitos de desempenho inferiores a 2 segundos para 10.000 obras precisam de ser medidos com testes reais; não são comprovados por este protótipo.
