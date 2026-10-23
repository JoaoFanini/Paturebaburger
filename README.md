# Patureba Burger

Site da Patureba Burger: cardápio completo, combos, promoção do hot-dog e pedido montado direto no WhatsApp (34) 9 9873-1080.

## Como funciona

- Página única em `index.html`, sem build e sem dependências: fontes e logo vão embutidas no próprio arquivo.
- Os botões de pedido abrem `https://wa.me/5534998731080` com a mensagem já escrita.
- A sacola monta o pedido (itens, quantidades, nome, endereço e observação) e envia tudo formatado para o WhatsApp.

## Publicar

Funciona direto na Vercel ou no GitHub Pages: aponte para a raiz do branch `main`.

## Atualizar preços

Os preços ficam no `<script>` do `index.html`, nas listas `MENU`, `COMBOS_X`, `COMBOS_D` e `ADDONS`, em centavos (ex.: `2450` = R$ 24,50).

## Pendências

- Trocar a ilustração do hambúrguer e os desenhos dos combos por fotos reais dos lanches.
- Confirmar taxa de entrega, formas de pagamento e horário de funcionamento.
- A logo original usa um personagem da Disney; o site usa só a faixa com o nome.

Fontes: Big Shoulders Display e Instrument Sans, licença SIL Open Font License 1.1.
