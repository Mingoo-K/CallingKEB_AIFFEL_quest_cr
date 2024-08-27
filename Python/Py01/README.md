# AIFFEL Campus Online Code Peer Review Templete
- 코더   : 고은비
- 리뷰어 : 강민구


# PRT(Peer Review Template)
- [✔]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 뒤집힌 단어 출력이 누락되어 있습니다.
    - "입력된 단어는 회문입니다"라는 코드가 완성되지 않았습니다.
     
    
- [✔]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - if word[i]  != word[-1 - i]:
    - 단어의 맨 처음과 맨 마지막부터 비교
    - word[-1] 코드 기능의 설명이 빠져있음
<img src=https://github.com/Mingoo-K/CallingKEB_AIFFEL_quest_cr/blob/86920d70828c1b504a738707a12037b6f2c44d25/Python/Py01/Py01-01.png>
          
        
        
- [✔]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - is_palindrome = '회문입니다'              # 변수 및 초깃값(True) 설정
      for i in range(len(word) // 2):   # 입력받은 문자 길이의 절반까지 반복
          if word[i]  != word[-1 - i]:    # 단어의 맨 처음과 맨 마지막부터 비교
            is_palindrome = '회문이 아닙니다'         # 서로 다르면 회문이 아니므로 False
            break

       print('입력된 단어는', is_palindrome)
   

        
- [✔]  **4. 회고를 잘 작성했나요?**
    - 회고 작성이 잘 되어있으며 현재 어려운점와 개선해야 할 부분을 이해하고 있다
        
        
- [✔]  **5. 코드가 간결하고 효율적인가요?**
        - 두가지 방식의 코드를 마지막 단계의 조건문을 변경하여 완성하였다
        - 간결하고 효율적인 코드이다
  
