```
git config --global user.name "이름"  
git config --global user.email 메일주소  
```
Global Config : 모든 GitHub Repo에 영향 (우선순위 낮음) , GitHub 계정이 2개 이상일 때 주의해서 사용 , 서버에서 사용 금지.  
Local Config : 현재 Repo에만 영향 (우선순위 높음) , git init 우선되어야 한다.  

설정 확인  
`git config --list`

에디터로 설정 확인  
`git config --global -e`

기본 에디터를 vscode로 설정  
`git config --global core.editor "code"`

리턴값 설정  
`윈도우 git config --global core-autocrlf True`  
`리눅스 git config --global core-autocrlf input`  

`.gitignore` 파일 -> 커밋에서 제외하는 파일을 기록  
    ex) `echo *.log > .gitignore`

```
…또는 명령줄에서 새 저장소를 만듭니다.
echo "# test" >> README.md 
git init 
git add README.md 
git commit -m "첫 번째 커밋" 
git branch -M main 
git remote add origin https://github.com/voodoogoat/home.git
 git push -u origin main

…또는 명령줄에서 기존 저장소를 푸시합니다.
git remote add origin https://github.com/voodoogoat/home.git
 git branch -M main 
git push -u origin main
```
