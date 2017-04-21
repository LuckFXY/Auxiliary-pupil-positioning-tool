# Auxiliary-pupil-positioning-tool
##安装 ：
* anaconda3 
* 用python执行 assist_tool_1.py
##步骤：
* 第一步：菜单栏open-folder
* 第二步：用鼠标进行标记
##快捷按键：
微调

	上下左右：w,s,a,f
	大小 q,e
	
对于一副新图，先编辑内圆	

	第一次space 从编辑内圆切换至外圆
	第二次space 保存并跳转到下一张图片
##输出：
mydata.db 
	
	数据库文件，保存用户数据，程序默认调用同目录下的数据库，没有则新建
	
data.csv

	程序手动导出文件，
	1. 菜单栏open-sqlit3 db 或者 open-folder 
	2. 菜单栏 output-csv file
	
output_image

	程序自动输出文件夹，保存修改后的图片
