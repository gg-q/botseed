
import os, sys, subprocess
subprocess.getoutput('pip install requests')
import requests, sys, os, time
import requests, time, random, os, sys
TOKEN = '5077625700:AAHvB_ij47sPrWmcPlrYHxdh-QIAjWUp4Po'
ID = '1597993450'
os.system('clear')
MM = int(('100260'))
os.system('clear')
oip = 'QWEASDZXCRTYDFCVBNMLKJHGTYUIOP'
numper = '1234567890'
upper = 'A'
aoo = '_'
all = upper + oip
all1 = numper
length = 1
for e in range(MM):
    s = ''.join(random.sample(all1, length))
    h = ''.join(random.sample(all, length))
    o = ''.join(random.sample(all, length))
    kk =  o+h+o+o+o+o+o+o
    ree = requests.get(f"https://t.me/{kk}").text
    if 'tgme_username_link' in ree:
        Account = requests.post(f"https://api.telegram.org/bot{TOKEN}/sendMessage?chat_id={ID}&text=  𝙪َِ𝙨َِ𝙚َِ𝙧َِ 𝙣َِ𝙖َِ𝙢َِ𝙚َِ  ♰  @{kk} 𝐏𝐘 ; '𝐀𝐋𝐈 ' ")
