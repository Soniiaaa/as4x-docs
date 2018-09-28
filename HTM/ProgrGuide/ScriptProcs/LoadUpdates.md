﻿<html>
<head>
<title>Системное событие документа LoadUpdates </title>
</head>

<body>

<p><strong><font size="4" face="Arial">Событие LoadUpdates<br>
<br>
</font></strong><font face="Arial">
<a href="Load.html">См. также</a>&nbsp; <u>Пример</u>&nbsp; <a href="../Functions/Asdata.html">
Применяется к</a></font></p>

<p class="label"><font face="Arial">Генерируется если значение 
свойства ArrayBased равно единице и свойство ISN заполнено. Служит для передачи 
ядру данных для обновления объекта источник данных. Событие должно возвратить 
объект типа XArrayDB количество колонок равно количеству колонок в источнике 
данных, а строки соответствуют строкам в источнике данных.</font></p>

<p class="label">&nbsp;</p>
<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial">Function <b>LoadUpdates(</b><i>ByVal lngISN as 
Long</i><b>)</b> As <i>XArrayDB</i><br>
<br>
End Function </font></p>

<p><font face="Arial">Синтаксис функции <b>LoadUpdates </b>состоит из 
следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows" id="table1">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><i>lngISN </i> </font></td>
    <td width="71%"><font face="Arial">численное выражение типа Long, 
	определяющее ISN обновляемых строк(и).</font></td>
  </tr>
  </table>

<p>&nbsp;</p>

</body>
</html>