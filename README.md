# ropeway_protecting_robot

로프웨이를 이용한 유해야생동물 퇴치기 소스코드입니다.

두개의 SBC가 사용되었습니다.
# nvidia 사의 jetson nano board : 영상처리로 사람/멧돼지/고라니 판단


opencv2로 영상 처리


pthread 사용


GPIO를 사용해 퇴치 LED 점멸


    
# robotis 사의 OpenCR 1.0 : Dynamicsel 구동
manipulator 2개, 짐벌 1개 제어


    dynamicsel protocol 2.0 
    manipulator : MX-64 3개와 XL430 2개
    짐벌 : XL330 3개

IMU센서로 짐벌 수평 제어

# 통신
두 SBC 간의 통신은 serial 통신(UART)을 사용하였습니다.
