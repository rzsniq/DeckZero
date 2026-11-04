# DeckZero

Transforma um celular ou tablet (até um aparelho antigo) num painel de atalhos para o PC, no estilo de uma "stream deck", sem comprar nada.

Criado por: @116matheus

## O que ele faz

- Botões de mídia: play/pause, próxima, volume, mudo
- Abre sites, programas e atalhos de teclado do Windows
- Medidores ao vivo de CPU, placa de vídeo, RAM e temperatura (se ajusta a qualquer PC)
- Mixer de volume por programa
- Touchpad e espelho da tela do PC
- Histórico da área de transferência
- Controle de RGB (via OpenRGB)
- Editar os ícones direto no celular: mover, excluir e adicionar
- Conectar lendo um QR code

## Como instalar

Baixe os dois arquivos na página de [Releases](../../releases/latest).

**No PC (Windows 10/11)**

1. Baixe o `DeckZero.exe` e coloque numa pasta só dele (ex.: `Documentos\DeckZero`).
2. Abra. Se aparecer "O Windows protegeu o computador", clique em **Mais informações → Executar assim mesmo** (o programa não tem assinatura paga).
3. A janela mostra um endereço e um QR code. Ao minimizar, ele fica no ícone perto do relógio.

**No celular ou tablet (Android 4.1 ou mais novo)**

1. Baixe e instale o `DeckZero.apk` (o Android vai pedir para permitir instalar de fontes desconhecidas).
2. Abra o app e toque em **LER QR CODE DO PC**, apontando para o QR code da janela do PC.

O PC e o aparelho precisam estar no **mesmo Wi-Fi**.

## Segurança

O QR code e o endereço levam o **código de acesso** do seu PC. Quem tiver esse código, na mesma rede, consegue controlar o PC. Não mostre nem mande para ninguém que não deveria.

## RGB

Para controlar as luzes RGB, instale o [OpenRGB](https://openrgb.org) e ligue o **SDK Server** nele. O DeckZero controla tudo que o OpenRGB reconhecer.
