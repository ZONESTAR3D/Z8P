[USER_GUIDE]: https://downgit.github.io/#/home?url=https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2
[INSTALLATION_GUIDE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide/readme.md
[INSTALL_VIDEO]: https://youtu.be/-oieO7U0LCc
[IMG_ACSWITCH]: https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/1-Installation_Guide/pic/selectAC.png
[POWER_ON]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#power-on
[VIDEO_POWER_ON]: https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/pic/PowerOn.gif
[LCD_MENU]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/DWIN_LCD_screen_Menu_Description
[LEVEL_BED]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#level-the-bed
[XYZ_CUBE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/3-TestGcode/xyz_cube.zip
[LOAD_FILAMENT]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#load-filaments
[M4_4CTEST]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/3-TestGcode/M4_4CTest.zip
[SLICING_GUIDE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme.md
[AUTOTEST_VIDEO]: https://youtu.be/iSsuy2ePWw8
[ADVANCE_FEATURES]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#advance-features
[Z8P_FAQ]: (https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ)

----
## <a id="choose-language">:globe_with_meridians: Choose language </a>
[![](./lanpic/EN.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step.md)
[![](./lanpic/ES.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-es.md)
[![](./lanpic/PT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-pt.md)
[![](./lanpic/FR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-fr.md)
[![](./lanpic/DE.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-de.md)
[![](./lanpic/IT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-it.md)
[![](./lanpic/RU.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-ru.md)
[![](./lanpic/JP.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-jp.md)
[![](./lanpic/KR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-kr.md)
<!-- [![](./lanpic/SA.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-ar.md) -->

----
# Guia passo a passo Z8P-MK2
Se você é iniciante em impressoras 3D e tem tanta documentação para ler, talvez não saiba por onde começar. Não se preocupe, entraremos nos detalhes desses documentos a seguir, passo a passo.    
Em uma palavra, o que você precisa fazer inclui as 4 etapas abaixo: **Instalar a máquina >> Imprimindo arquivo de teste >> Fatiando seu próprio arquivo 3D >> Imprimindo seu arquivo 3D**.    
Primeiramente, recomendamos que você [:arrow_down: **baixe todos os documentos**][USER_GUIDE] e salve-os em seu computador, e adicione esta página web aos favoritos do seu navegador.

## <a id="step1">Etapa 1. Instale a máquina e a fiação </a>
- **Instalação**. Consulte o [:book: **guia de instalação**][INSTALLATION_GUIDE] e [:clapper: **tutorial em vídeo de instalação**][INSTALL_VIDEO] para instalar a máquina.
- **Fiação**. O processo de fiação consiste basicamente em inserir o plugue na tomada correspondente. O que você precisa prestar atenção é garantir que o plugue esteja totalmente inserido na tomada. Principalmente para aqueles soquetes 2PIN que às vezes fazem mau contato.:warning: Ao conectar a cabeça de impressão (montagem hotend), consulte as imagens no guia de instalação com atenção e preste atenção para distinguir a cor dos conectores e a cor dos fios.

## <a id="step2">Etapa 2. Ligue o maiche e faça um teste simples e verifique </a>
- **Ligar**. Antes de ligar a alimentação CA, verifique se a configuração da chave seletora da fonte de alimentação 110V/220V está na posição correta ([**consulte esta imagem**][IMG_ACSWITCH]). E então você pode [**ligar a máquina**][POWER_ON]. :warning: observe que a máquina possui 2 interruptores de alimentação, um é o ***interruptor AC*** (o interruptor vermelho na parte traseira da caixa de controle, próximo à tomada de alimentação CA) e o outro é o ***interruptor DC ***(um botão redondo de metal no lado direito da caixa de controle), você precisa ligar o interruptor CA primeiro e depois pressionar e **manter pressionado o interruptor CC por cerca de 5 segundos** (solte até que o parafuso LCD mostre o LOGOTIPO ZONESTAR) para ligar a máquina.
- **Simplesmente teste**. Depois de ligar, você pode operar o menu na tela LCD ([**Descrição do menu LCD**][LCD_MENU]) para verificar se a máquina pode funcionar normalmente, seguindo as etapas abaixo:
   - **Preparar>>Auto Home>>Home All**. Esta etapa serve para fazer com que o cabeçote de impressão da máquina retorne à posição de origem.
   - **Preparar>>Temperatura>>Pré-aquecer PLA**. Esta etapa é verificar se a extremidade quente e se a cama quente pode ser aquecida normalmente. Nesta etapa, quando a temperatura do bico ultrapassar 60 graus, você deverá ver um ventilador no **lado direito** do cabeçote de impressão (hot end) girando, esse ventilador é chamado de "ventilador de resfriamento do hot end".
   - **Preparar>>Temperatura>>VENTILADOR**. Pressione o botão e definindo a velocidade do ventilador para 255, o ventilador no **lado esquerdo para cima** deve girar.
     Após realizar as 3 etapas acima, é basicamente determinado que a máquina está funcionando normalmente, você pode prosseguir com as etapas a seguir. Se você achar que alguma peça não está funcionando corretamente, verifique novamente a fiação ou faça um "teste automático eletrônico" para verificar. (consulte [:clapper: **turorial de vídeo de teste automático da máquina**][AUTOTEST_VIDEO]).

## <a id="step3">Etapa 3. Nivele a cama </a>
[![](https://img.youtube.com/vi/R3RfGnxx8hY/0.jpg)](https://www.youtube.com/watch?v=R3RfGnxx8hY)     
Antes de imprimir o arquivo de teste, é necessário fazer um simples nivelamento da base para definir a altura entre o bico e a base (plataforma de impressão), para que o filamento possa ficar bem colado na base durante a impressão. Consulte [**nivelar a cama**][LEVEL_BED] para fazer isso.

## <a id="step4"> Etapa 4. Imprimir modelo 3D de teste </a>
As impressoras FDM 3D só podem reconhecer arquivos gcode, precisamos copiar os arquivos gcode para o cartão SD e depois inserir o cartão SD na ranhura para cartões SD da impressora 3D e depois operar a tela LCD para começar a imprimir.
:warning: Incluso se você estiver familiarizado com as impressoras 3D, recomendamos imprimir pelo menos um modelo de teste de 4 cores para confirmar se a máquina funciona normalmente.
- **4.1 Imprimir um arquivo de teste de cor**    
[![](https://img.youtube.com/vi/ITHbO9VxTMo/0.jpg)](https://www.youtube.com/watch?v=ITHbO9VxTMo)
    - **Preparar arquivo gcode**. [:arrow_down: **descargue o arquivo zip xyz_cube**][XYZ_CUBE], descomprímalo no PC e depois copie o **xyz_cube.gcode** para o cartão SD. Conecte a tarjeta SD ao conector SD da máquina.
    - **Cargar filamento**. Consulte [:book: **aquí**][LOAD_FILAMENT] para carregar os 4 filamentos nas extrusoras e no hot end.
      ***:warning: para o hotend M4V6, você deve carregar 4 fios no hotend, mesmo imprimindo impressões em 3D de uma única cor.***
    - **Imprimir da tarjeta SD**. Mueva o elemento para o elemento **Imprimir** na tela LCD, clique no botão e elimine o arquivo **xyz_cube.gcode**, clique no botão para começar a imprimir.
    - **Ajuste a altura da boquilha**. Espere que a boquilla e a cama estejam quentes e observe a distância da boquilla até a cama para imprimir a primeira capa. Se você estiver muito gruesa ou muito perto, clique duas vezes na barra da tela LCD para abrir um menu **"babystep"** e depois gire a barra para ajustar com precisão a distância da boquilha até a cama.
    - **Esperar terminar a impressão**.

- **4.2 Imprimir um arquivo de teste de 4 cores**    
[![](https://img.youtube.com/vi/CA8pWOuJYmE/0.jpg)](https://www.youtube.com/watch?v=CA8pWOuJYmE)
    - **Preparar arquivo gcode**. [:arrow_down: **descargue o arquivo zip M4_4CTest**][M4_4CTEST] e descomprímalo no PC, e depois copie o **M4_4CTest.gcode** para a placa SD. Conecte a tarjeta SD ao conector SD da máquina.
    - **Filamentos de Cargar**. Consulte [:book: **aquí**][LOAD_FILAMENT] para carregar os 4 filamentos nas extrusoras e na extremidade quente.
    - **Imprimir da tarjeta SD**. Mueva o elemento para o elemento **Imprimir** na tela LCD, clique no perigo e elimine o arquivo **M4_4CTest.gcode**, clique no perigo para começar a imprimir.
    - **Ajuste a altura da boquilha**. Espere que a boquilla e a cama estejam quentes e observe a distância da boquilla até a cama para imprimir a primeira capa. Se você estiver muito gruesa ou muito perto, clique duas vezes na barra da tela LCD para abrir um menu **"babystep"** e depois gire a barra para ajustar com precisão a distância da boquilha até a cama.
    - **Esperar terminar a impressão**.

## <a id="step5">Etapa 5. Cortar seu próprio modelo 3D </a>
- Antes de imprimir seus próprios modelos 3D, você precisa converter o arquivo do modelo 3D (um arquivo de formato stl/obj/AMF que [descargou da Internet](#download) ou foi criado usando o mesmo) para um arquivo gcode, guarde este arquivo gcode à tarjeta SD e depois conecte a tarjeta SD à sua impressora 3D.     
    :pushpin: **O processo de conversão de um modelo 3D em um arquivo gcode se chama *rebanado***.
- Em primeiro lugar, você deve baixar o software de corte e instalá-lo em seu computador, configurar os parâmetros de sua máquina no software de corte ou carregar o arquivo pré-estável de sua máquina configurada pelo fabricante da impressora 3D.     
- Em seguida, você deve executar o software de corte e é possível que você também defina alguma configuração de corte de acordo com os recursos de seu arquivo de modelo 3D e depois execute o corte.     
    :pushpin: O software de corte recomendado é **PrusaSlicer**. Para saber como baixar, instalar e usar o **PrusaSlicer**, consulte o [***Guia de corte***][SLICING_GUIDE].

## <a id="step6">Etapa 6. Imprima seu próprio modelo 3D </a>
Depois de cortá-lo, copie o arquivo gcode gerado no cartão SD e depois imprima seguindo o [**paso 4**](#step4).

## <a id="step7">Etapa 7. Para usar funções avançadas </a>
Depois de compreender completamente todas as operações básicas, você poderá testar algumas funções avançadas desta máquina.
Para obter mais informações, consulte o [**Guia de uso de funções avançadas**][ADVANCE_FEATURES].

----
#### <a id="download"> :page_with_curl: sites famosos de download gratuito de modelos 3D </a>
  - [thingiverse](https://www.thingiverse.com/)  
  - [printables](https://www.printables.com/)  
  - [youmagine](https://www.youmagine.com/)   

----
