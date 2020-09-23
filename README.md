<div align="center">

## Change text within table cells


</div>

### Description

How do I change text within table cells? The following will only work in MSIE4:

Found at: http://www.irt.org
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Found on the Web](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/found-on-the-web.md)
**Level**          |Unknown
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__2-68.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/found-on-the-web-change-text-within-table-cells__2-212/archive/master.zip)





### Source Code

```
<SCRIPT LANGUAGE="JavaScript">
function myClick3() {
  document.all("ONE").innerText = 'This is table cell ONE';
  document.all("TWO").innerText = 'This is table cell TWO';
}
</SCRIPT>
<TABLE BORDER=1>
<TR><TD ID="ONE">This is the text in ONE</TD></TR>
<TR><TD ID="TWO">This is the text in TWO</TD></TR>
</TABLE>
<FORM><INPUT TYPE="BUTTON" VALUE="Click Me" onClick="myClick3()"></FORM>
```

