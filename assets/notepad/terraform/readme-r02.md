Se integró un Servidor de Calidad RedHat 8.0: SRVC0001, como nodo agente Jenkins. Este nodo tiene la función de ejecutar proyectos terraform. Visita el proyecto en Github: <a href="https://github.com/jurgennikolai/tf_jenkins_aws_instance" target="_blank"><u>https://github.com/jurgennikolai/tf_jenkins_aws_instance</u></a>.<br>
Al realizar un commit en el repositorio Github, automáticamente es reconocido por el Servidor Jenkins quien monitorea este cada cierto tiempo. Así mismo, una vez hecho el cambio procede a realizar los siguientes pasos: <br \>
<b> 1) </b> Jenkins procede a detectar los cambios en el repositorio. <br>
<img src="assets\notepad\terraform\terraform-r02-01.jpg" class="w-full" /><br>
<b> 2) </b>Al encontrarse en el paso de realizar el Apply, Jenkins solicitará confirmación. <br>
<img src="assets\notepad\terraform\terraform-r02-02.jpg" class="w-full" /><br>
<b> 3) </b>Una vez aplicado, se procederá generar la instancia en AWS.<br>
<img src="assets\notepad\terraform\terraform-r02-03.jpg" class="w-full" /><br>
<b> 4) </b>Así mismo, como paso final es realizar el Destroy en Terraform, el cual Jenkins tambien solicitará confirmación.<br>
<img src="assets\notepad\terraform\terraform-r02-04.jpg" class="w-full" /><br>
Finalmente, el panorama general de los pasos realizados por Jenkins sería: <br>
<img src="assets\notepad\terraform\terraform-r02-05.jpg" class="w-full" /><br>
<img src="assets\notepad\terraform\terraform-r02-06.jpg" class="w-full" /><br>