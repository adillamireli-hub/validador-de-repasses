# Validador de Repasses

Aplicativo de conferência de repasses financeiros para parceiros.

**Acesse:** https://adillamireli-hub.github.io/validador-de-repasses/

## O que faz

- Lê o contrato do parceiro (PDF, DOCX ou TXT) e extrai as regras comerciais:
  percentual de repasse, canais de venda, descontos e taxas.
- Importa a planilha mensal de repasses (XLSX, XLS ou CSV) e identifica
  automaticamente o significado de cada coluna.
- Recalcula cada lançamento pelas regras do contrato e aponta divergências,
  mostrando o memorial de cálculo componente a componente.

## Privacidade

Contratos e planilhas são processados inteiramente no navegador de quem usa.
Nenhum arquivo é enviado para servidor algum. Os contratos cadastrados ficam
salvos apenas no navegador local — cada pessoa tem sua própria base.

## Publicação

Esta pasta contém apenas o aplicativo compilado (`index.html`), gerado a partir
do código-fonte com:

```
npm run build:single
```
