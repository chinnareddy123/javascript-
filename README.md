# javascript-
var $table  =  $('<table></table>');

for(int i=0;i<1000;i++)
{
    console.log("received broadcast: " + msg + ", " + msg.data[i]);
    var $tr =  $('<tr></tr>');
    var $td =  $('<td></td>');
    $td.append(msg.data[i]);
    $tr.append($td);
    $table.append($tr);
}

$('div#target').empty().append($table);                         
#this will fill the table inside the element-.  
<div id="target"></div>
