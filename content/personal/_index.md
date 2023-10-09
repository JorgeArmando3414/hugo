+++
title = 'Personal'
date = 2023-09-25T09:38:19+02:00
draft = false
mermaidInitialize = "{ \"theme\": \"dark\" }"
mermaidZoom = true
+++

## Attachments

{{% attachments sort="asc" title="ficheros" style="green" icon="fas fa-star"/%}}

## Badge

{{% badge style="green" icon="fas fa-syringe" %}}Prueba{{% /badge %}}
{{% badge color="black" icon="fas fa-theater-masks" title="Prueba" %}}Prueba{{% /badge %}}
{{< badge style="tip" color="blue" >}}{{% icon heart %}}{{< /badge >}}
{{< badge style="warning" >}}{{% icon skull-crossbones %}}{{< /badge >}}

## Button

{{% button href="" color="fuchsia" icon="fa-brands fa-tiktok" iconposition="right" %}}**Prueba**{{% /button %}}
{{% button href="" icon="download" %}}{{% /button %}}

## Expand

{{% expand title="Expandeme..." %}}...................................................................................................{{% /expand %}}
{{% expand title="Expand me..." open="true" %}}No need to press you!{{% /expand %}}

## Icon

{{% icon icon="exclamation-triangle" %}}
{{% icon icon="angle-double-up" %}}
{{% icon icon="skull-crossbones" %}}

## Include

Inlude incluye otros archivos .md dentro de la pagina actual, pueden contener lenguaje markdown y sera tenido en cuenta al cargar el contenido de la pagina.

## Math

{{< math align="right" >}}
$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$
{{< /math >}}

```math
$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$
```

## Mermaid

```mermaid { align="center" zoom="true" }
graph LR;
    If --> Then
    Then --> Else
```

{{< mermaid >}}
---
title: Example Diagram
---
graph LR;
    A[Hard edge] -->|Link text| B(Round edge)
    B --> C{<strong>Decision</strong>}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]
{{< /mermaid >}}

## Notice

{{% notice style="primary" title="There may be pirates" icon="skull-crossbones" %}}
It is all about the boxes.
{{% /notice %}}

{{% notice style="warning" title="Here are dragons" icon="dragon" %}}
A **warning** disclaimer
{{% /notice %}}

## Tab

{{% tab title="c" %}}
```c
printf("Hello World!");
```
{{% /tab %}}

{{% tab title="_**Mixed**_" %}}
A tab can not only contain code but arbitrary text. In this case text **and** code will get a margin.
```python
printf("Hello World!");
```
{{% /tab %}}

## Highlight

{{< highlight lineNos="true" lineNoStart="1" type="py" hl_lines="3 5" title="python">}}
# the hardest part is to start writing code; here's a kickstart; just copy and paste this; it's free; the next lines will cost you serious credits
print("Hello")
print(" ")
print("World")
print("!")
{{< /highlight >}}