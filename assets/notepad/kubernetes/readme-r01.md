Laboratorio implementado sobre VMWare y el Sistema Operativo de Redhat 8.
Este cluster de kubernetes esta bajo el dominio network.com, el nodo master
y los nodos worker estan de la siguiente forma: <br />
*) K8SMASTER => k8smaster.network.com ~ 192.168.1.80 <br />
*) K8SWNODE1 => k8swnode1.network.com ~ 192.168.1.81 <br />
<img src="assets/notepad/kubernetes/kubernetes-r01-01.jpg" class="w-full" />
<br />
La integración y el estado de estos se puede visualizar mediante el comando:
$ kubectl get nodes <br />
<img src="assets/notepad/kubernetes/kubernetes-r01-02.jpg" class="w-full" />