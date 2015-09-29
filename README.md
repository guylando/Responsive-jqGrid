# Responsive-jqGrid
A little css that helps to turn your jqgrid to be more responsive.

The problem with layouts using tables tags is that the columns in the same row can't wrap to another row.
Thus its much better to use <div>s as table layout instead of <table> as shown here:
https://github.com/free-jqgrid/jqGrid/wiki/Redesign-of-the-structure-of-Navigator-Bar-of-the-pagers
But unfortunately some of the pagers components in jqgrid use <table> for layout and its complicated
to change jqgrid code now to <div>s so a workaround is that we will add scrollbars when the 
navigation table components overflow.
