# Computer_Graphics
2022-second semester
with [WebGL, Three.js, GLSL]
---
</br>

## 📌 project1
- ### 목적
    > 1. x, y, z축을 표현하고 카메라를 생성하여 구도를 원하는 대로 조절한다.
    > 2. 도형을 생성하고 x축을 기준으로 정렬하여 angle을 각자 다르게 표현한다.
- ### 결과물
<img width="418" alt="스크린샷 2023-03-22 오후 2 23 19" src="https://user-images.githubusercontent.com/84169614/226809866-783753ad-fda8-4534-ac8b-fdfbf9ec6757.png">


</br>
</br>



---
</br>

## 📌  문제점 및 해결방안
1. 문제점 
- 로컬 호스트로 접속했으나 화면에 표시되지 않은 문제

</br>

2. 해결시도

    1️⃣ 카메라 구도의 문제로 화면이 출력되지 않을 수 있다.
    </br>
    -> 확인해보니 카메라의 각도는 문제 없었다.

    </br>

    2️⃣ src경로가 제대로 지정되어 있지 않을 수 있다.
    </br>
    
    -> 본인이 파일 경로를 옮기면서 src경로를 수정하지 않아 생긴 문제였다. : 해결
    
    ```HTML
    <script type="text/javascript" src="../learning-threejs-master/libs/three.js"></script> 
    ```
    

 </br>
  </br>
   </br>
