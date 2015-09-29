# Responsive-jqGrid
A little css that helps turn your jqGrid into a responsive grid.

The problem with layouts using tables tags is that the columns in the same row can't wrap to another row.
Thus its much better to use &lt;div&gt;s as table layout instead of &lt;table&gt; as shown here:
https://github.com/free-jqgrid/jqGrid/wiki/Redesign-of-the-structure-of-Navigator-Bar-of-the-pagers
But unfortunately some of the pagers components in jqgrid use &lt;table&gt; for layout and its complicated
to change jqgrid code now to &lt;div&gt;s so a workaround is that we will add scrollbars when the 
navigation table components overflow.

Note: You must make the styles in this css override your other styles, this can be achieved by inserting those styles in a &lt;style&gt; script in your page or by adding !important to all the css properties in the script.
