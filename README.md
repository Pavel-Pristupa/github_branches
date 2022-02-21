# github_branches / Github_HW2
____
__1. На локальном репозитории сделать ветки для:__  
__- Postman__ - `git branch Postman`    
__- JMeter__ - `git branch JMeter`    
__- Checklists__ - `git branch Checklists`    
__- Bug_reports__ - `git branch Bug_reports`   
__- SQL__ - `git branch SQL`    
__- Charles__ - `git branch Charles`     
__- Mobile_testing__ - `git branch Mobile_testing`    
__OR we can use the following command:__  
`git branch Postman; git branch JMeter; git branch Checklists; git branch Bug_reports; git branch SQL; git branch Charles; git branch Mobile_testing`  
  
__2. Запушить все ветки на внешний репозиторий__  
`git push -u origin Postman JMeter Checklists Bug_reports SQL Charles Mobile_testing`  
__3. В ветке Bug_reports сделать текстовый документ со структурой баг репорта__  
`git checkout Bug_reports`  
`vim bug_report_structure.txt`  
:arrow_right: __i__  
  
*ID:  
Summary:  
Description:  
STR:  
AR:  
ER:  
Reporter:  
Assignee:  
Priority:  
Attachments:*  
  
:arrow_right: __Esc__  
:arrow_right: `:wq`  
  
__4. Запушить структуру багрепорта на внешний репозиторий__  
`git add . && git commit -m "bug_report_structure"`  
`git push`  
__5. Вмержить ветку Bug_reports в Main__  
`git checkout main` ___OR___ `git checkout -`  
`git merge Bug_reports`  
__6. Запушить main на внешний репозиторий.__  
`git push`  
__7. В ветке CheckLists набросать структуру чек листа.__  
`git checkout Checklists`  
`vim check_list_structure.txt`  
:arrow_right: __i__   
    
*Columns:  
ID  
Title  
Module  
ER  
Status  
Comments*  
  
:arrow_right: __Esc__  
:arrow_right: `:wq`  
__8. Запушить структуру на внешний репозиторий__  
`git add . && git commit -m "checklist structure"`  
`git push`  
__9. На внешнем репозитории сделать Pull Request ветки CheckLists в main__  
:arrow_right: go to https://github.com/Pavel-Pristupa/github_branches  
:arrow_right: Pull requests  
:arrow_right: Compare & pull request  
:arrow_right: Create pull request  
:arrow_right: Merge pull request :arrow_right: Confirm merge  
__10. Синхронизировать Внешнюю и Локальную ветки Main__  
`git checkout main` ___OR___ `git checkout -`  
`git fetch`  
`git pull`  
