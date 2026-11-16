# Tarea: links directos de Mercado Livre + PDF del presupuesto económico

> Pega este archivo en una sesión local de Claude (app de escritorio o Claude Code) que tenga
> la extensión **Claude in Chrome** conectada. Así Claude puede abrir Mercado Livre en tu navegador.

## Contexto

Es un presupuesto (orçamento) de pratos y pieles para la batería de la iglesia, que se le presenta al
misionero. El texto del PDF va en **portugués de Brasil**. Ya existen dos versiones:

- `orcamentos/orcamento-bateria-original.pdf`: original, R$ 2.972,50, con los 4 links directos.
- `orcamentos/orcamento-bateria-economico.pdf`: económico, R$ 2.557,70. **Problema:** los ítems 1 y 3
  llevan a páginas de búsqueda de Mercado Livre, no al anuncio del producto.

## Lo que hay que hacer

1. Con la extensión de Chrome, abre Mercado Livre y busca:
   - **Ítem 1:** "Kit Pratos Avatar Complex B20 14 16 20" con bag (hi-hat 14", crash 16", ride 20").
     Búsqueda: https://lista.mercadolivre.com.br/kit-pratos-avatar-complex-b20-14-16-20
     Elige el más barato que sea nuevo, de la línea **Complex** (no Standard), traiga la **bag**
     y tenga un vendedor con buena reputación. Precios vistos: R$ 1.930, R$ 1.999, R$ 2.290.
   - **Ítem 3:** "Pele Williams Target Black 10 filme duplo" (WB2). Si no aparece una más barata que
     R$ 112,80, usa el link original de abajo.
2. Anota para cada uno el **link directo** (página del anuncio), el **precio actual** y si tiene **frete grátis**.
3. Confirma también que siguen vigentes los precios de los ítems 2 y 4 (links abajo).
4. Rehaz `orcamentos/orcamento-bateria-economico.pdf`:
   - Una sola página A4, **letra grande**, con el mismo estilo que `orcamento-bateria-original.pdf`
     (encabezado azul oscuro con degradado, caja blanca con el total grande, ítems numerados en círculos,
     precio grande a la derecha, link "Ver no Mercado Livre →", barra oscura con el total).
   - Añade un recuadro verde con el **ahorro frente al original** (R$ 2.972,50).
   - Recalcula el total con los precios nuevos.
   - Revisa el PDF terminado antes de entregarlo: una sola página, sin texto cortado.
5. Haz commit en la rama `claude/percussion-equipment-budget-4aub2q` y push.

## Datos actuales del presupuesto económico

| # | Ítem | Precio (R$) | Link actual |
| --- | --- | --- | --- |
| 1 | Kit pratos Avatar Complex B20 14/16/20 + bag | 1.999,00 | búsqueda (cambiar por el link directo) |
| 2 | Kit pele caixa 14" Williams (porosa + resposta + esteira 40 fios + chave) | 309,90 | https://www.mercadolivre.com.br/kit-pele-caixa-14-williams-porosa-resposta-esteira-40-fios-chave/p/MLB45389276?pdp_filters=item_id%3AMLB3948755653 |
| 3 | Pele Williams Target WB2 Black 10" filme duplo | 98,90 (hoy aparece a ~117,90) | búsqueda; si no hay una más barata, usar: https://www.mercadolivre.com.br/pele-williams-target-wb2-black-10-filme-duplo-preta-com-ol/p/MLB28779697?pdp_filters=item_id%3AMLB5267441874 (R$ 112,80) |
| 4 | Pele surdo 16" Williams Black filme duplo | 149,90 | https://www.mercadolivre.com.br/pele-surdo-16-williams-black-filme-duplo/up/MLBU1961230763?pdp_filters=item_id%3AMLB1213163627 |
| | **Total** | **2.557,70** | |

## Reglas

- Mantener la **calidad**: los platos tienen que ser de bronce **B20**. Nada de "Zeus Mute" (son para
  practicar en silencio) ni parches Luen.
- Usar solo precios vistos en el anuncio, no inventados. Si algo no se puede confirmar, decirlo.
- La etiqueta del encabezado dice "Ministério de Louvor"; cámbiala si el usuario lo pide.
