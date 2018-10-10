# php-test
Create a php crawler to perform the following tasks:

# 1. Simple Task:
Get the links described under «a» and «b» from the following URL
https://www.homegate.ch/mieten/immobilien/kanton-zuerich/trefferliste?ep=1

 

a. Get only the links that have an ID in their URL like in the example below
 

'''
Example:
https://www.homegate.ch/mieten/108824868
'''
 

Info: They are up to 20x of these links on the given page

 

b. When you get the 20x links on the URL  https://www.homegate.ch/mieten/immobilien/kanton-zuerich/trefferliste?ep=1 then try to move to the next Page by counting up the last number in the URL and try to get the links described under «a» again
 

Example:

https://www.homegate.ch/mieten/immobilien/kanton-zuerich/trefferliste?ep=2

 

# 2. Additional Task:
Try to find out how many pages existing and automatically repeat the steps «a» and «b» till you reached the final page

 

Advanced Task:
Get the links described under «a» and «b» from the following URL

https://www.newhome.ch/de/kaufen/suchen/haus_wohnung/kanton_zuerich/liste.aspx?p=1

 

a. Get only the links that have an ID in their URL like in the example below
 

Example:

https://www.newhome.ch/de/kaufen/immobilien/haus/bauernhaus/ort_effretikon/5.0_zimmer/detail.aspx?pc=new&id=N875&liste=1

 

Info: This homepage has a bot protection and you can get blocked by it. Try to bypass the bot protection for example by using a proxy or do you find another way?

 

b. When you get the 20x links on the URL  https://www.homegate.ch/mieten/immobilien/kanton-zuerich/trefferliste?ep=1 then try to move to the next Page by counting up the last number in the URL and try to get the links described under «a» again
 

Example:

https://www.newhome.ch/de/kaufen/suchen/haus_wohnung/kanton_zuerich/liste.aspx?p=2

 
