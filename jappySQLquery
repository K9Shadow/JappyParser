select
t001.c001aa as Userid,
t001.c001ab as Username, 
datetime(c049ae, 'unixepoch', 'localtime') as Zeitstempel,
replace(c049ag, CHAR(10), '') as Chat, 
c049aa as ChatID, 
t001.c001ad as "registriertesAlter", 
replace(replace(t001.c001ae,'1','w'),'2','m') as registriertesGeschlecht, 
t001.c001av as registrierterVorname,
t121.c121ad as registriertePostleitzahl,
t121.c121ab as registrierterWohnort
from t049
inner join t001
ON t049.c049ad = t001.c001aa
inner join t121
ON t001.c001ay = t121.c121aa
ORDER by ChatID ASC
