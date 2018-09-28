﻿<html>
<head>
<title>Job Definition</title>
<style type="text/css">
.style1 {
	font-style: normal;
}
</style>
</head>

<body>

<p><strong><font size="4" face="Arial">Описание задания</font></strong></p>

<p class="label"><font face="Arial">Описывается задание.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><strong>JOB </strong> { <strong>&nbsp;Name</strong> = <em>
sJobName</em>;<br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>&nbsp; <strong>&nbsp;Caption</strong> 
= <em>sJobCaption</em>;<br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>&nbsp; <strong>&nbsp;ECaption</strong> 
= <em>sJobECaption</em>;<br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>&nbsp; <strong>&nbsp;Description</strong> 
= <em>sJobDescription</em>;<br><strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>&nbsp; <strong>&nbsp;Version</strong> 
= <em>nVersion</em>;<br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>&nbsp; <strong>&nbsp;Type</strong> =
<em>nJobType</em>;<br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>&nbsp; <strong>&nbsp;SourceModule</strong> 
= <em>sScriptModule</em>;<br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>&nbsp; <strong>&nbsp;Start</strong> = <em>
sStartProcedure</em>;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>ValidateParams</strong> =
    <em>jobValidateParams</em><br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>&nbsp; <strong>&nbsp;InitArray </strong>
= <em>
sInitArray</em>;<br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>&nbsp; <strong>&nbsp;DoForArrayElement</strong> 
= <em>
sDoForArrayElement</em>;<br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>&nbsp; <strong>&nbsp;ArrayElementDecs </strong>
= <em>
sArrayElementDecs</em>;<br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>&nbsp; <strong>&nbsp;SysID </strong>= <em>
sSysID</em>;<br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>&nbsp; <strong>&nbsp;Param</strong> 
{<strong>Name </strong>= <em>sParamName</em>1;<strong> Caption </strong>= <em>
sParamCaption</em>1;<strong> Type</strong>=<em>sParamType</em>1;};<br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>&nbsp; <strong>&nbsp;. . . . .</strong><br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>&nbsp; <strong>&nbsp;Param</strong> 
{<strong>Name </strong>= <em>sParamName</em>N;<strong> Caption </strong>= <em>
sParamCaption</em>N;<strong> Type</strong>=<em>sParamType</em>N;};<br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>&nbsp;};<br>
<br>
Синтаксис описания задания состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows" height="608">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%" height="18"><font face="Arial"><b>
	Параметр</b></font></td>
    <td class="label" width="71%" height="18"><font face="Arial"><strong>
	Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%" height="18"><font face="Arial"><em>sJobName</em></font></td>
    <td width="71%" height="18"><font face="Arial">строковое 
	выражение, определяющее идентификатор задания.</font></td>
  </tr>
  <tr>
    <td width="29%" height="36"><font face="Arial"><em>sJobCaption</em></font></td>
    <td width="71%" height="36"><font face="Arial">строковое 
	выражение, определяющее наименование-заголовок<br>
    задания.</font></td>
  </tr>
    <tr>
    <td width="29%" height="36"><font face="Arial"><em>sJobECaption</em></font></td>
    <td width="71%" height="36"><font face="Arial">строковое 
	выражение, определяющее наименование-заголовок<br>
    задания на иностранном языке.</font></td>
    </tr>
  <tr>
    <td width="29%" height="36"><font face="Arial"><em>sJobDescription</em></font></td>
    <td width="71%" height="36"><font face="Arial">строковое выражение, 
	определяющее описание
    задания.</font></td>
  </tr>
  <tr>
    <td width="29%" height="18"><em><font face="Arial">nVersion</font></em></td>
    <td width="71%" height="18"><font face="Arial">численное 
	выражение, определяющее номер версии описания задания.</font></td>
  </tr>
  <tr>
    <td width="29%" height="18"><font face="Arial"><em>nJobType</em></font></td>
    <td width="71%" height="18"><font face="Arial">численное 
	выражение, определяющее тип задания.<br>
    При значении<br>
    1&nbsp; - вызывается функция<span lang="ru">:</span> <span lang="ru"><strong><em>
	<br>
	Function</em></strong></span> </font><em><font face="Arial">
	sStartProcedure(<strong><span style="font-size: 12.0pt; font-family: &quot;Arial Armenian&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: EN-US; mso-fareast-language: EN-US; mso-bidi-language: AR-SA; mso-bidi-font-weight: bold" class="style1">ByVal</span><span style="font-size:12.0pt;font-family:
&quot;Arial Armenian&quot;,&quot;sans-serif&quot;;mso-fareast-font-family:&quot;Times New Roman&quot;;
mso-ansi-language:EN-US;mso-fareast-language:EN-US;mso-bidi-language:AR-SA;
font-weight:normal;mso-bidi-font-weight:bold"> </span></strong>
	<span style="font-size: 12.0pt; font-family: &quot;Arial Armenian&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: EN-US; mso-fareast-language: EN-US; mso-bidi-language: AR-SA; mso-bidi-font-weight: bold">
	Params</span><strong><span style="font-size:12.0pt;font-family:
&quot;Arial Armenian&quot;,&quot;sans-serif&quot;;mso-fareast-font-family:&quot;Times New Roman&quot;;
mso-ansi-language:EN-US;mso-fareast-language:EN-US;mso-bidi-language:AR-SA;
font-weight:normal;mso-bidi-font-weight:bold"> </span></strong>
	<span style="font-size: 12.0pt; font-family: &quot;Arial Armenian&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: EN-US; mso-fareast-language: EN-US; mso-bidi-language: AR-SA; mso-bidi-font-weight: bold">
	<strong>As Dictionary,</strong></span><strong><span style="font-size:12.0pt;font-family:
&quot;Arial Armenian&quot;,&quot;sans-serif&quot;;mso-fareast-font-family:&quot;Times New Roman&quot;;
mso-ansi-language:EN-US;mso-fareast-language:EN-US;mso-bidi-language:AR-SA;
font-weight:normal;mso-bidi-font-weight:bold"> </span></strong></em><strong>
	<span style="font-size: 12.0pt; font-family: &quot;Arial Armenian&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: EN-US; mso-fareast-language: EN-US; mso-bidi-language: AR-SA; mso-bidi-font-weight: bold">
	ByRef </span><em>
	<span style="font-size:12.0pt;font-family:
&quot;Arial Armenian&quot;,&quot;sans-serif&quot;;mso-fareast-font-family:&quot;Times New Roman&quot;;
mso-ansi-language:EN-US;mso-fareast-language:EN-US;mso-bidi-language:AR-SA;
font-weight:normal;mso-bidi-font-weight:bold">bCancel <span lang="ru">&nbsp;</span></span></em><span style="font-size: 12.0pt; font-family: &quot;Arial Armenian&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: EN-US; mso-fareast-language: EN-US; mso-bidi-language: AR-SA; mso-bidi-font-weight: bold">As 
	Boolean</span></strong><em>)<span lang="ru"> <strong><span class="style1">As</span>
	</strong></span></em><span lang="ru"><strong>
	<span style="font-size: 12.0pt; font-family: &quot;Arial Armenian&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: EN-US; mso-fareast-language: EN-US; mso-bidi-language: AR-SA; mso-bidi-font-weight: bold">
	AsRepViewer</span></strong><em> </em></span><em>;
	<br>
    </em>
    </font><font face="Arial">&nbsp;&nbsp;&nbsp; Параметр </font><em><font face="Arial">
	Cancel
    </font></em><font face="Arial">обеспечивает</font><em style="font-style: normal"><font face="Arial"> 
	остановку всех заданий.<br>
    </font></em><font face="Arial">2&nbsp; - вызывается процедура </font><em><font face="Arial">
    sInitArray(Params,VarArray)</font></em><font face="Arial">, а 
	потом -</font><em><font face="Arial"> </font></em><font face="Arial"> <em>
    sDoForArrayElement</em></font><em><font face="Arial">(Params,VarArrayElement)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    <br>
    </font></em><font face="Arial">3&nbsp; - вызывается процедура
    </font><em><font face="Arial">sSysID(...);</font></em></td>
  </tr>
    <tr>
    <td width="29%" height="36"><font face="Arial"><em>jobValidateParams</em></font></td>
    <td width="71%" height="36"><font face="Arial">строковое 
	выражение, определяющее идентификатор функции, которая выполняет проверку 
        передаваемых&nbsp; параметров.</font></td>
    </tr>
  <tr>
    <td width="29%" height="54"><em><font face="Arial">sScriptModule</font></em></td>
    <td width="71%" height="54"><font face="Arial">строковое 
	выражение, определяющее идентификатор модуля, где хранятся скриптовые 
	процедуры задания. Данный модуль уже должен существовать в системе и <a href="Module.html">
	заранее описан</a>.</font></td>
  </tr>
  <tr>
    <td width="29%" height="36"><em><font face="Arial">sStartProcedure</font></em></td>
    <td width="71%" height="36"><font face="Arial">строковое 
	выражение, определяющее идентификатор стартовой функции при <em>nJobType
    </em>=1, которая выполняется при запуске задания.</font></td>
  </tr>
