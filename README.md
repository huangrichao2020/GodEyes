# GodEyes
#制作：黄超超

#2018.7.25

#摄像头识别人像，实时计算坐标，输出高低电平，控制舵机转动，实现控制摄像头追踪效果

#欢迎观看我们的项目讲解视频：https://v.youku.com/v_show/id_XMzc0OTA2MjQ1Mg==.html?spm=a2h0j.11185381.listitem_page1.5~A

the “GodEye” field biometric identification system based on aliyun link Develop platform.
To know more please turn to watch the readme.txt.

1.Bone-web webApp：
	We can input ''bone start'' to run the Web in command-window. Welcome to watch ./Bone-web/app/pages/home/index.js.
	
2.Descending_Control_from_web： 
	Python reads the meassage of JSON files and send them to RaspberryPi by socket protocol.
	
3.godEyeTest_OpenCamera：
	Python starts the easy-recognition program on local for testing.
	
4.linkdevelop-webapp-device:
	Sending the camera-device message to clouds based on node.js SDk.
	
5.RaspberryPi _code:
	Python receives the coordinate of the object which has been recognized and controls several steering engines named Sg90 to track.
	
6.Recogniton_code:
	The main program of recognition based on tensorflow_modules through Python.
