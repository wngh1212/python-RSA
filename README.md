# python-RSA
python으로 구현한 RSA암호화

RSA 키 쌍 생성 및 저장:
private_key 변수에 RSA 개인 키를 생성한다
public_key 변수에 이 개인 키로부터 공개 키를 얻는다
개인 키와 공개 키를 각각 private_key.pem 및 public_key.pem 파일로 저장한다<br>
<img width="249" alt="스크린샷 2023-09-26 21 14 04" src="https://github.com/wngh1212/python-RSA/assets/88926634/7814f235-8745-44ec-91d5-e5856df07719"><br><br><br>
암호화 및 복호화:
message 변수에 암호화할 원본 메시지를 설정합니다.
public_key를 사용하여 원본 메시지를 암호화하고, private_key를 사용하여 암호문을 복호화한다<br>
결과 출력:<br>
<img width="631" alt="스크린샷 2023-09-26 21 15 56" src="https://github.com/wngh1212/python-RSA/assets/88926634/0428ea08-02b3-4ba8-b31a-6257bf111cc2">
<br>
원본 메시지, 암호화된 메시지, 그리고 복호화된 메시지를 출력합니다.
