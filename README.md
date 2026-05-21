[Aperte aqui para baixar a VM do PnetLab](https://drive.google.com/drive/folders/1h8y6L2dacmzpYOo9l2sSziUeawlDEpuZ?usp=sharing) 

O aluno deve baixar o arquivo disponibilizado no link, e extrair (extraia pelo terminal usando o unzip)

> [!NOTE]
> adapte o caminho para o lugar onde você baixou o arquivo

```
cd Downloads
unzip vm-pnet-zip
```

# Importando o apliance

![passo1](./screenshots/acessar-virtualbox.png)

Clique em Importar

![passo2](./screenshots/escolhendo-ovf)

Escolha o arquivo ´.ova´ e aperte em ´Próximo´

![passo3](./screenshots/importando-apliance.png)

Espere importar o apliance

# Depois de importar o apliance, é necessario fazer alguns ajustes

![passo4](./screenshots/apertar-configuracoes.png)

Vamos gerar novos endereços MAC nos adaptadores, Clique em Configurações>Rede>Adaptador1>Gerar um novo endereço MAC, Faça o mesmo para o adaptador 2 e aperte em ´OK´

![passo5](./screenshots/gerar-novo-mac.png)

Após gerar novos endereços MAC, Inicie a VM do PnetLab, faça login com usuario ´root´ e senha ´pnet´, e aperte a tecla ´enter´ confirmando as etapas (não é preciso alterar nada), Após confirmar tudo a VM irá reiniciar.

Quando a VM iniciar, ela ja pode ser acessada via SSH, e também acessada pelo navegador.

![passo6](./screenshots/acessando-int-web-pnet.png)

![passo7](./screenshots/acessando-lab.png)
![passo8](./screenshots/dentro-lab.png)

Dentro do PnetLab tem 2 cenários, você pode criar mais cenários ou adaptar os cénarios existentes.

