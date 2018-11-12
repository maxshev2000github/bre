# bre

sfdx force:package:install --wait 10 --publishwait 10 --package dreamhouse@0.1.0-1 -k test1234 -r -u MyScratchOrg

sfdx force:package:create --name "th-dreamhouse" --description "My DreamHouse Package" --packagetype Unlocked --path force-app --nonamespace --targetdevhubusername DevHub

sfdx force:package:create --name "th-dreamhouse" --description "My DreamHouse Package" --packagetype Unlocked --path force-app --nonamespace 

DevHub  maxim.shevchenko@brave-hawk-s8nnfb.com   00D1t000000rW83EAE  Connected
MyTP    maxim.shevchenko@curious-goat-58410.com  00D0X000000tBDeUAM  Connected