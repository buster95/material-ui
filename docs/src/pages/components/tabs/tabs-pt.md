---
title: Tabs React component
components: Tabs, Tab
---

# Tabs (Abas)

<p class="description">As guias facilitam a exploração e alternam entre diferentes visualizações.</p>

[Tabs](https://material.io/design/components/tabs.html) organizam e permitem a navegação entre grupos de conteúdo relacionados o no mesmo nível hierárquico.

## Guias Simples

Um exemplo simples sem frescuras.

{{"demo": "pages/components/tabs/SimpleTabs.js"}}

### Etiquetas embrulhadas

Os rótulos longos serão agrupados automaticamente nas guias. Se o marcador for muito longo para a guia, ele será excedido e o texto não ficará visível.

{{"demo": "pages/components/tabs/TabsWrappedLabel.js"}}

### Guia desativado

A Tab can be disabled by setting `disabled` property.

{{"demo": "pages/components/tabs/DisabledTabs.js"}}

## Corrigido Tabs

As guias fixas devem ser usadas com um número limitado de guias e quando o posicionamento consistente ajudar a memória muscular.

### Full width

A propriedade `variant="fullWidth"` deve ser usada em views menores. Esta demo também usa [react-swipeable-views](https://github.com/oliviertassinari/react-swipeable-views) para animar a transição de Guias e permite que estas sejam trocadas ao toque nos dispositivos.

{{"demo": "pages/components/tabs/FullWidthTabs.js"}}

### Centered

A propriedade `centered` deve ser usada para views maiores.

{{"demo": "pages/components/tabs/CenteredTabs.js"}}

## Guias Roláveis

### Botões de Rolagem Automática

Botões de rolagem para esquerda e direita serão apresentados automaticamente em dispositivos desktop e ocultados em dispositivos mobile. (baseado na largura de exibição do dispositivo)

{{"demo": "pages/components/tabs/ScrollableTabsButtonAuto.js"}}

### Botões de Rolagem Forçados

Botões de rolagem para esquerda e direita serão apresentados independente da largura de exibição do dispositivo.

{{"demo": "pages/components/tabs/ScrollableTabsButtonForce.js"}}

### Oculta Botões de Rolagem

Botões de rolagem para esquerda e direita nunca serão exibidos. Toda e qualquer rolagem será iniciada através dos mecanismos do navegador do dispositivo (exemplo: arrastar para direita ou esquerda, roda do mouse + shipt, etc.)

{{"demo": "pages/components/tabs/ScrollableTabsButtonPrevent.js"}}

## Customized tabs

Aqui está um exemplo de personalização do componente. Você pode aprender mais sobre isso na [página de documentação de substituições](/customization/components/).

{{"demo": "pages/components/tabs/CustomizedTabs.js"}}



## Guias Nav

Por padrão as guias usam um elemento `button`, mas você pode definir sua própria tag ou seu próprio componente. Aqui vai um exemplo de implementação de guia de navegação:

{{"demo": "pages/components/tabs/NavTabs.js"}}

## Guias de ícones

Os rótulos de guias podem ser todos os ícones ou todo o texto.

{{"demo": "pages/components/tabs/IconTabs.js"}}

{{"demo": "pages/components/tabs/IconLabelTabs.js"}}