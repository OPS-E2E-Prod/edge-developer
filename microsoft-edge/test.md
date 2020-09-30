# Test

## Basic markdown

### Bold

**Bold** Text

### Italic

*Italic* Text

### Numbered list 

1. item1
2. item2
3. item3

### Bulleted list 

- item1
- item2
- item3

### Checklist

- [ ] item1
- [ ] item2
- [x] item3

### Table 

| a     | b     |
--      | --
| 0     | 1
| 2     | 3     |
| 4     | 5 

### Link

[A](a.md)  
https://google.com

### Headings

Heading 1
======

Heading 2
--------

### Heading 3

### Heading 4

### Heading 5

### Heading 6

## Alert

> [!important]
> This is a warning containing some important message.asdasddasda

> [!note]
> This is a note which needs your attention, but it's not super important.

> [!tip]
> This is a note which needs your attention, but it's not super important.

> [!warning]
> This is a warning containing some important message

> [!Caution]
> This is a warning containing some important message.

## Code snippets

[!code-csharp[Main](test.cs)]

## Inclusion

[!include[title](test-include.md)]

## Tabbed conceptual

Tab group 1:

### [Tab Text 1](#tab/tabid-1)

Tab content-1-1.

### [Tab Text 2](#tab/tabid-2)

Tab content-2-1.

***

## Video (QuoteNoteSection)

> [!Video https://www.youtube.com/embed/TAaG0nUUy6A]

## Xref

[link_text](xref:test-uid)

## Images with border and lightbox

> [!div class="mx-imgBorder"]
> [![Image](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/media/active-directory-groups-view-azure-portal/groups-all-groups-blade-with-all-groups.png)](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/media/active-directory-groups-view-azure-portal/groups-all-groups-blade-with-all-groups.png#lightbox)

## Data matrix

## Code

```md
# heading

[Link](a.md)
```

```javascript
var as = 1;

var asdafsdadfaasdf
```

```powershell
New-Item -Path . -Name "testfile1.txt" -ItemType "file" -Value "This is a text string."
```

## HTML

<div class="NOTE">
  <h5>NOTE</h5>
  <p>note content</p>
</div>
<div class="WARNING">
  <h5>WARNING</h5>
  <p>WARNING content</p>
</div>

## Triple Colon

### ChromelessForm

::: form model="./devsandbox/ChromelessFormsTest.md" action="create-resource" submitText="Do it" :::

### Code

:::code source="test.cs" language="csharp":::

### Columns + Row

:::row:::
    :::column:::
        This is where your content goes.
    :::column-end:::
    :::column span="3":::
        This is where your content goes.
    :::column-end:::
:::row-end:::

### Image

:::image type="content" source="https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/media/active-directory-groups-view-azure-portal/groups-all-groups-blade-with-all-groups.png" alt-text=""example"":::

### Noloc

使用 :::no-loc text="Find"::: 方法.

### Video

:::video source="https://channel9.msdn.com/Shows/XamarinShow/Build-Your-First-Android-App-with-Visual-Studio-2019-and-Xamarin/player?nocookie=true" title="Video: Build-Your-First-Android-App-with-Visual-Studio-2019-and-Xamarin" max-width="400" upload-date="07/27/2020":::

### Zone

::: zone pivot="windows"
    hello
::: zone-end

### moniker Zone

## Section definition

> [!div class="tabbedCodeSnippets" data-resources="OutlookServices.Calendar"]
> ```cs
> cs code text
> ```
> ```javascript
> js code text
> ```