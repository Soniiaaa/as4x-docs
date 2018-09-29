<html>
<head>
<title>CreateDataDesc</title>
</head>

<body>

<h1><font size="4" face="Arial">Функция CreateDataDesc<br>
</font><a href="../../AsDataDesc.html">
    <font face="Arial" size="3">
        <strong>
            свойства&nbsp;&nbsp; методы
        </strong>
    </font>
</a></h1>

<p><font face="Arial">Создает объект типа динамический источник данных. Данная 
    функция служит для создания динамических данных, значения которых не сохраняются в базе данных.</font></p>

<p>&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><strong>set</strong> <em>sDynDataDesc</em><strong> 
= CreateDataDesc</strong></font></p>

<p><font face="Arial">Синтаксис функции <strong>CreateDataDesc</strong></b>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr vAlign="top">
    <td width="29%"><em><font face="Arial">sDynDataName</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее переменную, ссылающуюся на экземпляр объекта динамического источника данных.</font></td>
  </tr>
</table>

<p>&nbsp;</p>

<p class="label"><font face="Arial"><b>Примечание</b></font></p>

<p class="label"><a href="../../../constructors.html"><font face="Arial">
См. также</font></a></p>

<p class="label">&nbsp;</p>

<p><strong><font face="Arial" size="3">Пример функции </font><font
face="Arial">Create</font><font face="Arial" size="3">Dialog</font></strong></p>

<p><font face="Arial">В примере вызывается функция CreateDataDesc, через 
sDynDataDesc возвращается ссылка на обьект типа динамический источник данных со всеми его свойствами и 
методами. </font></p>

<p><font face="Arial"><br>
Dim sDynDataDesc as AsDataDesc<br>
Dim xView As AsView<br>
Set sDynDataDesc = <strong>CreateDataDesc</strong><br>
sDynDataDesc.<a href="../../AsDataDesc/Caption_DDesc.html">Caption</a> = &quot;DynDescCaption&quot;<br>
sDynDataDesc.<a href="../../AsDataDesc/HeadLinesCount_DDesc.html">HeadLinesCount</a> = 1<br>
sDynDataDesc.<a href="../../AsDataDesc/DataIndicate_DDesc.html">DataIndicate</a> = 1<br>
sDynDataDesc.<a href="../../AsDataDesc/AddColumn_DDesc.html">AddColumn</a>(&quot;fCODE&quot;, &quot;Код&quot;, &quot;Code&quot;, &quot;C(8)&quot;, &quot;fCode&quot;, False, True, True)<br>
sDynDataDesc.<a href="../../AsDataDesc/SQL_DDesc.html">SQL</a> = &quot;Select fCODE from Table&quot;<br>
Set xView  = <strong>CreateDynamicView(sDynDataDesc)</strong><br>
Browse(xView)<br>
</font></p>
</body>
</html>