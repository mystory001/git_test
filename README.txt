git 사용에 익숙해지기

C:\Users\User\git
README.txt

1. 로컬 저장소 만들기
초기화 작업 : git init => 폴더 안에 숨긴 폴더로 .git이 생성됨(※리눅스에서 '.' 은 숨긴 파일을 뜻함), .git 폴더에 git으로 생성한 버전들의 정보와 원격저장소 주소 등이 들어 있으며, .git 폴더를 로컬 저장소라고 부름

2. 커밋 만들기
git에서 생성된 각 버전을 커밋(Commit)이라고 부름.
1) 버전 관리를 위해서 내 정보를 등록해야함. 그 이유는 각 버전을 누가 만들었는지 알아야 협업하는데 편리하기 때문이다.
git config --global user.email "001cloudid@gmail.com"
git config --global user.name "mystory001"
2) 커밋에 추가할 파일을 선택
git add README.txt => 스테이지에 올릴 파일
※git add . => 모든 파일을 github에 올릴 때 사용
3) git status => new file: README.txt. 새로운 버전을 생성하게 되면 추가될 파일을 뜻함
4) git commit -m "설명" => 살명과 함께 커밋을 만듦
5) README.txt 파일을 수정 후 저장
6) 두번째 커밋을 만듦
* 반복

push 하기
git push origin master => master로 push