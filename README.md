# jlc_gEDA_pcb
嘉立创 gEDA pcb 封装库


使用方法:  
  
cd ~  
git  clone https://github/com/lshw/jlc_gEDA_pcb  

编辑pcb的设置文件  
vi ～/.pcb/preferences  
增加或修改:  
library-newlib = ～/jlc_gEDA_pcb/packages:/home/liushiwei/pcb/packages  
可以用冒号间隔多个库目录  

重新打开pcb软件，lib里就可以列出元件了。  
也可以在pcb软件里 点[File] -> [Preferences] -> [Library] 进行修改  
