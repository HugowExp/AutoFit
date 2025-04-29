# AutoFit

## PORTUGUÊS

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
 de saída

## ENGLISH

-When importing a .txt file with the "Import Data" button, your
 spectrum will be plotted immediately.
 
-When selecting the "Calculate Baseline" option, the program will calculate
 the baseline automatically using the arPLS method and will show
 the difference between your spectrum with and without baseline correction.
 
-With the "Find Peaks" option, the program will automatically perform
 a preliminary selection of potential peaks.
 
-Holding the left mouse button at the graph boundaries allows you to
 select a rectangular region for zooming. Left-click
 to reset the zoom.
 
-By pressing the "a" and "d" keys on your keyboard, you enter "add"
 and "delete" modes respectively. With these modes active, you can right-click
 on a graph point to add/delete
 a peak from the peak list. Peak numbering is done and updated
 automatically.
 
-With "Export Data", you can export both baseline data
 and peak data. If you've calculated the baseline,
 a file named BL_{spectrum filename}.txt will appear in the AutoFit.exe
 folder, containing the original spectrum with baseline correction.
 If you've also identified peaks, a second file
 named PK_{spectrum filename}.txt will appear, containing peak coordinates
 and numbers, following the format P({peak number}).
 
-With "Exit", you can terminate the program after confirming
 through an exit confirmation.

## 中国人

-通过点击“导入数据”按钮导入.txt文件后，
 程序将立即绘制出光谱图。
 
-选择“计算基线”选项时，程序会通过arPLS算法
 自动计算基线，并显示原始光谱与基线校正后的差异。
 
-使用“寻峰”功能时，程序会自动执行
 初步的潜在峰识别。
 
-按住鼠标左键在图表边界拖动，
 可框选矩形区域进行放大。
 左键单击图表可重置缩放。
 
-键盘按下“a”或“d”键分别进入“添加”
 和“删除”模式。激活这些模式后，
 右键点击图表上的点可添加/删除
 峰列表中的峰。峰编号会自动
 更新。
 
-通过“导出数据”可同时导出基线数据
 和峰数据。若已计算基线，
 程序所在文件夹将生成BL_{光谱文件名}.txt文件，
 内含基线校正后的光谱数据。
 若已识别峰，则会额外生成
 PK_{光谱文件名}.txt文件，记录峰坐标
 和编号，格式为P({峰编号})。
 
-选择“退出”时，程序将在确认后
 终止运行。
