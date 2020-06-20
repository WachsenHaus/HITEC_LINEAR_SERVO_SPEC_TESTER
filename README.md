# HITEC_LINEAR_SERVO_SPEC_TESTER
리니어서보의 스펙 측정을 위한 측정기의 회로와 펌웨어, 그리고 구동을 위한 PC UI프로젝트입니다.

측정기 하드웨어 스펙
전원 : 12V smps 
 용도 : 서보 구동을위한 전원공급.
전압강하 : Dc To DC Buck타입 12v to 5v 사용. 
 용도 : 메인 mcu와 센서들 전원공급용. 
  
MCU : STM32F767ZI

전류측정기 : INA131 CHip을 이용한 회로 구성.
  
전압측정기 : 전압 Divide를 응용한 회로 구성.
