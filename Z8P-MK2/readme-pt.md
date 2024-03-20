## <a id="choose-language">:globe_with_meridians: Choose language </a>
[![](./lanpic/EN.png)](./readme.md)
[![](./lanpic/ES.png)](./readme-es.md)
[![](./lanpic/PT.png)](./readme-pt.md)
[![](./lanpic/FR.png)](./readme-fr.md)
[![](./lanpic/DE.png)](./readme-de.md)
[![](./lanpic/IT.png)](./readme-it.md)
[![](./lanpic/RU.png)](./readme-ru.md)
[![](./lanpic/JP.png)](./readme-jp.md)
[![](./lanpic/KR.png)](./readme-kr.md)
<!-- [![](./lanpic/SA.png)](./readme-ar.md) -->

------
# Z8P-MK2 Guia do Utilizador
## :warning: ATENÇÃO POR FAVOR
### loudspeaker Antes de usar a máquina, leia [:book:"Precauções para usar M4V6"](https://github.com/ZONESTAR3D/Upgrade-kit-guide/blob/main/HOTEND/M4/M4_V6/M4V6_Precaution.md) com cuidado.
### loudspeaker Deve carregar 4 filamentos no hotend M4V6 simultaneamente, a operação incorreta pode bloquear o hotend de cores misturadas. Se o bloqueio do hot end for causado por operação incorreta, não será coberto pela garantia. Para saber como carregar filamentos, consulte [:book: this guide](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/readme.md#load-filaments).
### loudspeaker Se você é um iniciante em impressora 3D, leia atentamente o [:book: Guia Passo a Passo][step_by_step_guide] e siga o guia para fazer passo a passo. Se você tem experiência em impressoras 3D, leia também brevemente o [:book: Guia passo a passo][step_by_step_guide] pelo menos e certifique-se de saber como carregar o filamento no hot end M4.

### [:clapper: Assistir ao tutorial em vídeo](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/6-VideoTutorial)
Criamos muitos tutoriais em vídeo para esta máquina, clique em [:clapper:**aqui**](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/6-VideoTutorial) para assistir.

