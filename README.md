# envmobil

O envmobil, é uma ferramenta simples com o objetivo de facilitar a preparação do ambiente, para teste mobile. Ele permite instalar o frida, fazer download dos frida-server e acessar o ambiente, evitando que alguma biblioteca impacte na utilização de outra ferramenta.
<br>OBS: Se faz necessario o uso do Pyhton3.x e o pip ou pip3

## Utilização

Instalação do ambiente e do frida:<br>
`envmobil -i`

Instalação do ambiente, frida e download do server:<br>
`envmobil -i -d`

Efetuando apenas o download do server:<br>
`envmobil -d`

Acesso rapido<br>
`envmobil -q`

Apenas acessar<br>
`envmobil`

```
Opções:
    -q, --quick       Ativa o ambiente virtual sem exibir mensagens.
    -i, --install     Instala o Frida e baixa os pacotes do frida-server.
    -d, --download    Faz o download dos pacotes do frida-server sem instalar.
    -h, --help        Exibe esta mensagem de ajuda.

    Padrão Path: ~/ENVMOBILE
```
