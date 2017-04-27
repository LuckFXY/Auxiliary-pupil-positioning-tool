# Auxiliary-pupil-positioning-tool
## 更新

4.23重要更新 

* 加入粗略的预定位功能 
* 数据库文件名化简
* 批量导出修改后的图片
	
## 安装 ：
* anaconda3  python3.5（至少是python3）
* 用python执行 Auxiliary-pupil-positioning-tool 2.5

  a) cd 脚本所在目录
  
  b) python Auxiliary-pupil-positioning-tool 2.5
  
## 步骤：

	* 利用数据库存储信息，用户可以在任何时候
	   开始标记，修正以前的图片，关闭程序
	* 左右翻页不会修改数据库，保存会更新数据库
	* 在编辑外圆时，空格会保存并翻页

1. 菜单栏open-folder 打开图片所在根目录
2. 用鼠标进行从**左上角向后下角**拖动，画圆以标记 （**先内圆再外圆**）
3. 空格下一步
	


## 快捷按键：
微调

	上下左右：w,s,a,f
	大小 q,e 每次增幅为2像素,**要求鼠标画圆时，园的半径为偶数**
	
对于一副新图，先编辑内圆	

	第一次space 从编辑内圆切换至外圆
	第二次space 保存并跳转到下一张图片
## 输出：
mydata.db 
	
	数据库文件，保存用户数据，程序默认调用同目录下的数据库，没有则新建
	
data.csv

	程序手动导出文件:
	1. 菜单栏open-folder 
	2. 菜单栏 output-csv file
	
output_image

	程序自动输出文件夹，保存修改后的图片
