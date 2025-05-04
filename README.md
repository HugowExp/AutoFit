..............................................................
.                                                            .                 
.    █████╗ ██╗   ██╗████████╗ ██████╗ ███████╗██╗████████╗  .                 
.   ██╔══██╗██║   ██║╚══██╔══╝██╔═══██╗██╔════╝██║╚══██╔══╝  .                 
.   ███████║██║   ██║   ██║   ██║   ██║█████╗  ██║   ██║     .                 
.   ██╔══██║██║   ██║   ██║   ██║   ██║██╔══╝  ██║   ██║     .                  
.   ██║  ██║╚██████╔╝   ██║   ╚██████╔╝██║     ██║   ██║     .                  
.   ╚═╝  ╚═╝ ╚═════╝    ╚═╝    ╚═════╝ ╚═╝     ╚═╝   ╚═╝     .                  
.                                                            .              
..............................................................

PORTUGUÊS

-Ao selecionar o botão "Silício", o programa automaticamente calcula 
a baseline, e comparando os R-quadrado, escolhe a melhor modelo que
faz o fit do pico do silício (entre Gaussiana, Lorentziana e Voigt).

-Abaixo do botão Silício, temos o valor do centro da função usada para
fitar o pico.

-Ao importar o silício, os próximos espectros (usando o botão de importar
dados), estão todos corrigidos horizontalmente.

-Ao importar um arquivo .txt com o botão "Importar dados", seu
 espectro logo será plotado.

-Selecionando a opção "Calcular baseline", o programa calculará
 a linha de base automaticamente através do método arPLS e mostrará
 a diferença entre seu espectro sem e com correção da linha de base.

-Com a opção "Encontrar picos", o programa fará automaticamente uma
 seleção prévia de possíveis picos.

-Segurando o botão esquerdo do mouse nos limites do gráfico, podemos
 selecionar uma região retangular na qual será dado um zoom. Clique 
 com o botão esquerdo do mouse caso queira resetar o zoom.

-Apertando, no teclado, os botões "a" e "d" entramos no modo "adicionar"
 e "deletar", respectivamente. Com esses modos ativados, podemos clicar
 com o botão direito do mouse em um ponto do gráfico e adicionar/deletar 
 um pico na lista de picos. A enumeração dos picos é feita e atualizada 
 automaticamente.

-Em "exportar dados", podemos exportar tanto os dados da linha de base
 quanto os dados dos picos. Caso você tenha calculado a linha de base, 
 surgirá na pasta em que o AutoFit.exe está um arquivo BL_{nome do arquivo 
 do espectro}.txt, este contém o espectro original, mas com a linha de base 
 corrigida. Caso tenha também identificado os picos, surgirá um segundo arquivo
 com nome PK_{nome do arquivo do espectro}.txt, este contém a coordenada do pico
 e seu número, seguindo o formato P({número do pico}).

-Em sair, você poderá encerrar a execução do programa mediante uma confirmação 
 de saída.

-Se você está lendo este .txt, provavelmente já sabe para que serve o botão "Ajuda".

ENGLISH

-When selecting the "Silicon" button, the program automatically calculates the baseline
 and, by comparing the R-squared values, chooses the best model to fit the silicon peak
 (among Gaussian, Lorentzian, and Voigt).

-Below the Silicon button, we have the center value of the function used to fit the peak.

-When importing silicon, the subsequent spectra (using the "Import data" button) are all
 horizontally corrected.

-When importing a .txt file with the "Import data" button, its spectrum will be plotted
 shortly.

-Selecting the "Calculate baseline" option, the program will automatically compute the
 baseline using the arPLS method and display the difference between your spectrum with
 and without baseline correction.

-With the "Find peaks" option, the program will automatically make a preliminary
 selection of possible peaks.

-By holding the left mouse button within the graph's boundaries, we can select a
 rectangular region to zoom in. Left-click again to reset the zoom.

-Pressing the "a" and "d" keys on the keyboard activates "add" and "delete" modes,
 respectively. With these modes enabled, right-clicking on a point in the graph will
 add/delete a peak from the peak list. The peak numbering is automatically updated.

-Under "Export data," we can export both baseline data and peak data. If you have
 calculated the baseline, a file named BL_{spectrum filename}.txt will appear in the
 folder containing AutoFit.exe, which includes the original spectrum with baseline
 correction. If peaks have also been identified, a second file named 
PK_{spectrum filename}.txt will appear, containing the peak coordinates and their
 assigned number in the format P({peak number}).

-Under "Exit," you can terminate the program's execution after a confirmation prompt.

-If you're reading this .txt, you probably already know what the "Help" button does.

中国人

-选择"硅(Silicon)"按钮时，程序会自动计算基线，并通过比较R平方值，在（高斯、洛伦兹和Voigt
）模型中选择最适合硅峰拟合的模型。

-硅按钮下方显示用于拟合峰值的函数中心值。

-导入硅数据后，后续通过"导入数据"按钮加载的所有光谱都会自动进行水平校正。

-使用"导入数据"按钮导入.txt文件时，其光谱将立即绘制显示。

-选择"计算基线"选项，程序将使用arPLS方法自动计算基线，并显示基线校正前后的光谱差异。

-启用"寻峰"选项时，程序会自动进行初步的峰值预选。

-在图表范围内按住鼠标左键可框选矩形区域进行放大，再次左键点击可重置缩放。

-键盘按"a"或"d"键可分别进入"添加"或"删除"模式。在这些模式下，
右键点击图表上的点可在峰值列表中添加/删除峰值，峰值编号会自动更新。

-通过"导出数据"可导出基线数据和峰值数据。若已计算基线，
AutoFit.exe所在文件夹将生成BL_{光谱文件名}.txt文件
，包含基线校正后的原始光谱数据；若已识别峰值，将额外生成PK_{光谱文件名}.txt文件
，按P({峰值编号})格式记录峰值坐标。

-点击"退出"可通过确认提示关闭程序。

-如果您正在阅读本.txt文件，您应该已经了解"帮助"按钮的功能。
