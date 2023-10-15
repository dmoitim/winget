# winget
A ferramenta de linha de comando winget permite que os usuários descubram, instalem, atualizem, removam e configurem aplicativos em computadores com Windows 10 e Windows 11. Essa ferramenta é a interface do cliente para o serviço Gerenciador de Pacotes do Windows.

Abaixo seguem os comandos para a instalação dos programas que utilizo.

### Para procurar programas
~~~
winget search <nome_do_programa>
~~~

### Para instalar programas
~~~
winget install --id Google.Chrome -h
winget install --id Mozilla.Firefox -h
winget install --id 7zip.7zip -h
winget install --id Zoom.Zoom -h
winget install --id VideoLAN.VLC -h
winget install --id Microsoft.VisualStudioCode -h
winget install --id OpenVPNTechnologies.OpenVPN -h
winget install --id TheDocumentFoundation.LibreOffice -h
winget install --id Git.Git -h
winget install --id TortoiseGit.TortoiseGit -h
winget install --id Oracle.JDK.17 -h
winget install --id Skillbrains.Lightshot -h
winget install --id Docker.DockerDesktop -h
winget install --id Postman.Postman -h
winget install --id OpenJS.NodeJS.LTS -h
~~~

### Para verificar os programas que possuem atualização
~~~
winget upgrade
~~~

### Para atualizar todos os programas
~~~
winget upgrade --all
~~~

### Para atualizar um programa específico
~~~
winget upgrade --id TheDocumentFoundation.LibreOffice
~~~
