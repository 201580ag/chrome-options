# selenium security options - english
```
options.add_experimental_option("excludeSwitches", ["enable-automation"]) # Remove automation message
options.add_argument('--incognito') # Enable incognito mode
options.add_argument("--start-maximized") # Maximize browser window
options.add_argument("--force-dark-mode") # Enable browser dark mode
options.add_argument('--sandbox') # Restrict access to system resources during browser execution to enhance security.
options.add_argument('--disable-blink-features=AutomationControlled') # Disable feature detection for browser automation.
options.add_argument('--disable-notifications') # Disable browser notifications.
options.add_argument('--disable-application-cache') # Disable browser application cache.
options.add_argument('--disable-save-password-bubble') # Disable password save pop-up.
options.add_argument('--disable-offer-store-unmasked-wallet-cards') # Disable saving unmasked wallet cards.
options.add_argument('--disable-offer-upload-credit-cards') # Disable credit card upload.
options.add_argument('--disable-popup-blocking') # Disable pop-up blocking.
options.add_argument('--disable-infobars') # Hide the infobar.
options.add_argument("--disable-webcam") # Disable webcam.
options.add_argument("--disable-audio") # Disable microphone.
options.add_argument('--incognito') # Enable browser incognito mode.
options.add_argument("--disable-geolocation") # Disable geolocation.
options.add_argument("--disable-javascript") # Disable JavaScript execution.
```
# 보안 기능 옵션 - korean
```
options.add_experimental_option("excludeSwitches", ["enable-automation"]) # 자동화 메시지 제거
options.add_argument('--incognito')# 브라우저 시크릿 탭 모드
options.add_argument("--start-maximized") # 브라우저 창 최대화
options.add_experimental_option("excludeSwitches", ["enable-logging"])# 브라우저를 실행할 때 로깅 기능을 끄기
options.add_argument("--force-dark-mode")# 브라우저 다크 모드 활성화
options.add_argument('--sandbox')# 브라우저를 실행하는 동안 시스템 리소스에 대한 액세스를 제한하여 보안을 강화하는 역할을 합니다.
options.add_argument('--disable-blink-features=AutomationControlled')# 브라우저 자동화에 대한 감지를 방지하는 기능을 비활성화합니다.
options.add_argument('--disable-notifications')# 브라우저에서 알림을 표시하는 기능을 비활성화합니다.
options.add_argument('--disable-application-cache')# 브라우저의 애플리케이션 캐시를 비활성화합니다.
options.add_argument('--disable-save-password-bubble')# 비밀번호 저장 팝업을 비활성화합니다.
options.add_argument('--disable-offer-store-unmasked-wallet-cards')# 마스크되지 않은 지갑 카드 저장을 비활성화합니다.
options.add_argument('--disable-offer-upload-credit-cards')#신용 카드 업로드를 비활성화합니다.
options.add_argument('--disable-popup-blocking')# 팝업 차단 기능을 비활성화합니다.
options.add_argument('--disable-infobars')# 정보 표시줄을 숨깁니다.
options.add_argument("--disable-webcam") # 웹캠 비활성화
options.add_argument("--disable-audio") # 마이크 비활성화
options.add_argument('--incognito')# 브라우저 시크릿 탭 모드
options.add_argument("--disable-geolocation") # 위치정보 비활성화
options.add_argument("--disable-javascript") # 자바스크립트 실행 비활성화
```