</TBODY>
  <tr>
    <td width="29%" height="54"><font face="Arial"> <em>sInitArray</em></font></td>
    <td width="71%" height="54"><font face="Arial">строковое 
	выражение, определяющее идентификатор процедуры инициализации массива при
    <em>nJobType </em>=2, которая выполняется при запуске задания.</font></td>
  </tr>
  <tr>
    <td width="29%" height="18"><font face="Arial"> <em>
    sDoForArrayElement</em></font></td>
    <td width="71%" height="18"><font face="Arial">строковое 
	выражение, определяющее идентификатор процедуры выполняющей действие для 
	каждого элемента массива при <em>nJobType </em>=2, которая выполняется после 
	запуска процедуры инициализации массива.</font></td>
  </tr>
  <tr>
    <td width="29%" height="19"><font face="Arial"> <em>
    sArrayElementDecs</em></font></td>
    <td width="71%" height="19"><font face="Arial">строковое 
	выражение, определяющее идентификатор процедуры, которая возвращает код и 
	наименование для каждого элемента массива при <em>nJobType </em>=2.</font></td>
  </tr>
<tr>
    <td width="29%" height="19"><font face="Arial"> <em>sSysID</em></font></td>
    <td width="71%" height="19"><font face="Arial">строковое 
	выражение, определяющее идентификатор системной функции при <em>nJobType
    </em>=3, которая выполняется при запуске задания.</font></td>
  </tr>
  <tr>
    <td width="29%" height="18"><em><font face="Arial">sParamName</font></em></td>
    <td width="71%" height="18"><font face="Arial">строковое 
	выражение, определяющее идентификатор параметра.</font></td>
  </tr>
  <tr>
    <td width="29%" height="18"><em><font face="Arial">sParamCaption</font></em></td>
    <td width="71%" height="18"><font face="Arial">строковое 
	выражение, определяющее наименование параметра.</font></td>
  </tr>
  <tr>
    <td width="29%" height="18"><em><font face="Arial">sParamType</font></em></td>
    <td width="71%" height="18"><font face="Arial">строковое 
	выражение, определяющее <a href="../types.html">внутренний тип</a> параметра.</font></td>
  </tr>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Примечание</b></font></p>

<p class="label"><font
face="Arial"><a href="../Defs.html">См. также</a></font></p>
</body>
</html>