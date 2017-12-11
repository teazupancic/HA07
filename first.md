1.Welche verschiedenen Layout-Arten gibt es? Was sind die Unterschiede?

Festes Layout:
-Bei einem festen Layout sind die Dimensionen in der Einheit Pixel angegeben
-Eine dynamische Anpassung des Layouts für unterschiedliche Geräte ist nicht möglich

Flüssiges und elastisches Layout:
-Ein fluides oder flüssiges Layout wird in Prozenten des Viewportdefiniert
-Ändert sich die Größe des Viewport, ändern sich auch die Dimensionen des Layouts
-Bei einem elastischen Layout werden die Breitenangaben in der Einheit em angegeben, die sich auf die Schriftgröße bezieht

Adaptives Layout:
-Das adaptive Layout ist ein festes Layout, welches in mehreren Versionen existiert und sich bei Änderung des Viewport anpasst

Responsive Layout:
Das responsive Layout vereint die Eigenschaften des adaptiven und des flüssigen Layouts

2.Worauf beziehen sich Prozentangaben? Finden Sie heraus, worauf sich Prozentangaben bei margin-left, margin-top, height, font-size und border-top-width beziehen (z.B. im MDN).

margin-left:10%  --> margin beginnt 10% von links, wenn 100% die gesamte Breite ist.

margin.top:20% --> Der Prozentsatz wird in Bezug auf die Breite des umschließenden Blocks der generierten Box berechnet. (gleich)

height:10% --> div .boxes elternelement (150px), height 10% von 150 px.

font-size --> default 16px = 100%

top-border-width:500% --> bleibt gleich??!!

3.Was ist die Einheit em und was ist der Unterschied zur Einheit rem?
Während em relativ zur Schriftgröße seines direkten oder nächsten Elternteils ist, ist rem nur relativ zur html (root) font-size.

4.Was bedeuten die Einheiten vw und vh?
vw: 1/100th viewport width
vh: 1/100th viewport height
