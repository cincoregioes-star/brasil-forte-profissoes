# BRASIL FORTE — Status da auditoria Hotmart

**Data:** 22/10/2026  
**Escopo:** GitHub `cincoregioes-star/brasil-forte-profissoes` + pendências de acesso à Hotmart.  
**Importante:** nenhum pagamento, compra de teste, alteração de produto ou anúncio foi executado neste processo.

## Auditoria estática concluída
- [x] Acesso de manutenção ao repositório confirmado.
- [x] `checkouts.js`: 12 chaves de produto e 12 URLs HTTPS `pay.hotmart.com` distintas.
- [x] `index.html`: 12 itens de catálogo; cada `slug` encontra checkout correspondente.
- [x] 120 questões gratuitas: 10 por profissão, distribuídas em dois blocos de 5.
- [x] 36 situações de entrevista, 3 por profissão.
- [x] Pasta `ebooks-gratis/`: 12 PDFs listados, com nome correspondente a cada `slug`.
- [x] Referências de IDs de DOM inspecionadas no script principal: nenhuma ausente na marcação.
- [x] O código de vitrine constrói botões de compra com as URLs associadas.
- [x] Registro de publicação desatualizado identificado e corrigido em `GUIA-DE-PUBLICACAO.md`.

## Não verificado: exige sessão Hotmart ou teste real
- [ ] Conferir por acesso autenticado o estado comercial e a oferta de cada produto.
- [ ] Validar preço, título e vendedor nas 12 páginas reais de checkout.
- [ ] Conferir os **12 e-books completos** e os **12 ZIPs de simulados** nos conteúdos entregues ao comprador, inclusive nomes e conteúdos correspondentes.
- [ ] Testar liberação, download, extração e execução após compra autorizada ou pré-visualização suportada.
- [ ] Testar o site publicado em dispositivos/navegador reais e a navegação até as telas de pagamento.
- [ ] Obter autorização expressa antes de divulgação/publicação comercial definitiva.

## Produto e associação de checkout
Ver relação completa em [MAPEAMENTO-HOTMART-CONFERIR.md](MAPEAMENTO-HOTMART-CONFERIR.md). As 12 associações foram informadas ou confirmadas pelo proprietário em 21/10; somente duas tinham comprovação anterior por capturas de tela.

## Observação de escopo
O código foi inspecionado estaticamente. Não há como concluir que o produto está pronto para comercialização **sem comprovar os arquivos de entrega e os fluxos reais de checkout**. Os itens validados não precisam ser refeitos.

## Próxima ação operacional
Acessar a conta produtora da Hotmart e auditar somente os quatro pontos pendentes por produto: **oferta, valor, materiais e entrega**; registrar resultado sem recriar produtos.
