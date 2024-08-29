PS C:\Users\Jonas> git init
Initialized empty Git repository in C:/Users/Jonas/.git/
PS C:\Users\Jonas> git config --local user.name "Jonas Godoy"              
PS C:\Users\Jonas> git config --local user.email "jonas.gdiamantinos@gmail.com"
PS C:\Users\Jonas> git config --global core.editor "code --wait"
PS C:\Users\Jonas> git config --global init.defaultBranch main
PS C:\Users\Jonas> git config --list
PS C:\Users\Jonas\Downloads\Git\Jonas> git status   
No commits yet
        calculadora.py
nothing added to commit but untracked files present 
PS C:\Users\Jonas\Downloads\Git\Jonas> git add calculadora.py
PS C:\Users\Jonas\Downloads\Git\Jonas> git status -s
A  calculadora.py
PS C:\Users\Jonas\Downloads\Git\Jonas> git commit
PS C:\Users\Jonas\Downloads\Git\Jonas> git log
commit 106dd12a6a4e3951ed06ab5a50165e9246dabe54 (HEAD -> main)
Author: Jonas Godoy <jonas.gdiamantinos@gmail.com>  
Date:   Wed Aug 28 17:59:37 2024 -0300
    gitPython: funcao somar implementada
PS C:\Users\Jonas\Downloads\Git\Jonas> git add teste_calculadora.py
PS C:\Users\Jonas\Downloads\Git\Jonas> git status -s

A  teste_calculadora.py
PS C:\Users\Jonas\Downloads\Git\Jonas> git commit   
[main 8c6b9dc] GitPython: teste da funcao somar     
 1 file changed, 2 insertions(+)
 create mode 100644 teste_calculadora.py 
PS C:\Users\Jonas\Downloads\Git\Jonas> apostila02(git-python): teste da funcao somar
PS C:\Users\Jonas\Downloads\Git\Jonas> git tag -a v1.0.0 -m "operacacao adicao implementada e testada"
PS C:\Users\Jonas\Downloads\Git\Jonas> git show v1.0.0
Tagger: Jonas Godoy <jonas.gdiamantinos@gmail.com>
Date:   Wed Aug 28 18:09:06 2024 -0300
PS C:\Users\Jonas\Downloads\Git\Jonas> git add calculadora.py
PS C:\Users\Jonas\Downloads\Git\Jonas> git commit -m "GitPhiton: funcao subtracao"
PS C:\Users\Jonas\Downloads\Git\Jonas> git add teste_calculadora.py
PS C:\Users\Jonas\Downloads\Git\Jonas> git tag -a 1.0.2 -m "funcao multiplicacao"
PS C:\Users\Jonas\Downloads\Git\Jonas> git add calculadora.py
PS C:\Users\Jonas\Downloads\Git\Jonas> git commit -m "GitPhiton: funcao divisao"
PS C:\Users\Jonas\Downloads\Git\Jonas> git add teste_calculadora.py
PS C:\Users\Jonas\Downloads\Git\Jonas> git tag -a v1.0.3 -m "funcao divisao"
PS C:\Users\Jonas\Downloads\Git\Jonas> git branch -M main
PS C:\Users\Jonas\Downloads\Git\Jonas> git remote add origin https://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@github.com/JonasGodoy600/2024_FATEC_PYTHON.git
PS C:\Users\Jonas\Downloads\Git\Jonas> git push -u origin main
PS C:\Users\Jonas\Downloads\Git\Jonas> git push origin --tags
