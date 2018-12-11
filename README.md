利用opencv库实现的面部特征检测（搬运）。  
使用时程序目录下要有lbfmodel.yaml和haarcascade_frontalface_alt2.xml。  
效果![结果](https://github.com/HEYAHONG/FacialLandmarkDetection/raw/master/result/result.png) 
编译命令（需要装好opencv库）：   
mkdir build    
cd build   
cmake ../  
make   
即可生成程序文件,运行时需要把yaml和xml文件放到程序目录     
Please download to use code 
1. [haarcascade_frontalface_alt2.xml](https://raw.githubusercontent.com/opencv/opencv/master/data/haarcascades/haarcascade_frontalface_alt2.xml) 
2. [lbfmodel.yaml](https://raw.githubusercontent.com/kurnianggoro/GSOC2017/master/data/lbfmodel.yaml)
