# BRASIL FORTE Profissões — Operação comercial Hotmart
Atualização: 21/10/2026.

## Situação verificada
- Os 12 produtos BRASIL FORTE foram cadastrados e receberam e-mails da Hotmart de "produto aprovado para vendas" em 21/10/2026.
- Preço de cada pacote: R$ 19,90 (pagamento único), garantia configurada de 7 dias.
- Entrega cadastrada na Hotmart: e-book PDF e simulado digital em ZIP.
- **PENDENTE:** recuperar os 12 URLs individuais reais de divulgação/pagamento da Hotmart. Os valores no `checkouts.js` estão vazios de propósito. Sem eles, o site não encaminha à compra.
- Nenhuma compra de teste paga, anúncio, duplicação de produto ou contratação de serviço foi realizada nesta migração.

## Como completar a integração sem recriar produtos
1. Abra https://app.hotmart.com e faça login na conta produtora.
2. Entre em **Produtos → Meus produtos**, escolha um produto e entre em **Links de divulgação**.
3. Copie o link da **Página de pagamento** ou o link oficial de vendas apontado pela Hotmart. O checkout deve pertencer àquele produto e à oferta de R$ 19,90.
4. Abra `PAINEL-CONFIGURAR-CHECKOUTS.html` pelo navegador, preencha o campo do ID correspondente e repita até os 12.
5. O painel aceita somente `pay.hotmart.com`, `go.hotmart.com` e `hotm.art`; recusa links repetidos e URLs não seguras.
6. Clique em **Baixar checkouts.js** e substitua esse arquivo no repositório `cincoregioes-star/brasil-forte-profissoes`. Não é necessário alterar os produtos na Hotmart.
7. Aguarde a publicação automática do GitHub Pages e verifique o endereço https://cincoregioes-star.github.io/brasil-forte-profissoes/.
8. Clique na compra de CADA produto e confira título, preço, produtora, entrega e garantia no checkout. **Não efetue pagamentos reais sem autorização.**
9. Verifique, no painel do produtor, a entrega de cada PDF e ZIP, o funcionamento dos arquivos e o simulado offline. Não publique ZIPs premium no repositório público.
10. Após os 12 links e verificações, iniciar divulgação orgânica (Instagram/WhatsApp) antes de qualquer novo anúncio pago.

## Cuidados essenciais
- O GitHub Pages é a vitrine; a Hotmart é responsável pelo pagamento e pela entrega do material comprado.
- O conteúdo premium fica apenas na Hotmart. Na pasta `ebooks-gratis` devem ficar apenas PDFs de amostra.
- Não inclua tokens da Hotmart, dados de compradores, senhas ou credenciais em arquivos públicos.
- Os materiais são educativos, sem promessa de trabalho, diploma ou qualificação regulamentada.
- Em produtos de saúde e segurança do trabalho, revisar orientações técnicas antes de campanhas.
- As páginas de compra só ficam ativas após a ligação dos URLs oficiais e revisão de cada checkout.
