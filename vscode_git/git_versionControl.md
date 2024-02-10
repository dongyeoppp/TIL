##  vscode에서 git으로 협업하기  

* commit 후 push 하기 
    * Source Control에서 message(git hub에서 last commit message로 보임) 입력 후 commit!  
    <br>  
    <img src="./img/image1.png">

    * ```git log --oneline --all --graph``` 터미널에 입력 -> commit이 잘 되었는지 확인  
    <br>  
    <img src="./img/image2.png">

    * push 이후  
    <br>  
    <img src="./img/image3.png">

* pull과 push 목록 확인 가능  
<br>  
<img src="./img/image4.png">

* github에서 협업하기  
    * setting -> collaborators -> add people -> 사용자 이메일 입력 or username 입력
    * 충돌  
        * 같은 부분을 수정하면 충돌 발생  
        <img src="./img/image5.png">
        <br>
    * 충돌_해결하기  
        * 충돌이 발생한 곳에 특수기호를 지우고 수정할 내용 입력  
        * 아래 빨간 박스의 느낌표는 충돌을 의미함  
        * 빨간 박스 옆에 + 버튼(stage changes)을 누른 후 commit  
        <img src="./img/image6.png">  