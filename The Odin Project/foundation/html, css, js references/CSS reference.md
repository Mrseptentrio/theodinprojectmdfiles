# CSS reference

Use this **CSS reference** to browse an [alphabetical index](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#index) of all of the standard [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) properties, [pseudo-classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes), [pseudo-elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements), [data types](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Types), [functional notations](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions) and [at-rules](https://developer.mozilla.org/en-US/docs/Web/CSS/At-rule). You can also browse [key CSS concepts](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#concepts) and a list of [selectors organized by type](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#selectors). Also included is a brief [DOM-CSS / CSSOM reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#dom-css_cssom).

## [Basic rule syntax](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#basic_rule_syntax "Permalink to Basic rule syntax")

### [Style rule syntax](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#style_rule_syntax "Permalink to Style rule syntax")

```
style-rule ::=
    selectors-list {
      properties-list
    }
```

... where :

```
selectors-list ::=
    selector[:pseudo-class] [::pseudo-element]
    [, selectors-list]

properties-list ::=
    [property : value] [; properties-list]
```

See the index of [_selectors_](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#selectors), [_pseudo-classes_](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#pseudo), and _[pseudo-elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#pseudo)_ below. The syntax for each specified _value_ depends on the data type defined for each specified _property_.

#### Style rule examples

```
strong {
  color: red;
}

div.menu-bar li:hover > ul {
  display: block;
}
```

For a beginner-level introduction to the syntax of selectors, see our [guide on CSS Selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors). Be aware that any [syntax](https://developer.mozilla.org/en-US/docs/Web/CSS/Syntax) error in a rule definition invalidates the entire rule. Invalid rules are ignored by the browser. Note that CSS rule definitions are entirely (ASCII) [text-based](https://www.w3.org/TR/css-syntax-3/#intro), whereas DOM-CSS / CSSOM (the rule management system) is [object-based](https://www.w3.org/TR/cssom/#introduction).

### [At-rule syntax](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#at-rule_syntax "Permalink to At-rule syntax")

As the structure of at-rules varies widely, please see [At-rule](https://developer.mozilla.org/en-US/docs/Web/CSS/At-rule) to find the syntax of the specific one you want.

## [Index](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#index "Permalink to Index")

**Note:** The property names in this index do **not** include the [JavaScript names](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Properties_Reference) where they differ from the CSS standard names.

-

-   [`--*`](https://developer.mozilla.org/en-US/docs/Web/CSS/--*)
-   [`-webkit-line-clamp`](https://developer.mozilla.org/en-US/docs/Web/CSS/-webkit-line-clamp)

A

-   [`accent-color`](https://developer.mozilla.org/en-US/docs/Web/CSS/accent-color)
-   [`:active`](https://developer.mozilla.org/en-US/docs/Web/CSS/:active)
-   [`additive-symbols (@counter-style)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@counter-style/additive-symbols)
-   [`::after (:after)`](https://developer.mozilla.org/en-US/docs/Web/CSS/::after)
-   [`align-content`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)
-   [`align-items`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items)
-   [`align-self`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-self)
-   [`align-tracks`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-tracks)
-   [`all`](https://developer.mozilla.org/en-US/docs/Web/CSS/all)
-   `<an-plus-b>`
-   [`<angle>`](https://developer.mozilla.org/en-US/docs/Web/CSS/angle)
-   [`<angle-percentage>`](https://developer.mozilla.org/en-US/docs/Web/CSS/angle-percentage)
-   [`animation`](https://developer.mozilla.org/en-US/docs/Web/CSS/animation)
-   [`animation-delay`](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-delay)
-   [`animation-direction`](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-direction)
-   [`animation-duration`](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-duration)
-   [`animation-fill-mode`](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-fill-mode)
-   [`animation-iteration-count`](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-iteration-count)
-   [`animation-name`](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-name)
-   [`animation-play-state`](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-play-state)
-   [`animation-timing-function`](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-timing-function)
-   [`@annotation`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-feature-values#@annotation)
-   [`annotation()`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant-alternates#annotation())
-   [`:any-link`](https://developer.mozilla.org/en-US/docs/Web/CSS/:any-link)
-   [`appearance`](https://developer.mozilla.org/en-US/docs/Web/CSS/appearance)
-   [`ascent-override (@font-face)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/ascent-override)
-   [`aspect-ratio`](https://developer.mozilla.org/en-US/docs/Web/CSS/aspect-ratio)
-   [`attr()`](https://developer.mozilla.org/en-US/docs/Web/CSS/attr())

B

-   [`::backdrop`](https://developer.mozilla.org/en-US/docs/Web/CSS/::backdrop)
-   [`backdrop-filter`](https://developer.mozilla.org/en-US/docs/Web/CSS/backdrop-filter)
-   [`backface-visibility`](https://developer.mozilla.org/en-US/docs/Web/CSS/backface-visibility)
-   [`background`](https://developer.mozilla.org/en-US/docs/Web/CSS/background)
-   [`background-attachment`](https://developer.mozilla.org/en-US/docs/Web/CSS/background-attachment)
-   [`background-blend-mode`](https://developer.mozilla.org/en-US/docs/Web/CSS/background-blend-mode)
-   [`background-clip`](https://developer.mozilla.org/en-US/docs/Web/CSS/background-clip)
-   [`background-color`](https://developer.mozilla.org/en-US/docs/Web/CSS/background-color)
-   [`background-image`](https://developer.mozilla.org/en-US/docs/Web/CSS/background-image)
-   [`background-origin`](https://developer.mozilla.org/en-US/docs/Web/CSS/background-origin)
-   [`background-position`](https://developer.mozilla.org/en-US/docs/Web/CSS/background-position)
-   [`background-position-x`](https://developer.mozilla.org/en-US/docs/Web/CSS/background-position-x)
-   [`background-position-y`](https://developer.mozilla.org/en-US/docs/Web/CSS/background-position-y)
-   [`background-repeat`](https://developer.mozilla.org/en-US/docs/Web/CSS/background-repeat)
-   [`background-size`](https://developer.mozilla.org/en-US/docs/Web/CSS/background-size)
-   [`<basic-shape>`](https://developer.mozilla.org/en-US/docs/Web/CSS/basic-shape)
-   [`::before (:before)`](https://developer.mozilla.org/en-US/docs/Web/CSS/::before)
-   [`:blank`](https://developer.mozilla.org/en-US/docs/Web/CSS/:blank)
-   `bleed (@page)`
-   [`<blend-mode>`](https://developer.mozilla.org/en-US/docs/Web/CSS/blend-mode)
-   `block-overflow`
-   [`block-size`](https://developer.mozilla.org/en-US/docs/Web/CSS/block-size)
-   [`blur()`](https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/blur())
-   [`border`](https://developer.mozilla.org/en-US/docs/Web/CSS/border)
-   [`border-block`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block)
-   [`border-block-color`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block-color)
-   [`border-block-end`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block-end)
-   [`border-block-end-color`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block-end-color)
-   [`border-block-end-style`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block-end-style)
-   [`border-block-end-width`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block-end-width)
-   [`border-block-start`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block-start)
-   [`border-block-start-color`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block-start-color)
-   [`border-block-start-style`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block-start-style)
-   [`border-block-start-width`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block-start-width)
-   [`border-block-style`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block-style)
-   [`border-block-width`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-block-width)
-   [`border-bottom`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-bottom)
-   [`border-bottom-color`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-bottom-color)
-   [`border-bottom-left-radius`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-bottom-left-radius)
-   [`border-bottom-right-radius`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-bottom-right-radius)
-   [`border-bottom-style`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-bottom-style)
-   [`border-bottom-width`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-bottom-width)
-   [`border-collapse`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-collapse)
-   [`border-color`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-color)
-   [`border-end-end-radius`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-end-end-radius)
-   [`border-end-start-radius`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-end-start-radius)
-   [`border-image`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-image)
-   [`border-image-outset`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-image-outset)
-   [`border-image-repeat`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-image-repeat)
-   [`border-image-slice`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-image-slice)
-   [`border-image-source`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-image-source)
-   [`border-image-width`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-image-width)
-   [`border-inline`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline)
-   [`border-inline-color`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline-color)
-   [`border-inline-end`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline-end)
-   [`border-inline-end-color`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline-end-color)
-   [`border-inline-end-style`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline-end-style)
-   [`border-inline-end-width`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline-end-width)
-   [`border-inline-start`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline-start)
-   [`border-inline-start-color`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline-start-color)
-   [`border-inline-start-style`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline-start-style)
-   [`border-inline-start-width`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline-start-width)
-   [`border-inline-style`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline-style)
-   [`border-inline-width`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-inline-width)
-   [`border-left`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-left)
-   [`border-left-color`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-left-color)
-   [`border-left-style`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-left-style)
-   [`border-left-width`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-left-width)
-   [`border-radius`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-radius)
-   [`border-right`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-right)
-   [`border-right-color`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-right-color)
-   [`border-right-style`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-right-style)
-   [`border-right-width`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-right-width)
-   [`border-spacing`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-spacing)
-   [`border-start-end-radius`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-start-end-radius)
-   [`border-start-start-radius`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-start-start-radius)
-   [`border-style`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-style)
-   [`border-top`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-top)
-   [`border-top-color`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-top-color)
-   [`border-top-left-radius`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-top-left-radius)
-   [`border-top-right-radius`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-top-right-radius)
-   [`border-top-style`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-top-style)
-   [`border-top-width`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-top-width)
-   [`border-width`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-width)
-   [`bottom`](https://developer.mozilla.org/en-US/docs/Web/CSS/bottom)
-   [`@bottom-center`](https://developer.mozilla.org/en-US/docs/Web/CSS/@page#page-margin-box-type)
-   [`box-decoration-break`](https://developer.mozilla.org/en-US/docs/Web/CSS/box-decoration-break)
-   [`box-shadow`](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow)
-   [`box-sizing`](https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing)
-   [`break-after`](https://developer.mozilla.org/en-US/docs/Web/CSS/break-after)
-   [`break-before`](https://developer.mozilla.org/en-US/docs/Web/CSS/break-before)
-   [`break-inside`](https://developer.mozilla.org/en-US/docs/Web/CSS/break-inside)
-   [`brightness()`](https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/brightness())

C

-   [`calc()`](https://developer.mozilla.org/en-US/docs/Web/CSS/calc())
-   [`caption-side`](https://developer.mozilla.org/en-US/docs/Web/CSS/caption-side)
-   [`caret-color`](https://developer.mozilla.org/en-US/docs/Web/CSS/caret-color)
-   [`@character-variant`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-feature-values#@character-variant)
-   [`character-variant()`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant-alternates#character-variant())
-   [`@charset`](https://developer.mozilla.org/en-US/docs/Web/CSS/@charset)
-   [`:checked`](https://developer.mozilla.org/en-US/docs/Web/CSS/:checked)
-   [`circle()`](https://developer.mozilla.org/en-US/docs/Web/CSS/basic-shape#circle())
-   [`clamp()`](https://developer.mozilla.org/en-US/docs/Web/CSS/clamp())
-   [`clear`](https://developer.mozilla.org/en-US/docs/Web/CSS/clear)
-   [`clip`](https://developer.mozilla.org/en-US/docs/Web/CSS/clip)
-   [`clip-path`](https://developer.mozilla.org/en-US/docs/Web/CSS/clip-path)
-   [`<color>`](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value)
-   [`color`](https://developer.mozilla.org/en-US/docs/Web/CSS/color)
-   [`color-adjust`](https://developer.mozilla.org/en-US/docs/Web/CSS/color-adjust)
-   [`color-scheme`](https://developer.mozilla.org/en-US/docs/Web/CSS/color-scheme)
-   [`column-count`](https://developer.mozilla.org/en-US/docs/Web/CSS/column-count)
-   [`column-fill`](https://developer.mozilla.org/en-US/docs/Web/CSS/column-fill)
-   [`column-gap`](https://developer.mozilla.org/en-US/docs/Web/CSS/column-gap)
-   [`column-rule`](https://developer.mozilla.org/en-US/docs/Web/CSS/column-rule)
-   [`column-rule-color`](https://developer.mozilla.org/en-US/docs/Web/CSS/column-rule-color)
-   [`column-rule-style`](https://developer.mozilla.org/en-US/docs/Web/CSS/column-rule-style)
-   [`column-rule-width`](https://developer.mozilla.org/en-US/docs/Web/CSS/column-rule-width)
-   [`column-span`](https://developer.mozilla.org/en-US/docs/Web/CSS/column-span)
-   [`column-width`](https://developer.mozilla.org/en-US/docs/Web/CSS/column-width)
-   [`columns`](https://developer.mozilla.org/en-US/docs/Web/CSS/columns)
-   [`conic-gradient()`](https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/conic-gradient())
-   [`contain`](https://developer.mozilla.org/en-US/docs/Web/CSS/contain)
-   [`content`](https://developer.mozilla.org/en-US/docs/Web/CSS/content)
-   [`content-visibility`](https://developer.mozilla.org/en-US/docs/Web/CSS/content-visibility)
-   [`contrast()`](https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/contrast())
-   [`<counter>`](https://developer.mozilla.org/en-US/docs/Web/CSS/counter())
-   [`counter-increment`](https://developer.mozilla.org/en-US/docs/Web/CSS/counter-increment)
-   [`counter-reset`](https://developer.mozilla.org/en-US/docs/Web/CSS/counter-reset)
-   [`counter-set`](https://developer.mozilla.org/en-US/docs/Web/CSS/counter-set)
-   [`@counter-style`](https://developer.mozilla.org/en-US/docs/Web/CSS/@counter-style)
-   [`counters()`](https://developer.mozilla.org/en-US/docs/Web/CSS/counters())
-   [`cross-fade()`](https://developer.mozilla.org/en-US/docs/Web/CSS/cross-fade())
-   [`cubic-bezier()`](https://developer.mozilla.org/en-US/docs/Web/CSS/easing-function#cubic-bezier())
-   [`::cue`](https://developer.mozilla.org/en-US/docs/Web/CSS/::cue)
-   [`::cue-region`](https://developer.mozilla.org/en-US/docs/Web/CSS/::cue-region)
-   [`:current`](https://developer.mozilla.org/en-US/docs/Web/CSS/:current)
-   [`cursor`](https://developer.mozilla.org/en-US/docs/Web/CSS/cursor)
-   [`<custom-ident>`](https://developer.mozilla.org/en-US/docs/Web/CSS/custom-ident)
-   [`length#ch`](https://developer.mozilla.org/en-US/docs/Web/CSS/length#ch)
-   [`length#cm`](https://developer.mozilla.org/en-US/docs/Web/CSS/length#cm)

D

-   [`angle#deg`](https://developer.mozilla.org/en-US/docs/Web/CSS/angle#deg)
-   [`:default`](https://developer.mozilla.org/en-US/docs/Web/CSS/:default)
-   [`:defined`](https://developer.mozilla.org/en-US/docs/Web/CSS/:defined)
-   [`descent-override (@font-face)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/descent-override)
-   [`<dimension>`](https://developer.mozilla.org/en-US/docs/Web/CSS/dimension)
-   [`:dir`](https://developer.mozilla.org/en-US/docs/Web/CSS/:dir)
-   [`direction`](https://developer.mozilla.org/en-US/docs/Web/CSS/direction)
-   [`:disabled`](https://developer.mozilla.org/en-US/docs/Web/CSS/:disabled)
-   [`display`](https://developer.mozilla.org/en-US/docs/Web/CSS/display)
-   [`<display-box>`](https://developer.mozilla.org/en-US/docs/Web/CSS/display-box)
-   [`<display-inside>`](https://developer.mozilla.org/en-US/docs/Web/CSS/display-inside)
-   [`<display-internal>`](https://developer.mozilla.org/en-US/docs/Web/CSS/display-internal)
-   [`<display-legacy>`](https://developer.mozilla.org/en-US/docs/Web/CSS/display-legacy)
-   [`<display-listitem>`](https://developer.mozilla.org/en-US/docs/Web/CSS/display-listitem)
-   [`<display-outside>`](https://developer.mozilla.org/en-US/docs/Web/CSS/display-outside)
-   [`drop-shadow()`](https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/drop-shadow())
-   [`resolution#dpcm`](https://developer.mozilla.org/en-US/docs/Web/CSS/resolution#dpcm)
-   [`resolution#dpi`](https://developer.mozilla.org/en-US/docs/Web/CSS/resolution#dpi)
-   [`resolution#dppx`](https://developer.mozilla.org/en-US/docs/Web/CSS/resolution#dppx)

E

-   [`element()`](https://developer.mozilla.org/en-US/docs/Web/CSS/element())
-   [`ellipse()`](https://developer.mozilla.org/en-US/docs/Web/CSS/basic-shape#ellipse())
-   [`:empty`](https://developer.mozilla.org/en-US/docs/Web/CSS/:empty)
-   [`empty-cells`](https://developer.mozilla.org/en-US/docs/Web/CSS/empty-cells)
-   [`:enabled`](https://developer.mozilla.org/en-US/docs/Web/CSS/:enabled)
-   [`env()`](https://developer.mozilla.org/en-US/docs/Web/CSS/env())
-   [`length#em`](https://developer.mozilla.org/en-US/docs/Web/CSS/length#em)
-   [`length#ex`](https://developer.mozilla.org/en-US/docs/Web/CSS/length#ex)

F

-   [`fallback (@counter-style)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@counter-style/fallback)
-   [`filter`](https://developer.mozilla.org/en-US/docs/Web/CSS/filter)
-   [`<filter-function>`](https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function)
-   [`:first`](https://developer.mozilla.org/en-US/docs/Web/CSS/:first)
-   [`:first-child`](https://developer.mozilla.org/en-US/docs/Web/CSS/:first-child)
-   [`::first-letter (:first-letter)`](https://developer.mozilla.org/en-US/docs/Web/CSS/::first-letter)
-   [`::first-line (:first-line)`](https://developer.mozilla.org/en-US/docs/Web/CSS/::first-line)
-   [`:first-of-type`](https://developer.mozilla.org/en-US/docs/Web/CSS/:first-of-type)
-   [`fit-content()`](https://developer.mozilla.org/en-US/docs/Web/CSS/fit-content)
-   [`<flex>`](https://developer.mozilla.org/en-US/docs/Web/CSS/flex_value)
-   [`flex`](https://developer.mozilla.org/en-US/docs/Web/CSS/flex)
-   [`flex-basis`](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-basis)
-   [`flex-direction`](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-direction)
-   [`flex-flow`](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-flow)
-   [`flex-grow`](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-grow)
-   [`flex-shrink`](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-shrink)
-   [`flex-wrap`](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-wrap)
-   [`flex_value#fr`](https://developer.mozilla.org/en-US/docs/Web/CSS/flex_value#fr)
-   [`float`](https://developer.mozilla.org/en-US/docs/Web/CSS/float)
-   [`:focus`](https://developer.mozilla.org/en-US/docs/Web/CSS/:focus)
-   [`:focus-visible`](https://developer.mozilla.org/en-US/docs/Web/CSS/:focus-visible)
-   [`:focus-within`](https://developer.mozilla.org/en-US/docs/Web/CSS/:focus-within)
-   [`font`](https://developer.mozilla.org/en-US/docs/Web/CSS/font)
-   [`font-display (@font-face)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/font-display)
-   [`@font-face`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face)
-   [`font-family`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-family)
-   [`font-family (@font-face)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/font-family)
-   [`font-feature-settings`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-feature-settings)
-   `font-feature-settings (@font-face)`
-   [`@font-feature-values`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-feature-values)
-   [`font-kerning`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-kerning)
-   [`font-language-override`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-language-override)
-   [`font-optical-sizing`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-optical-sizing)
-   [`font-size`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-size)
-   [`font-size-adjust`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-size-adjust)
-   [`font-stretch`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-stretch)
-   [`font-stretch (@font-face)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/font-stretch)
-   [`font-style`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-style)
-   [`font-style (@font-face)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/font-style)
-   [`font-synthesis`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-synthesis)
-   [`font-variant`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant)
-   [`font-variant (@font-face)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/font-variant)
-   [`font-variant-alternates`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant-alternates)
-   [`font-variant-caps`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant-caps)
-   [`font-variant-east-asian`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant-east-asian)
-   [`font-variant-ligatures`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant-ligatures)
-   [`font-variant-numeric`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant-numeric)
-   [`font-variant-position`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant-position)
-   [`font-variation-settings`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variation-settings)
-   [`font-variation-settings (@font-face)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/font-variation-settings)
-   [`font-weight`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-weight)
-   [`font-weight (@font-face)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/font-weight)
-   [`forced-color-adjust`](https://developer.mozilla.org/en-US/docs/Web/CSS/forced-color-adjust)
-   [`format()`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/src#format())
-   [`<frequency>`](https://developer.mozilla.org/en-US/docs/Web/CSS/frequency)
-   [`<frequency-percentage>`](https://developer.mozilla.org/en-US/docs/Web/CSS/frequency-percentage)
-   [`:fullscreen`](https://developer.mozilla.org/en-US/docs/Web/CSS/:fullscreen)
-   [`:future`](https://developer.mozilla.org/en-US/docs/Web/CSS/:future)

G

-   [`angle#grad`](https://developer.mozilla.org/en-US/docs/Web/CSS/angle#grad)
-   [`gap`](https://developer.mozilla.org/en-US/docs/Web/CSS/gap)
-   [`<gradient>`](https://developer.mozilla.org/en-US/docs/Web/CSS/gradient)
-   [`::grammar-error`](https://developer.mozilla.org/en-US/docs/Web/CSS/::grammar-error)
-   [`grayscale()`](https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/grayscale())
-   [`grid`](https://developer.mozilla.org/en-US/docs/Web/CSS/grid)
-   [`grid-area`](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-area)
-   [`grid-auto-columns`](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-auto-columns)
-   [`grid-auto-flow`](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-auto-flow)
-   [`grid-auto-rows`](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-auto-rows)
-   [`grid-column`](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-column)
-   [`grid-column-end`](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-column-end)
-   [`grid-column-start`](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-column-start)
-   [`grid-row`](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-row)
-   [`grid-row-end`](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-row-end)
-   [`grid-row-start`](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-row-start)
-   [`grid-template`](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template)
-   [`grid-template-areas`](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-areas)
-   [`grid-template-columns`](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-columns)
-   [`grid-template-rows`](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-rows)

H

-   [`frequency#Hz`](https://developer.mozilla.org/en-US/docs/Web/CSS/frequency#hz)
-   [`hanging-punctuation`](https://developer.mozilla.org/en-US/docs/Web/CSS/hanging-punctuation)
-   [`:has`](https://developer.mozilla.org/en-US/docs/Web/CSS/:has)
-   [`height`](https://developer.mozilla.org/en-US/docs/Web/CSS/height)
-   [`height (@viewport)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@viewport)
-   `@historical-forms`
-   [`:host()`](https://developer.mozilla.org/en-US/docs/Web/CSS/:host())
-   [`:host-context()`](https://developer.mozilla.org/en-US/docs/Web/CSS/:host-context())
-   [`:hover`](https://developer.mozilla.org/en-US/docs/Web/CSS/:hover)
-   [`hsl()`](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value#hsl())
-   [`hsla()`](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value#hsla())
-   [`hue-rotate()`](https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/hue-rotate())
-   [`hyphens`](https://developer.mozilla.org/en-US/docs/Web/CSS/hyphens)

I

-   [`<ident>`](https://developer.mozilla.org/en-US/docs/Web/CSS/ident)
-   [`<image>`](https://developer.mozilla.org/en-US/docs/Web/CSS/image)
-   [`image()`](https://developer.mozilla.org/en-US/docs/Web/CSS/image#the_image()_functional_notation)
-   [`image-orientation`](https://developer.mozilla.org/en-US/docs/Web/CSS/image-orientation)
-   [`image-rendering`](https://developer.mozilla.org/en-US/docs/Web/CSS/image-rendering)
-   [`image-resolution`](https://developer.mozilla.org/en-US/docs/Web/CSS/image-resolution)
-   [`image-set()`](https://developer.mozilla.org/en-US/docs/Web/CSS/image/image-set())
-   [`@import`](https://developer.mozilla.org/en-US/docs/Web/CSS/@import)
-   [`:in-range`](https://developer.mozilla.org/en-US/docs/Web/CSS/:in-range)
-   [`:indeterminate`](https://developer.mozilla.org/en-US/docs/Web/CSS/:indeterminate)
-   [`inherit`](https://developer.mozilla.org/en-US/docs/Web/CSS/inherit)
-   [`inherits (@property)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@property/inherits)
-   [`initial`](https://developer.mozilla.org/en-US/docs/Web/CSS/initial)
-   [`initial-letter`](https://developer.mozilla.org/en-US/docs/Web/CSS/initial-letter)
-   [`initial-letter-align`](https://developer.mozilla.org/en-US/docs/Web/CSS/initial-letter-align)
-   [`initial-value (@property)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@property/initial-value)
-   [`inline-size`](https://developer.mozilla.org/en-US/docs/Web/CSS/inline-size)
-   [`inset`](https://developer.mozilla.org/en-US/docs/Web/CSS/inset)
-   [`inset()`](https://developer.mozilla.org/en-US/docs/Web/CSS/basic-shape#inset())
-   [`inset-block`](https://developer.mozilla.org/en-US/docs/Web/CSS/inset-block)
-   [`inset-block-end`](https://developer.mozilla.org/en-US/docs/Web/CSS/inset-block-end)
-   [`inset-block-start`](https://developer.mozilla.org/en-US/docs/Web/CSS/inset-block-start)
-   [`inset-inline`](https://developer.mozilla.org/en-US/docs/Web/CSS/inset-inline)
-   [`inset-inline-end`](https://developer.mozilla.org/en-US/docs/Web/CSS/inset-inline-end)
-   [`inset-inline-start`](https://developer.mozilla.org/en-US/docs/Web/CSS/inset-inline-start)
-   [`<integer>`](https://developer.mozilla.org/en-US/docs/Web/CSS/integer)
-   [`:invalid`](https://developer.mozilla.org/en-US/docs/Web/CSS/:invalid)
-   [`invert()`](https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/invert())
-   [`:is`](https://developer.mozilla.org/en-US/docs/Web/CSS/:is)
-   [`isolation`](https://developer.mozilla.org/en-US/docs/Web/CSS/isolation)
-   [`length#in`](https://developer.mozilla.org/en-US/docs/Web/CSS/length#in)

J

-   [`justify-content`](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)
-   [`justify-items`](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-items)
-   [`justify-self`](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-self)
-   [`justify-tracks`](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-tracks)

K

-   [`frequency#kHz`](https://developer.mozilla.org/en-US/docs/Web/CSS/frequency#khz)
-   [`@keyframes`](https://developer.mozilla.org/en-US/docs/Web/CSS/@keyframes)

L

-   [`:lang`](https://developer.mozilla.org/en-US/docs/Web/CSS/:lang)
-   [`:last-child`](https://developer.mozilla.org/en-US/docs/Web/CSS/:last-child)
-   [`:last-of-type`](https://developer.mozilla.org/en-US/docs/Web/CSS/:last-of-type)
-   `leader()`
-   [`:left`](https://developer.mozilla.org/en-US/docs/Web/CSS/:left)
-   [`left`](https://developer.mozilla.org/en-US/docs/Web/CSS/left)
-   [`@left-bottom`](https://developer.mozilla.org/en-US/docs/Web/CSS/@page#page-margin-box-type)
-   [`<length>`](https://developer.mozilla.org/en-US/docs/Web/CSS/length)
-   [`<length-percentage>`](https://developer.mozilla.org/en-US/docs/Web/CSS/length-percentage)
-   [`letter-spacing`](https://developer.mozilla.org/en-US/docs/Web/CSS/letter-spacing)
-   [`line-break`](https://developer.mozilla.org/en-US/docs/Web/CSS/line-break)
-   `line-clamp`
-   [`line-gap-override (@font-face)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/line-gap-override)
-   [`line-height`](https://developer.mozilla.org/en-US/docs/Web/CSS/line-height)
-   [`line-height-step`](https://developer.mozilla.org/en-US/docs/Web/CSS/line-height-step)
-   [`linear-gradient()`](https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/linear-gradient())
-   [`:link`](https://developer.mozilla.org/en-US/docs/Web/CSS/:link)
-   [`list-style`](https://developer.mozilla.org/en-US/docs/Web/CSS/list-style)
-   [`list-style-image`](https://developer.mozilla.org/en-US/docs/Web/CSS/list-style-image)
-   [`list-style-position`](https://developer.mozilla.org/en-US/docs/Web/CSS/list-style-position)
-   [`list-style-type`](https://developer.mozilla.org/en-US/docs/Web/CSS/list-style-type)
-   [`local()`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/src#local())
-   [`:local-link`](https://developer.mozilla.org/en-US/docs/Web/CSS/:local-link)

M

-   [`length#mm`](https://developer.mozilla.org/en-US/docs/Web/CSS/length#mm)
-   [`margin`](https://developer.mozilla.org/en-US/docs/Web/CSS/margin)
-   [`margin-block`](https://developer.mozilla.org/en-US/docs/Web/CSS/margin-block)
-   [`margin-block-end`](https://developer.mozilla.org/en-US/docs/Web/CSS/margin-block-end)
-   [`margin-block-start`](https://developer.mozilla.org/en-US/docs/Web/CSS/margin-block-start)
-   [`margin-bottom`](https://developer.mozilla.org/en-US/docs/Web/CSS/margin-bottom)
-   [`margin-inline`](https://developer.mozilla.org/en-US/docs/Web/CSS/margin-inline)
-   [`margin-inline-end`](https://developer.mozilla.org/en-US/docs/Web/CSS/margin-inline-end)
-   [`margin-inline-start`](https://developer.mozilla.org/en-US/docs/Web/CSS/margin-inline-start)
-   [`margin-left`](https://developer.mozilla.org/en-US/docs/Web/CSS/margin-left)
-   [`margin-right`](https://developer.mozilla.org/en-US/docs/Web/CSS/margin-right)
-   [`margin-top`](https://developer.mozilla.org/en-US/docs/Web/CSS/margin-top)
-   [`margin-trim`](https://developer.mozilla.org/en-US/docs/Web/CSS/margin-trim)
-   [`::marker`](https://developer.mozilla.org/en-US/docs/Web/CSS/::marker)
-   `marks (@page)`
-   [`mask`](https://developer.mozilla.org/en-US/docs/Web/CSS/mask)
-   [`mask-border`](https://developer.mozilla.org/en-US/docs/Web/CSS/mask-border)
-   [`mask-border-mode`](https://developer.mozilla.org/en-US/docs/Web/CSS/mask-border-mode)
-   [`mask-border-outset`](https://developer.mozilla.org/en-US/docs/Web/CSS/mask-border-outset)
-   [`mask-border-repeat`](https://developer.mozilla.org/en-US/docs/Web/CSS/mask-border-repeat)
-   [`mask-border-slice`](https://developer.mozilla.org/en-US/docs/Web/CSS/mask-border-slice)
-   [`mask-border-source`](https://developer.mozilla.org/en-US/docs/Web/CSS/mask-border-source)
-   [`mask-border-width`](https://developer.mozilla.org/en-US/docs/Web/CSS/mask-border-width)
-   [`mask-clip`](https://developer.mozilla.org/en-US/docs/Web/CSS/mask-clip)
-   [`mask-composite`](https://developer.mozilla.org/en-US/docs/Web/CSS/mask-composite)
-   [`mask-image`](https://developer.mozilla.org/en-US/docs/Web/CSS/mask-image)
-   [`mask-mode`](https://developer.mozilla.org/en-US/docs/Web/CSS/mask-mode)
-   [`mask-origin`](https://developer.mozilla.org/en-US/docs/Web/CSS/mask-origin)
-   [`mask-position`](https://developer.mozilla.org/en-US/docs/Web/CSS/mask-position)
-   [`mask-repeat`](https://developer.mozilla.org/en-US/docs/Web/CSS/mask-repeat)
-   [`mask-size`](https://developer.mozilla.org/en-US/docs/Web/CSS/mask-size)
-   [`mask-type`](https://developer.mozilla.org/en-US/docs/Web/CSS/mask-type)
-   [`masonry-auto-flow`](https://developer.mozilla.org/en-US/docs/Web/CSS/masonry-auto-flow)
-   [`math-style`](https://developer.mozilla.org/en-US/docs/Web/CSS/math-style)
-   [`matrix()`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/matrix())
-   [`matrix3d()`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/matrix3d())
-   [`max()`](https://developer.mozilla.org/en-US/docs/Web/CSS/max())
-   [`max-block-size`](https://developer.mozilla.org/en-US/docs/Web/CSS/max-block-size)
-   [`max-height`](https://developer.mozilla.org/en-US/docs/Web/CSS/max-height)
-   [`max-height (@viewport)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@viewport)
-   [`max-inline-size`](https://developer.mozilla.org/en-US/docs/Web/CSS/max-inline-size)
-   `max-lines`
-   [`max-width`](https://developer.mozilla.org/en-US/docs/Web/CSS/max-width)
-   [`max-width (@viewport)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@viewport)
-   [`max-zoom (@viewport)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@viewport)
-   [`@media`](https://developer.mozilla.org/en-US/docs/Web/CSS/@media)
-   [`min()`](https://developer.mozilla.org/en-US/docs/Web/CSS/min())
-   [`min-block-size`](https://developer.mozilla.org/en-US/docs/Web/CSS/min-block-size)
-   [`min-height`](https://developer.mozilla.org/en-US/docs/Web/CSS/min-height)
-   [`min-height (@viewport)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@viewport)
-   [`min-inline-size`](https://developer.mozilla.org/en-US/docs/Web/CSS/min-inline-size)
-   [`min-width`](https://developer.mozilla.org/en-US/docs/Web/CSS/min-width)
-   [`min-width (@viewport)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@viewport)
-   [`min-zoom (@viewport)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@viewport)
-   [`minmax()`](https://developer.mozilla.org/en-US/docs/Web/CSS/minmax())
-   [`mix-blend-mode`](https://developer.mozilla.org/en-US/docs/Web/CSS/mix-blend-mode)
-   [`time#ms`](https://developer.mozilla.org/en-US/docs/Web/CSS/time#ms)

N

-   [`@namespace`](https://developer.mozilla.org/en-US/docs/Web/CSS/@namespace)
-   [`negative (@counter-style)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@counter-style/negative)
-   [`:not`](https://developer.mozilla.org/en-US/docs/Web/CSS/:not)
-   [`:nth-child`](https://developer.mozilla.org/en-US/docs/Web/CSS/:nth-child)
-   [`:nth-col`](https://developer.mozilla.org/en-US/docs/Web/CSS/:nth-col)
-   [`:nth-last-child`](https://developer.mozilla.org/en-US/docs/Web/CSS/:nth-last-child)
-   [`:nth-last-col`](https://developer.mozilla.org/en-US/docs/Web/CSS/:nth-last-col)
-   [`:nth-last-of-type`](https://developer.mozilla.org/en-US/docs/Web/CSS/:nth-last-of-type)
-   [`:nth-of-type`](https://developer.mozilla.org/en-US/docs/Web/CSS/:nth-of-type)
-   [`<number>`](https://developer.mozilla.org/en-US/docs/Web/CSS/number)

O

-   [`object-fit`](https://developer.mozilla.org/en-US/docs/Web/CSS/object-fit)
-   [`object-position`](https://developer.mozilla.org/en-US/docs/Web/CSS/object-position)
-   [`offset`](https://developer.mozilla.org/en-US/docs/Web/CSS/offset)
-   [`offset-anchor`](https://developer.mozilla.org/en-US/docs/Web/CSS/offset-anchor)
-   [`offset-distance`](https://developer.mozilla.org/en-US/docs/Web/CSS/offset-distance)
-   [`offset-path`](https://developer.mozilla.org/en-US/docs/Web/CSS/offset-path)
-   [`offset-position`](https://developer.mozilla.org/en-US/docs/Web/CSS/offset-position)
-   [`offset-rotate`](https://developer.mozilla.org/en-US/docs/Web/CSS/offset-rotate)
-   [`:only-child`](https://developer.mozilla.org/en-US/docs/Web/CSS/:only-child)
-   [`:only-of-type`](https://developer.mozilla.org/en-US/docs/Web/CSS/:only-of-type)
-   [`opacity`](https://developer.mozilla.org/en-US/docs/Web/CSS/opacity)
-   [`opacity()`](https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/opacity())
-   [`:optional`](https://developer.mozilla.org/en-US/docs/Web/CSS/:optional)
-   [`order`](https://developer.mozilla.org/en-US/docs/Web/CSS/order)
-   [`orientation (@viewport)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@viewport)
-   [`@ornaments`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-feature-values#@ornaments)
-   [`ornaments()`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant-alternates#ornaments())
-   [`orphans`](https://developer.mozilla.org/en-US/docs/Web/CSS/orphans)
-   [`:out-of-range`](https://developer.mozilla.org/en-US/docs/Web/CSS/:out-of-range)
-   [`outline`](https://developer.mozilla.org/en-US/docs/Web/CSS/outline)
-   [`outline-color`](https://developer.mozilla.org/en-US/docs/Web/CSS/outline-color)
-   [`outline-offset`](https://developer.mozilla.org/en-US/docs/Web/CSS/outline-offset)
-   [`outline-style`](https://developer.mozilla.org/en-US/docs/Web/CSS/outline-style)
-   [`outline-width`](https://developer.mozilla.org/en-US/docs/Web/CSS/outline-width)
-   [`overflow`](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow)
-   [`overflow-anchor`](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow-anchor)
-   [`overflow-block`](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow-block)
-   [`overflow-clip-margin`](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow-clip-margin)
-   [`overflow-inline`](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow-inline)
-   [`overflow-wrap`](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow-wrap)
-   [`overflow-x`](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow-x)
-   [`overflow-y`](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow-y)
-   [`overscroll-behavior`](https://developer.mozilla.org/en-US/docs/Web/CSS/overscroll-behavior)
-   [`overscroll-behavior-block`](https://developer.mozilla.org/en-US/docs/Web/CSS/overscroll-behavior-block)
-   [`overscroll-behavior-inline`](https://developer.mozilla.org/en-US/docs/Web/CSS/overscroll-behavior-inline)
-   [`overscroll-behavior-x`](https://developer.mozilla.org/en-US/docs/Web/CSS/overscroll-behavior-x)
-   [`overscroll-behavior-y`](https://developer.mozilla.org/en-US/docs/Web/CSS/overscroll-behavior-y)

P

-   [`Pseudo-classes`](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes)
-   [`Pseudo-elements`](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements)
-   [`length#pc`](https://developer.mozilla.org/en-US/docs/Web/CSS/length#pc)
-   [`length#pt`](https://developer.mozilla.org/en-US/docs/Web/CSS/length#pt)
-   [`length#px`](https://developer.mozilla.org/en-US/docs/Web/CSS/length#px)
-   [`pad (@counter-style)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@counter-style/pad)
-   [`padding`](https://developer.mozilla.org/en-US/docs/Web/CSS/padding)
-   [`padding-block`](https://developer.mozilla.org/en-US/docs/Web/CSS/padding-block)
-   [`padding-block-end`](https://developer.mozilla.org/en-US/docs/Web/CSS/padding-block-end)
-   [`padding-block-start`](https://developer.mozilla.org/en-US/docs/Web/CSS/padding-block-start)
-   [`padding-bottom`](https://developer.mozilla.org/en-US/docs/Web/CSS/padding-bottom)
-   [`padding-inline`](https://developer.mozilla.org/en-US/docs/Web/CSS/padding-inline)
-   [`padding-inline-end`](https://developer.mozilla.org/en-US/docs/Web/CSS/padding-inline-end)
-   [`padding-inline-start`](https://developer.mozilla.org/en-US/docs/Web/CSS/padding-inline-start)
-   [`padding-left`](https://developer.mozilla.org/en-US/docs/Web/CSS/padding-left)
-   [`padding-right`](https://developer.mozilla.org/en-US/docs/Web/CSS/padding-right)
-   [`padding-top`](https://developer.mozilla.org/en-US/docs/Web/CSS/padding-top)
-   [`@page`](https://developer.mozilla.org/en-US/docs/Web/CSS/@page)
-   [`page-break-after`](https://developer.mozilla.org/en-US/docs/Web/CSS/page-break-after)
-   [`page-break-before`](https://developer.mozilla.org/en-US/docs/Web/CSS/page-break-before)
-   [`page-break-inside`](https://developer.mozilla.org/en-US/docs/Web/CSS/page-break-inside)
-   [`paint()`](https://developer.mozilla.org/en-US/docs/Web/CSS/image/paint())
-   [`paint-order`](https://developer.mozilla.org/en-US/docs/Web/CSS/paint-order)
-   [`::part`](https://developer.mozilla.org/en-US/docs/Web/CSS/::part)
-   [`:past`](https://developer.mozilla.org/en-US/docs/Web/CSS/:past)
-   [`path()`](https://developer.mozilla.org/en-US/docs/Web/CSS/path())
-   [`:paused`](https://developer.mozilla.org/en-US/docs/Web/CSS/:paused)
-   [`<percentage>`](https://developer.mozilla.org/en-US/docs/Web/CSS/percentage)
-   [`perspective`](https://developer.mozilla.org/en-US/docs/Web/CSS/perspective)
-   [`perspective()`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/perspective())
-   [`perspective-origin`](https://developer.mozilla.org/en-US/docs/Web/CSS/perspective-origin)
-   [`:picture-in-picture`](https://developer.mozilla.org/en-US/docs/Web/CSS/:picture-in-picture)
-   [`place-content`](https://developer.mozilla.org/en-US/docs/Web/CSS/place-content)
-   [`place-items`](https://developer.mozilla.org/en-US/docs/Web/CSS/place-items)
-   [`place-self`](https://developer.mozilla.org/en-US/docs/Web/CSS/place-self)
-   [`::placeholder`](https://developer.mozilla.org/en-US/docs/Web/CSS/::placeholder)
-   [`:placeholder-shown`](https://developer.mozilla.org/en-US/docs/Web/CSS/:placeholder-shown)
-   [`:playing`](https://developer.mozilla.org/en-US/docs/Web/CSS/:playing)
-   [`pointer-events`](https://developer.mozilla.org/en-US/docs/Web/CSS/pointer-events)
-   [`polygon()`](https://developer.mozilla.org/en-US/docs/Web/CSS/basic-shape#polygon())
-   [`<position>`](https://developer.mozilla.org/en-US/docs/Web/CSS/position_value)
-   [`position`](https://developer.mozilla.org/en-US/docs/Web/CSS/position)
-   [`prefix (@counter-style)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@counter-style/prefix)
-   [`@property`](https://developer.mozilla.org/en-US/docs/Web/CSS/@property)

Q

-   [`length#Q`](https://developer.mozilla.org/en-US/docs/Web/CSS/length#q)
-   [`quotes`](https://developer.mozilla.org/en-US/docs/Web/CSS/quotes)

R

-   [`angle#rad`](https://developer.mozilla.org/en-US/docs/Web/CSS/angle#rad)
-   [`length#rem`](https://developer.mozilla.org/en-US/docs/Web/CSS/length#rem)
-   [`radial-gradient()`](https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/radial-gradient())
-   [`range (@counter-style)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@counter-style/range)
-   [`<ratio>`](https://developer.mozilla.org/en-US/docs/Web/CSS/ratio)
-   [`:read-only`](https://developer.mozilla.org/en-US/docs/Web/CSS/:read-only)
-   [`:read-write`](https://developer.mozilla.org/en-US/docs/Web/CSS/:read-write)
-   [`rect()`](https://developer.mozilla.org/en-US/docs/Web/CSS/shape#rect())
-   [`repeat()`](https://developer.mozilla.org/en-US/docs/Web/CSS/repeat())
-   [`repeating-linear-gradient()`](https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/repeating-linear-gradient())
-   [`repeating-radial-gradient()`](https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/repeating-radial-gradient())
-   [`:required`](https://developer.mozilla.org/en-US/docs/Web/CSS/:required)
-   [`resize`](https://developer.mozilla.org/en-US/docs/Web/CSS/resize)
-   [`<resolution>`](https://developer.mozilla.org/en-US/docs/Web/CSS/resolution)
-   [`revert`](https://developer.mozilla.org/en-US/docs/Web/CSS/revert)
-   [`rgb()`](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value#rgb())
-   [`rgba()`](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value#rgba())
-   [`:right`](https://developer.mozilla.org/en-US/docs/Web/CSS/:right)
-   [`right`](https://developer.mozilla.org/en-US/docs/Web/CSS/right)
-   [`@right-bottom`](https://developer.mozilla.org/en-US/docs/Web/CSS/@page#page-margin-box-type)
-   [`:root`](https://developer.mozilla.org/en-US/docs/Web/CSS/:root)
-   [`rotate`](https://developer.mozilla.org/en-US/docs/Web/CSS/rotate)
-   [`rotate()`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/rotate())
-   [`rotate3d()`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/rotate3d())
-   [`rotateX()`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/rotateX())
-   [`rotateY()`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/rotateY())
-   [`rotateZ()`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/rotateZ())
-   [`row-gap`](https://developer.mozilla.org/en-US/docs/Web/CSS/row-gap)
-   [`ruby-align`](https://developer.mozilla.org/en-US/docs/Web/CSS/ruby-align)
-   `ruby-merge`
-   [`ruby-position`](https://developer.mozilla.org/en-US/docs/Web/CSS/ruby-position)

S

-   [`saturate()`](https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/saturate())
-   [`scale`](https://developer.mozilla.org/en-US/docs/Web/CSS/scale)
-   [`scale()`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/scale())
-   [`scale3d()`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/scale3d())
-   [`scaleX()`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/scaleX())
-   [`scaleY()`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/scaleY())
-   [`scaleZ()`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/scaleZ())
-   [`:scope`](https://developer.mozilla.org/en-US/docs/Web/CSS/:scope)
-   [`scroll-behavior`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-behavior)
-   [`scroll-margin`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-margin)
-   [`scroll-margin-block`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-margin-block)
-   [`scroll-margin-block-end`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-margin-block-end)
-   [`scroll-margin-block-start`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-margin-block-start)
-   [`scroll-margin-bottom`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-margin-bottom)
-   [`scroll-margin-inline`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-margin-inline)
-   [`scroll-margin-inline-end`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-margin-inline-end)
-   [`scroll-margin-inline-start`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-margin-inline-start)
-   [`scroll-margin-left`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-margin-left)
-   [`scroll-margin-right`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-margin-right)
-   [`scroll-margin-top`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-margin-top)
-   [`scroll-padding`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-padding)
-   [`scroll-padding-block`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-padding-block)
-   [`scroll-padding-block-end`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-padding-block-end)
-   [`scroll-padding-block-start`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-padding-block-start)
-   [`scroll-padding-bottom`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-padding-bottom)
-   [`scroll-padding-inline`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-padding-inline)
-   [`scroll-padding-inline-end`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-padding-inline-end)
-   [`scroll-padding-inline-start`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-padding-inline-start)
-   [`scroll-padding-left`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-padding-left)
-   [`scroll-padding-right`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-padding-right)
-   [`scroll-padding-top`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-padding-top)
-   [`scroll-snap-align`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-snap-align)
-   [`scroll-snap-stop`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-snap-stop)
-   [`scroll-snap-type`](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-snap-type)
-   [`scrollbar-color`](https://developer.mozilla.org/en-US/docs/Web/CSS/scrollbar-color)
-   [`scrollbar-gutter`](https://developer.mozilla.org/en-US/docs/Web/CSS/scrollbar-gutter)
-   [`scrollbar-width`](https://developer.mozilla.org/en-US/docs/Web/CSS/scrollbar-width)
-   [`::selection`](https://developer.mozilla.org/en-US/docs/Web/CSS/::selection)
-   `selector()`
-   [`sepia()`](https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/sepia())
-   [`<shape>`](https://developer.mozilla.org/en-US/docs/Web/CSS/shape)
-   [`shape-image-threshold`](https://developer.mozilla.org/en-US/docs/Web/CSS/shape-image-threshold)
-   [`shape-margin`](https://developer.mozilla.org/en-US/docs/Web/CSS/shape-margin)
-   [`shape-outside`](https://developer.mozilla.org/en-US/docs/Web/CSS/shape-outside)
-   [`size (@page)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@page/size)
-   [`size-adjust (@font-face)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/size-adjust)
-   [`skew()`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/skew())
-   [`skewX()`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/skewX())
-   [`skewY()`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/skewY())
-   [`::slotted`](https://developer.mozilla.org/en-US/docs/Web/CSS/::slotted)
-   [`speak-as (@counter-style)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@counter-style/speak-as)
-   [`::spelling-error`](https://developer.mozilla.org/en-US/docs/Web/CSS/::spelling-error)
-   [`src (@font-face)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/src)
-   [`steps()`](https://developer.mozilla.org/en-US/docs/Web/CSS/easing-function#steps())
-   [`<string>`](https://developer.mozilla.org/en-US/docs/Web/CSS/string)
-   [`@styleset`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-feature-values#@styleset)
-   [`styleset()`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant-alternates#styleset())
-   [`@stylistic`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-feature-values#@stylistic)
-   [`stylistic()`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant-alternates#stylistic())
-   [`suffix (@counter-style)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@counter-style/suffix)
-   [`@supports`](https://developer.mozilla.org/en-US/docs/Web/CSS/@supports)
-   [`@swash`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-feature-values#@swash)
-   [`swash()`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant-alternates#swash())
-   [`symbols (@counter-style)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@counter-style/symbols)
-   [`symbols()`](https://developer.mozilla.org/en-US/docs/Web/CSS/symbols())
-   [`syntax (@property)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@property/syntax)
-   [`system (@counter-style)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@counter-style/system)
-   [`time#s`](https://developer.mozilla.org/en-US/docs/Web/CSS/time#s)

T

-   [`angle#turn`](https://developer.mozilla.org/en-US/docs/Web/CSS/angle#turn)
-   [`tab-size`](https://developer.mozilla.org/en-US/docs/Web/CSS/tab-size)
-   [`table-layout`](https://developer.mozilla.org/en-US/docs/Web/CSS/table-layout)
-   [`:target`](https://developer.mozilla.org/en-US/docs/Web/CSS/:target)
-   `target-counter()`
-   `target-counters()`
-   [`::target-text`](https://developer.mozilla.org/en-US/docs/Web/CSS/::target-text)
-   `target-text()`
-   [`:target-within`](https://developer.mozilla.org/en-US/docs/Web/CSS/:target-within)
-   [`text-align`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-align)
-   [`text-align-last`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-align-last)
-   [`text-combine-upright`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-combine-upright)
-   [`text-decoration`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration)
-   [`text-decoration-color`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-color)
-   [`text-decoration-line`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line)
-   [`text-decoration-skip`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-skip)
-   [`text-decoration-skip-ink`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-skip-ink)
-   [`text-decoration-style`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-style)
-   [`text-decoration-thickness`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-thickness)
-   [`text-emphasis`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-emphasis)
-   [`text-emphasis-color`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-emphasis-color)
-   [`text-emphasis-position`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-emphasis-position)
-   [`text-emphasis-style`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-emphasis-style)
-   [`text-indent`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-indent)
-   [`text-justify`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-justify)
-   [`text-orientation`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-orientation)
-   [`text-overflow`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-overflow)
-   [`text-rendering`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-rendering)
-   [`text-shadow`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-shadow)
-   [`text-size-adjust`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-size-adjust)
-   [`text-transform`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-transform)
-   [`text-underline-offset`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-underline-offset)
-   [`text-underline-position`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-underline-position)
-   [`<time>`](https://developer.mozilla.org/en-US/docs/Web/CSS/time)
-   [`<time-percentage>`](https://developer.mozilla.org/en-US/docs/Web/CSS/time-percentage)
-   [`<timing-function>`](https://developer.mozilla.org/en-US/docs/Web/CSS/easing-function)
-   [`top`](https://developer.mozilla.org/en-US/docs/Web/CSS/top)
-   [`@top-center`](https://developer.mozilla.org/en-US/docs/Web/CSS/@page#page-margin-box-type)
-   [`touch-action`](https://developer.mozilla.org/en-US/docs/Web/CSS/touch-action)
-   [`transform`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform)
-   [`transform-box`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-box)
-   [`<transform-function>`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function)
-   [`transform-origin`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-origin)
-   [`transform-style`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-style)
-   [`transition`](https://developer.mozilla.org/en-US/docs/Web/CSS/transition)
-   [`transition-delay`](https://developer.mozilla.org/en-US/docs/Web/CSS/transition-delay)
-   [`transition-duration`](https://developer.mozilla.org/en-US/docs/Web/CSS/transition-duration)
-   [`transition-property`](https://developer.mozilla.org/en-US/docs/Web/CSS/transition-property)
-   [`transition-timing-function`](https://developer.mozilla.org/en-US/docs/Web/CSS/transition-timing-function)
-   [`translate`](https://developer.mozilla.org/en-US/docs/Web/CSS/translate)
-   [`translate()`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/translate())
-   [`translate3d()`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/translate3d())
-   [`translateX()`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/translateX())
-   [`translateY()`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/translateY())
-   [`translateZ()`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/translateZ())
-   `type()`

U

-   [`unicode-bidi`](https://developer.mozilla.org/en-US/docs/Web/CSS/unicode-bidi)
-   [`unicode-range (@font-face)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/unicode-range)
-   [`unset`](https://developer.mozilla.org/en-US/docs/Web/CSS/unset)
-   [`<url>`](https://developer.mozilla.org/en-US/docs/Web/CSS/url())
-   [`url()`](https://developer.mozilla.org/en-US/docs/Web/CSS/url()#the_url()_functional_notation)
-   [`:user-invalid`](https://developer.mozilla.org/en-US/docs/Web/CSS/:user-invalid)
-   [`user-select`](https://developer.mozilla.org/en-US/docs/Web/CSS/user-select)
-   [`:user-valid`](https://developer.mozilla.org/en-US/docs/web/css/:user-valid)
-   [`user-zoom (@viewport)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@viewport)

V

-   [`length#vh`](https://developer.mozilla.org/en-US/docs/Web/CSS/length#vh)
-   [`length#vmax`](https://developer.mozilla.org/en-US/docs/Web/CSS/length#vmax)
-   [`length#vmin`](https://developer.mozilla.org/en-US/docs/Web/CSS/length#vmin)
-   [`length#vw`](https://developer.mozilla.org/en-US/docs/Web/CSS/length#vw)
-   [`:valid`](https://developer.mozilla.org/en-US/docs/Web/CSS/:valid)
-   [`var()`](https://developer.mozilla.org/en-US/docs/Web/CSS/var())
-   [`vertical-align`](https://developer.mozilla.org/en-US/docs/Web/CSS/vertical-align)
-   [`@viewport`](https://developer.mozilla.org/en-US/docs/Web/CSS/@viewport)
-   [`viewport-fit (@viewport)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@viewport)
-   [`visibility`](https://developer.mozilla.org/en-US/docs/Web/CSS/visibility)
-   [`:visited`](https://developer.mozilla.org/en-US/docs/Web/CSS/:visited)

W

-   [`:where`](https://developer.mozilla.org/en-US/docs/Web/CSS/:where)
-   [`white-space`](https://developer.mozilla.org/en-US/docs/Web/CSS/white-space)
-   [`widows`](https://developer.mozilla.org/en-US/docs/Web/CSS/widows)
-   [`width`](https://developer.mozilla.org/en-US/docs/Web/CSS/width)
-   [`width (@viewport)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@viewport)
-   [`will-change`](https://developer.mozilla.org/en-US/docs/Web/CSS/will-change)
-   [`word-break`](https://developer.mozilla.org/en-US/docs/Web/CSS/word-break)
-   [`word-spacing`](https://developer.mozilla.org/en-US/docs/Web/CSS/word-spacing)
-   [`word-wrap`](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow-wrap)
-   [`writing-mode`](https://developer.mozilla.org/en-US/docs/Web/CSS/writing-mode)

X

-   [`resolution#x`](https://developer.mozilla.org/en-US/docs/Web/CSS/resolution#x)

Z

-   [`z-index`](https://developer.mozilla.org/en-US/docs/Web/CSS/z-index)
-   [`zoom (@viewport)`](https://developer.mozilla.org/en-US/docs/Web/CSS/@viewport)

Others

-   [`--*`](https://developer.mozilla.org/en-US/docs/Web/CSS/--*)

## [Selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#selectors "Permalink to Selectors")

The following are the various [selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors), which allow styles to be conditional based on various features of elements within the DOM.

### [Basic selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#basic_selectors "Permalink to Basic selectors")

**Basic selectors** are fundamental selectors; these are the most basic selectors that are frequently combined to create other, more complex selectors.

-   [Universal selector](https://developer.mozilla.org/en-US/docs/Web/CSS/Universal_selectors) `*`, `ns|*`, `*|*`, `|*`
-   [Type selector](https://developer.mozilla.org/en-US/docs/Web/CSS/Type_selectors) `elementname`
-   [Class selector](https://developer.mozilla.org/en-US/docs/Web/CSS/Class_selectors) `.classname`
-   [ID selector](https://developer.mozilla.org/en-US/docs/Web/CSS/ID_selectors) `#idname`
-   [Attribute selector](https://developer.mozilla.org/en-US/docs/Web/CSS/Attribute_selectors) `[attr=value]`

### [Grouping selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#grouping_selectors "Permalink to Grouping selectors")

[Selector list](https://developer.mozilla.org/en-US/docs/Web/CSS/Selector_list) `A, B`

Specifies that both `A` and `B` elements are selected. This is a grouping method to select several matching elements.

### [Combinators](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#combinators "Permalink to Combinators")

Combinators are selectors that establish a relationship between two or more simple selectors, such as "`A` is a child of `B`" or "`A` is adjacent to `B`."

[Adjacent sibling combinator](https://developer.mozilla.org/en-US/docs/Web/CSS/Adjacent_sibling_combinator) `A + B`

Specifies that the elements selected by both `A` and `B` have the same parent and that the element selected by `B` immediately follows the element selected by `A` horizontally.

[General sibling combinator](https://developer.mozilla.org/en-US/docs/Web/CSS/General_sibling_combinator) `A ~ B`

Specifies that the elements selected by both `A` and `B` share the same parent and that the element selected by `A` comes before—but not necessarily immediately before—the element selected by `B`.

[Child combinator](https://developer.mozilla.org/en-US/docs/Web/CSS/Child_combinator) `A > B`

Specifies that the element selected by `B` is the direct child of the element selected by `A`.

[Descendant combinator](https://developer.mozilla.org/en-US/docs/Web/CSS/Descendant_combinator) `A B`

Specifies that the element selected by `B` is a descendant of the element selected by `A`, but is not necessarily a direct child.

[Column combinator](https://developer.mozilla.org/en-US/docs/Web/CSS/Column_combinator) `A || B`

Specifies that the element selected by `B` is located within the table column specified by `A`. Elements which span multiple columns are considered to be a member of all of those columns.

### [Pseudo](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#pseudo "Permalink to Pseudo")

[Pseudo classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes) `:`

Specifies a special state of the selected element(s).

[Pseudo elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements) `::`

Represents entities that are not included in HTML.

See also [Selectors in the Selectors Level 4 specification](https://www.w3.org/TR/selectors/#overview).

## [Concepts](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#concepts "Permalink to Concepts")

### [Syntax and semantics](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#syntax_and_semantics "Permalink to Syntax and semantics")

-   [CSS syntax](https://developer.mozilla.org/en-US/docs/Web/CSS/Syntax)
-   [At-rules](https://developer.mozilla.org/en-US/docs/Web/CSS/At-rule)
-   [Cascade](https://developer.mozilla.org/en-US/docs/Web/CSS/Cascade)
-   [Comments](https://developer.mozilla.org/en-US/docs/Web/CSS/Comments)
-   [Descriptor](https://developer.mozilla.org/en-US/docs/Glossary/Descriptor_(CSS))
-   [Inheritance](https://developer.mozilla.org/en-US/docs/Web/CSS/inheritance)
-   [Shorthand properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Shorthand_properties)
-   [Specificity](https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity)
-   [Value definition syntax](https://developer.mozilla.org/en-US/docs/Web/CSS/Value_definition_syntax)
-   [CSS unit and value types](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Values_and_Units)
-   [CSS functional notations](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions)

### [Values](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#values "Permalink to Values")

-   [Actual value](https://developer.mozilla.org/en-US/docs/Web/CSS/actual_value)
-   [Computed value](https://developer.mozilla.org/en-US/docs/Web/CSS/computed_value)
-   [Initial value](https://developer.mozilla.org/en-US/docs/Web/CSS/initial_value)
-   [Resolved value](https://developer.mozilla.org/en-US/docs/Web/CSS/resolved_value)
-   [Specified value](https://developer.mozilla.org/en-US/docs/Web/CSS/specified_value)
-   [Used value](https://developer.mozilla.org/en-US/docs/Web/CSS/used_value)

### [Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#layout "Permalink to Layout")

-   [Block formatting context](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Block_formatting_context)
-   [Box model](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model)
-   [Containing block](https://developer.mozilla.org/en-US/docs/Web/CSS/Containing_block)
-   [Layout mode](https://developer.mozilla.org/en-US/docs/Web/CSS/Layout_mode)
-   [Margin collapsing](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Mastering_margin_collapsing)
-   [Replaced elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Replaced_element)
-   [Stacking context](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Positioning/Understanding_z_index/The_stacking_context)
-   [Visual formatting model](https://developer.mozilla.org/en-US/docs/Web/CSS/Visual_formatting_model)

## [DOM-CSS / CSSOM](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#dom-css_cssom "Permalink to DOM-CSS / CSSOM")

### [Major object types](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#major_object_types "Permalink to Major object types")

-   [`Document.styleSheets`](https://developer.mozilla.org/en-US/docs/Web/API/Document/styleSheets)
-   `[styleSheets](https://developer.mozilla.org/en-US/docs/Web/API/StyleSheetList "styleSheets")[i].[cssRules](https://developer.mozilla.org/en-US/docs/Web/API/CSSRuleList "cssRules")`
-   `cssRules[i].[cssText](https://developer.mozilla.org/en-US/docs/Web/API/CSSRule/cssText "cssText")` (selector & style)
-   `cssRules[i].[selectorText](https://developer.mozilla.org/en-US/docs/Web/API/CSSStyleRule/selectorText "selectorText")`
-   [`HTMLElement.style`](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/style)
-   `HTMLElement.style.[cssText](https://developer.mozilla.org/en-US/docs/Web/API/CSSStyleDeclaration/cssText "cssText")` (just style)
-   [`Element.className`](https://developer.mozilla.org/en-US/docs/Web/API/Element/className)
-   [`Element.classList`](https://developer.mozilla.org/en-US/docs/Web/API/Element/classList)

### [Important methods](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#important_methods "Permalink to Important methods")

-   [`CSSStyleSheet.insertRule()`](https://developer.mozilla.org/en-US/docs/Web/API/CSSStyleSheet/insertRule)
-   [`CSSStyleSheet.deleteRule()`](https://developer.mozilla.org/en-US/docs/Web/API/CSSStyleSheet/deleteRule)

## [See also](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#see_also "Permalink to See also")

-   [Mozilla CSS extensions](https://developer.mozilla.org/en-US/docs/Web/CSS/Mozilla_Extensions) (prefixed with `-moz-`)
-   [WebKit CSS extensions](https://developer.mozilla.org/en-US/docs/Web/CSS/WebKit_Extensions) (mostly prefixed with `-webkit-`)
-   [Microsoft CSS extensions](https://developer.mozilla.org/en-US/docs/Web/CSS/Microsoft_Extensions) (prefixed with `-ms-`)