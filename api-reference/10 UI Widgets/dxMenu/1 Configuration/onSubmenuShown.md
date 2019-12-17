---
id: dxMenu.Options.onSubmenuShown
type: function(e)
default: null
EventForAction: dxMenu.submenuShown
---
---
##### shortDescription
A function that is executed after a submenu is displayed.

##### param(e): Object
Information about the event.

##### field(e.component): {WidgetName}
The widget's instance.

##### field(e.element): dxElement
#include common-ref-elementparam with { element: "widget" }

##### field(e.model): Object
The model data. Available only if Knockout is used.

##### field(e.rootItem): dxElement
#include common-ref-elementparam with { element: "root menu element" }

---