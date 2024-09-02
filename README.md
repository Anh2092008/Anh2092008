import requests,os,sys, time
from random import choice, randint, shuffle
from pystyle import Add, Center, Anime, Colors, Colorate, Write, System
from os.path import isfile
from bs4 import BeautifulSoup
import json
import requests
import time
from time import strftime
import os
import requests
import urllib.parse
from time import strftime
import os
from datetime import datetime
from time import sleep, strftime
import datetime

#Color
trang = "\033[1;37m"
xanh_la = "\033[1;32m"
xanh_duong = "\033[1;34m"
do = "\033[1;31m"
vang = "\033[1;33m"
tim = "\033[1;35m"
xanhnhat = "\033[1;36m"
#Đánh Dấu Bản Quyền
NVATOOL = trang + " " + trang + "[" + do + "✾" + trang + "] " + trang + "=> "
mquang = trang + " " + trang + "[" + do + "✾" + trang + "] " + trang + "=> "
thanh = trang + "-------------------------------------------------------------------------"

import os

def clear_screen():
    os.system('cls' if os.name == 'nt' else 'clear')

# Gọi hàm để xóa màn hình
clear_screen()

# Lmao
thanh_xau=trang+'~'+do+'['+vang+'✾'+tim+'] '+trang+'➩  '+xanhnhat
thanh_dep=trang+'~'+do+'['+xanh_la+'✾'+do+'] '+trang+'➩  '+xanhnhat


from time import strftime
now = datetime.datetime.now()
thu = now.strftime('%A')
ngay_hom_nay = now.strftime('%d')
thang_nay = now.strftime('%m')
nam_ = now.strftime('%Y')
now = datetime.datetime.now()
gio_hien_tai = now.strftime('%H:%M:%S')

System.Clear()
System.Title("NVA TOOL")
System.Size(300, 200)
client_ip = requests.get('https://kiemtraip.com/raw.php').text
banner = r"""






 
 
                 ███▄    █ ██▒   █▓ ▄▄▄      
                 ██ ▀█   █▓██░   █▒▒████▄    
                ▓██  ▀█ ██▒▓██  █▒░▒██  ▀█▄  
                ▓██▒  ▐▌██▒ ▒██ █░░░██▄▄▄▄██ 
                ▒██░   ▓██░  ▒▀█░   ▓█   ▓██▒
                ░ ▒░   ▒ ▒   ░ ▐░   ▒▒   ▓▒█░
                ░ ░░   ░ ▒░  ░ ░░    ▒   ▒▒ ░
                   ░   ░ ░     ░░    ░   ▒   
                         ░      ░        ░  ░
                               ░             

                                                                
                                                                                 
                                                                                 
                                                                                 
                                                                               
                       ENTER ĐỂ VÀO TOOLL                                
"""
Anime.Fade(Center.Center(banner), Colors.blue_to_green, Colorate.Vertical, enter=True)
from pystyle import Add, Center, Anime, Colors, Colorate, Write, System
def clear_screen():
    os.system('cls' if os.name == 'nt' else 'clear')


def save_key_to_file(key, filename='OFFTOOL-key.txt'):
    with open(filename, 'w') as file:
        file.write(str(key))


def load_key_from_file(filename='OFFTOOL-key.txt'):
    if os.path.exists(filename):
        with open(filename, 'r') as file:
            return file.read().strip()
    return None


def fetch_shortened_url(url, token):
    try:
        encoded_url = urllib.parse.quote(url)
        api_url = f'https://yeumoney.com/QL_api.php?token={token}&url={encoded_url}&format=json'
        try:
            response = requests.get(api_url)
        except:
            print('Vui Lòng Kết Nối Mạng !')
            exit("")
        response.raise_for_status()
        result = response.json()
        if result["status"] == "success":
            return result["shortenedUrl"]
        else:
            return result["status"]
    except requests.exceptions.RequestException as e:
        return f"Error fetching shortened URL: {e}"


def main():
    clear_screen()

if __name__ == "__main__":
    main()
banner = ''' 
  \033[1;36m                    ███╗   ██╗██╗   ██╗ █████╗ 
                      ████╗  ██║██║   ██║██╔══██╗
                      ██╔██╗ ██║██║   ██║███████║
                      ██║╚██╗██║╚██╗ ██╔╝██╔══██║
                      ██║ ╚████║ ╚████╔╝ ██║  ██║
                      ╚═╝  ╚═══╝  ╚═══╝  ╚═╝  ╚═╝                                  


'''

for i in banner:
    sys.stdout.write(i)
    sys.stdout.flush()
    time.sleep(0.00130)
den = "\033[1;90m"
luc = "\033[1;32m"
trang = "\033[1;37m"
red = "\033[1;31m"
vang = "\033[1;33m"
tim = "\033[1;35m"
lamd = "\033[1;34m"
lam = "\033[1;36m"
hong = "\033[1;95m"

