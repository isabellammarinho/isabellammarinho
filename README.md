### Hi there, I'm Isabella Marinho🌙

📌 Developer Full Stack Java Jr. |Student at @GenerationBrasil


<div align="center">
  <a href="https://github.com/isabellammarinho">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=isabellammarinho&show_icons=true&theme=jolly&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=isabellammarinho&layout=compact&langs_count=7&theme=jolly"/>
</div>
<div style="display: inline_block"><br>
  <img align="center" alt="Isa-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="Isa-Ts" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg">
  <img align="center" alt="Isa-React" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg">
  <img align="center" alt="Isa-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="Isa-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="Isa-Spring boot" height="30" width="40" src="https://img.icons8.com/color/48/000000/spring-logo.png"/>
  <img align="center" alt="Isa-Spring MySQL" height="30" width="40" src="https://img.icons8.com/ios/50/000000/mysql-logo.png"/>
  
  ##
 
<div> 
  <a href = "mailto:isabellamarcelomarinho@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/isabella-marinho-b75311221/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
 
 ![snake animation](https://github.com/isabellammarinho/isabellammarinho/blob/output/github-contribution-grid-snake.svg)
 
 
</div>
  
  <p align="center"> Hello :) </p>
<p align="center">   <img alingn="center" src="https://profile-counter.glitch.me/isabellammarinho/count.svg" /></p>
  
  <HTML>
	<HEAD><TITLE>Exibir Data e Hora em HTML </TITLE>
		<script src="https://code.jquery.com/jquery-1.11.2.js"></script>
		<script type="text/javascript">
			jQuery(window).load(function($){
				atualizaRelogio();
			});
		</script>
	</HEAD>
	<BODY>
		<div>
			<output id="data" style="font-family: 'arial black', 'avant garde'; font-size: 24px;"></output>
		</div>
		<div>
			<output id="hora" style="font-family: 'arial black', 'avant garde'; font-size: 24px;"></output>				
		</div>			
	</BODY>
	<script>
		function atualizaRelogio(){ 
			var momentoAtual = new Date();
			
			var vhora = momentoAtual.getHours();
			var vminuto = momentoAtual.getMinutes();
			var vsegundo = momentoAtual.getSeconds();
			
			var vdia = momentoAtual.getDate();
			var vmes = momentoAtual.getMonth() + 1;
			var vano = momentoAtual.getFullYear();
			
			if (vdia < 10){ vdia = "0" + vdia;}
			if (vmes < 10){ vmes = "0" + vmes;}
			if (vhora < 10){ vhora = "0" + vhora;}
			if (vminuto < 10){ vminuto = "0" + vminuto;}
			if (vsegundo < 10){ vsegundo = "0" + vsegundo;}

			dataFormat = vdia + " / " + vmes + " / " + vano;
			horaFormat = vhora + " : " + vminuto + " : " + vsegundo;

			document.getElementById("data").innerHTML = dataFormat;
			document.getElementById("hora").innerHTML = horaFormat;

			setTimeout("atualizaRelogio()",1000);
		}
	</script>	
</HTML>
