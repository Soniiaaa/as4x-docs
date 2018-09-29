<html>
<head>
<title>Диалог\AddPage</title>
</head>

<body>

<p><strong><font size="4" face="Arial">Метод AddPage<br>
<br>
</font></strong><font face="Arial"><a href="../Asustpar.html">См. также</a>&nbsp;
<a href="../../Examples/E_AsUstPar.html">Пример</a>&nbsp; <a href="../Asustpar.html">
Применяется к</a></font></p>

<p><font face="Arial">Добавляет страницу в пользовательский диалог.</font></p>

<p>&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><strong>call</strong> <em>object</em>.<strong>AddPage(</strong><em>sCaption,
</em>[<em>sECaption</em>]<strong>)</strong></font></p>

<p><font face="Arial">Синтаксис метода <strong>AddPage</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">object</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее переменную, ссылающуюся на экземпляр объекта пользовательского 
	диалога.</font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">sCaption</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее заголовок добавляемой страницы в диалоге.</font></td>
  </tr>
</TBODY>
  <tr>
    <td width="29%"><font face="Arial"><em>sECaption</em></font></td>
    <td width="71%"><font face="Arial">необязательное строковое 
	выражение, определяющее заголовок добавляемой страницы в диалоге на 
	иностранном языке.</font></td>
  </tr>
  </table>

<p>&nbsp;</p>

<p class="label"><font face="Arial"><b>Примечание</b></font></p>

<p class="label"><font face="Arial">После добавления страницы каждый 
новый реквезит добавляется к этой странице. Если диалог имеет только одну 
страницу, то можно добавлять реквезиты без вызова данного метода. </font></p>

</body>
</html>