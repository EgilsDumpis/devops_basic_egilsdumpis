/devops_basic_egilsdumpis/git_repos/module_1 (main)
$ git hash-object hw1.2.py
d2cb5858ff01eb91de19436027ec611a64f4d3ab

/devops_basic_egilsdumpis/git_repos/module_2 (main)
$ git hash-object hw1.2.py
d2cb5858ff01eb91de19436027ec611a64f4d3ab

Izvēlējos salīdzināt faila hw1.2.py hash. Abos gadījumos file hash ir vienāds.

Kommandas lai redzētu pēdējo divu nedēļu izmaiņas:
    1) git log --since=2.weeks
    2) git log --since='2022-01-03' --until='2022-04-24'

Atrast Lauras Pacilio commit:
    git log --author="Laura Pacilio"

Vai Laura ir vaikusi commit vakar? :
    git log --since='2022-04-23' --until='2022-04-23' --author="Laura Pacilio"

    Laura vakar nav veikusi commit.

*
    git log --since='2021-04-20' --until='2021-04-21'

    Pieņemu ka commit ir ievietots ar kommandu "git commit --date="4 day ago" -m "message""

    Ar šo kommandu commitojot šo failu man izdevās iegūt tādu pašu rezultātu:  
 
[![N| *atbilde*](https://fv2-5.failiem.lv/thumb_show.php?i=8jeaknvyp&view)]
