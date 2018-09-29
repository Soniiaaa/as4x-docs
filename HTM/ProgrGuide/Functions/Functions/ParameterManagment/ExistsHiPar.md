<html>
<head>
<title>ExistsHiPar</title>
</head>

<body>

<p><strong><font size="4" face="Arial">Функция ExistsHiPar</font></strong></p>

<p class="label"><font face="Arial">Возвращает признак существования 
параметра с заданным идентификатором на указанную дату.</font></p>

<p class="label"><font face="Arial">Возвращаемое значение логическое.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><strong>ExistsHiPar</strong>(<em>sParId, dDate, 
bSoftGet</em>)</font></p>

<p><font face="Arial">Синтаксис функции <strong>ExistsHiPar</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr vAlign="top">
    <td width="29%"><em><font face="Arial">sParId</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор параметра</font></td>
  </tr>
</TBODY>
  <tr>
    <td width="29%"><em><font face="Arial">dDate</font></em></td>
    <td width="71%"><font face="Arial">выражение типа даты, 
	указывающее на дату изменения параметра</font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">bSoftGet</font></em></td>
    <td width="71%"><font face="Arial">логическое выражение, 
	определяющее признак мягкого поиска параметра. Если <em>bSoftGet = </em>
	True, то проводится поиск по последней имеющейся дате, а если <em>bSoftGet = </em>
	False, то проводится точный поиск параметра по указанной дате.</font></td>
  </tr>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Примечание</b></font></p>

<p class="label"><a href="../../../functions.html"><font face="Arial">
См. также</font></a></p>
</body>
</html>