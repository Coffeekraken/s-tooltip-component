# STooltipComponent Classes

This file provide the mixins to generate tooltip classes


## Mixins


### s-tooltip-classes

Print out the bare and style tooltip css
Generated classes:
- `.tooltip`
- `.tooltip--tl`
- `.tooltip--t`
- `.tooltip--tr`
- `.tooltip--l`
- `.tooltip--r`
- `.tooltip--bl`
- `.tooltip--b`
- `.tooltip--br`
- `.tooltip--c`
- `.tooltip--{color}`
- `.tooltip--active, .tooltip.active, .tooltip[active], :hover > .tooltip, .active > .tooltip, [active] > .tooltip`


Name  |  Type  |  Description  |  Status  |  Default
------------  |  ------------  |  ------------  |  ------------  |  ------------
$color  |  **{ List<Color> }**  |  The colors to generate  |  optional  |  default primary secondary
$sides  |  **{ List<String> }**  |  The sides to generate  |  optional  |  tl t tr l r bl b br c


### s-tooltip-classes-bare

Print out the bare tooltip css
Generated classed
- `.tooltip`
- `.tooltip--tl`
- `.tooltip--t`
- `.tooltip--tr`
- `.tooltip--l`
- `.tooltip--r`
- `.tooltip--bl`
- `.tooltip--b`
- `.tooltip--br`
- `.tooltip--c`
- `.tooltip.active, .tooltip[active], :hover > .tooltip, .active > .tooltip, [active] > .tooltip`


Name  |  Type  |  Description  |  Status  |  Default
------------  |  ------------  |  ------------  |  ------------  |  ------------
$sides  |  **{ List<String> }**  |  The sides to generate  |  optional  |  tl t tr l r bl b br c


### s-tooltip-classes-style

Print out the style tooltip css
Generated classes:
- `.tooltip`
- `.tooltip--tl`
- `.tooltip--t`
- `.tooltip--tr`
- `.tooltip--l`
- `.tooltip--r`
- `.tooltip--bl`
- `.tooltip--b`
- `.tooltip--br`
- `.tooltip--c`
- `.tooltip--{color}`
- `.tooltip--active, .tooltip.active, .tooltip[active], :hover > .tooltip, .active > .tooltip, [active] > .tooltip`


Name  |  Type  |  Description  |  Status  |  Default
------------  |  ------------  |  ------------  |  ------------  |  ------------
$color  |  **{ List<Color> }**  |  The colors to generate  |  optional  |  default primary secondary
$sides  |  **{ List<String> }**  |  The sides to generate  |  optional  |  tl t tr l r bl b br c