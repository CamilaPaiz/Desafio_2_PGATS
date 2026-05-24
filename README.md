# Desafio_2_PGATS
Repositório  curso PGATS

# Exercício 1 - Serviço de Pagamento

Este projeto implementa uma classe JavaScript que registra pagamentos e consulta o último pagamento realizado.

## Funcionalidade

- Armazena pagamentos em uma lista interna
- Cada pagamento possui:
  - `codigoBarras`
  - `empresa`
  - `valor`
  - `categoria` (`cara` quando `valor > 100.0`, caso contrário `padrão`)
- Método `pagar(codigoBarras, empresa, valor)` adiciona um pagamento
- Método `consultarUltimoPagamento()` retorna apenas o último pagamento registrado

## Estrutura do projeto

- `src/ServicoDePagamento.js` - classe do serviço de pagamento
- `test/servicoDePagamento.test.js` - testes com Mocha e `node:assert`
- `package.json` - configurações do npm e script de teste

## Instalação
npm install

## Executar testes
npx mocha

## Observações

- O projeto usa módulos ES (`type: "module"` no `package.json`).
- Use `assert.equal` para comparar objetos nos testes.

