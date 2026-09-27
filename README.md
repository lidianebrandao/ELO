# Elo Documentação Imobiliária

Site institucional estático em português para orientação documental e elaboração de requerimentos de imóveis em Maceió.

## Como abrir

Abra o arquivo index.html no navegador. O site funciona diretamente, sem instalação de dependências e sem conexão para carregar a página. Os links de atendimento abrem o WhatsApp e precisam de internet.

## Arquivos

- index.html: conteúdo, serviços, valores, perguntas frequentes e ilustração vetorial.
- styles.css: apresentação e adaptação para celulares, tablets e computadores.
- script.js: menu no celular e atualização do ano.
- favicon.svg: ícone da marca no navegador.

## Informações comerciais

- Marca: Elo Documentação Imobiliária.
- WhatsApp: (82) 99900-7478, com código do país 55.
- Análise documental: R$ 200,00.
- Entrega da análise: até dois dias úteis após recebimento dos documentos e confirmação do pagamento.
- A análise inclui orientação, lista de documentos necessários e orçamento para elaboração do requerimento.
- O valor da análise é descontado da elaboração quando contratada.
- Acompanhamento no cartório: indicação de despachante, com contratação separada.
- Atendimento on-line; presencial em casos excepcionais.

## Publicação

Repositório do projeto: https://github.com/lidianebrandao/ELO

O workflow `.github/workflows/pages.yml` publica o site no GitHub Pages a cada envio para a branch `main`. Também é possível executá-lo manualmente pela aba **Actions**. A publicação usa apenas `index.html`, `styles.css`, `script.js` e `favicon.svg`.

Para habilitar a primeira publicação:

1. Abra [Settings → Pages](https://github.com/lidianebrandao/ELO/settings/pages) no repositório.
2. Em **Build and deployment → Source**, selecione **GitHub Actions**.
3. Na aba [Actions](https://github.com/lidianebrandao/ELO/actions/workflows/pages.yml), escolha **Publicar site no GitHub Pages → Run workflow**, usando a branch `main`.

Depois que a execução terminar com sucesso, o site ficará disponível em **https://lidianebrandao.github.io/ELO/**. Novos envios para `main` atualizarão esse endereço automaticamente. Não é necessário configurar um domínio próprio.

O site não usa fontes externas, bibliotecas, rastreadores, cookies, formulários ou armazenamento de documentos. O contato e as orientações de contratação acontecem pelo WhatsApp. Nome pessoal, formação e vínculo profissional não são apresentados.

O nome e o símbolo visual foram preparados para este projeto. Não foi feita verificação de disponibilidade de marca ou domínio.
