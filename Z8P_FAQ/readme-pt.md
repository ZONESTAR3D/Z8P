## <a id="choose-language">:globe_with_meridians: Choose language </a>
[![](./lanpic/EN.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme.md)
[![](./lanpic/ES.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-es.md)
[![](./lanpic/PT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-pt.md)
[![](./lanpic/FR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-fr.md)
[![](./lanpic/DE.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-de.md)
[![](./lanpic/IT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-it.md)
[![](./lanpic/RU.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-ru.md)
[![](./lanpic/JP.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-jp.md)
[![](./lanpic/KR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-kr.md)
[![](./lanpic/SA.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-ar.md)

----
# Solução de problemas do Z8P

-----
## Referência
Para encontrar e resolver o problema do produto, pode ser necessário usar a função de teste automático, abrir a caixa de controle para verificar a fiação ou ajustar a corrente do motor, usar um "teste de troca" para verificar um componente eletrônico, etc. .. Aqui listamos esses guias, fotos e tutoriais em vídeo para sua referência.
### Fiação
- [:art: Como abrir a caixa de controle](./pic/OpenControlBox.png)
- [:art: Fiação na placa de controle](./pic/Z8P_wiring.png)

### Teste automático de peças eletrônicas
Z8P possui um programa de teste automático de eletrônicos integrado. Você pode usar este programa para determinar de onde vem o problema quando qualquer componente eletrônico encontra um problema. Para iniciar este programa, você precisa abrir o menu "**Info**" e girar o botão para apontar para o item "**Data: xx-xx-xx**" e, em seguida, pressionar o botão cinco vezes.
#### Vídeo tutorial
[![](https://img.youtube.com/vi/iSsuy2ePWw8/0.jpg)](https://www.youtube.com/watch?v=iSsuy2ePWw8)

### Sobre "teste de troca"
Quando descobrimos que há um problema funcional na máquina, e a causa do problema tem múltiplas possibilidades (várias peças podem causar o mesmo problema), temos a oportunidade de utilizar o chamado "**teste de troca** " para localizar a causa do problema o mais rápido possível.
Por exemplo, se o motor do eixo Z esquerdo não funcionar, o problema pode vir da fiação, do motor de passo, do cabo do motor, do módulo de acionamento do motor na placa de controle ou da placa de controle. Como existem dois conjuntos de sistemas de acionamento do eixo Z na máquina - sistemas de acionamento Z esquerdo e sistema de acionamento Z direito - que são idênticos, podemos trocar as mesmas peças/componentes/fios nos lados esquerdo e direito, um por um, para confirmar de onde vem o problema.
As peças da máquina que podem realizar o teste de troca incluem:
- Motor X/Y e interruptor de fim de curso.
- Motor ZL/ZR e interruptor de limite
- 4 conjuntos de motores extrusores
- Aquecedor de cartucho e sensor de temperatura da cama quente e hot end.

-----
## Conteúdo
- **[A máquina não pode inicializar](./Issue_of_startup/readme.md)**
<!-- - **[Hot end está bloqueado/obstruído](./Issue_mix_color_hotend_cloged/readme.md)** -->
- **[Problema de aquecimento](./Issue_heating/readme.md)**
- **[Desligamento automático ao imprimir do cartão SD](./Issue_auto_shut_down/readme.md)**
- **[Como corrigir problema de bloqueio da extrusora](./Issue_extruder_blocked/readme.md)**
- **[Como corrigir problema de descarga insuficiente da extrusora](./Issue_of_Extruder_insufficient_discharge/readme.md)**
- **[Falha ao conectar USB no Cura](./issue_of_connect_USB_in_Cura/readme.md)**
- **[A impressora pausa automaticamente ao imprimir do cartão SD](./Issue_auto_pause/readme.md)**
- **[Problema de cartão SD não lido](./Issue_not_read_sdcard/readme.md)**
- **[Problema com botão da tela LCD](#dwinscreen)**

----
## Outras referências
- **[44 problemas comuns de impressão 3D](https://github.com/ZONESTAR3D/Document-and-User-Guide/tree/master/FAQ)**
- **[Todos os problemas e soluções (@All3DP.com)](https://all3dp.com/1/common-3d-printing-problems-troubleshooting-3d-printer-issues/)**

-----
## <a id="dwinscreen">Problema no botão da tela LCD</a>
Se você achar que o botão da tela LCD está preso, você pode clicar em [:gift: this link](https://www.aliexpress.com/item/3256805596235491.html) para comprar um teclado substituto. Se o seu produto estiver dentro do período de garantia (dentro de 12 meses a partir da data de recebimento da embalagem), entre em contato conosco após fazer o pedido e iremos fornecer-lhe um serviço pós-venda.
Como substituir o teclado da tela LCD, assista ao vídeo tutorial:
- Para a versão de soldagem (mais antiga), consulte [:clapper: este vídeo](https://youtu.be/Xwfczp3nLOY).
- Para a versão FPC (mais recente), consulte [:clapper: este vídeo](https://youtu.be/z9E6glRZRIQ).
####
![](./pic/keypad.jpg)

-----
## :email: Se você não conseguir encontrar uma solução para resolver seu problema depois de ler o FAQ, entre em contato com nossa equipe de suporte técnico: support@zonestar3d.com.