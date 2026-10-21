# Revisão obrigatória — Checkouts Hotmart BRASIL FORTE

**Data:** 21 de outubro de 2026. **Origem dos URLs:** mensagem do proprietário com 12 links https://pay.hotmart.com.

## Status de comprovação

- E-mails da Hotmart confirmam aprovação de 12 produtos com IDs próprios.
- Os links `Q108126245C` (Atendimento e Vendas, ID 8776492) e `P108126174G` (Auxiliar Administrativo, ID 8776453) foram conferidos por capturas de tela da página de pagamento. Ambos exibem título compatível e preço R$ 19,90.
- A correspondência dos **outros 10** foi inferida da correlação entre IDs crescentes de cadastro e códigos numéricos crescentes de checkout. É uma **hipótese forte, não uma validação oficial**.
- Os destinos não puderam ser abertos automaticamente para conferir nomes dos produtos. Esta alteração está em uma *branch de validação* e **não deve ser mesclada** sem conferir individualmente os títulos e a entrega.

## Relação preparada

| Produto | ID Hotmart | Checkout recebido | Situação |
|---|---:|---|---|
| Auxiliar Administrativo | 8776453 | https://pay.hotmart.com/P108126174G | Confirmado em captura: título + R$ 19,90 |
| Logística e Almoxarifado | 8776483 | https://pay.hotmart.com/O108126233P | Pendente conferir título |
| Atendimento, Vendas e Caixa | 8776492 | https://pay.hotmart.com/Q108126245C | Confirmado em captura: título + R$ 19,90 |
| Inteligência Artificial no Trabalho | 8776504 | https://pay.hotmart.com/N108126261F | Pendente conferir título |
| Excel e Análise de Dados | 8776509 | https://pay.hotmart.com/D108126270R | Pendente conferir título |
| Cuidador de Idosos | 8776515 | https://pay.hotmart.com/M108126280C | Pendente conferir título |
| Técnico de Enfermagem | 8776527 | https://pay.hotmart.com/G108126293N | Pendente conferir título |
| Manutenção Predial | 8776530 | https://pay.hotmart.com/A108126301C | Pendente conferir título |
| Segurança do Trabalho | 8776534 | https://pay.hotmart.com/H108126318K | Pendente conferir título |
| Orientador Social e SUAS | 8776537 | https://pay.hotmart.com/X108126328U | Pendente conferir título |
| Compras Públicas | 8776542 | https://pay.hotmart.com/O108126338P | Pendente conferir título |
| Cibersegurança e LGPD | 8776545 | https://pay.hotmart.com/G108126347E | Pendente conferir título |

## Validação por produto

Para cada URL acima:

1. Abrir o endereço (sem concluir compra), e verificar se o **título do produto** corresponde à linha da tabela.
2. Conferir **preço R$ 19,90**, moeda, pagamento único e identificação do vendedor.
3. Confirmar na conta Hotmart que o arquivo entregue inclui e-book PDF e simulado HTML/ZIP da profissão correspondente.
4. Conferir prazo de garantia aplicável e entrega no ambiente do comprador.
5. Marcar a associação como validada, e só então mesclar no ramo principal.

**Não fazer compras, contratar serviços, divulgar checkouts não conferidos, nem publicar arquivos premium no GitHub.**
