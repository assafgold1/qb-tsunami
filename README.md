# qb-tsunami

search "TriggerServerEvent('qb-phone:server:sendNewMail', {"
replace with "TriggerServerEvent('gksphone:NewMail', {"
you will need to remove the qb-phone Dependencie from the fxmanifest
