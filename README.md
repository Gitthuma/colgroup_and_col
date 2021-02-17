Active learning: colgroup and col

Using colgroup and col in a table

1. First, make a local copy of our timetable.html file in a new directory on your local machine. The HTML contains the same table you saw above, minus the column styling information.

2. Add a &lt;colgroup&gt; element at the top of the table, just underneath the &lt;table&gt; tag, in which you can add your &lt;col&gt; elements (see the remaining steps below).

3. The first two columns need to be left unstyled.

4. Add a background color to the third column. The value for your style attribute is background-color:#97DB9A;

5. Set a separate width on the fourth column. The value for your style attribute is width: 42px;

6. Add a background color to the fifth column. The value for your style attribute is background-color: #97DB9A;

7. Add a different background color plus a border to the sixth column, to signify that this is a special day and she's teaching a new class. The values for your style attribute are background-color:#DCC48E; border:4px solid #C1437A;

8. The last two days are free days, so just set them to no background color but a set width; the value for the style attribute is width: 42px;

Live web: https://gitthuma.github.io/colgroup_and_col/