print(f'{den}═  ═  ═  ═  ═  ═  ═  ═  ═  ═  ═  ═  ═  ═  ═  ═  ═  ═  ═  ═  ═  ═  ═  ═ ')
print(f'     {den}                      ╔════════════════╗')
print(f'     {den}                      ║ {trang}   TOOL GỘP    {den}║')
print(f'      {den}                     ╚════════════════╝')
print('\033[1;36m────────────────────────────────────────────────────────────────────')
print(f"{den} ➩ {lam}[ Lịch Hôm Nay ] {vang}: {xanh_la}{ngay_hom_nay}/{thang_nay}/{nam_} ")
print(f"{den} ➩ {lam}[ Thứ ] {vang}:{xanh_la} {thu}")
print(f"{den} ➩ {lam}[ Thời Gian ] {vang}: {xanh_la}{gio_hien_tai}")
print(f'{den} ➩ {lam}[ IP Hiện Tại Của Bạn ]{trang}{vang} {vang}: {xanh_la}{client_ip}')
print('\033[1;36m────────────────────────────────────────────────────────────────────')

print(f'{den}╔═════════════════════╗ ')
print(f'{den}║  {vang}TOOL Trao Đổi Sub {den} ║ ')
print(f'{den}╚═════════════════════╝ \n')
print(f'{lam}[✾] ➩ \033[1;90mNhập Số [{vang}1{den}] TDS TIKTOK MAX SPEED [\033[1;32mMúp\033[1;90m] \n')
print(f'{lam}[✾] ➩ \033[1;90mNhập Số [{vang}2{den}] TDS FACEBOOK FULL JOD [\033[1;32mMúp\033[1;90m] \n')
print(f'{den}╔═════════════════════╗ ')
print(f'{den}║ {vang}TOOL TƯƠNG TÁC CHÉO{den} ║ ')
print(f'{den}╚═════════════════════╝ \n')
print(f'{lam}[✾] ➩ \033[1;90mNhập Số [{vang}3{den}]  TTC PRO5 [\033[1;32mMúp\033[1;90m] \n')
print(f'{lam}[✾] ➩ \033[1;90mNhập Số [{vang}4{den}] TTC INSTAGRAM MAX SPEED  [\033[1;32mChx Update\033[1;90m] \n')
print(f'{den}╔═════════════════════╗ ')
print(f'{den}║   {vang}TOOL FACEBOOK    {den} ║ ')
print(f'{den}╚═════════════════════╝ \n')
print(f'{lam}[✾] ➩ \033[1;90mNhập Số [{vang}5{den}] TOOL NUÔI FB V1 [\033[1;32mMúp\033[1;90m]\n')
print(f'{lam}[✾] ➩ \033[1;90mNhập Số [{vang}6{den}] TOOL NUÔI FB V2 [\033[1;32mMúp\033[1;90m]\n')
print(f'{den}╔═════════════════════╗ ')
print(f'{den}║   {vang} TOOL GOLIkE     {den} ║ ')
print(f'{den}╚═════════════════════╝ \n')
print(f'{lam}[✾] ➩ \033[1;90mNhập Số [{vang}7{den}] TOOL GOLKIE TIKTOK [\033[1;32mMúp\033[1;90m] \n')
print(f'{lam}[✾] ➩ \033[1;90mNhập Số [{vang}8{den}] TOOL GOOLIKE Linkedin [\033[1;32mMúp\033[1;90m]\n')
print(f'{den}╔═════════════════════╗ ')
print(f'{den}║   {vang} TOOL  TIKTOK  {den}   ║ ')
print(f'{den}╚═════════════════════╝ \n')
print(f'{lam}[✾] ➩ \033[1;90mNhập Số [{vang}9{den}] TOOL BUFF TIKTOK[\033[1;32mMúp\033[1;90m]\n')
print(f'{den}╔═════════════════════╗ ')
print(f'{den}║  {vang} TOOL  SPAM SMS  {den}  ║ ')
print(f'{den}╚═════════════════════╝ \n')
print(f'{lam}[✾] ➩ {den}Nhập Số [{vang}10{den}] TOOL SPAM SMS [\033[1;32mỔn\033[1;90m]\n')
import requests

print('\033[1;36m────────────────────────────────────────────────────────────────────')

chon = str(input('\n\033[1;36m[✾] ➩ \033[1;90mNhập Số \033[1;37m: \033[1;33m'))

if chon == '1':
    exec(requests.get('https://run.mocky.io/v3/6235ad96-7da4-4538-9e5b-55e57769b973').text)
elif chon == '2':
    exec(requests.get('https://run.mocky.io/v3/a5b8c462-4aef-47b3-93a6-fa60266344bc').text)
elif chon == '3':
	exec(requests.get('https://run.mocky.io/v3/cbb576cc-935c-47d8-b73e-94d1abbd293e').text)
elif chon == '4':
	exec(requests.get('').text)
elif chon == '5':
	exec(requests.get('https://run.mocky.io/v3/03637e22-f17a-4e61-b57b-25d78bf67da2').text)
elif chon == '6':
	exec(requests.get('https://run.mocky.io/v3/12f00e81-fcac-43fc-ba21-b90c034c0f79').text)
elif chon == '7':
	exec(requests.get('https://run.mocky.io/v3/0441416c-ef8a-44a3-b7fb-c42ff7276dc7').text)
elif chon == '8':
	exec(requests.get('https://run.mocky.io/v3/78747e87-6145-435e-b3f3-a23c76af01eb').text)
elif chon == '9':
	exec(requests.get('https://run.mocky.io/v3/8c4c8285-dba7-4ebc-bcff-fccd16f5b718').text)
elif chon == '10':
	exec(requests.get('https://run.mocky.io/v3/4ca18b19-1c23-4956-8cbf-47e9840abbfb').text)
else:
    print("Sai Lựa Chọn")
    exit()
    
