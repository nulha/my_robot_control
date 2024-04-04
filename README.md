# ros_rasp_gpio_control

1. 우분투에 ROS 패키지 생성 (키보드 입력을 처리하는 노드를 포함하는 패키지이다.)

1. catkin_ws에 my_robot_control 패키지를 생성한 후, keyboard_control_node.py 에 키보드 입력을 받아 라즈베리파이로 명령을 전송하는 노드를 생성한다.

1. 라즈베리파이에 패키지를 만들고  gpio를 제어하는 로직을 포함한 노드 motor_control_node.py를 생성한다 (우분투 컴퓨터로부터 키보드 입력에 해당하는 ros 메시지를 수신하여 gpio 핀 상태를 제어하는 것이다.)
