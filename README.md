‘My Pet’ 웹 사이트


  Visual Code Studio를 사용하였으며 django 환경설정들을 마친 뒤 home이라는 app이름으로 app을 생성하였습니다. 
  Html파일들을 templates 폴더에 CSS + 이미지, 동영상 파일들을 static 폴더로 구분하여서 꺼내쓰는 방식으로 사용하였습니다. 
  html 들어있는 폴더를 view.py에 함수 추가, urls.py 에 경로를 설정하여 주어 구성하였습니다. 
  home.html은 home.css와 나머지 html 파일들은 모두 menu.css와 연결하였습니다. 
시작화면과 4가지의 각 화면으로 넘어갈 수 있는 메뉴화면으로 구성하였습니다.
시작화면에서 Enter 버튼을 클릭하면 Menu 화면으로 넘어가며 이곳에서 원하는 화면으로 선택하여 넘어갈 수 있습니다. 
뒤로 가기 버튼으로 다시 메뉴화면으로도 갈 수 있습니다.
메뉴화면에서는 각각 나의 펫에 대한 간단한 정보 소개화면, 사진을 볼 수 있는 화면, 동영상을 볼 수 있는 화면, 인스타그램 사이트를 연결해주는 버튼들로 보여주도록 구성하였습니다.

home화면과 menu화면 그리고 각 버튼클릭시에 나오는 화면들의 실행사진들 입니다. ↓ 

Home : home.html에 해당, 구경하기 버튼에 onclick이 적용되면 menu.html로 이동 ↓
![image](https://github.com/gunnuuu/Mypet/assets/105582355/a3faeefc-4f47-4f66-8a34-023aa88f41c9)

Menu : menu.html에 해당, 원하는 화면으로 이동할 수 있는 중간 화면으로 각 버튼에 onclick이 적용시 html 혹은 해당 링크로 이동 ↓
![image](https://github.com/gunnuuu/Mypet/assets/105582355/bcfa77ee-4fea-4b65-9f41-87dc8e8aa618)


About : about.html에 해당, 간단한 설명이며 뒤로가기 이미지 클릭시 menu.html로 이동↓
![image](https://github.com/gunnuuu/Mypet/assets/105582355/6107badd-905c-4548-843a-53743a85ab33)


Pictures : pictures.html 해당, 사진들이며 뒤로가기 이미지 클릭시 menu.html로 이동 ↓
![image](https://github.com/gunnuuu/Mypet/assets/105582355/95b7641f-ed4b-4597-8680-6fd1132234d9)

Video : video.html 해당, 영상 실행가능하며 역시 뒤로가기 이미지 클릭시 menu.html로 이동 ↓
![image](https://github.com/gunnuuu/Mypet/assets/105582355/b49c31b6-64a5-4f3a-ade9-a509c669beb2)


마지막 버튼클릭시에 연결되는 인스타그램 사이트 화면 ↓
![image](https://github.com/gunnuuu/Mypet/assets/105582355/4ee41dad-bc6b-4075-93aa-f456a038d1f1)



GitHub링크 : https://github.com/gunnuuu/Mypet
웹사이트 링크 : http://127.0.0.1:8000/
