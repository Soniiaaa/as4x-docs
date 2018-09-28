﻿<html>
<head>
<title>Системное событие диалога ValueChanged </title>
</head>

<body>

<p><strong><font size="4" face="Arial">Событие ValueChanged<br>
<br>
</font></strong><font face="Arial"><a href="../scriptstproced.html">См. 
также</a>&nbsp; <u>Пример</u>&nbsp; <a href="../Functions/Asustpar.html">
Применяется к</a></font></p>

<p class="label"><font face="Arial">Генерируется при попытке выхода из 
поля заполнения реквизита. Служит для проверки введенных значений реквизита на 
соответствие некоторому условию.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial">Sub <strong>ValueChanged</strong>(</font><em><font face="Arial">objDialog, 
Cancel, RekvName</font></em><font face="Arial"><i>, oldValue</i>)<br>
<em>&nbsp;&nbsp;&nbsp;&nbsp; statements</em><br>
End Sub</font></p>

<p><font face="Arial">Синтаксис события <strong>ValueChanged
</strong>состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows" height="161">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%" height="18"><font face="Arial"><b>
	Параметр</b></font></td>
    <td class="label" width="71%" height="18"><font face="Arial"><strong>
	Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%" height="36"><em><font face="Arial">objDialog</font></em></td>
    <td width="71%" height="36"><font face="Arial">строковое 
	выражение, определяющее переменную, ссылающуюся на экземпляр объекта 
	пользовательского диалога.</font></td>
  </tr>
  <tr>
    <td width="29%" height="33"><em><font face="Arial">Cancel</font></em></td>
    <td width="71%" height="33"><font face="Arial">необязательная 
	логическая переменная, возвращаюущая признак сохранения фокуса для реквизита <i>
    RekvName</i>. При True - фокус остается на реквизите <i>RekvName</i>, а при 
	False - переходит на следующий реквизит.</font></td>
  </tr>
  <tr>
    <td width="29%" height="9"><em><font face="Arial">RekvName</font></em></td>
    <td width="71%" height="9"><font face="Arial">строковое выражение, 
	определяющее наименование реквизита диалога.</font></td>
  </tr>
  <tr>
    <td width="29%" height="9"><font face="Arial"><i>oldValue</i></font></td>
    <td width="71%" height="9"><font face="Arial">выражение типа 
	Variant, определяющее старое значение реквизита. </font></td>
  </tr>
  </table>

</body>
</html>