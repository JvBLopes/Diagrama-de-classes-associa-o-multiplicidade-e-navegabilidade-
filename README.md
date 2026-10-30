# Diagrama de classes: associação, multiplicidade e navegabilidade

Tema 6 — Engenharia de Software, 2026/2, 2º bimestre.

## Integrantes

- João Vitor Bucco Lopes — RA 26008551-2
- Loreanne de Quadros Pereira — RA 26010347-2

## Conteúdo

Explicação dos conceitos de associação, papéis, multiplicidade e navegabilidade com exemplos genéricos baseados nos slides da disciplina. O modelo didático usa Cliente, Pedido, ItemPedido, Produto, Cupom e Pagamento, sem referência a uma empresa ou loja específica. As multiplicidades de todas as cinco ligações são justificadas nos dois sentidos.

## Trabalho escrito

- [PDF](docs/Trabalho_Tema_6_Joao_e_Loreanne.pdf)
- [Word editável](docs/Trabalho_Tema_6_Joao_e_Loreanne.docx)

Após editar o Word, clique com o botão direito sobre o sumário e escolha Atualizar campo → Atualizar o índice inteiro antes de exportar novamente para PDF.

## Diagramas

Os arquivos-fonte são editáveis no draw.io. As imagens foram exportadas pelo draw.io Desktop.

| Figura | Arquivo-fonte | Imagem |
|---|---|---|
| 1 — Leitura de uma associação | [draw.io](diagramas/leitura_associacao.drawio) | [PNG](diagramas/leitura_associacao.png) |
| 2 — Diagrama geral com seis classes | [draw.io](diagramas/sistema_pedidos.drawio) | [PNG](diagramas/sistema_pedidos.png) |
| 3 — Associação, papéis e leitura nos dois sentidos | [draw.io](diagramas/associacao_papeis.drawio) | [PNG](diagramas/associacao_papeis.png) |
| 4 — Multiplicidades entre Pedido, ItemPedido e Produto | [draw.io](diagramas/multiplicidade_itens.drawio) | [PNG](diagramas/multiplicidade_itens.png) |
| 5 — Cupom e pagamento como relações opcionais | [draw.io](diagramas/navegabilidade_opcional.drawio) | [PNG](diagramas/navegabilidade_opcional.png) |

## Convenção

As multiplicidades ficam junto da classe quantificada e são lidas nos dois sentidos. Conforme a convenção didática dos slides, ligações sem seta de navegabilidade permitem acesso bidirecional. Setas abertas indicam o sentido de acesso representado. O losango preenchido junto de Pedido indica composição.

## Entrega

Publicar este conteúdo em um repositório público do GitHub, mantendo as pastas docs e diagramas, e enviar o link no fórum do Studeo. Confirmar com o professor a aceitação do modelo didático usado. A apresentação oral é uma etapa separada, com duração máxima de 10 minutos e participação dos dois integrantes.
