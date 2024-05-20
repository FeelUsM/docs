# h1
## h2
### h3
#### h4
##### h5
###### h6
####### h7

*italic*  
_italic_  
**bold**  
__bold__  
**bold *italic***  
__bold *italic*__  
**bold _italic_**  
__bold _italic___  
*italic **bold***  
_italic **bold**_  
*italic __bold__*  
_italic __bold___  

x<sub>i</sub>  
x<sup>i</sup>

> quote
>

`code`

```
code
code
code
```

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> 111

<table>
  <tr>
    <td rowspan="2">One</td>
    <td>Two</td>
  </tr>
  <tr>
    <td >four</td>
  </tr>
  <tr>
    <td colspan="2">Three</td>
  </tr>
</table>


```stl
solid cube_corner
  facet normal 0 -1 0
    outer loop
      vertex 0 0 0
      vertex 1 0 0
      vertex 0 0 1
    endloop
  endfacet
  facet normal 0 0 -1
    outer loop
      vertex 0 0 0
      vertex 0 1 0
      vertex 1 0 0
    endloop
  endfacet
  facet normal -1 0 0
    outer loop
      vertex 0 0 0
      vertex 0 0 1
      vertex 0 1 0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1 0 0
      vertex 0 1 0
      vertex 0 0 1
    endloop
  endfacet
endsolid
```

The background color is `#ffffff` for light mode and `#000000` for dark mode.
