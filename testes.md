# Testes automatizados

Que a nossa aplicação continue funcionando indepenente do número de novas funcionalidades e do número de devs no time.

1. Testes unitários (TDD)

Testam funcionalidades específicas da nossa aplicação (precisam ser funções puras).

JAMAIS: Chamada a uma API, efeito colateral

2. Testes de integração

Testam uma funcionalidade completa, passando por varias camadas da aplicação.

Route -> Controller -> Serviço -> Repositório -> ...

3. Testes E2E

Testes que simulam a ação do usuário dentro da nossa aplicação.

1. Clique no input de email
2. Preencha samileleite77@gmail.com
3. Clique no input de senha
4. Preencha 123456
5. Clique no botão logar
6. Espero que a página tenha enviado o usuário para o dashboard

# TDD (Test Driven Development)

- Quando o usuário se cadastrar na plicação, ele deve receber um email de boas vindas;
