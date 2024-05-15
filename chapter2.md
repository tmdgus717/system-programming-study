#아스키코드 vs 유니코드
## section01 : Windows에서의 유니코드
SBCS(Single Byte Character Set)
- 아스키코드
- 문자를 표현하는데 1바이트만 사용 (2^8)

MBCS(Multi Byte Character Set)
- 동일한 바이트 수가 아닌 <b>다양한 바이트 수를 이용해서 문자를 표현</b>
- 유니코드 X >> MBCS 는 SBCS 를 포함하여 아스키코드에서 정의하는 문자는 1바이트로 처리한다.

WBCS(Wide Byte Character Set)
- 유니코드
- 모든 문자를 2바이트로 처리