### :file_folder: [1.Guia de instalação][INSTALLATION]
- **[:book: Guia de instalação][INSTALLATION]**
- **[:blue_book:Arquivo PDF do guia de instalação e uso rápido](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/Z8PMK2_Installation_and_quick_use_guide.pdf)**
- **[:clapper: Tutorial em vídeo de instalação](https://youtu.be/-oieO7U0LCc)**
- **[:book: descrição do menu da tela LCD][LCD_MENU]**
- **[:art: Bloco de fiação](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide/Z8PMK2_Wiring_Block.jpg)**
- **[:art: Diagrama de fiação](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide/Z8PM4-MK2_Wiring_Diagram.jpg)**

### :file_folder: [2.Guia de operação][Operation_Guide]
- **[:book: Guia Básico de Operação][Operation_Guide]**
- **[:book: Guia do usuário do M4V6 Mix Color Hotend][M4V6_Guide]**
- **Recursos avançados**
   - **[Desligamento automático :book:][auto_shutdown] [:clapper:](https://youtu.be/SJLpmJL-tG4)**
   - **[Mistura de impressão em cores :book:][mix_color]**
   - **[Nivelamento automático da cama :book:][auto_leveling] [:clapper:](https://youtu.be/Zoyl6PybsUk)**
   - **[Recuperação de perda de energia :clapper:](https://youtu.be/f-PpasByiiE)**
   - **[Retração automática :book:][Auto_Retraction]**
- **[:book: Imprimir do PC][PrintFromPC]**
  
### :file_folder: [3.Imprimir arquivos Gcode de teste][Test_gcode]
#### :arrow_down: [Baixar arquivo gcode de teste][Test_gcode]
#### :pencil: O que é código G na impressão 3D?
Código G são informações ou instruções que a impressora 3D requer para imprimir um objeto tridimensional, é a linguagem que a impressora 3D pode entender. O código G é gerado pelo seu software de fatiamento, traduzindo um arquivo de modelagem 3D padrão, como um arquivo STL, no código que sua impressora 3D específica compreenderá.
:page_with_curl: [**Referência 1**](https://beginner3dprinting.com/what-is-g-code-in-3d-printing/) :page_with_curl: [**Referência 2**](https://www.reprap.org/wiki/G-code)

### :file_folder: [4.Guia de fatiamento][Slicing_Guide_Z8P]
#### :arrow_down: [Baixe o software silcer e leia o guia de fatiamento][Slicing_Guide_Z8P]
#### :pencil: O que é fatiar na impressão 3D?
Slicing é um software que todos usam ao criar objetos e produtos em uma impressora 3D. O software fornece à impressora um caminho a seguir. O software de fatiamento pega sua imagem e a converte em códigos G que sua impressora 3D pode entender. Esses códigos G são um tipo de instrução sobre como a impressora precisa imprimir seu design.:page_with_curl: [**Referência 1**](https://loveandrobots.com/what-is-slicing-in-3d-printing/ ) :page_with_curl: [**Referência 2**](https://en.wikipedia.org/wiki/Slicer_(3D_printing))

### :file_folder: [5. Imprimir peças stl][PrintParts]
#### :arrow_down: [Baixar arquivos stl das peças de impressão][PrintParts]

### :link: [6.Firmware](https://github.com/ZONESTAR3D/Firmware/tree/master/Z8/Z8P/Z8PM4Pro-MK2)
- **[:arrow_down: Arquivo bin do firmware](https://github.com/ZONESTAR3D/Firmware/tree/master/Z8/Z8P/Z8PM4Pro-MK2).**
- **[:arrow_down: Código-fonte do firmware](https://github.com/ZONESTAR3D/source-code-for-3d-printer).**
#### :pencil: O que é arquivo bin e código fonte?
> **Arquivo bin de firmware** é a memória exata gravada na memória flash incorporada.
> **Código-fonte do firmware** é a parte central do firmware. Todo o firmware pode ser considerado como diferentes submódulos. Ele está dividido em vários subarquivos. Esses arquivos são chamados de arquivos de origem. E todos os arquivos do programa são chamados de arquivo fonte ou código fonte. Agora nosso código fonte de firmware é baseado em [**marlin**](https://www.marlinfw.org).

### 7.Solução de problemas
- :book: [**Soluções de problemas para Z8P**](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/readme.md)

### Recursos atualizáveis  
- **Adesivo de colchão térmico PEI Springs:+1:**      
O adesivo para cama quente de chapa de aço com mola PEI é mais durável do que o adesivo original para cama quente. Com a cama quente lisa de um lado voltada para cima, também pode tornar a parte inferior da impressão mais lisa. **[:gift: Compre](http://bit.ly/3GbI9Sr) / [:gift: Compre](https://bit.ly/3VkmXOi)**
- **Extrusora de engrenagem dupla:+1:**    
A extrusora de engrenagem dupla pode aumentar significativamente a força para empurrar/puxar o filamento, reduzindo bastante a probabilidade de defeitos de impressão e falhas de impressão causadas pelo deslizamento do filamento na extrusora.**[:book: User guide](https://bit.ly/UM_BMG)** **[:gift: Compre](https://bit.ly/46Vyd9H) / [:gift: Compre](https://bit.ly/AE_4xBMG)**
- **Sensor de esgotamento de filamento :+1:**   
Ao atualizar este item, você pode controlar remotamente sua impressora 3D. **[:book: Guia do usuário][guide_FROD]** [:gift:Comprar](https://www.aliexpress.com/item/4001309957376.html)
- **Módulo de controle sem fio WiFi  :+1:**    
Ao atualizar este item, você pode controlar remotamente sua impressora 3D. **[:book: Guia do usuário][guide_WIFI]** [:gift:Comprar](https://www.aliexpress.com/item/1005002378551489.html)  
- **Hotend de cores sem mistura  :+1:**   
Ao atualizar este item, o tamanho da torre principal colorida para impressão de modelos multicoloridos é muito menor. **[:book: Guia do usuário][guide_E4]** [:gift:Comprar](https://www.aliexpress.com/item/1005002951777699.html)
- **Extrusora de acionamento direto :+1:**   
Ao atualizar este projeto, você pode imprimir materiais flexíveis (como filamento TPU). **[:book: Guia do usuário][guide_DDE]** [:gift:Comprar](https://www.aliexpress.com/item/1005002847644867.html)
- **Motor laser**    
Ao atualizar este item, você pode transformar sua impressora 3D em uma simples máquina de gravação a laser. Módulos de laser de maior potência podem melhorar a velocidade de gravação ou suportar materiais com ponto de fusão mais alto. **[:book: Guia do usuário][guide_Laser]** [:gift:Comprar](https://www.aliexpress.com/item/1005004908160260.html)

-----
[step_by_step_guide]: https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step.md
[INSTALLATION]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide
[Operation_Guide]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide
[M4V6_Guide]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/HOTEND/M4%20%204-IN-1-OUT%20Mixing%20Color%20Hotend/M4_V6
[Test_gcode]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/3-TestGcode
[Slicing_Guide_Z8P]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide
[PrintParts]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/5-PrintParts/
[LCD_MENU]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/DWIN_LCD_screen_Menu_Description
[mix_color]: https://github.com/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color
[auto_leveling]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling
[auto_shutdown]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Shut_Down
[Auto_Retraction]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Retraction
[PrintFromPC]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/PrintFromPC
[guide_FROD]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/FROD
[guide_WIFI]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/FROD
[guide_E4]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/HOTEND/E4%204-IN-1-OUT%20Non-Mixing%20Color%20Hotend
[guide_DDE]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/Direct_Drive_Extrruder
[guide_Laser]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/Laser_Engraving
