# Multipass
Dicas Multipass dia a dia


<h1>Instalando</h1>
<p>sudo snap install multipass</p>


<h1>Criar</h1>
<p>multipass launch -n k8s -c 2 -m 2G -d 20GB</p>

<h1>Listar</h1>
<p>multipass list</p>

<h1>Conectar</h1>
<p>multipass shell k8s <br>
multipass exec k8s --name --cat teste.txt
</p>

<h1>Montar disco</h1>
<p>multipass mount /home/jean k8s:/externo</p>

<h1>Desmontar disco</h1>
<p>multipass unmount k8s</p>

<h1>Deletar</h1>
<p>multipass delete<br>
multipass purge</p>


<h1>Detalhes VM</h1>
<p>multipass info k8s</p>