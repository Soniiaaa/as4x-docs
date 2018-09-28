﻿<html>
<head>
<title>Таблица NOTIFICATIONS</title>
</head>

<body>

<h1><font size="4" face="Arial">Таблица NOTIFICATIONS</font></h1>

<p><font face="Arial">Таблицa хранения оповещений.<br>
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
    <td width="20%"><font face="Arial">fNID</font></td>
    <td width="20%"><font face="Arial">uniqueidentifier</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">идентификатор оповещения</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fSENDER</font></td>
    <td width="20%"><font face="Arial">smallint</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">идентификатор 
	пользователя-отправителя</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fBODY</font></td>
    <td width="20%"><font face="Arial">varchar (255)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">текст оповещения</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fCREATED</font></td>
    <td width="20%"><font face="Arial">datetime</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">дата создания и отправки 
	оповещения</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fEXPIRE</font></td>
    <td width="20%"><font face="Arial">datetime</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">дата уничтожения оповещения</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fCOLOR</font></td>
    <td width="20%"><font face="Arial">int</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">цвет оповещения</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fISN</font></td>
    <td width="20%"><font face="Arial">int</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">ISN документа, который 
	прикреплен к оповещению. По умолчанию принимает значение -1 (нет 
	прикрепленных документов).&nbsp;</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fMODE</font></td>
    <td width="20%"><font face="Arial">tinyint</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">состояние документа, который 
	прикреплен к оповещению&nbsp;</font></td>
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
    <td width="33%"><font face="Arial">iNOTIFICATIONS1</font></td>
    <td width="33%"><font face="Arial">UNIQUE,&nbsp; CLUSTERED</font></td>
    <td width="33%"><font face="Arial">fNID</font></td>
  </tr>
  <tr>
    <td width="33%"><font face="Arial">iNOTIFICATIONS2</font></td>
    <td width="33%">NOT CLUSTERED</td>
    <td width="33%"><font face="Arial">fEXPIRE</font></td>
  </tr>
</table>

<p class="label"><font face="Arial"><b><br>
<br>
Примечание</b></font></p>

<p class="label"><font face="Arial"><a href="database_scheme.html">См. 
также</a></font></p>
</body>
</html>