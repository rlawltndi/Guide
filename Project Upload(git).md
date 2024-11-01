###github에 git으로 project 올리기

1. 업로드 할 프로젝트에서 git bash 열기
2. git init ("해당 폴더를 깃으로 관리하겟다" 라고 지정)
3. git add . (로컬의 변경사항을 스테이지에 올린다.) 스테이지 : 임시로 저장되는 공간
4. git commit -m "project init" (변경사항 적용)
5. git branch -M main (브랜치 이름을 main으로 설정)
6. git remote add origin 깃허브 repository 주소 (깃허브의 저장소와 연결)
7. git push origin main (로컬의 변경사항을 github에 push)

