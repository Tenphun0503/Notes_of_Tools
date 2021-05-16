# Markdown Syntax

The most of content are learned from [Markdown-Tutorial](https://github.com/luong-komorebi/Markdown-Tutorial)

This Title is written as `# Markdown Syntax`

There are six sizes of Headers `#, ##, ###, ####, #####, ######` 

----------------------------------------------------------------------------------------------------------------
#### The Content of This Page
1. [Some Common Syntax](#somecommonsytax)
2. [Use of Table](#useoftable)
3. [Use of Enter and Space](#useofenterandspace)
4. [Some Other Uses](#someotheruses)

<div id = 'somecommonsytax'/>

-----------------------------------------------------------------------------------------------------------------
#### Some Common Syntax (This is a H4)
|Syntax                 |Effect                 |
|-----------------------|-----------------------|
|`*Italic*`             |*Italic*               |
|`**Bold**`             |**Bold**               |
|`~Strike through~`     |~Strike thorugh~       |
|``Code``               |`print('Hello World')` |
|`[text](url)`          |[My main page](https://github.com/Tenphun0503)|
|`![img](url)`          |![tingImg](https://github.com/Tenphun0503/ToolsNotes/blob/main/Markdown/tinyImg.png) Click the img|
|`[![img](urlImg)](url)`|[![tingImg](https://github.com/Tenphun0503/ToolsNotes/blob/main/Markdown/tinyImg.png)](https://github.com/Tenphun0503) Click again,it's different|

<div id = 'useoftable'/>

-----------------------------------------------------------------------------------------------------------------

#### Use of Table
```
|Syntax                 |Effect                 |
|-----------------------|-----------------------|
|`*Italic*`             |*Italic*               |
|`**Bold**`             |**Bold**               |
|`~Strike through~`     |~Strike thorugh~       | 
```

Effect shows as above, or we can use html table
```
<table>
    <tr>
        <td>Syntax
        <td>Effect
    <tr>
        <td>`*Italic*`
        <td>*Italic*
</table>
```
Effect shows as:  
<table>
    <tr>
        <td>Numer
        <td>Name
    <tr>
        <td>1
        <td>Joe
    <tr>
        <td>2
        <td>Eva
</table>

<div id = 'useofenterandspace'/>

-----------------------------------------------------------------------------------------------------------------
#### Use of Enter and Space
```
The form follows as below:  
input 
output
```

`line1 'enter' line2`  
line1
line2

`line1 'enter' 'enter' line2`  
line1

line2

`line1 'space' 'space' 'enter' line2`  
line1  
line2

<div id = 'someotheruses'/>

------------------------------------------------------------------------------------------------------------------
#### Some Other Uses  
`* unorder list`
* item1
* item2

`1. order list`
1. item1
2. item2

`> Quote`
> No pain No gain

Use  \` to insert Code  
Use \`\`\` to insert a code block  
Use at least three - or * to draw a line

--------------------------------------------------------------------------------------------------------------------
