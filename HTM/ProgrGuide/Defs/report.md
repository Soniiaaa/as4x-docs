﻿<html>
<head>
<title>Report Definition</title>
</head>

<body>

<p><strong><font size="4" face="Arial">Описание отчета</font></strong></p>

<p class="label"><font face="Arial">Описывается отчет.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><strong>REPORT</strong> { <strong>Name</strong> 
= <em>sReportName</em>;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>Caption</strong> = <em>sReportCaption</em>;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>ECaption</strong> = <em>sReportECaption</em>;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>Version</strong> = <em>nVersion</em>;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>Start</strong> = <em>sStartProcedure</em>;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>SourceModule</strong> = <em>sScriptModule</em>;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; };<br>
<br>
Синтаксис описания отчета состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sReportName</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор отчета</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sReportCaption</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее наименование-заголовок<br>
    отчета</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sReportECaption</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее наименование-заголовок<br>
    отчета на иностранном языке</font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">nVersion</font></em></td>
    <td width="71%"><font face="Arial">численное выражение, 
	определяющее номер версии описания отчета</font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">sStartProcedure</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор стартовой процедуры, которая выполняется первой 
	при запуске отчета</font></td>
  </tr>
</TBODY>
  <tr>
    <td width="29%"><em><font face="Arial">sScriptModule</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор модуля, где хранятся скриптовые процедуры отчета. 
	Данный модуль уже должен существовать в системе и <a href="Module.html">
	заранее описан</a>.</font></td>
  </tr>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Примечание</b></font></p>

<p class="label"><a href="../Functions/Functions/SysDefManagment/RunReport.html"><font
face="Arial">См. также</font></a></p>
</body>
</html>