# Artigo de curiosidade

É uma página web responsiva hospedada no site fictício chamado **Curiosidades de Tecnologia**. O artigo fala sobre o **Bugdroid** (mascote do Android) explicando a sua história e curiosidades sobre ele.

### Tecnologias utilizadas

- HTML
- CSS

## O que aprendi nesse projeto?

Esse foi o meu primeiro projeto que desenvolvi quando estava no início dos meus estudos de programação. Nele, eu coloquei em prática o que aprendi sobre:
- Manipulação de imagens;
- Responsividade com media queries;
- Estrutura HTML e tags semântica e não semântica;
- Estilização, gradientes e transições simples com CSS;
- Incorporar vídeos na página e adaptá-lo para outros dispositivos;
- UI/UX design básico.

## 🖥️ Como rodar o projeto na sua máquina

### Computador ou notebook

- É preciso de uma IDE e uma extensão que rode o projeto localmente no seu navegador. Recomendo o **VS Code** e sua extensão **Live Server**. Motivo: VS Code é um programa leve e simples de usar, enquanto o Live Server foi criado com essa finalidade.

#### Passo a passo

1. No repositório do projeto, clique em **Code**.
2. Clique em **Download ZIP**. Faça o download no seu desktop.
3. Após a instalação, extraia o arquivo ZIP.
4. Clique com botão direito na pasta extraída.
5. Clique em **Abrir com o Code**.
6. Clique em extensões.
7. Procure por essa extensão:

![](readme/live-server.png)

Em seguida, clique em instalar.

8. Após a instalação, feche a página da **Extensão**.
9. Clique em **Explorador** para voltar.
10. No canto inferior direito, clique em **Go Live**. O projeto abrirá automaticamente no seu navegador.

Para interromper o servidor, clique em `Port: ...` (no mesmo lugar onde você clicou para rodar o projeto).

### Em outros dispositivos

É possível acessar o projeto em outro dispositivo, como um celular, desde que os dispositivos estejam conectados à **mesma rede local**.

1. Com o projeto rodando, observe o número da porta na URL. Por exemplo:

```
http://127.0.0.1:5500/
```

Nesse exemplo, a porta é `5500`.

`127.0.0.1` é o **endereço do localhost** e só pode ser acessado pelo próprio computador.

2. Abra o terminal no seu computador e digite:

```
ipconfig
```

Procure por algo como:

```
Endereço IPv4 . . . . . . . . . . : IP_do_endereço
```

O `IP_do_endereço` é o endereço local do seu computador na rede, você irá usá-lo para acessar o projeto em outro dispositivo.

2. No outro dispositivo, abra o navegador e digite o IP local junto com a porta na barra de endereço.

```
SEU_IP_LOCAL:n°_porta
```

Em seguida, dê enter.

3. Feche o terminal.