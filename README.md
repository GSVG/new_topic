# new_topic
training

<!DOCTYPE html> 
<HTML> 
        <HEAD> 
            <META charset="utf-8"> 
            <TITLE>Оформление таблицы с данными</TITLE> 
			<STYLE type="text/css">
			table{
				border-collapse:collapse;
			}
			th, td{ 
				border-bottom: 2px dotted #6F676C;
				border-right: 2px dotted #6F676C;
				padding: 3px;
			}
			th:nth-last-child(1), td:nth-last-child(1){ border-right:none; }
			
		/*	tr:first-child>th:nth-child(6){
				border-right:none;
			}
			tr:nth-child(n+1)>td:nth-child(6){
				border-right:none;
			}
		*/	
			tr:nth-child(n+2)>th{
				text-align:left;
			}
			tr:nth-child(odd){
				background-color:#ccc; 
			}
			tr:nth-child(even){
				background-color:#fff; 
			}
			tr:first-child{                       
				background-color: #777; 
				color: #fff; 
			}
			tr:nth-child(n+1):hover{  
				font:italic 1.1em Arial;
				background-color:#868585;
				cursor:pointer;
			}
			caption {                     
				caption-side: bottom;		  /*переносим caption в низ таблицы*/ 
				text-shadow:0 0 1px #aaa; 		/*задаем размер, цвет, тень ...*/
				font-variant: small-caps; 		/*и изменяем стиль текста*/
			}
			</STYLE>	
        </HEAD> 
        <BODY>
			<table>
				<caption>ДАННЫЕ О СОТРУДНИКАХ</caption>
 				 <tr>
					 <th>ФИО</th>
					 <th>пол</th> 
					 <th>должность</th>
					 <th>дата рож.</th>
					 <th>Данные 01</th>
					 <th>Данные 02</th>
				 </tr>
				 <tr>
					 <th>Иванов Иван Иванович</th>
					 <td>М</td> 
					 <td>начальник</td>
					 <td>01.01.1960</td>
					 <td>4567</td>
					 <td>3453</td>
				 </tr>
				 <tr>
					 <th>Петрова Илонна Петровна</th>
					 <td>Ж</td> 
					 <td>секретарь</td>
					 <td>01.01.1989</td>
					 <td>98795</td>
					 <td>46523</td>
				 </tr>
				 <tr>
					 <th>Сидоров Илья Игоревич</th>
					 <td>М</td> 
					 <td>бухгалтер</td>
					 <td>01.01.1979</td>
					 <td>743434</td>
					 <td>987979</td>
				 </tr>
				 <tr>
					 <th>Пупин Фёдор Фёдорович</th>
					 <td>М</td> 
					 <td>водитель</td>
					 <td>01.01.1963</td>
					 <td>74323434</td>
					 <td>9232379</td>
				 </tr>
				 <tr>
					 <th>Крупин Сергей Иванович</th>
					 <td>М</td> 
					 <td>водитель 2</td>
					 <td>01.01.1983</td>
					 <td>3234534</td>
					 <td>923123379</td>
				</tr>
			 </table>
        </BODY> 
</HTML> 
