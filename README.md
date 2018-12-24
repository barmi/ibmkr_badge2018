# IBM KR badge2018
한국 IBM developerWorks IoT cloud용 뱃지관련 내용

# 기본정보
* https://github.com/hongjsk/avocado2018/blob/master/dwmeetup201812/tutorial1.md

# 참고정보
## builtin 소스
* 초기 device에 들어있는 파일을 다음 방법으로 일부 읽어내서 정리
  * [catfile() 함수로 파일 읽기](doc/catfile.md)

## firmware update
```
esptool.py erase_flash
esptool.py -b 921600 write_flash 0x1000 firmware.bin
```
