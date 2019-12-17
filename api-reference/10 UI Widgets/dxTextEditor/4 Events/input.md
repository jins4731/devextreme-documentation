---
id: dxTextEditor.input
type: eventType
---
---
##### shortDescription
Raised each time the widget's input is changed while the widget is focused.

##### param(e): Object
Information about the event.

##### field(e.component): {WidgetName}
The widget's instance.

##### field(e.element): dxElement
#include common-ref-elementparam with { element: "widget" }

##### field(e.event): event
#include common-ref-eventparam

##### field(e.jQueryEvent).deprecated
Use 'event' instead.

##### field(e.jQueryEvent): jQuery.Event
The jQuery event that caused the handler execution. Deprecated in favor of the **event** field.

##### field(e.model): Object
The model data. Available only if Knockout is used.

---
Main article: [onInput](/api-reference/10%20UI%20Widgets/dxTextEditor/1%20Configuration/onInput.md '{basewidgetpath}/Configuration/#onInput')

#####See Also#####
#include common-link-handleevents