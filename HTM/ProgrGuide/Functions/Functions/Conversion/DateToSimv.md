<html>
<head>
<title>DateToSimv</title>
</head>

<body>

<p><strong><font size="4" face="Arial">Функция DateToSimv</font></strong></p>

<p><font face="Arial">Расчитывает и возвращает дату прописью, в виде 
символьной строки.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><strong>DateToSimv</strong>(<em>dtDate</em> [<em>,intLanguage</em>] 
[<em>,intFormat</em>],[<em>,bShowDayYearAsString</em>])</font></p>

<p><font face="Arial">Синтаксис функции <strong>DateToSimv</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr vAlign="top">
    <td width="29%"><font face="Arial"><em>dtDate</em></font></td>
    <td width="71%"><font face="Arial">выражение типа даты, 
	определяющая дату для преобразования<br>
    в представление прописью</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>intLanguage</em></font></td>
    <td width="71%"><font face="Arial">необязательный параметр типа 
	Variant, вариант языка, пока есть армянский (1), русский (2), английский 
	(3). Если не задан, то принимается значение по умолчанию 1 - армянский.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>intFormat</em></font></td>
    <td width="71%"><font face="Arial">необязательный числовой 
	параметр, вариант сокращения возвращаемых наименований месяцев</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>bShowDayYearAsString</em></font></td>
    <td width="71%"><font face="Arial">необязательный логический 
	параметр, признак позаыавать день и год в виде строки (True) или числа 
	(False). Если не задан, то принимается значение по умолчанию False. </font></td>
  </tr>
</TBODY>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Установки</b></font></p>

<p><font face="Arial">Установки для <em>intFormat</em>
следующие:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Значение</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr vAlign="top">
    <td width="29%"><font face="Arial">0</font></td>
    <td width="71%"><font face="Arial">значение по умолчанию, 
	возвращает полные наименования месяцев</font></td>
  </tr>
  <tr vAlign="top">
    <td width="29%"><font face="Arial">&gt;0</font></td>
    <td width="71%"><font face="Arial">наименования месяцев выводить в 
	сокращенном варианте</font></td>
  </tr>
</TBODY>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Примечание</b></font></p>

<p class="label"><font face="Arial">Эту функцию удобно использовать в 
первичных печатных документах.</font></p>

<p class="label"><a href="../../../functions.html"><font face="Arial">
См. также</font></a></p>

<p class="label">&nbsp;</p>

<h1><font size="3" face="Arial"><strong>Пример функции DateToSimv</strong></font></h1>

<p><font face="Arial"><font size="3">Строковая переменная </font>
dDatePrompt получает значение &quot;15 янв 1999г.&quot;</font></p>

<p><font face="Arial">dDatePrompt = <strong>DateToSimv</strong>(&quot;1/15/1999&quot;, 
&quot;2&quot;, 1)<br>
<br>
</font></p>
</body>
</html>