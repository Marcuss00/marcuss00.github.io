<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Page Title</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <link rel='stylesheet' type='text/css' media='screen' href='main.css'>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Dosis&display=swap" rel="stylesheet">

</head>
    <style>*{
     font-family: 'Dosis', sans-serif;

}
 body{
     height: 100vh;
     display: grid;
     justify-content: center;
     align-items: center;
     font-size: 17px;
 }
table {
     
     border-collapse: collapse;
     box-shadow: 2px 5px 10px 2px ;
     overflow: hidden;
     text-align: center;
     
}
thead{
     box-shadow: 0 5px 10px;
     
}

th {
     border-collapse: collapse;
     padding:7px 14px 7px ;
     letter-spacing: 0.7rem ;
    
}
td{
     padding:5px 10px 7px ;
}
.name{
    
     box-shadow: 1.2px 1.2px 1.2px 1.2px grey;
}
.name:hover{
    
     box-shadow: 1.2px 1.2px 1.2px 1.2px rgb(214, 208, 208) inset;
}
    </style>

<body> 
    <table>
        <thead >
            <tr id="data" class="data">
                <th style="text-align: left;" ><td>Name </td></th>
                <th style="text-align: left;"><td>Roll No. </td></th>
                <th style="text-align: left;"><td>Marks</td></th>
            </tr>
        </thead>

        <tbody id="data00" > <tr class="data" id="data01" >
                <th><td  ><p class="name">abhishek </p>  </td></th>
                <th><td>1101</td></th>
                <th><td>99 </td></th>
            </tr>

            <tr id="data02" class="data">
                <th><td > <p class="name">ajay</p>  </td></th>
                <th><td>1102</td></th>
                <th><td>98 </td></th>
            </tr>

            <tr id="data03" class="data">
                <th><td ><p class="name"> bunty </p> </td></th>
                <th><td>1103</td></th>
                <th><td>98 </td></th>
            </tr>

            <tr id="data04" class="data">
                <th><td><p class="name"> Gulshan </p> </td></th>
                <th><td>1104</td></th>
                <th><td>97 </td></th>
            </tr>

            <tr id="data05" class="data">
                <th><td><p class="name">karan </p></td></th>
                <th><td>1105 </td></th>
                <th><td>96 </td></th>
            </tr>

           <tr id="data06" class="data">
                <th><td> <p class="name">komal </p> </td></th>
                <th><td>1106</td></th>
                <th><td>95 </td></th>
            </tr>
            
                <tr id="data07" class="data">
               <th><td><p class="name"> neeraj</p> </td></th>
                <th><td>1107</td></th>
                <th class="data"><td>94 </td></th>
                </tr>


             <tr id="data08" class="data"> 
                <th><td> <p class="name">priyanka </p> </td></th>
                <th><td>1108</td></th>
                <th><td>93 </td></th> 
            </tr>
        </tbody>
       <tfoot id="data09">
           <tr>
     <th>
         <td colspan="5" style = "text-align:center"> good day </td>
     </th>
    </tr>
       </tfoot>
    </table>
</body>
</html>
