﻿<html>
<head>
<title>Таблица DOCP</title>
</head>

<body>

<h1><font size="4" face="Arial">Таблица DOCP</font></h1>

<p><font face="Arial">Таблицa хранения отношений типа потомок-предок 
для документов.<br>
</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="20%"><font face="Arial"><b>Поле</b></font></td>
    <td class="label" width="20%"><font face="Arial"><strong>Тип 
	данных</strong></font></td>
    <td class="label" width="20%"><font face="Arial"><strong>Null</strong></font></td>
    <td class="label" width="40%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fISN</font></td>
    <td width="20%"><font face="Arial">int</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">идентификационный номер 
	документа</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fNAME</font></td>
    <td width="20%"><font face="Arial">char(8)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">тип документа</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fPARENTISN</font></td>
    <td width="20%"><font face="Arial">int</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">идентификационный номер 
	документа родителя</font></td>
  </tr>
	<tr>
    <td width="20%"><font face="Arial">fDCD</font></td>
    <td width="20%"><font face="Arial">datetime</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">дата создания документа</font></td>
  </tr>
</TBODY>
</table>

<p class="label"><font face="Arial"><b><br>
Индекс</b></font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
  <tr vAlign="top">
    <td class="label" width="33%"><font face="Arial"><b>Имя индекса</b></font></td>
    <td class="label" width="33%"><font face="Arial"><strong>Тип </strong></font></td>
    <td class="label" width="33%"><font face="Arial"><strong>Имя 
	столбцов</strong></font></td>
  </tr>
  <tr>
    <td width="33%"><font face="Arial">iDOCP1</font></td>
    <td width="33%"><font face="Arial">UNIQUE,&nbsp; CLUSTERED</font></td>
    <td width="33%"><font face="Arial">fISN, fPARENTISN</font></td>
  </tr>
  <tr>
    <td width="33%"><font face="Arial">iDOCP2</font></td>
    <td width="33%">&nbsp;</td>
    <td width="33%"><font face="Arial">fPARENTISN, fISN</font></td>
  </tr>
</table>

<p class="label"><font face="Arial"><b><br>
Примечание</b></font></p>

<p class="label"><font face="Arial"><a href="database_scheme.html">См. 
также</a></font></p>
</body>
</html>