# penetration-testing


* 안드로이드

  - 파일 넣고 빼기 좋은 관리 프로그램 : apkFileManager

  - 디컴파일러 : Bytecode-Viewer-2.9.22.jar // 빠른 속도, 쉬움, 자바 디컴파일 코드와 바이트 코드 같이 제공, 플러그인 제공(코드 다이어그램, 악성코드 여부 판단)

  - 디컴파일러 : jadx

  - 에뮬레이터 : nox


* ios

  - 파일 넣고 빼기 좋은 관리 프로그램 : 3utools

  - 시디아 임팩터 : 앱스토어 등록 안된 ipa파일 설치 가능


* 안드로이드, ios

  - ida ; 디스어셈블러 : 바이너리 파일 -> 어셈블리어 ;; 플러그인 지원, 거의 모든 CPU 지원, obfuscation(난독화) 코드 해석 잘됌

  - F12 ; 그래프기능,  jni_all ; java native interface : 자바코드가 자바VM에서 동작할 때, 네이티브 언어로 작성된 코드를 자바에서 사용하거나, 네이티브 언어에서 자바의 클래스와 메서드를 사용할 수 있게 해주는 프로그래밍 인터페이스


* 웹

  - 피들러 ; 모바일 앱 분석하기 좋음
  
  - 버프슈트
  
  - 와이어샤크


* 크롬 익스텐션

  - EditThisCookie
  
  - (Falcon Proxy) or (Proxy-SwitchyOmega)
  
  - Wappalyzer ; 웹사이트 구성 알 수 있는 도구
  
  - User-Agent Switcher ; 사용자 환경 스푸핑하는 도구
  
  - retire.js ; js 라이브러리 취약점을 찾아주는 도구


* 그 외

  - Everything
  
  - Hxd


* 파이썬

  - beautifulsoup/ 크롤링
  
  - Frida / 후킹



# IDA

AndroidManifest.xml 파일에 debuggable속성을 넣어줘서 리패키징 필요

IDA PRO버전 -> 원격 디버깅 가능

