## <a id="choose-language">:globe_with_meridians: Choose language </a>
[![](./lanpic/EN.png)](#EN)
[![](./lanpic/ES.png)](#ES)
[![](./lanpic/PT.png)](#PT)
[![](./lanpic/FR.png)](#FR)
[![](./lanpic/DE.png)](#DE)
[![](./lanpic/IT.png)](#IT)
[![](./lanpic/RU.png)](#RU)
[![](./lanpic/JP.png)](#JP)
[![](./lanpic/KR.png)](#KR)
<!-- [![](./lanpic/SA.png)](#arabic) -->

-----
<a id="EN"></a>

# Z8P-MK2 Step-by-Step Guide
If you're a beginner with 3D printers, with so much documentation to read, you might not know where to start. Don't worry, we'll go into the details of these documents next step by step.   
In a word, what you need to do includes the below 4 steps: **Install the machine >> Printing test file >> Slicing your own 3d file >> Printing your 3d file**.        
First at all, we recommend that you [:arrow_down: **download all the documents**][USER_GUIDE] and save them to your computer, and add this web page to your browser's favorites.
## Step 1. Install the machine and Wiring
- **Installation**. Refer to the [:book: **installation guide**][INSTALLATION_GUIDE] and [ :clapper: **installation video tutorial**][INSTALL_VIDEO] to install the machine. 
- **Wiring**. The process of wiring is basically to insert the plug into the corresponding socket. What you need to pay attention is to make sure the plug is fully inserted into the socket. Especially for those 2PIN sockets that sometimes make poor contact. :warning: When you wiring the print head (hotend assembly), please refer to the pictures in the installation guide carefully and pay attention to distinguish both the color of the connectors and the color of the wires.
## Step 2. Power on the maiche and do a simply test and verify
- **Power ON**. Before switching on the AC power, please check whether the setting of the 110V/220V power supply selector switch is set to the correct position ([**refer to this picture**][IMG_ACSWITCH]). And then you can [**turn on the power of machine**][POWER_ON]. :warning: Please note that the machine has 2 power switches, one is ***AC switch***(the red switch on the back of the control box, near to the AC Power socket) and another is ***DC switch***(a round metal push button switch on the right side of the control box), you need to turn on the AC switch first and then press and **hold the DC switch about 5 seconds** (release until the LCD screew show ZONESTAR LOGO) to turn on the machine.
- **Simply Test**. After power on, you can operate the menu on the LCD screen ([**LCD Menu description**][LCD_MENU]) to verify whether the machine can work normally, the steps as below:
  - **Prepare>>Auto Home>>Home All**. This step is to make the print head of the machine return to the origin position.
  - **Prepare>>Temperature>>Preheat PLA**. This step is to check the hot end and the hot bed can be heated normally. In this step, when the temperature of the nozzle exceeds 60 degrees, you should see a fan on the **right side** of the print head (hot end) spin up, this fan is called "hot end cooling fan". 
  - **Prepare>>Temperature>>FAN**. Press the knob and setting the fan speed to 255, the fan on the **left side up** should spin up.   
    After did the above 3 steps, it is basically determined that the machine are working normally, you can proceed the following steps. If you find that any part is not working properly, please double check the wiring, or to do a "electronics auto testing" to check. (refer to[ :clapper: **machine auto testing video turorial**][AUTOTEST_VIDEO]).
## Step 3. Level the bed
Before printing the test file, you need to do a simple bed leveling to set the height between the nozzle and the bed (printing platform), so that the filament can be sticked on the bed well when printing. Please refer to [**level the bed**][LEVEL_BED] to do it.

## Step 4. Print test 3d model
FDM 3D printers can only recognize gcode files, we need to copy the gcode files to the SD card, and then insert the SD card into the SD card slot of the 3D printer, and then operature the LCD screen to start to print.    
:warning: Even if you are familiar with 3D printers, it is recommended that you print at least one 4-color test model to confirm that the machine works normally.
- **4.1 Print a one color test file**
  - **Prepare gcode file**. [:arrow_down: **download xyz_cube zip file**][XYZ_CUBE] and unzip it on PC, and then copy the **xyz_cube.gcode** to SD card. Plug the SD card to the SD socket of machine.
  - **Load filament**. Refer to [:book: **here**][LOAD_FILAMENT] to load all 4 filaments to the extruders and hot end.     
    ***:warning: For M4V6 hotend, you need to load 4 filament to the hotend even you print one color 3d prints.*** 
  - **Print from SD card**. Move item to **Print** item on LCD screen and click the knob and choose **xyz_cube.gcode** file, click knob to start print.
  - **Fine tune nozzle height**. Wait the nozzle and hotbed heated, and watch the distance from the nozzle to the bed when printing the first layer, if it is too fat or too close, double click the knob of LCD screen to open a **"babystep"** menu, and then rotate the knob to fine tune the distance from the nozzle to the bed.
  - **Wait for printing finished**.
- **4.2 Print a 4 color test file**
  - **Prepare gcode file**. [:arrow_down: **download M4_4CTest zip file**][M4_4CTEST] and unzip it on PC, and then copy the **M4_4CTest.gcode** to SD card. Plug the SD card to the SD socket of machine.
  - **Load filaments**. Refer to [:book: **here**][LOAD_FILAMENT] to load all 4 filaments to the extruders and the hot end.
  - **Print from SD card**. Move item to **Print** item on LCD screen and click the knob and choose **M4_4CTest.gcode** file, click knob to start print.
  - **Fine tune nozzle height**. Wait the nozzle and hotbed heated, and watch the distance from the nozzle to the bed when printing the first layer, if it is too fat or too close, double click the knob of LCD screen to open a **"babystep"** menu, and then rotate the knob to fine tune the distance from the nozzle to the bed.
  - **Wait for printing finished**.
## Step 5. Slicing your own 3d model
- Before printing your own 3D models, you need to convert the 3d model file (a stl/obj/AMF format file which [downloaded from the internet](#download) or drawing by yourself) to a gcode file, save this gcode file to SD card and then plug the SD card to your 3d printer.      
  :pushpin: **The process of converting a 3D model into a gcode file is called *slicing***.   
- Firstly you need to download the slicing software and install it on your computer, and set the parameters of your machine in the slicing software or load the preset file of your machine which set by the 3d printer manufacture.   
- Next, you need to run the slicing software, and may also need to set some slicing setting according to the characteristics of your 3D model file and then do slicing.      
  :pushpin: The recommended slicing software is **PrusaSlicer**, for how to download, install and use **PrusaSlicer** , please refer to [***Slicing Guide***][SLICING_GUIDE].     
#### <a id="download"> :page_with_curl: Famous free 3D model download websites </a>
  - [thingiverse](https://www.thingiverse.com/)  
  - [printables](https://www.printables.com/)  
  - [youmagine](https://www.youmagine.com/)   
## Step 6. Printing your own 3d model
After sliced, copy the generated gcode file to the SD card and then print it following the [**step 4**](#step-4-print-test-3d-model).
## Step 7. To use advance features
After you fully understand all the basic operations, you can try some advance functions of this machine. 
For details, please refer to [**Advance Features Use Guide**][ADVANCE_FEATURES].

------
<a id="ES"></a>

# Guía paso a paso de Z8P-MK2 [:arrow_heading_up:](#choose-language)
Si eres un principiante con las impresoras 3D y tienes tanta documentación para leer, es posible que no sepas por dónde empezar. No se preocupe, entraremos en los detalles de estos documentos a continuación paso a paso.     
En una palabra, lo que debe hacer incluye los siguientes 4 pasos: **Instalar la máquina >> Imprimir el archivo de prueba >> Cortar su propio archivo 3D >> Imprimir su archivo 3D**.     
En primer lugar, te recomendamos que [:arrow_down: **descargues todos los documentos**][USER_GUIDE], los guardes en tu ordenador y añadas esta página web a los favoritos de tu navegador.
## Paso 1. Instale la máquina y el cableado
- **Instalación**. Consulte el [:book: **guía de instalación**][INSTALLATION_GUIDE] y [:clapper: **videotutorial de instalación**][INSTALL_VIDEO] para instalar la máquina.
- **Alambrado**. El proceso de cableado consiste básicamente en introducir el enchufe en el enchufe correspondiente. Lo que debe prestar atención es asegurarse de que el enchufe esté completamente insertado en el enchufe. Especialmente para esos enchufes de 2PIN que a veces hacen mal contacto.      
:warning: Al cablear el cabezal de impresión (ensamblaje del hotend), consulte atentamente las imágenes de la guía de instalación y preste atención para distinguir tanto el color de los conectores como el color de los cables.
## Paso 2. Encienda el maiche y haga una prueba y verificación sencillas.
- **Encendido**. Antes de encender la alimentación de CA, verifique si la configuración del interruptor selector de fuente de alimentación de 110V/220V está en la posición correcta ([**consulte esta imagen**][IMG_ACSWITCH]). Y luego podrá [**encender la máquina**][POWER_ON]. :warning: Tenga en cuenta que la máquina tiene 2 interruptores de alimentación, uno es ***interruptor de CA*** (el interruptor rojo en la parte posterior de la caja de control, cerca de la toma de corriente de CA) y otro es ***interruptor de CC ***(un interruptor de botón redondo de metal en el lado derecho de la caja de control), primero debe encender el interruptor de CA y luego presionar y **mantener presionado el interruptor de CC unos 5 segundos** (suelte hasta que el tornillo LCD muestra el LOGOTIPO de ZONESTAR) para encender la máquina.
- **Simplemente prueba**. Después del encendido, puede operar el menú en la pantalla LCD ([**Descripción del menú LCD**][LCD_MENU]) para verificar si la máquina puede funcionar normalmente, siguiendo los pasos a continuación:
   - **Preparar>>Inicio automático>>Inicio todo**. Este paso es para hacer que el cabezal de impresión de la máquina regrese a la posición original.
   - **Preparar>>Temperatura>>Precalentar PLA**. Este paso es para verificar que el extremo caliente y la cama caliente se puedan calentar normalmente. En este paso, cuando la temperatura de la boquilla supera los 60 grados, debería ver girar un ventilador en el **lado derecho** del cabezal de impresión (extremo caliente), este ventilador se llama "ventilador de enfriamiento del extremo caliente".
   - **Preparar>>Temperatura>>VENTILADOR**. Presione la perilla y ajuste la velocidad del ventilador a 255, el ventilador del **lado izquierdo hacia arriba** debería girar.
     Después de realizar los 3 pasos anteriores, básicamente se determina que la máquina está funcionando normalmente, puede continuar con los siguientes pasos. Si descubre que alguna pieza no funciona correctamente, verifique nuevamente el cableado o realice una "prueba automática de electrónica" para verificar. (consulte[:clapper: **tutorial en vídeo sobre pruebas automáticas de máquinas**][AUTOTEST_VIDEO]).
## Paso 3. Nivela la cama
Antes de imprimir el archivo de prueba, debe realizar una simple nivelación de la cama para establecer la altura entre la boquilla y la cama (plataforma de impresión), de modo que el filamento se pueda adherir bien a la cama al imprimir. Consulta [**nivelar la cama**][LEVEL_BED] para hacerlo.
## Paso 4. Imprimir modelo 3D de prueba
Las impresoras FDM 3D solo pueden reconocer archivos gcode, necesitamos copiar los archivos gcode a la tarjeta SD y luego insertar la tarjeta SD en la ranura para tarjetas SD de la impresora 3D y luego operar la pantalla LCD para comenzar a imprimir.
:warning: Incluso si está familiarizado con las impresoras 3D, se recomienda imprimir al menos un modelo de prueba de 4 colores para confirmar que la máquina funciona normalmente.
- **4.1 Imprimir un archivo de prueba de un color**
   - **Preparar archivo gcode**. [:arrow_down: **descargue el archivo zip xyz_cube**][XYZ_CUBE], descomprímalo en la PC y luego copie el **xyz_cube.gcode** a la tarjeta SD. Conecte la tarjeta SD al conector SD de la máquina.
   - **Cargar filamento**. Consulte [:book: **aquí**][LOAD_FILAMENT] para cargar los 4 filamentos en los extrusores y el hot end.
     ***:warning: para el hotend M4V6, debes cargar 4 filamentos en el hotend incluso si imprimes impresiones en 3D de un solo color.***
   - **Imprimir desde tarjeta SD**. Mueva el elemento al elemento **Imprimir** en la pantalla LCD, haga clic en la perilla y elija el archivo **xyz_cube.gcode**, haga clic en la perilla para comenzar a imprimir.
   - **Ajuste la altura de la boquilla**. Espere a que la boquilla y la cama se calienten y observe la distancia desde la boquilla hasta la cama al imprimir la primera capa. Si está demasiado gruesa o demasiado cerca, haga doble clic en la perilla de la pantalla LCD para abrir un menú **"babystep"** y luego gire la perilla para ajustar con precisión la distancia desde la boquilla hasta la cama.
   - **Esperar a que termine la impresión**.
- **4.2 Imprimir un archivo de prueba de 4 colores**
   - **Preparar archivo gcode**. [:arrow_down: **descargue el archivo zip M4_4CTest**][M4_4CTEST] y descomprímalo en la PC, y luego copie el **M4_4CTest.gcode** a la tarjeta SD. Conecte la tarjeta SD al conector SD de la máquina.
   - **Cargar filamentos**. Consulte [:book: **aquí**][LOAD_FILAMENT] para cargar los 4 filamentos en las extrusoras y el extremo caliente.
   - **Imprimir desde tarjeta SD**. Mueva el elemento al elemento **Imprimir** en la pantalla LCD, haga clic en la perilla y elija el archivo **M4_4CTest.gcode**, haga clic en la perilla para comenzar a imprimir.
   - **Ajuste la altura de la boquilla**. Espere a que la boquilla y la cama se calienten y observe la distancia desde la boquilla hasta la cama al imprimir la primera capa. Si está demasiado gruesa o demasiado cerca, haga doble clic en la perilla de la pantalla LCD para abrir un menú **"babystep"** y luego gire la perilla para ajustar con precisión la distancia desde la boquilla hasta la cama.
   - **Esperar a que termine la impresión**.
## Paso 5. Cortar tu propio modelo 3D
- Antes de imprimir sus propios modelos 3D, necesita convertir el archivo del modelo 3D (un archivo de formato stl/obj/AMF que [descargó de Internet](#download_es) o lo dibujó usted mismo) a un archivo gcode, guarde este archivo gcode a la tarjeta SD y luego conecte la tarjeta SD a su impresora 3D.     
   :pushpin: **El proceso de convertir un modelo 3D en un archivo gcode se llama *rebanado***.
- En primer lugar, debe descargar el software de corte e instalarlo en su computadora, y configurar los parámetros de su máquina en el software de corte o cargar el archivo preestablecido de su máquina configurado por el fabricante de la impresora 3D.
- A continuación, debe ejecutar el software de corte y es posible que también deba establecer alguna configuración de corte de acuerdo con las características de su archivo de modelo 3D y luego realizar el corte.     
   :pushpin: El software de corte recomendado es **PrusaSlicer**. Para saber cómo descargarlo, instalarlo y utilizar **PrusaSlicer**, consulte la [***Guía de corte***][SLICING_GUIDE].
#### <a id="download_es"> :page_with_curl: sitios web famosos de descarga gratuita de modelos 3D </a>
  - [thingiverse](https://www.thingiverse.com/)  
  - [printables](https://www.printables.com/)  
  - [youmagine](https://www.youmagine.com/)   
## Paso 6. Imprime tu propio modelo 3D
Después de cortarlo, copie el archivo gcode generado en la tarjeta SD y luego imprímalo siguiendo el [**paso 4**](#paso-4-imprimir-modelo-3d-de-prueba).
## Paso 7. Para utilizar funciones avanzadas
Una vez que comprenda completamente todas las operaciones básicas, podrá probar algunas funciones avanzadas de esta máquina.
Para obtener más información, consulte la [**Guía de uso de funciones avanzadas**][ADVANCE_FEATURES].

-----
<a id="PT"></a>

# Guia passo a passo Z8P-MK2 [:arrow_heading_up:](#choose-language)
Se você é iniciante em impressoras 3D e tem tanta documentação para ler, talvez não saiba por onde começar. Não se preocupe, entraremos nos detalhes desses documentos a seguir, passo a passo.    
Em uma palavra, o que você precisa fazer inclui as 4 etapas abaixo: **Instalar a máquina >> Imprimindo arquivo de teste >> Fatiando seu próprio arquivo 3D >> Imprimindo seu arquivo 3D**.    
Primeiramente, recomendamos que você [:arrow_down: **baixe todos os documentos**][USER_GUIDE] e salve-os em seu computador, e adicione esta página web aos favoritos do seu navegador.
## Etapa 1. Instale a máquina e a fiação
- **Instalação**. Consulte o [:book: **guia de instalação**][INSTALLATION_GUIDE] e [:clapper: **tutorial em vídeo de instalação**][INSTALL_VIDEO] para instalar a máquina.
- **Fiação**. O processo de fiação consiste basicamente em inserir o plugue na tomada correspondente. O que você precisa prestar atenção é garantir que o plugue esteja totalmente inserido na tomada. Principalmente para aqueles soquetes 2PIN que às vezes fazem mau contato.:warning: Ao conectar a cabeça de impressão (montagem hotend), consulte as imagens no guia de instalação com atenção e preste atenção para distinguir a cor dos conectores e a cor dos fios.
## Etapa 2. Ligue o maiche e faça um teste simples e verifique
- **Ligar**. Antes de ligar a alimentação CA, verifique se a configuração da chave seletora da fonte de alimentação 110V/220V está na posição correta ([**consulte esta imagem**][IMG_ACSWITCH]). E então você pode [**ligar a máquina**][POWER_ON]. :warning: observe que a máquina possui 2 interruptores de alimentação, um é o ***interruptor AC*** (o interruptor vermelho na parte traseira da caixa de controle, próximo à tomada de alimentação CA) e o outro é o ***interruptor DC ***(um botão redondo de metal no lado direito da caixa de controle), você precisa ligar o interruptor CA primeiro e depois pressionar e **manter pressionado o interruptor CC por cerca de 5 segundos** (solte até que o parafuso LCD mostre o LOGOTIPO ZONESTAR) para ligar a máquina.
- **Simplesmente teste**. Depois de ligar, você pode operar o menu na tela LCD ([**Descrição do menu LCD**][LCD_MENU]) para verificar se a máquina pode funcionar normalmente, seguindo as etapas abaixo:
   - **Preparar>>Auto Home>>Home All**. Esta etapa serve para fazer com que o cabeçote de impressão da máquina retorne à posição de origem.
   - **Preparar>>Temperatura>>Pré-aquecer PLA**. Esta etapa é verificar se a extremidade quente e se a cama quente pode ser aquecida normalmente. Nesta etapa, quando a temperatura do bico ultrapassar 60 graus, você deverá ver um ventilador no **lado direito** do cabeçote de impressão (hot end) girando, esse ventilador é chamado de "ventilador de resfriamento do hot end".
   - **Preparar>>Temperatura>>VENTILADOR**. Pressione o botão e definindo a velocidade do ventilador para 255, o ventilador no **lado esquerdo para cima** deve girar.
     Após realizar as 3 etapas acima, é basicamente determinado que a máquina está funcionando normalmente, você pode prosseguir com as etapas a seguir. Se você achar que alguma peça não está funcionando corretamente, verifique novamente a fiação ou faça um "teste automático eletrônico" para verificar. (consulte [:clapper: **turorial de vídeo de teste automático da máquina**][AUTOTEST_VIDEO]).
## Etapa 3. Nivele a cama
Antes de imprimir o arquivo de teste, é necessário fazer um simples nivelamento da base para definir a altura entre o bico e a base (plataforma de impressão), para que o filamento possa ficar bem colado na base durante a impressão. Consulte [**nivelar a cama**][LEVEL_BED] para fazer isso.
## Paso 4. Imprimir modelo 3D de teste
As impressoras FDM 3D só podem reconhecer arquivos gcode, precisamos copiar os arquivos gcode para o cartão SD e depois inserir o cartão SD na ranhura para cartões SD da impressora 3D e depois operar a tela LCD para começar a imprimir.
:warning: Incluso se você estiver familiarizado com as impressoras 3D, recomendamos imprimir pelo menos um modelo de teste de 4 cores para confirmar se a máquina funciona normalmente.
- **4.1 Imprimir um arquivo de teste de cor**
    - **Preparar arquivo gcode**. [:arrow_down: **descargue o arquivo zip xyz_cube**][XYZ_CUBE], descomprímalo no PC e depois copie o **xyz_cube.gcode** para o cartão SD. Conecte a tarjeta SD ao conector SD da máquina.
    - **Cargar filamento**. Consulte [:book: **aquí**][LOAD_FILAMENT] para carregar os 4 filamentos nas extrusoras e no hot end.
      ***:warning: para o hotend M4V6, você deve carregar 4 fios no hotend, mesmo imprimindo impressões em 3D de uma única cor.***
    - **Imprimir da tarjeta SD**. Mueva o elemento para o elemento **Imprimir** na tela LCD, clique no botão e elimine o arquivo **xyz_cube.gcode**, clique no botão para começar a imprimir.
    - **Ajuste a altura da boquilha**. Espere que a boquilla e a cama estejam quentes e observe a distância da boquilla até a cama para imprimir a primeira capa. Se você estiver muito gruesa ou muito perto, clique duas vezes na barra da tela LCD para abrir um menu **"babystep"** e depois gire a barra para ajustar com precisão a distância da boquilha até a cama.
    - **Esperar terminar a impressão**.
- **4.2 Imprimir um arquivo de teste de 4 cores**
    - **Preparar arquivo gcode**. [:arrow_down: **descargue o arquivo zip M4_4CTest**][M4_4CTEST] e descomprímalo no PC, e depois copie o **M4_4CTest.gcode** para a placa SD. Conecte a tarjeta SD ao conector SD da máquina.
    - **Filamentos de Cargar**. Consulte [:book: **aquí**][LOAD_FILAMENT] para carregar os 4 filamentos nas extrusoras e na extremidade quente.
    - **Imprimir da tarjeta SD**. Mueva o elemento para o elemento **Imprimir** na tela LCD, clique no perigo e elimine o arquivo **M4_4CTest.gcode**, clique no perigo para começar a imprimir.
    - **Ajuste a altura da boquilha**. Espere que a boquilla e a cama estejam quentes e observe a distância da boquilla até a cama para imprimir a primeira capa. Se você estiver muito gruesa ou muito perto, clique duas vezes na barra da tela LCD para abrir um menu **"babystep"** e depois gire a barra para ajustar com precisão a distância da boquilha até a cama.
    - **Esperar terminar a impressão**.
## Paso 5. Cortar seu próprio modelo 3D
- Antes de imprimir seus próprios modelos 3D, você precisa converter o arquivo do modelo 3D (um arquivo de formato stl/obj/AMF que [descargou da Internet](#download_pt) ou foi criado usando o mesmo) para um arquivo gcode, guarde este arquivo gcode à tarjeta SD e depois conecte a tarjeta SD à sua impressora 3D.     
    :pushpin: **O processo de conversão de um modelo 3D em um arquivo gcode se chama *rebanado***.
- Em primeiro lugar, você deve baixar o software de corte e instalá-lo em seu computador, configurar os parâmetros de sua máquina no software de corte ou carregar o arquivo pré-estável de sua máquina configurada pelo fabricante da impressora 3D.     
- Em seguida, você deve executar o software de corte e é possível que você também defina alguma configuração de corte de acordo com os recursos de seu arquivo de modelo 3D e depois execute o corte.     
    :pushpin: O software de corte recomendado é **PrusaSlicer**. Para saber como baixar, instalar e usar o **PrusaSlicer**, consulte o [***Guia de corte***][SLICING_GUIDE].
#### <a id="download_pt"> :page_with_curl: sites famosos de download gratuito de modelos 3D </a>
  - [thingiverse](https://www.thingiverse.com/)  
  - [printables](https://www.printables.com/)  
  - [youmagine](https://www.youmagine.com/)   
## Paso 6. Imprima seu próprio modelo 3D
Depois de cortá-lo, copie o arquivo gcode gerado no cartão SD e depois imprima seguindo o [**paso 4**](#paso-4-imprimir-modelo-3d-de-teste).
## Paso 7. Para usar funções avançadas
Depois de compreender completamente todas as operações básicas, você poderá testar algumas funções avançadas desta máquina.
Para obter mais informações, consulte o [**Guia de uso de funções avançadas**][ADVANCE_FEATURES].

-----
<a id="FR"></a>

# Guide étape par étape du Z8P-MK2 [:arrow_heading_up:](#choose-language)
Si vous débutez avec les imprimantes 3D, avec autant de documentation à lire, vous ne savez peut-être pas par où commencer. Ne vous inquiétez pas, nous entrerons dans les détails de ces documents étape par étape.      
En un mot, ce que vous devez faire comprend les 4 étapes ci-dessous: **Installer la machine >> Impression du fichier de test >> Découper votre propre fichier 3D >> Imprimer votre fichier 3D**.       
Tout d'abord, nous vous recommandons de [:arrow_down: **télécharger tous les documents**][USER_GUIDE] et de les enregistrer sur votre ordinateur, puis d'ajouter cette page Web aux favoris de votre navigateur.
## Étape 1. Installez la machine et le câblage
- **Installation**. Reportez-vous au [:book: **guide d'installation**][INSTALLATION_GUIDE] et au [:clapper: **tutoriel vidéo d'installation**][INSTALL_VIDEO] pour installer la machine.
- **Câblage**. Le processus de câblage consiste essentiellement à insérer la fiche dans la prise correspondante. Ce à quoi vous devez faire attention, c'est vous assurer que la fiche est complètement insérée dans la prise. Surtout pour ces prises 2PIN qui font parfois un mauvais contact. :warning: Lorsque vous câblez la tête d'impression (ensemble hotend), veuillez vous référer attentivement aux images du guide d'installation et faire attention à distinguer à la fois la couleur des connecteurs et la couleur des fils.
## Étape 2. Allumez la maiche et effectuez simplement un test et une vérification
- **Allumer**. Avant de mettre sous tension, veuillez vérifier si le réglage du sélecteur d'alimentation 110 V/220 V est réglé sur la bonne position ([**se référer à cette image**][IMG_ACSWITCH]). Et puis vous pouvez [**allumer la machine**][POWER_ON]. :warning: Veuillez noter que la machine dispose de 2 interrupteurs d'alimentation, l'un est un ***interrupteur AC*** (l'interrupteur rouge à l'arrière du boîtier de commande, près de la prise d'alimentation AC) et un autre est un ***interrupteur DC. *** (un bouton-poussoir rond en métal sur le côté droit du boîtier de commande), vous devez d'abord allumer l'interrupteur CA, puis appuyer et **maintenir l'interrupteur CC pendant environ 5 secondes ** (relâchez jusqu'à ce que la vis LCD afficher le logo ZONESTAR) pour allumer la machine.
- **Testez simplement**. Après la mise sous tension, vous pouvez utiliser le menu sur l'écran LCD ([**Description du menu LCD**][LCD_MENU]) pour vérifier si la machine peut fonctionner normalement, en suivant les étapes ci-dessous:
   - **Préparer>>Auto Home>>Home All**. Cette étape consiste à faire revenir la tête d'impression de la machine à sa position d'origine.
   - **Préparer>>Température>>Préchauffer le PLA**. Cette étape consiste à vérifier l'extrémité chaude et le lit chaud peut être chauffé normalement. Dans cette étape, lorsque la température de la buse dépasse 60 degrés, vous devriez voir un ventilateur sur le **côté droit** de la tête d'impression (extrémité chaude) tourner, ce ventilateur est appelé « ventilateur de refroidissement de l'extrémité chaude ».
   - **Préparation>>Température>>VENTILATEUR**. Appuyez sur le bouton et réglez la vitesse du ventilateur sur 255, le ventilateur situé **côté gauche vers le haut** devrait tourner.
     Après avoir effectué les 3 étapes ci-dessus, il est essentiellement déterminé que la machine fonctionne normalement, vous pouvez procéder aux étapes suivantes. Si vous constatez qu'une pièce ne fonctionne pas correctement, veuillez vérifier le câblage ou effectuer un « test automatique de l'électronique » pour vérifier. (reportez-vous à[ :clapper: **tutoriel vidéo de test automatique de la machine**][AUTOTEST_VIDEO]).
## Étape 3. Nivelez le lit
Avant d'imprimer le fichier de test, vous devez effectuer un simple nivellement du lit pour régler la hauteur entre la buse et le lit (plateforme d'impression), afin que le filament puisse bien coller sur le lit lors de l'impression. Veuillez vous référer à [**niveler le lit**][LEVEL_BED] pour le faire.

## Étape 4. Imprimer le modèle 3D de test
Les imprimantes 3D FDM ne peuvent reconnaître que les fichiers gcode, nous devons copier les fichiers gcode sur la carte SD, puis insérer la carte SD dans la fente pour carte SD de l'imprimante 3D, puis utiliser l'écran LCD pour commencer à imprimer.
:warning: Même si vous êtes familier avec les imprimantes 3D, il est recommandé d'imprimer au moins un modèle de test en 4 couleurs pour confirmer que la machine fonctionne normalement.
- **4.1 Imprimer un fichier de test d'une couleur**
   - **Préparer le fichier gcode**. [:arrow_down: **téléchargez le fichier zip xyz_cube**][XYZ_CUBE] et décompressez-le sur PC, puis copiez le **xyz_cube.gcode** sur la carte SD. Branchez la carte SD sur la prise SD de la machine.
   - **Charger le filament**. Reportez-vous à [:book: **here**][LOAD_FILAMENT] pour charger les 4 filaments dans les extrudeuses et la partie chaude.
     ***:warning: pour le hotend M4V6, vous devez charger 4 filaments sur le hotend même si vous imprimez des impressions 3D d'une seule couleur.***
   - **Imprimer depuis la carte SD**. Déplacez l'élément vers l'élément **Imprimer** sur l'écran LCD, cliquez sur le bouton et choisissez le fichier **xyz_cube.gcode**, cliquez sur le bouton pour lancer l'impression.
   - **Régler finement la hauteur de la buse**. Attendez que la buse et le foyer soient chauffés, et surveillez la distance entre la buse et le lit lors de l'impression de la première couche, si elle est trop grasse ou trop proche, double-cliquez sur le bouton de l'écran LCD pour ouvrir un menu **"babystep"** , puis tournez le bouton pour affiner la distance entre la buse et le lit.
   - **Attendez la fin de l'impression**.
- **4.2 Imprimer un fichier de test en 4 couleurs**
   - **Préparer le fichier gcode**. [:arrow_down: **téléchargez le fichier zip M4_4CTest**][M4_4CTEST] et décompressez-le sur PC, puis copiez le **M4_4CTest.gcode** sur la carte SD. Branchez la carte SD sur la prise SD de la machine.
   - **Charger les filaments**. Reportez-vous à [:book: **here**][LOAD_FILAMENT] pour charger les 4 filaments dans les extrudeuses et l'extrémité chaude.
   - **Imprimer depuis la carte SD**. Déplacez l'élément vers l'élément **Imprimer** sur l'écran LCD, cliquez sur le bouton et choisissez le fichier **M4_4CTest.gcode**, cliquez sur le bouton pour lancer l'impression.
   - **Régler finement la hauteur de la buse**. Attendez que la buse et le foyer soient chauffés, et surveillez la distance entre la buse et le lit lors de l'impression de la première couche, si elle est trop grasse ou trop proche, double-cliquez sur le bouton de l'écran LCD pour ouvrir un menu **"babystep"** , puis tournez le bouton pour affiner la distance entre la buse et le lit.
   - **Attendez la fin de l'impression**.

## Étape 5. Découper votre propre modèle 3D
- Avant d'imprimer vos propres modèles 3D, vous devez convertir le fichier de modèle 3D (un fichier au format stl/obj/AMF qui [téléchargé depuis Internet](#download_fr) ou dessiné par vous-même) en un fichier gcode, enregistrez ce fichier gcode sur la carte SD, puis branchez la carte SD sur votre imprimante 3D.     
   :pushpin: **Le processus de conversion d'un modèle 3D en fichier Gcode est appelé *slicing***.
- Tout d'abord, vous devez télécharger le logiciel de découpage et l'installer sur votre ordinateur, puis définir les paramètres de votre machine dans le logiciel de découpage ou charger le fichier prédéfini de votre machine défini par le fabricant de l'imprimante 3D.
- Ensuite, vous devez exécuter le logiciel de découpage, et vous devrez peut-être également définir certains paramètres de découpage en fonction des caractéristiques de votre fichier de modèle 3D, puis effectuer le découpage.     
   :pushpin: Le logiciel de découpage recommandé est **PrusaSlicer**. Pour savoir comment télécharger, installer et utiliser **PrusaSlicer**, veuillez vous référer au [***Slicing Guide***][SLICING_GUIDE].
#### <a id="download_fr"> :page_with_curl: Célèbres sites de téléchargement de modèles 3D gratuits </a>
  - [thingiverse](https://www.thingiverse.com/)  
  - [printables](https://www.printables.com/)  
  - [youmagine](https://www.youmagine.com/)   
## Étape 6. Imprimer votre propre modèle 3D
Une fois découpé, copiez le fichier gcode généré sur la carte SD, puis imprimez-le en suivant la [**étape 4**](#étape-4-imprimer-le-modèle-3d-de-test).
## Étape 7. Pour utiliser les fonctionnalités avancées
Après avoir parfaitement compris toutes les opérations de base, vous pouvez essayer certaines fonctions avancées de cette machine.
Pour plus de détails, veuillez consulter le [**Guide d'utilisation des fonctionnalités avancées**][ADVANCE_FEATURES].

-----
<a id="DE"></a>

# Z8P-MK2 Schritt-für-Schritt-Anleitung [:arrow_heading_up:](#choose-language)
Wenn Sie ein Anfänger im Umgang mit 3D-Druckern sind und so viel Dokumentation zu lesen haben, wissen Sie möglicherweise nicht, wo Sie anfangen sollen. Keine Sorge, wir gehen im nächsten Schritt Schritt für Schritt auf die Details dieser Dokumente ein.     
Kurz gesagt, was Sie tun müssen, umfasst die folgenden 4 Schritte: **Installieren Sie die Maschine >> Drucken Sie die Testdatei >> Schneiden Sie Ihre eigene 3D-Datei >> Drucken Sie Ihre 3D-Datei**.     
Zunächst empfehlen wir Ihnen, [:arrow_down: **alle Dokumente herunterzuladen**][USER_GUIDE], sie auf Ihrem Computer zu speichern und diese Webseite zu den Favoriten Ihres Browsers hinzuzufügen.
## Schritt 1. Installieren Sie die Maschine und die Verkabelung
- **Installation**. Informationen zur Installation der Maschine finden Sie im [:book: **Installationshandbuch**][INSTALLATION_GUIDE] und im [ :clapper: **Installationsvideo-Tutorial**][INSTALL_VIDEO].
- **Verkabelung**. Der Verkabelungsprozess besteht im Wesentlichen darin, den Stecker in die entsprechende Steckdose einzustecken. Sie müssen darauf achten, dass der Stecker vollständig in die Steckdose eingesteckt ist. Besonders für die 2PIN-Buchsen, die manchmal einen schlechten Kontakt herstellen. :warning: Wenn Sie den Druckkopf verkabeln (Hotend-Montage), sehen Sie sich bitte sorgfältig die Bilder in der Installationsanleitung an und achten Sie darauf, sowohl die Farbe der Anschlüsse als auch die Farbe der Drähte zu unterscheiden.
## Schritt 2. Schalten Sie die Maiche ein und führen Sie einen einfachen Test und eine Überprüfung durch
- **Ein**. Bevor Sie den Wechselstrom einschalten, prüfen Sie bitte, ob die Einstellung des 110-V-/220-V-Stromversorgungswahlschalters auf die richtige Position eingestellt ist ([**siehe dieses Bild**][IMG_ACSWITCH]). Und dann können Sie [**die Maschine einschalten**][POWER_ON]. :warning: Bitte beachten Sie, dass die Maschine über zwei Netzschalter verfügt, einer ist ein ***AC-Schalter*** (der rote Schalter auf der Rückseite des Steuerkastens, in der Nähe der AC-Steckdose) und der andere ist ein ***DC-Schalter*** (ein runder Druckknopfschalter aus Metall auf der rechten Seite des Steuerkastens), Sie müssen zuerst den Wechselstromschalter einschalten und dann **den Gleichstromschalter etwa 5 Sekunden lang gedrückt halten** (lassen Sie ihn los, bis die LCD-Schraube einrastet ZONESTAR-LOGO anzeigen), um das Gerät einzuschalten.
- **Einfach testen**. Nach dem Einschalten können Sie das Menü auf dem LCD-Bildschirm ([**Beschreibung des LCD-Menüs**][LCD_MENU]) bedienen, um zu überprüfen, ob das Gerät normal funktioniert. Führen Sie dazu die folgenden Schritte aus:
   - **Vorbereiten>>Auto Home>>Home All**. Dieser Schritt dient dazu, den Druckkopf des Geräts in die Ausgangsposition zurückzubringen.
   - **Vorbereiten>>Temperatur>>PLA vorheizen**. In diesem Schritt wird überprüft, ob das heiße Ende normal beheizt werden kann. Wenn in diesem Schritt die Temperatur der Düse 60 Grad übersteigt, sollten Sie sehen, wie sich ein Lüfter auf der **rechten Seite** des Druckkopfs (Hot-End) dreht. Dieser Lüfter wird als „Hot-End-Kühlventilator“ bezeichnet.
   - **Vorbereiten>>Temperatur>>LÜFTER**. Drücken Sie den Knopf und stellen Sie die Lüftergeschwindigkeit auf 255 ein. Der Lüfter auf der **linken Seite oben** sollte sich drehen.
     Nachdem Sie die oben genannten drei Schritte ausgeführt haben und grundsätzlich festgestellt haben, dass die Maschine normal funktioniert, können Sie mit den folgenden Schritten fortfahren. Wenn Sie feststellen, dass ein Teil nicht ordnungsgemäß funktioniert, überprüfen Sie bitte die Verkabelung noch einmal oder führen Sie zur Überprüfung einen „Automatischen Elektroniktest“ durch. (Siehe [ :clapper: **Video-Tutorial zum automatischen Testen von Maschinen**][AUTOTEST_VIDEO]).
## Schritt 3. Richten Sie das Bett aus
Bevor Sie die Testdatei drucken, müssen Sie eine einfache Bettnivellierung durchführen, um die Höhe zwischen der Düse und dem Bett (Druckplattform) einzustellen, damit das Filament beim Drucken gut auf dem Bett haften kann. Bitte lesen Sie hierzu [**das Bett nivellieren**][LEVEL_BED].
## Schritt 4. Test-3D-Modell drucken
FDM-3D-Drucker können nur Gcode-Dateien erkennen. Wir müssen die Gcode-Dateien auf die SD-Karte kopieren, dann die SD-Karte in den SD-Kartensteckplatz des 3D-Druckers einlegen und dann den LCD-Bildschirm bedienen, um mit dem Drucken zu beginnen.
:warning: Auch wenn Sie mit 3D-Druckern vertraut sind, wird empfohlen, mindestens ein 4-Farben-Testmodell zu drucken, um zu bestätigen, dass die Maschine normal funktioniert.
- **4.1 Eine einfarbige Testdatei drucken**
   - **Gcode-Datei vorbereiten**. [:arrow_down: **xyz_cube zip-Datei herunterladen**][XYZ_CUBE] und auf dem PC entpacken und dann den **xyz_cube.gcode** auf die SD-Karte kopieren. Stecken Sie die SD-Karte in den SD-Anschluss des Geräts.
   - **Filament laden**. Siehe [:book: **hier**][LOAD_FILAMENT], um alle 4 Filamente in die Extruder und das heiße Ende zu laden.
     ***:warning: Für das M4V6-Hotend müssen Sie 4 Filamente in das Hotend laden, auch wenn Sie einfarbige 3D-Drucke drucken.***
   - **Drucken von SD-Karte**. Bewegen Sie das Element auf dem LCD-Bildschirm zum Element **Drucken**, klicken Sie auf den Knopf und wählen Sie die Datei **xyz_cube.gcode** aus. Klicken Sie auf den Knopf, um den Druck zu starten.
   - **Düsenhöhe fein einstellen**. Warten Sie, bis die Düse und das Heizbett erhitzt sind, und achten Sie beim Drucken der ersten Schicht auf den Abstand von der Düse zum Bett. Wenn diese zu dick oder zu nah ist, doppelklicken Sie auf den Knopf des LCD-Bildschirms, um ein **"Babystep"**-Menü zu öffnen , und drehen Sie dann den Knopf, um den Abstand von der Düse zum Bett fein einzustellen.
   - **Warten Sie, bis der Druckvorgang abgeschlossen ist**.
- **4.2 Drucken einer 4-Farben-Testdatei**
   - **Gcode-Datei vorbereiten**. [:arrow_down: **M4_4CTest-Zip-Datei herunterladen**][M4_4CTEST] und auf dem PC entpacken und dann den **M4_4CTest.gcode** auf die SD-Karte kopieren. Stecken Sie die SD-Karte in den SD-Anschluss des Geräts.
   - **Filamente laden**. Siehe [:book: **hier**][LOAD_FILAMENT], um alle 4 Filamente in die Extruder und das heiße Ende zu laden.
   - **Drucken von SD-Karte**. Bewegen Sie das Element auf dem LCD-Bildschirm zum Element **Drucken**, klicken Sie auf den Knopf und wählen Sie die Datei **M4_4CTest.gcode** aus. Klicken Sie auf den Knopf, um den Druck zu starten.
   - **Düsenhöhe fein einstellen**. Warten Sie, bis die Düse und das Heizbett erhitzt sind, und achten Sie beim Drucken der ersten Schicht auf den Abstand von der Düse zum Bett. Wenn diese zu dick oder zu nah ist, doppelklicken Sie auf den Knopf des LCD-Bildschirms, um ein **"Babystep"**-Menü zu öffnen , und drehen Sie dann den Knopf, um den Abstand von der Düse zum Bett fein einzustellen.
   - **Warten Sie, bis der Druckvorgang abgeschlossen ist**.
## Schritt 5. Schneiden Sie Ihr eigenes 3D-Modell
- Bevor Sie Ihre eigenen 3D-Modelle drucken, müssen Sie die 3D-Modelldatei (eine Datei im stl/obj/AMF-Format, die Sie [aus dem Internet heruntergeladen haben](#download_de) oder die Sie selbst gezeichnet haben) in eine Gcode-Datei konvertieren und diese Gcode-Datei speichern auf die SD-Karte und schließen Sie die SD-Karte dann an Ihren 3D-Drucker an.     
   :pushpin: **Der Prozess der Konvertierung eines 3D-Modells in eine Gcode-Datei wird *Slicing*** genannt.
- Zuerst müssen Sie die Slicing-Software herunterladen und auf Ihrem Computer installieren und die Parameter Ihrer Maschine in der Slicing-Software einstellen oder die voreingestellte Datei Ihrer Maschine laden, die vom Hersteller des 3D-Druckers festgelegt wurde.
- Als nächstes müssen Sie die Slicing-Software ausführen und möglicherweise auch einige Slicing-Einstellungen entsprechend den Eigenschaften Ihrer 3D-Modelldatei festlegen und dann das Slicing durchführen.     
   :pushpin: Die empfohlene Slicing-Software ist **PrusaSlicer**. Informationen zum Herunterladen, Installieren und Verwenden von **PrusaSlicer** finden Sie in der [***Slicing-Anleitung***][SLICING_GUIDE].
#### <a id="download_de"> :page_with_curl: Berühmte kostenlose Websites zum Herunterladen von 3D-Modellen </a>
  - [thingiverse](https://www.thingiverse.com/)  
  - [printables](https://www.printables.com/)  
  - [youmagine](https://www.youmagine.com/)   
## Schritt 6. Drucken Sie Ihr eigenes 3D-Modell
Kopieren Sie nach dem Slicen die generierte Gcode-Datei auf die SD-Karte und drucken Sie sie dann gemäß [**Schritt 4**](#schritt-4-test-3d-modell-drucken) aus.
## Schritt 7. So nutzen Sie erweiterte Funktionen
Nachdem Sie alle grundlegenden Vorgänge vollständig verstanden haben, können Sie einige erweiterte Funktionen dieses Geräts ausprobieren.
Einzelheiten finden Sie im [**Benutzerhandbuch für erweiterte Funktionen**][ADVANCE_FEATURES].


-----
<a id="IT"></a>

# Z8P-MK2 Guida passo passo [:arrow_heading_up:](#choose-language)
Se sei un principiante con le stampanti 3D, con così tanta documentazione da leggere, potresti non sapere da dove cominciare. Non preoccuparti, entreremo nei dettagli di questi documenti passo dopo passo.     
In una parola, ciò che devi fare include i 4 passaggi seguenti: **Installa la macchina >> Stampa del file di prova >> Taglia il tuo file 3D >> Stampa il tuo file 3D**.     
Innanzitutto ti consigliamo di [:arrow_down: **scaricare tutti i documenti**][USER_GUIDE] e salvarli sul tuo computer e aggiungere questa pagina web ai preferiti del tuo browser.
## Passaggio 1. Installare la macchina e il cablaggio
- **Installazione**. Fare riferimento a [:book: **guida all'installazione**][GUIDA_INSTALLAZIONE] e [ :clapper: **tutorial video all'installazione**][INSTALL_VIDEO] per installare la macchina.
- **Cablaggio**. Il processo di cablaggio consiste sostanzialmente nell'inserire la spina nella presa corrispondente. Ciò a cui devi prestare attenzione è assicurarti che la spina sia completamente inserita nella presa. Soprattutto per quelle prese a 2 PIN che a volte fanno uno scarso contatto. :warning: Quando si collega la testina di stampa (gruppo hotend), fare riferimento attentamente alle immagini nella guida all'installazione e prestare attenzione a distinguere sia il colore dei connettori che il colore dei fili.
## Passaggio 2. Accendi la macchina ed esegui semplicemente un test e una verifica
- **Accensione**. Prima di accendere l'alimentazione CA, verificare se l'impostazione del selettore dell'alimentazione 110 V/220 V è impostata sulla posizione corretta ([**fare riferimento a questa immagine**][IMG_ACSWITCH]). Quindi puoi [**accendere la macchina**][POWER_ON].       :warning: Si prega di notare che la macchina è dotata di 2 interruttori di alimentazione, uno è ***interruttore CA*** (l'interruttore rosso sul retro della scatola di controllo, vicino alla presa di alimentazione CA) e un altro è ***interruttore CC ***(un interruttore a pulsante rotondo in metallo sul lato destro della scatola di controllo), è necessario prima accendere l'interruttore CA, quindi premere e **tenere premuto l'interruttore CC per circa 5 secondi** (rilasciare finché la vite LCD mostrare il LOGO ZONESTAR) per accendere la macchina.
- **Basta provare**. Dopo l'accensione, è possibile utilizzare il menu sullo schermo LCD ([**Descrizione menu LCD**][LCD_MENU]) per verificare se la macchina può funzionare normalmente, procedendo come segue:
   - **Prepara>>Ritorno automatico>>Home tutto**. Questo passaggio serve a far ritornare la testina di stampa della macchina nella posizione di origine.
   - **Preparazione>>Temperatura>>Preriscaldamento PLA**. Questo passaggio consiste nel controllare l'hot end e che il letto caldo possa essere riscaldato normalmente. In questo passaggio, quando la temperatura dell'ugello supera i 60 gradi, dovresti vedere una ventola sul **lato destro** della testina di stampa (hot end) che gira, questa ventola è chiamata "ventola di raffreddamento dell'hot end".
   - **Preparazione>>Temperatura>>VENTOLA**. Premere la manopola e impostare la velocità della ventola su 255, la ventola sul **lato sinistro in alto** dovrebbe girare.
     Dopo aver eseguito i 3 passaggi precedenti, una volta accertato che la macchina funziona normalmente, è possibile procedere con i passaggi seguenti. Se si riscontra che qualche parte non funziona correttamente, ricontrollare il cablaggio o eseguire un "test automatico dell'elettronica" per verificare. (fare riferimento a [:clapper: **tutorial video sul test automatico della macchina**][AUTOTEST_VIDEO]).
## Passaggio 3. Livellare il letto
Prima di stampare il file di prova, è necessario eseguire un semplice livellamento del letto per impostare l'altezza tra l'ugello e il letto (piattaforma di stampa), in modo che il filamento possa aderire bene al letto durante la stampa. Per farlo, fai riferimento a [**livellare il letto**][LEVEL_BED].
## Passaggio 4. Stampa del modello 3D di prova
Le stampanti 3D FDM possono riconoscere solo i file gcode, dobbiamo copiare i file gcode sulla scheda SD, quindi inserire la scheda SD nello slot per scheda SD della stampante 3D, quindi utilizzare lo schermo LCD per iniziare a stampare.
:warning: Anche se hai familiarità con le stampanti 3D, si consiglia di stampare almeno un modello di prova a 4 colori per confermare che la macchina funzioni normalmente.
- **4.1 Stampare un file di prova a un colore**
   - **Prepara il file gcode**. [:arrow_down: **scarica il file zip xyz_cube**][XYZ_CUBE] e decomprimilo sul PC, quindi copia il **xyz_cube.gcode** sulla scheda SD. Collegare la scheda SD alla presa SD della macchina.
   - **Caricare il filamento**. Fare riferimento a [:book: **qui**][LOAD_FILAMENT] per caricare tutti e 4 i filamenti negli estrusori e nell'hot end.
     ***:warning: per l'hotend M4V6, è necessario caricare 4 filamenti sull'hotend anche se si stampano stampe 3D a un colore.***
   - **Stampa da scheda SD**. Sposta l'elemento sull'elemento **Stampa** sullo schermo LCD, fai clic sulla manopola e scegli il file **xyz_cube.gcode**, fai clic sulla manopola per avviare la stampa.
   - **Regolazione fine dell'altezza dell'ugello**. Attendi che l'ugello e il piano caldo siano riscaldati e osserva la distanza dall'ugello al letto durante la stampa del primo strato, se è troppo largo o troppo vicino, fai doppio clic sulla manopola dello schermo LCD per aprire un menu **"babystep"** , quindi ruotare la manopola per regolare con precisione la distanza dall'ugello al piano.
   - **Attendere il completamento della stampa**.
- **4.2 Stampare un file di prova a 4 colori**
   - **Prepara il file gcode**. [:arrow_down: **scarica il file zip M4_4CTest**][M4_4CTEST] e decomprimilo sul PC, quindi copia il **M4_4CTest.gcode** sulla scheda SD. Collegare la scheda SD alla presa SD della macchina.
   - **Caricare i filamenti**. Fare riferimento a [:book: **qui**][LOAD_FILAMENT] per caricare tutti e 4 i filamenti negli estrusori e nell'hot end.
   - **Stampa da scheda SD**. Spostare l'elemento sull'elemento **Stampa** sullo schermo LCD, fare clic sulla manopola e scegliere il file **M4_4CTest.gcode**, fare clic sulla manopola per avviare la stampa.
   - **Regolazione fine dell'altezza dell'ugello**. Attendi che l'ugello e il piano caldo siano riscaldati e osserva la distanza dall'ugello al letto durante la stampa del primo strato, se è troppo largo o troppo vicino, fai doppio clic sulla manopola dello schermo LCD per aprire un menu **"babystep"** , quindi ruotare la manopola per regolare con precisione la distanza dall'ugello al letto.
   - **Attendere il completamento della stampa**.
## Passaggio 5. Affettare il tuo modello 3D
- Prima di stampare i tuoi modelli 3D, devi convertire il file del modello 3D (un file in formato stl/obj/AMF che [scaricato da Internet](#download_it) o disegnato da te) in un file gcode, salva questo file gcode sulla scheda SD, quindi collega la scheda SD alla stampante 3D.
   :pushpin: **Il processo di conversione di un modello 3D in un file gcode è chiamato *slicing***.
- Innanzitutto devi scaricare il software di slicing e installarlo sul tuo computer, quindi impostare i parametri della tua macchina nel software di slicing o caricare il file di preimpostazione della tua macchina impostato dal produttore della stampante 3D.
- Successivamente, è necessario eseguire il software di affettatura e potrebbe anche essere necessario impostare alcune impostazioni di affettatura in base alle caratteristiche del file del modello 3D e quindi eseguire l'affettatura.
   :pushpin: Il software di slicing consigliato è **PrusaSlicer**, per come scaricare, installare e utilizzare **PrusaSlicer**, fare riferimento alla [***Guida allo slicing***][SLICING_GUIDE].
#### <a id="download_it"> :page_with_curl: Famosi siti web per il download gratuito di modelli 3D </a>
  - [thingiverse](https://www.thingiverse.com/)  
  - [printables](https://www.printables.com/)  
  - [youmagine](https://www.youmagine.com/)   
## Passaggio 6. Stampa il tuo modello 3D
Dopo averlo affettato, copia il file gcode generato sulla scheda SD e quindi stampalo seguendo il [**passaggio 4**](#passaggio-4-stampa-del-modello-3d-di-prova).
## Passaggio 7. Per utilizzare le funzionalità avanzate
Dopo aver compreso appieno tutte le operazioni di base, è possibile provare alcune funzioni avanzate di questa macchina.
Per ulteriori dettagli, fare riferimento alla [**Guida all'uso delle funzionalità avanzate**][ADVANCE_FEATURES].

-----
<a id="RU"></a>

# Z8P-MK2 Пошаговое руководство [:arrow_heading_up:](#choose-language)
Если вы новичок в работе с 3D-принтерами и вам нужно прочитать так много документации, вы, возможно, не знаете, с чего начать. Не волнуйтесь, дальше мы шаг за шагом углубимся в детали этих документов.    
Короче говоря, то, что вам нужно сделать, включает в себя следующие 4 шага: **Установите устройство >> Печать тестового файла >> Нарезка собственного 3D-файла >> Печать 3D-файла**.    
Прежде всего, мы рекомендуем вам [:arrow_down: **загрузить все документы**][USER_GUIDE], сохранить их на своем компьютере и добавить эту веб-страницу в избранное вашего браузера.
## Шаг 1. Установите машину и проводку.
- **Монтаж**. Чтобы установить устройство, обратитесь к [:book: **руководству по установке**][INSTALLATION_GUIDE] и [ :clapper: **видеоруководству по установке**][INSTALL_VIDEO].
- **Проводка**. Процесс подключения заключается в вставке вилки в соответствующую розетку. На что нужно обратить внимание, так это на то, чтобы вилка полностью вставлена в розетку. Особенно для тех 2-контактных розеток, у которых иногда плохой контакт. :warning: При подключении печатающей головки (хотэнд-сборки) внимательно сверьтесь с изображениями в руководстве по установке и обратите внимание на цвет разъемов и цвет проводов.
## Шаг 2. Включите компьютер и выполните простое тестирование и проверку.
- **Включить**. Прежде чем включать питание переменного тока, проверьте, установлен ли селекторный переключатель источника питания 110 В/220 В в правильное положение ([**см. это изображение**][IMG_ACSWITCH]). После этого вы сможете [**включить питание устройства**][POWER_ON].       :warning: Обратите внимание, что машина имеет 2 выключателя питания: один — ***выключатель переменного тока*** (красный переключатель на задней стороне блока управления, рядом с розеткой переменного тока), а другой — ***выключатель постоянного тока. ***(круглый металлический кнопочный переключатель на правой стороне блока управления), сначала необходимо включить переключатель переменного тока, а затем нажать и **удерживать переключатель постоянного тока около 5 секунд** (отпускать до тех пор, пока на ЖК-дисплее не появится покажите логотип ZONESTAR), чтобы включить машину.
- **Просто тест**. После включения питания вы можете управлять меню на ЖК-экране ([**Описание ЖК-меню**][LCD_MENU]), чтобы проверить, может ли машина работать нормально, выполнив следующие действия:
   - **Подготовка>>Авто Домой>>Дом Все**. Этот шаг заключается в том, чтобы вернуть печатающую головку машины в исходное положение.
   - **Подготовка>>Температура>>Предварительный нагрев PLA**. Этот шаг заключается в проверке горячего конца и возможности нормального нагрева горячего стола. На этом этапе, когда температура сопла превышает 60 градусов, вы должны увидеть вращающийся вентилятор на **правой стороне** печатающей головки (горячий конец). Этот вентилятор называется «вентилятор охлаждения горячего конца».
   - **Подготовка>>Температура>>ВЕНТИЛЯТОР**. Нажмите ручку и установите скорость вентилятора на 255, вентилятор **слева вверх** должен вращаться.
     После того, как вы выполнили вышеуказанные 3 шага и установили, что машина работает нормально, вы можете перейти к следующим шагам. Если вы обнаружите, что какая-либо часть не работает должным образом, дважды проверьте проводку или выполните «автоматическое тестирование электроники». (см. [:clapper: **видеоурок по автоматическому тестированию машины**][AUTOTEST_VIDEO]).
## Шаг 3. Выровняйте кровать
Перед печатью тестового файла необходимо выполнить простое выравнивание стола, чтобы установить высоту между соплом и столом (печатной платформой), чтобы нить могла хорошо приклеиться к столу при печати. Чтобы сделать это, обратитесь к [**выровняйте кровать**][LEVEL_BED].
## Шаг 4. Распечатайте тестовую 3d модель
3D-принтеры FDM могут распознавать только файлы gcode, нам нужно скопировать файлы gcode на SD-карту, а затем вставить SD-карту в слот SD-карты 3D-принтера, а затем запустить ЖК-экран, чтобы начать печать.
:warning: Даже если вы знакомы с 3D-принтерами, рекомендуется распечатать хотя бы одну тестовую 4-цветную модель, чтобы убедиться, что аппарат работает нормально.
- **4.1 Печать одноцветного тестового файла**
   - **Подготовьте файл gcode**. [:arrow_down: **загрузите zip-файл xyz_cube**][XYZ_CUBE] и разархивируйте его на ПК, а затем скопируйте **xyz_cube.gcode** на SD-карту. Подключите SD-карту к SD-разъему машины.
   - **Загрузите нить**. Обратитесь к [:book: **здесь**][LOAD_FILAMENT], чтобы загрузить все 4 нити в экструдеры и горячий конец.     
     ***:warning: для хотэнда M4V6 вам необходимо загрузить 4 нити накаливания в хотэнд, даже если вы печатаете одноцветные 3D-отпечатки.***  
   - **Печать с SD-карты**. Переместите элемент в элемент **Печать** на ЖК-экране, нажмите ручку и выберите файл **xyz_cube.gcode**, нажмите ручку, чтобы начать печать.
   - **Точная настройка высоты сопла**. Подождите, пока сопло и нагревательный стол нагреются, и следите за расстоянием от сопла до стола при печати первого слоя. Если он слишком толстый или слишком близкий, дважды щелкните ручку ЖК-экрана, чтобы открыть меню **«маленького шага»**. , а затем поверните ручку, чтобы точно настроить расстояние от сопла до станины.
   - **Дождитесь завершения печати**.
- **4.2 Распечатка 4-цветного тестового файла**
   - **Подготовьте файл gcode**. [:arrow_down: **загрузите ZIP-файл M4_4CTest**][M4_4CTEST] и разархивируйте его на ПК, а затем скопируйте **M4_4CTest.gcode** на SD-карту. Подключите SD-карту к SD-разъему машины.
   - **Загрузите нити**. Обратитесь к [:book: **здесь**][LOAD_FILAMENT], чтобы загрузить все 4 нити в экструдеры и горячий конец.
   - **Печать с SD-карты**. Переместите элемент в элемент **Печать** на ЖК-экране, нажмите ручку и выберите файл **M4_4CTest.gcode**, нажмите ручку, чтобы начать печать.
   - **Точная настройка высоты сопла**. Подождите, пока сопло и нагревательный стол нагреются, и следите за расстоянием от сопла до стола при печати первого слоя. Если он слишком толстый или слишком близкий, дважды щелкните ручку ЖК-экрана, чтобы открыть меню **маленького шага**. , а затем поверните ручку, чтобы точно настроить расстояние от сопла до станины.
   - **Дождитесь завершения печати**.
## Шаг 5. Нарезка собственной 3d-модели
- Перед печатью собственных 3D-моделей вам необходимо преобразовать файл 3D-модели (файл формата stl/obj/AMF, который [скачан из Интернета](#download_ru) или нарисован самостоятельно) в файл gcode, сохраните этот файл gcode. на SD-карту, а затем подключите SD-карту к 3D-принтеру.
   :pushpin: **Процесс преобразования 3D-модели в файл gcode называется *нарезкой***.
- Во-первых, вам необходимо загрузить программное обеспечение для нарезки и установить его на свой компьютер, а также установить параметры вашего устройства в программном обеспечении для нарезки или загрузить предварительно заданный файл вашего устройства, установленный производителем 3D-принтера.
- Далее вам необходимо запустить программное обеспечение для нарезки, а также, возможно, потребуется установить некоторые параметры нарезки в соответствии с характеристиками файла 3D-модели, а затем выполнить нарезку.
   :pushpin: Рекомендуемое программное обеспечение для нарезки — **PrusaSlicer**. Чтобы узнать, как загрузить, установить и использовать **PrusaSlicer**, обратитесь к [***Руководству по нарезке***][SLICING_GUIDE].
#### <a id="download_ru"> :page_with_curl: Известные веб-сайты бесплатной загрузки 3D-моделей </a>
  - [thingiverse](https://www.thingiverse.com/)  
  - [printables](https://www.printables.com/)  
  - [youmagine](https://www.youmagine.com/)   
## Шаг 6. Печать собственной 3d-модели
После нарезки скопируйте сгенерированный файл gcode на SD-карту, а затем распечатайте его, выполнив [**шаг 4**](#шаг-4-распечатайте-тестовую-3d-модель).
## Шаг 7. Использование дополнительных функций
После того, как вы полностью поймете все основные операции, вы сможете опробовать некоторые дополнительные функции этой машины.
Подробную информацию см. в [**Руководстве по использованию дополнительных функций**][ADVANCE_FEATURES].

-----
<a id="JP"></a>

# Z8P-MK2 ステップバイステップガイド [:arrow_heading_up:](#choose-language)
3D プリンターの初心者の場合、読むべきドキュメントが多すぎて、どこから始めればよいかわからないかもしれません。 心配しないでください。これらのドキュメントの詳細については、次から順に説明していきます。    
一言で言えば、行う必要があることは以下の 4 つのステップです: **マシンのインストール >> テスト ファイルの印刷 >> 独自の 3D ファイルのスライス >> 3D ファイルの印刷**。    
まず、[:arrow_down: **すべてのドキュメントをダウンロード**][USER_GUIDE] してコンピュータに保存し、この Web ページをブラウザのお気に入りに追加することをお勧めします。
## ステップ 1. 機械の設置と配線
- **インストール**。 マシンをインストールするには、[:book: **インストール ガイド**][INSTALLATION_GUIDE] および [:clapper: **インストール ビデオ チュートリアル**][INSTALL_VIDEO]を参照してください。
- **配線**。 配線のプロセスは基本的に、対応するソケットにプラグを挿入することです。 注意する必要があるのは、プラグがソケットに完全に差し込まれていることを確認することです。 特に接触不良を起こすことがある2PINソケットに最適です。 :warning: プリント ヘッド (ホットエンド アセンブリ) を配線するときは、インストール ガイドの図をよく参照し、コネクタの色とワイヤの色の両方を区別するように注意してください。
## ステップ 2. マイシェの電源を入れ、簡単なテストと検証を実行します。
- **電源オン**。 AC 電源を入れる前に、110V/220V 電源切り替えスイッチの設定が正しい位置に設定されているかどうかを確認してください ([**この図を参照**][IMG_ACSWITCH])。 そして、[**マシンの電源を入れる**][POWER_ON]することができます。 :warning: マシンには 2 つの電源スイッチがあることに注意してください。1 つは ***AC スイッチ*** (コントロール ボックスの背面、AC 電源ソケットの近くにある赤いスイッチ) で、もう 1 つは ***DC スイッチです。 ***(コントロール ボックスの右側にある丸い金属製の押しボタン スイッチ)、最初に AC スイッチをオンにしてから、**DC スイッチを約 5 秒間押し続ける必要があります** (LCD ネジが固定されるまで放します) ZONESTAR ロゴを表示）して本機の電源を入れます。
- **単純にテスト**。 電源を入れた後、LCD 画面上のメニュー ([**LCD メニューの説明**][LCD_MENU]) を操作して、マシンが正常に動作するかどうかを確認できます。手順は次のとおりです。
   - **準備>>オートホーム>>ホームオール**。 本機のプリントヘッドを原点位置に戻す作業です。
   - **準備>>温度>>PLAを予熱**。 このステップは、ホットエンドとホットベッドが正常に加熱できることを確認するためのものです。 このステップでは、ノズルの温度が 60 度を超えると、プリント ヘッド (ホット エンド) の **右側** にあるファンが回転するのが見えます。このファンは「ホット エンド冷却ファン」と呼ばれます。
   - **準備>>温度>>FAN**。 ノブを押してファン速度を 255 に設定すると、**左側が上**のファンが回転します。
     上記の 3 つの手順を実行すると、基本的にマシンが正常に動作していると判断され、次の手順に進むことができます。 部品が正常に動作していない場合は、配線を再確認するか、「電子自動テスト」を実行してチェックしてください。 ([:clapper: **マシン自動テスト ビデオ チュートリアル**][AUTOTEST_VIDEO] を参照)。
## ステップ 3. ベッドを水平にします
テストファイルを印刷する前に、印刷時にフィラメントがベッドにしっかりと貼り付くように、簡単なベッドレベリングを行ってノズルとベッド (印刷プラットフォーム) の間の高さを設定する必要があります。 これを行うには、[**ベッドを水平にする**][LEVEL_BED]を参照してください。
## ステップ 4. 3D モデルの印刷テスト
FDM 3D プリンタは gcode ファイルのみを認識できるため、gcode ファイルを SD カードにコピーし、SD カードを 3D プリンタの SD カード スロットに挿入し、LCD 画面を操作して印刷を開始する必要があります。
:warning: 3D プリンタに慣れている場合でも、マシンが正常に動作することを確認するために、少なくとも 1 つの 4 色のテスト モデルを印刷することをお勧めします。
- **4.1 1 色のテスト ファイルを印刷する**
   - **gcode ファイルを準備します**。 [:arrow_down: **xyz_cube zip ファイルをダウンロード**][XYZ_CUBE] を PC 上で解凍し、**xyz_cube.gcode** を SD カードにコピーします。 SD カードをマシンの SD ソケットに差し込みます。
   - **フィラメントをロード**。 4 本のフィラメントすべてを押出機とホットエンドにロードするには、[:book: **こちら**][LOAD_FILAMENT] を参照してください。   
     ***:warning: M4V6 ホットエンドの場合、1 色の 3D プリントを印刷する場合でも、ホットエンドに 4 つのフィラメントをロードする必要があります。***
   - **SD カードから印刷**。 LCD 画面上の **印刷** 項目に項目を移動し、ノブをクリックして **xyz_cube.gcode** ファイルを選択し、ノブをクリックして印刷を開始します。
   - **ノズルの高さを微調整します**。 ノズルとホットベッドが加熱されるのを待ち、最初のレイヤーを印刷するときにノズルからベッドまでの距離に注意してください。距離が太すぎるか近すぎる場合は、LCD 画面のノブをダブルクリックして **「ベイビーステップ」** メニューを開きます 、ノブを回してノズルからベッドまでの距離を微調整します。
   - **印刷が完了するまで待ちます**。
- **4.2 4 色のテスト ファイルを印刷する**
   - **gcode ファイルを準備します**。 [:arrow_down: **M4_4CTest zip ファイルをダウンロード**][M4_4CTEST] を PC で解凍し、**M4_4CTest.gcode** を SD カードにコピーします。 SD カードをマシンの SD ソケットに差し込みます。
   - **フィラメントをロード**。 4 本のフィラメントすべてを押出機とホットエンドにロードするには、[:book: **こちら**][LOAD_FILAMENT] を参照してください。
   - **SD カードから印刷**。 LCD 画面上の **印刷** 項目に項目を移動し、ノブをクリックして **M4_4CTest.gcode** ファイルを選択し、ノブをクリックして印刷を開始します。
   - **ノズルの高さを微調整します**。 ノズルとホットベッドが加熱されるのを待ち、最初のレイヤーを印刷するときにノズルからベッドまでの距離に注意してください。距離が太すぎるか近すぎる場合は、LCD 画面のノブをダブルクリックして **「ベイビーステップ」** メニューを開きます 、ノブを回してノズルからベッドまでの距離を微調整します。
   - **印刷が完了するまで待ちます**。
## ステップ 5. 独自の 3D モデルをスライスする
- 独自の 3D モデルを印刷する前に、3D モデル ファイル ([インターネットからダウンロード](#download_jp) または自分で描画した stl/obj/AMF 形式のファイル) を gcode ファイルに変換し、この gcode ファイルを保存する必要があります。 を SD カードにコピーし、SD カードを 3D プリンタに接続します。
   :pushpin: **3D モデルを gcode ファイルに変換するプロセスは *スライス*** と呼ばれます。
- まず、スライス ソフトウェアをダウンロードしてコンピュータにインストールし、スライス ソフトウェアでマシンのパラメータを設定するか、3D プリンタ メーカーによって設定されたマシンのプリセット ファイルをロードする必要があります。
- 次に、スライス ソフトウェアを実行する必要があります。また、3D モデル ファイルの特性に応じていくつかのスライス設定を行ってからスライスを実行する必要がある場合もあります。
   :pushpin: 推奨されるスライス ソフトウェアは **PrusaSlicer** です。**PrusaSlicer** のダウンロード、インストール、使用方法については、[***スライス ガイド***][SLICING_GUIDE] を参照してください。
#### <a id="download_jp"> :page_with_curl: 有名な無料 3D モデル ダウンロード Web サイト </a>
  - [thingiverse](https://www.thingiverse.com/)  
  - [printables](https://www.printables.com/)  
  - [youmagine](https://www.youmagine.com/)   
## ステップ 6. 独自の 3D モデルを印刷する
スライス後、生成された gcode ファイルを SD カードにコピーし、[**ステップ 4**](#ステップ-4-3d-モデルの印刷テスト) に従って印刷します。
## ステップ 7. 高度な機能を使用するには
基本操作をすべて理解したら、本機の高度な機能を試してみましょう。
詳細については、[**高度な機能利用ガイド**][ADVANCE_FEATURES]を参照してください。


-----
<a id="KR"></a>

# Z8P-MK2 단계별 가이드 [:arrow_heading_up:](#choose-language)
3D 프린터 초보자이고 읽어야 할 문서가 너무 많으면 어디서부터 시작해야 할지 모를 수도 있습니다. 걱정하지 마십시오. 다음 단계에서 이러한 문서의 세부 사항을 살펴보겠습니다.    
한마디로, 당신이 해야 할 일은 아래 4단계를 포함합니다: **머신 설치 >> 테스트 파일 인쇄 >> 자신의 3D 파일 슬라이싱 >> 3D 파일 인쇄**.    
우선, [:arrow_down: **모든 문서를 다운로드**][USER_GUIDE]하여 컴퓨터에 저장하고 이 웹페이지를 브라우저의 즐겨찾기에 추가하는 것이 좋습니다.
## Step 1. 기계 설치 및 배선
- **설치**. [:book: **설치 가이드**][INSTALLATION_GUIDE] 및 [ :clapper: **설치 비디오 튜토리얼**][INSTALL_VIDEO]을 참조하여 머신을 설치하세요.
- **배선**. 배선 과정은 기본적으로 해당 소켓에 플러그를 삽입하는 것입니다. 주의할 점은 플러그가 소켓에 완전히 꽂혀 있는지 확인하는 것입니다. 특히 접촉 불량이 발생하는 2PIN 소켓의 경우 더욱 그렇습니다. :warning: 프린트 헤드(핫엔드 어셈블리)를 배선할 때 설치 가이드의 그림을 주의 깊게 참조하고 커넥터 색상과 와이어 색상을 모두 구별하도록 주의하십시오.
## Step 2. 본체의 전원을 켜고 간단하게 테스트 및 검증을 합니다.
- **전원 켜짐**. AC 전원을 켜기 전에 110V/220V 전원 공급 선택 스위치의 설정이 올바른 위치로 설정되어 있는지 확인하십시오([**이 그림 참조**][IMG_ACSWITCH]). 그런 다음 [**머신의 전원을 켭니다**][POWER_ON]할 수 있습니다. :warning: 기기에는 2개의 전원 스위치가 있습니다. 하나는 ***AC 스위치***(제어 상자 뒷면, AC 전원 소켓 근처에 있는 빨간색 스위치)이고 다른 하나는 ***DC 스위치입니다. ***(컨트롤 박스 오른쪽에 있는 둥근 금속 푸시 버튼 스위치) 먼저 AC 스위치를 켠 다음 **DC 스위치를 약 5초 동안** 누르고 있어야 합니다(LCD 나사가 나올 때까지 놓습니다). ZONESTAR 로고 표시)를 눌러 기기를 켜세요.
- **간단한 테스트**. 전원을 켠 후 LCD 화면의 메뉴([**LCD 메뉴 설명**][LCD_MENU])를 조작하여 기기가 정상적으로 작동하는지 확인할 수 있습니다. 단계는 다음과 같습니다.
   - **준비>>자동 홈>>모두 홈**을 준비하세요. 이 단계는 기계의 프린트 헤드를 원점 위치로 되돌리는 단계입니다.
   - **준비>>온도>>PLA 예열**. 이 단계는 핫엔드를 확인하고 핫베드가 정상적으로 가열될 수 있는지 확인하는 단계입니다. 이 단계에서 노즐의 온도가 60도를 초과하면 프린트 헤드(핫 엔드)의 **오른쪽**에 있는 팬이 회전하는 것을 볼 수 있으며, 이 팬을 "핫 엔드 냉각 팬"이라고 합니다.
   - **준비>>온도>>팬**을 준비하세요. 손잡이를 누르고 팬 속도를 255로 설정하면 **왼쪽이 위로** 팬이 회전해야 합니다.
     위의 3단계를 수행한 후 기본적으로 기기가 정상적으로 작동하는 것으로 확인되면 다음 단계를 진행할 수 있습니다. 부품이 제대로 작동하지 않는 경우 배선을 다시 확인하거나 "전자 장치 자동 테스트"를 수행하여 확인하십시오. ([ :clapper: **머신 자동 테스트 동영상 튜토리얼**][AUTOTEST_VIDEO] 참조).
## 3단계. 침대 수평 맞추기
테스트 파일을 출력하기 전 간단한 베드 레벨링을 하여 노즐과 베드(프린팅 플랫폼) 사이의 높이를 설정해야 프린팅 시 필라멘트가 베드에 잘 붙을 수 있습니다. [**침대 수평 맞추기**][LEVEL_BED]를 참조하여 수행하세요.
## 4단계. 3D 모델 프린트 테스트
FDM 3D 프린터는 gcode 파일만 인식할 수 있습니다. gcode 파일을 SD 카드에 복사한 다음 SD 카드를 3D 프린터의 SD 카드 슬롯에 삽입한 다음 LCD 화면을 조작하여 인쇄를 시작해야 합니다.
:warning:3D프린터에 익숙하시더라도 4색 테스트 모델을 1개 이상 출력하여 기계가 정상적으로 작동하는지 확인하시는 것을 권장합니다.
- **4.1 단색 테스트 파일 인쇄**
   - **gcode 파일을 준비하세요**. [:arrow_down: **xyz_cube zip 파일 다운로드**][XYZ_CUBE] PC에서 압축을 푼 후 **xyz_cube.gcode**를 SD 카드에 복사하세요. SD 카드를 기기의 SD 소켓에 연결합니다.
   - **필라멘트를 로드하세요**. 필라멘트 4개를 모두 압출기와 핫엔드에 로드하려면 [:book: **여기**][LOAD_FILAMENT]를 참조하세요.     
     ***:warning: M4V6 핫엔드의 경우 단색 3D 프린트를 인쇄하더라도 핫엔드에 필라멘트 4개를 로드해야 합니다.***
   - **SD 카드에서 인쇄**. LCD 화면의 **Print** 항목으로 항목을 이동한 후 손잡이를 클릭하고 **xyz_cube.gcode** 파일을 선택한 후 손잡이를 클릭하여 인쇄를 시작합니다.
   - **노즐 높이를 미세 조정하세요**. 노즐과 핫베드가 가열될 때까지 기다렸다가 첫 번째 레이어를 인쇄할 때 노즐에서 베드까지의 거리를 확인하세요. 너무 뚱뚱하거나 너무 가까운 경우 LCD 화면의 손잡이를 두 번 클릭하여 **"베이비스텝"** 메뉴를 엽니다. 을 누른 다음 손잡이를 돌려 노즐에서 베드까지의 거리를 미세 조정합니다.
   - **인쇄가 완료될 때까지 기다립니다**.
- **4.2 4색 테스트 파일 인쇄**
   - **gcode 파일을 준비하세요**. [:arrow_down: **M4_4CTest zip 파일 다운로드**][M4_4CTEST] PC에서 압축을 푼 다음 **M4_4CTest.gcode**를 SD 카드에 복사합니다. SD 카드를 기기의 SD 소켓에 연결합니다.
   - **필라멘트를 로드합니다**. [:book: **여기**][LOAD_FILAMENT]를 참조하여 필라멘트 4개를 모두 압출기와 핫엔드에 로드하세요.
   - **SD 카드에서 인쇄**. LCD 화면에서 항목을 **Print** 항목으로 이동하고 손잡이를 클릭한 후 **M4_4CTest.gcode** 파일을 선택하고 손잡이를 클릭하여 인쇄를 시작합니다.
   - **노즐 높이를 미세 조정하세요**. 노즐과 핫베드가 가열될 때까지 기다렸다가 첫 번째 레이어를 인쇄할 때 노즐에서 베드까지의 거리를 확인하세요. 너무 뚱뚱하거나 너무 가까운 경우 LCD 화면의 손잡이를 두 번 클릭하여 **"베이비스텝"** 메뉴를 엽니다. 을 누른 다음 손잡이를 돌려 노즐에서 베드까지의 거리를 미세 조정합니다.
   - **인쇄가 완료될 때까지 기다립니다**.
## 5단계. 나만의 3D 모델 슬라이스하기
- 자신만의 3D 모델을 인쇄하기 전에 3D 모델 파일([인터넷에서 다운로드](#download_kr)하거나 직접 그리는 stl/obj/AMF 형식 파일)을 gcode 파일로 변환하고 이 gcode 파일을 저장해야 합니다. SD 카드에 연결한 다음 SD 카드를 3D 프린터에 연결하세요.     
   :pushpin: **3D 모델을 gcode 파일로 변환하는 과정을 *슬라이싱***이라고 합니다.
- 먼저 슬라이싱 소프트웨어를 다운로드하여 컴퓨터에 설치하고 슬라이싱 소프트웨어에서 기계의 매개변수를 설정하거나 3D 프린터 제조업체에서 설정한 기계의 사전 설정 파일을 로드해야 합니다.
- 다음으로 슬라이싱 소프트웨어를 실행해야 하며, 3D 모델 파일의 특성에 따라 일부 슬라이싱 설정을 지정한 다음 슬라이싱을 수행해야 할 수도 있습니다.     
   :pushpin: 권장되는 슬라이싱 소프트웨어는 **PrusaSlicer**입니다. **PrusaSlicer** 다운로드, 설치 및 사용 방법은 [***슬라이싱 가이드***][SLICING_GUIDE]를 참조하세요.
#### <a id="download_kr"> :page_with_curl: 유명한 무료 3D 모델 다운로드 웹사이트 </a>
  - [thingiverse](https://www.thingiverse.com/)  
  - [printables](https://www.printables.com/)  
  - [youmagine](https://www.youmagine.com/)   
## 6단계. 나만의 3D 모델 프린팅
슬라이스 후 생성된 gcode 파일을 SD 카드에 복사한 후 [**4단계**](#4단계-3d-모델-프린트-테스트)에 따라 인쇄합니다.
## Step 7. 고급 기능을 사용하려면
모든 기본 작동을 완전히 이해한 후에는 이 기기의 일부 고급 기능을 사용해 볼 수 있습니다.
자세한 내용은 [**고급 기능 사용 가이드**][ADVANCE_FEATURES]를 참조하세요.

-----
[USER_GUIDE]: https://downgit.github.io/#/home?url=https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2
[INSTALLATION_GUIDE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide/readme.md
[INSTALL_VIDEO]: https://youtu.be/-oieO7U0LCc
[IMG_ACSWITCH]: https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/1-Installation_Guide/pic/selectAC.png
[POWER_ON]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#power-on
[LCD_MENU]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/DWIN_LCD_screen_Menu_Description
[LEVEL_BED]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#level-the-bed
[XYZ_CUBE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/3-TestGcode/xyz_cube.zip
[LOAD_FILAMENT]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#load-filaments
[M4_4CTEST]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/3-TestGcode/M4_4CTest.zip
[SLICING_GUIDE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme.md
[AUTOTEST_VIDEO]: https://youtu.be/iSsuy2ePWw8
[ADVANCE_FEATURES]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#advance-features