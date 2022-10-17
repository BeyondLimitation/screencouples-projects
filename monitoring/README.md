# OSS 기반의 네트워크 모니터링

##  개요
오픈소스 소프트웨어 모니터링 소프트웨어인 InfluxDB, Telegraf를 사용해 Cisco CSR Router를 비롯해 벤더와 관계없이 CPU사용량과 같은 장비의 상태를 모니터링 하는 것을 목적으로 만들었음.


## 구축 환경
운영체제: Window 11 HOME 21H2(Build 22000.978)

Docker : 20.10.17

Influx DB : v2.3.0+SNAPSHOT.090f681737

Flux : v0.171.0

Telegraf : 1.24

## 참고 자료

 - Youtube

[https://www.youtube.com/watch?v=f2eyVfCTLi0&t](https://www.youtube.com/watch?v=f2eyVfCTLi0&t)

https://www.youtube.com/watch?v=NOWoLfpY2kE


 - 공식 사이트 자료
 
[Telegraf Input Plugin: snmp](https://github.com/influxdata/telegraf/tree/release-1.23/plugins/inputs/snmp)

https://github.com/docker-library/docs/blob/master/influxdb/README.md

https://www.influxdata.com/blog/running-influxdb-2-0-and-telegraf-using-docker/
