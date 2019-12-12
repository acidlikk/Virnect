# Virnect
IoT Sensor System

1. 스마트 진동 센서: 3
2. 방폭형 스마트 진동센서: 3
3. 스마트 전류 센서(WF): 3
4. 스마트 전류 센서(RMS): 3
5. 스마트 환경 센서(3종): 9
6. 스마트게이트웨이 Dynamic: 1
7. 스마트게이트웨이 Static: 1
8. Vibration Transducer: 3
9. Multi-Channel Data Logger: 1
10. 서버시스템: 1

## Dynamic
- 구성
  - 스마트게이트웨이 Dynamic: 1
  - Base Module: 4
  - 스마트 진동 센서: 3
  - 방폭형 스마트 진동센서: 3 (스마트 진동 센서 모서리 자르고 사용)
- 통신
  - 1:6 연결
- 문제점
  - 하드웨어 수량: 스마트 진동 센서 RF 확인
  - 방폭형 펌웨어: 스마트 진동 센서 그대로 사용 예정
  - 1대로 시간차 사용해서?
  
## Static
- 구성
  - 스마트게이트웨이 Static: 1
  - Base Module: 2.4GHz: 2, 900MHz: 1
  - 스마트 전류 센서(WF)
  - 스마트 전류 센서(RMS)
  - 스마트 환경 센서(3종)
- 통신
  - 15대
  - 2.4GHz: 6
  - 900MHz: 9
- 문제점
  - 하드웨어 수량: 
  - WF 자가발전?
  - 스마트 환경 센서 펌웨어: 1분마다 전송, 통신채널 고정, 
  - 세팅?
  
## MCDL
- 구성
  - Multi-Channel Data Logger
  - Vibration Transducer
- 문제점
  - 하드웨어 수량: OK
  - Artik?, Sampling?
