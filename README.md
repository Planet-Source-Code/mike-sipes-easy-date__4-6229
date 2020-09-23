<div align="center">

## Easy Date


</div>

### Description

VERY simple code to display a nicely formatted date on your web page. (IE - Wednesday, June 14, 2000)
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Mike Sipes](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/mike-sipes.md)
**Level**          |Beginner
**User Rating**    |3.5 (21 globes from 6 users)
**Compatibility**  |ASP \(Active Server Pages\)
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__4-1.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/mike-sipes-easy-date__4-6229/archive/master.zip)





### Source Code

```
<%
 DateToday = WeekdayName(Weekday(Weekday(Date()))) & ", " & MonthName(Month(date())) & " " & Day(Date()) & ", " & Year(Date())
%>
'Place this where you want the date to display:
<%=DateToday%>
```

