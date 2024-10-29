git config --global user.name "이름"  
git config --global user.email 메일주소  

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

