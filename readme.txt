Catfish.java:定义了Catfish作为LivingBeing的子类，活与死的成员变量，每次游泳所需消耗能量的成员变量、
	   行与列、能量和年龄的成员变量、图片名的成员变量、构造方法（定义了catfish的年龄、能量、位置、生死状态）、
	   定义了几个get方法用以返回鱼的数据、定义了die方法用以改变鱼的生死状态、isDead方法用以判断鱼的生死状态并返回一个布尔变量、
	   一个游泳的方法（规定了游泳消耗能量、游至随机的行与列）、一个用以使鱼在能量消耗完死亡，未消耗完年龄增长并游泳的方法。
HtmlAnchor.java HtmlImage.java HtmlPage.java HtmlTable.java:作用同上一个实验中的这些java文件。
LivingBeing.java:定义了抽象类，定义了创造生物的方法与几个局部变量、几个抽象的成员变量、用于扩充自类的内容（？不确定）
MySImulation.java:规定了servlet的名字和URL路径、doPost方法（以html页面回应），对html页面进行了规定、其他部分看不太懂、不清楚引入了什么类。
Simulation.java:定义了生成随机数的方法和变量、返回始末行列的方法和变量、次数变量以及模拟记录次数的方法
SimulationServlt.java SimulationView.java:作用与上一个实验几乎相同
initialWorldFish.html:正常的模拟鱼塘
MySimulation.html:点击后会回再放项目，即跳转到一个与initialWorldFish相同的页面上，再进行模拟。
二者的不同之处在于表单提交的action和按钮的作用不同。