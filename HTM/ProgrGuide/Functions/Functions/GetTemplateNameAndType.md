<html>
<head>
<title>GetTemplateNameAndType</title>
    <style type="text/css">
        .style1 {
            font-family: Arial;
        }
        .style2
        {
            height: 30px;
        }
    </style>
</head>

<body>

<p><font size="4" face="Arial"><strong>Функция GetTemplateNameAndType</strong></font></p>

<p><font face="Arial">Возвращает имя и тип&nbsp; шаблона из строки формата. </font></p>

<p><font face="Arial">Возвращаемый тип&nbsp; значения логическое.</font></p>
    <p>&nbsp;</p>

<p><font face="Arial"><b>Синтаксис</b></font></p>

<p><span class="style1"><strong>GetTemplateNameAndType</strong></span><font face="Arial"><strong>(</strong><em>templateNameWithType, 
    </em>[<em>templateName</em>]<strong>, </strong>&nbsp;[<em>templateType</em>]<strong>, &nbsp;</strong>[<em>backSlash</em><strong>])</strong></font></p>

<p><font face="Arial">Синтаксис функции <strong>GetTemplateNameAndType</strong><span class="style1"><strong>
    </strong></span>состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr vAlign="top">
    <td width="29%"><em><font face="Arial">templateNameWithType</font></em></td>
    <td width="71%"><font face="Arial">обязательное строковое выражение, определяющее 
        строку формата.</font></td>
  </tr>
    <tr>
    <td width="29%" class="style2"><font face="Arial"><em>templateName</em></font></td>
    <td width="71%" class="style2"><font face="Arial">необязательное строковое 
        выражение, определяющее имя возвращаемого шаблона.</font></td>
    </tr>
    <tr>
    <td width="29%"><font face="Arial"><em>templateType</em></font></td>
    <td width="71%"><font face="Arial">необязательное строковое выражение, определяющее 
        тип возвращаемого шаблона. </font></td>
    </tr>
    <tr>
    <td width="29%"><font face="Arial"><em>backSlash</em></font></td>
    <td width="71%"><font face="Arial">необязательное логическое выражение, определяющее 
        разделитель между именем шаблона и его типом в строке формата <em>
        templateNameWithType</em>. По умолчанию принимает значение True. </font></td>
    </tr>
    </table>

    <p>
        &nbsp;</p>
    <p>
        <font face="Arial"><b>Примечание</b></font></p>
    <p>
        <font face="Arial">&nbsp;&nbsp; Строка формата <em>templateNameWithType </em>имеет следующий 
        вид = [ИмяШаблона+Разделитель(&#39;\&#39; или &#39;/&#39;)+ТипШаблона], где разделитель (&#39;\&#39; или 
        &#39;/&#39;) определяется согласно параметру backSlash: Елси backSlash = True, то 
        разделитель = &#39;\&#39;, в противном случае разделитель = &#39;/&#39;.</font></p>
    <p>
        <font face="Arial"><a href="../../functions.html">См. также</a></font></p>

</body>
</html>