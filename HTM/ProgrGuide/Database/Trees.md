﻿<html>
<head>
<title>Таблица TREES</title>
</head>

<body>

<h1><font size="4" face="Arial">Таблица TREES</font></h1>

<p><font face="Arial">Таблицa всех деревьев и простых классификаторов.<br>
</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="20%"><font face="Arial"><b>Поле</b></font></td>
    <td class="label" width="20%"><font face="Arial"><strong>Тип 
	данных</strong></font></td>
    <td class="label" width="20%"><strong><font face="Arial">Null</font></strong></td>
    <td class="label" width="40%"><strong><font face="Arial">Описание</font></strong></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fTREEID</font></td>
    <td width="20%"><font face="Arial">char (8)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">идентификатор дерева</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fCODE</font></td>
    <td width="20%"><font face="Arial">char (20)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">код элемента данного дерева</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fNAME</font></td>
    <td width="20%"><font face="Arial">varchar (50)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">наименование элемента дерева</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fCODX</font></td>
    <td width="20%"><font face="Arial">varchar (255)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">путь место элемента в дереве</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fLEAF</font></td>
    <td width="20%"><font face="Arial">char (1)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">признак лепестка элемента. 
	Значение 1 означает, что элемент дерева является лепестком (конечным 
	элементом дерева). Значение 0 означает, что данный элемент в &nbsp; дереве 
	является узловым. </font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fPARENT</font></td>
    <td width="20%"><font face="Arial">char (20)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">код элемента родителя, для 
	корня Null</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fISN</font></td>
    <td width="20%"><font face="Arial">int</font></td>
    <td width="20%"><font face="Arial">NULL</font></td>
    <td width="40%"><font face="Arial">ISN документа элемента дерева. 
	Если узел дерева не является документом, тогда данный атрибут содержит 
	значение -1.</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fENAME</font></td>
    <td width="20%"><font face="Arial">varchar (50)</font></td>
    <td width="20%"><font face="Arial">NULL</font></td>
    <td width="40%"><font face="Arial">иностранное наименование 
	элемента дерева</font></td>
  </tr>
</TBODY>
  <tr>
    <td width="20%"><font face="Arial">fDOCTYPE</font></td>
    <td width="20%"><font face="Arial">char(8)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">идентификатор документа 
	элемента дерева. Если узел дерева не является документом, тогда данный 
	атрибут содержит значение &quot;&quot;.</font></td>
  </tr>
</table>

<p class="label"><font face="Arial"><b><br>
Индекс</b></font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
  <tr vAlign="top">
    <td class="label" width="33%"><font face="Arial"><b>Имя индекса</b></font></td>
    <td class="label" width="33%"><font face="Arial"><strong>Тип </strong></font></td>
    <td class="label" width="33%"><strong><font face="Arial">Имя 
	столбцов</font></strong></td>
  </tr>
  <tr>
    <td width="33%"><font face="Arial">iTREES1</font></td>
    <td width="33%"><font face="Arial">UNIQUE, <br>
    CLUSTERED</font></td>
    <td width="33%"><font face="Arial">fTREEID, fCODE</font></td>
  </tr>
  <tr>
    <td width="33%"><font face="Arial">iTREES2</font></td>
    <td width="33%"><font face="Arial">UNIQUE</font></td>
    <td width="33%"><font face="Arial">fTREEID, fCODX</font></td>
  </tr>
  <tr>
    <td width="33%"><font face="Arial">iTREES3</font></td>
    <td width="33%">&nbsp;</td>
    <td width="33%"><font face="Arial">fTREEID, fPARENT</font></td>
  </tr>
  <tr>
    <td width="33%"><font face="Arial">iTREES4</font></td>
    <td width="33%">&nbsp;</td>
    <td width="33%"><font face="Arial">fISN, fTREEID</font></td>
  </tr>
</table>

<p class="label"><font face="Arial"><b><br>
<br>
Примечание</b></font></p>

<p class="label"><a href="database_scheme.html"><font face="Arial">См. 
также</font></a></p>
</body>
</html>