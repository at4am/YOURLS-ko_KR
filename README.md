# YOURLS 1.7 한국어화
> YOURLS 1.7의 한국어 번역입니다.

## YOURLS 한국어 번역 파일 설치하기

YOURLS를 한국어화 하려면 다음 단계를 진행해주세요.

### 1. YOURLS가 설치되어 있는 디렉토리에 있는 설정파일인 `/user/config.php` 파일을 열어 아래와 같이 언어설정 부분을 수정하세요.
```php
/** YOURLS language
 ** Change this setting to use a translation file for your language, instead of the default English.
 ** That translation file (a .mo file) must be installed in the user/language directory.
 ** See http://yourls.org/translations for more information */
define( 'YOURLS_LANG', '' ); //다음 부분을 define( 'YOURLS_LANG', 'ko_KR' );로 변경해 주세요
```

### 2. `/user/languages` 디렉토리에 번역 파일인 `ko_KR.po`와 `ko_KR.mo`를 옮겨주세요.

## 라이센스

YOURLS의 라이센스인 MIT 라이센스를 따릅니다.

## 알림

주관적인 번역이므로 오타나 매끄럽지 못한 번역이 있을 수 있습니다. 번역 파일에 문제가 있거나, 번역에 문제가 있으면 [mail@4am.kr](mailto:mail@4am.kr)로 알려주시거나, 이슈에 등록해주시면 감사하겠습니다.
