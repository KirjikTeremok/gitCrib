1. git init
2. git status
3. git add          (-all, .)
4. git commit -m 'textInformation'
5. git log
6. git remote add origin git@github.com:%�:%Name%/%reposNa
7. git remote -v
8. git push (-u origin master)

```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged    -- "???"     --> tracked/comitted;

%% стрелка без текста для примера: 
  A --> B;
```  
