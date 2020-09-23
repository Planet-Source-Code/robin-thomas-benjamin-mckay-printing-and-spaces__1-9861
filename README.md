<div align="center">

## Printing and spaces


</div>

### Description

The purpose of this article is to introduce the new user to the art of printing quickly and simply.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Robin Thomas Benjamin McKay](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/robin-thomas-benjamin-mckay.md)
**Level**          |Intermediate
**User Rating**    |2.6 (13 globes from 5 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[VB function enhancement](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/vb-function-enhancement__1-25.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/robin-thomas-benjamin-mckay-printing-and-spaces__1-9861/archive/master.zip)





### Source Code

```
Many people believe VB to be a major pain as like other programming languages because they are too tech. So are most things if you think about it for long enough and you're new to it. Anyway, here is a simple way to print in visual basic and also introduce you to a neat printing method. I take no credit for this because it is an article I found elsewhere.
Create a new standard.exe
create two labels
do what you want with the labels. The name and the captions don't matter.
Now, create a button and change its caption to: &Print and its name to cmdPrint.
In the button's code window, type the following code:
Printer.Print label1.caption; spc(30); label2.caption
The above code must all be on 1 line.
Good. You've mastered a simple printing method.
You can, of course, manipulate the printing methods above to print documents in a snazzy manner.
Before End Sub, type the following code:
Printer.Enddoc
This ensures the print job ends as you finish printing. Nice one!
```

