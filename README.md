🐋 Desafio Full Cycle - Módulo Docker: Desafio Go

📝 Instruções Esse desafio é muito empolgante principalmente se você nunca trabalhou com a linguagem Go!
Você terá que publicar uma imagem no docker hub. Quando executarmos:
docker run <seu-user>/fullcycle
Temos que ter o seguinte resultado: Full Cycle Rocks!!
Se você perceber, essa imagem apenas realiza um print da mensagem como resultado final, logo, vale a pena dar uma conferida no próprio site da Go Lang para aprender como fazer um "olá mundo".
Lembrando que a Go Lang possui imagens oficiais prontas, vale a pena consultar o Docker Hub.
3) A imagem de nosso projeto Go precisa ter menos de 2MB =)
Dica: No vídeo de introdução sobre o Docker quando falamos sobre o sistema de arquivos em camadas, apresento uma imagem "raiz", talvez seja uma boa utilizá-la.
Suba o projeto em um repositório Git remoto e coloque o link da imagem que subiu no Docker Hub.
Compartilhe o link do repositório do Git remoto para corrigirmos seu projeto.
Divirta-se!


🚀 Tecnologias 
Docker 
Golang

🔥Como executar o projeto Executar:
docker build -t <name>/fullcycle . vai gerar a imagem  
docker run --rm <name>/fullcycle

🐋 Link Docker Hub
https://hub.docker.com/repository/docker/leandroabreuferreira/fullcycle
