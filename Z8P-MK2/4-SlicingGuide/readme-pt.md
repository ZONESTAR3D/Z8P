## <a id="choose-language">:globe_with_meridians: Choose language </a>
[![](../lanpic/EN.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme.md)
[![](../lanpic/ES.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-es.md)
[![](../lanpic/PT.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-pt.md)
[![](../lanpic/FR.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-fr.md)
[![](../lanpic/DE.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-de.md)
[![](../lanpic/IT.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-it.md)
[![](../lanpic/RU.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-ru.md)
[![](../lanpic/JP.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-jp.md)
[![](../lanpic/KR.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-kr.md)
<!-- [![](../lanpic/SA.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-ar.md) -->

----
# Manual de instalação e usuário do PrusaSlicer
Em primeiro lugar, as impressoras 3D FDM só podem processar arquivos gcode, enquanto os formatos padrão para arquivos gráficos 3D são geralmente stl, obj e amf etc.. Antes de imprimir arquivos de modelo 3D na impressora 3D FDM, você precisa converter arquivos gráficos 3D em arquivos gcode no computador, esse processo é chamado de ***"slicing"***. O software que suporta a conversão de arquivos gráficos 3D em arquivos gcode é chamado de software de fatiamento.
PrusaSlicer é um dos softwares de fatiamento mais populares da atualidade, particularmente adequado para impressoras 3D multicoloridas (multiextrusoras). Recomendamos o uso do software de fatiamento PrusaSlicer para gerar arquivos gcode.

----
## :book: Conteúdo
1. **[Baixar PrusaSlicer](#a1)**
2. **[Execute PrusaSlicer e escolha a impressora](#a2)**
3. **[Escolha as predefinições do sistema](#a3)**
4. **[Cortar modelo 3D de uma cor](#a4)**
5. **[Cortar modelo 3D multicolorido](#a5)**

## <a id="a1">1. Baixe o PrusaSlicer</a>
:clapper: [**Como baixar e instalar software de fatiamento**](https://youtu.be/SgyXD-kQIeo)
### ![](./pic/win.png) Para Windows
#### Clique [:arrow_down:**aqui**](https://github.com/ZONESTAR3D/Slicing-Guide/releases/tag/PrusaSlicer2.4.2) para baixar o software PrusaSlicer e salvá-lo em seu PC.
![](./pic/download.gif)
#### E descompacte o arquivo baixado em seu PC ou laptop
![](./pic/unzip.png)
### ![](./pic/macos.png) Para Macos ou Linux
- [Baixe o software PrusaSlicer com perfis zonestar](https://github.com/ZONESTAR3D/Slicing-Guide/releases/tag/2.4.2)

## <a id="a2">2. Execute o PrusaSlicer e escolha a impressora </a>
#### 2.1 Encontre o PrsuaSlicer.exe e clique nele para executar
![](./pic/run1.png)
#### 2.2 Escolha sua impressora, "Outros fornecedores>>Zonestar FFF>>modelo de sua impressora>>acabamento"
![](./pic/run2.png)

## <a id="a3">3. Escolha predefinições do sistema</a>
Escolha as predefinições do sistema de acordo com sua impressora, hotend e as cores que deseja imprimir:
![](./pic/run3.png)
- Se você precisar imprimir um modelo 3D de uma cor, escolha ***Z8 + One Color***.
- Se você imprimir um modelo 3D multicolorido, escolha ***Z8 + M4 HOTEND***.

## <a id="a4">4. Fatiar uma cor</a>
:clapper: [**Guia de fatiamento - para impressão em uma cor**](https://youtu.be/g-YSgV44Rik)
#### 4.1 escolha predefinições de impressora *Z8 + One Color*
![](./pic/slicing1C-1.png)
#### 4.2 carregar arquivo de modelo 3D (arquivo stl/obj/AMF etc.)
![](./pic/slicing1C-2.png)
#### 4.3 Escolha o tipo de filamento de impressão
![](./pic/slicing1C-3.png)
#### 4.4 Se necessário, você pode redimensionar, cortar e girar o modelo 3D
![](./pic/slicing1C-4.png)
#### 4.5 Defina as configurações de impressão: altura da camada, velocidade de impressão, suporte, preenchimento, etc.
![](./pic/slicing1C-5.png)    
Talvez seja necessário definir esses parâmetros de acordo com o formato do modelo e seus requisitos de qualidade de impressão. Para alguns modelos, o objeto ainda não pode ser impresso com sucesso se as configurações estiverem incorretas. Para obter detalhes, consulte:
- [**Introdução ao PrusaSlicer**](https://www.prusa3d.com/page/prusaslicer_424/)
- [**Manual do usuário Slic3r**](https://manual.slic3r.org/)
#### 4.6 Fatiamento
![](./pic/slicing1C-6.png)
#### 4.7 Visualize o resultado fatiado (arquivo gcode) e salve no arquivo gcode em seu PC e copie para o cartão SD
![](./pic/slicing1C-7.png)
## <a id="a5">5. Fatiar multicolorido </a>
- :clapper: [**Guia de fatiamento - para impressão multicolorida**](https://youtu.be/AIKrszmxvE4)
#### 5.1 escolha predefinições de impressora *Z8 + M4 hotend*
![](./pic/slicingM4-1.png)
#### 5.2 carregar arquivos de modelo 3D (arquivo stl/obj/AMF etc.)
![](./pic/slicingM4-2.png) ![](./pic/slicingM4-21.png)
##### :memo: Normalmente, o modelo dividido precisa imprimir multicolorido, ou seja, um modelo 3D foi dividido em vários arquivos STL de acordo com as cores, e esses arquivos usam a mesma posição da coordenada de origem para que possam ser mesclado corretamente.
##### :star2: PrusaSlicer tem um novo recurso muito poderoso. Ele pode [pintar cores para o modelo 3D](https://youtu.be/Yx4fKDRGEJ4). Com esta função, você pode converter um modelo 3D de uma cor em um modelo 3D de várias cores.
#### 5.3 Escolha o tipo de filamento de impressão - PLA e defina a cor do filamento
![](./pic/slicingM4-3.png)
#### 5.4 Atribuir extrusoras a diferentes peças
![](./pic/slicingM4-4.png)
#### 5.5 Se necessário, você pode redimensionar, cortar e girar o modelo 3D
![](./pic/slicingM4-5.png)
#### 5.6 Defina as configurações de impressão: altura da camada, velocidade de impressão, suporte, preenchimento, etc.
![](./pic/slicingM4-6.png)
Você precisa definir esses parâmetros de acordo com o formato do modelo e seus requisitos de qualidade de impressão. Mesmo para alguns modelos, a impressão não pode ser concluída normalmente sem suporte. Para obter detalhes, consulte:
- [**Introdução ao PrusaSlicer**](https://www.prusa3d.com/page/prusaslicer_424/)
- [**Manual do usuário Slic3r**](https://manual.slic3r.org/)    
:warning: Observe que *Retração quando a ferramenta está desativada* deve ser definido como 0.
![](./pic/slicingM4-7.jpg)
#### 5.7 Definir parâmetros para torre de limpeza
##### Você pode notar que um quadrado quadrado aparecerá na figura fatiada, que é chamado de "Wipe tower" no PrusaSlicer. Como para a impressora multicolorida, ao trocar de extrusora, ainda existem os filamentos de cores anteriores dentro do hotend, ela precisa ser limpa antes de imprimir outra cor.
![](./pic/slicingM4-71.png)
##### Para obter um melhor efeito de limpeza e minimizar o desperdício de filamento, podemos definir a quantidade de purga de cor de acordo com as diferentes cores. Preste atenção na tabela a seguir, as colunas mostram a cor do filamento da última extrusora impressa e as linhas mostram a cor do filamento da próxima extrusora a ser impressa.
##### Quando mudamos da extrusora com filamento de cor mais clara para a extrusora com consumíveis de cor mais escura, podemos definir um apagamento de extrusão menor. Pelo contrário, quando mudamos da extrusora com consumíveis de cor mais escura para a extrusora com filamento de cor mais escura, precisamos definir um apagamento de extrusão menor     
![](./pic/slicingM4-72.png)
#### 5.8 Fatiamento
![](./pic/slicingM4-8.png)
#### 5.9 Visualize o resultado fatiado (arquivo gcode) e salve no arquivo gcode em seu PC e copie para o cartão SD
![](./pic/slicingM4-9.png)