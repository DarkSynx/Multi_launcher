# Multi_launcher
Multi launcher et un launcher de jeux configurable 

Launcher pour de multiple usage mais surtout je l'ai créé pour permettre au dévellopeur de jeux libre
,de les diffuser via leur site internet simplement . et surtout que le client qui utilise le launcher 
puisse disposé de la derier version et jouer . 


une version en préparation,
ajout de : 

 login et password  
 
 la gestion des langues
 
 possibilité d'auto télécharger le launcher si on dispose que de l'executable 

 l'ajout d'un bloque d'information web 
 
 possibilité l'executé les jeux encapsulé et virtualisé avec enigma virtual box 
 
 
 
 fichier ini de la version 1.3.3.1
 
[config]<br/>
force_hash = 0<br/>
modedebug = 1<br/>
devtest = 1<br/>
active_login = 1<br/>
active_nick = 1<br/>
exec = "myexe_execute_after.exe"<br/>
pseudo = "My NickName"<br/>
login = " My Login "<br/>
icolauncher = "data\ML.ico"<br/>
passwordhas = "SHA1"<br/>
dir = "download"<br/>
dirtmp = ".\data\tmp"<br/>
width = 710<br/>
height = 400<br/>
szfilenohash = 100000000<br/>
has_file_ptc = "haval160,4"<br/>
[progressbar]<br/>
pgb_general_width = 630<br/>
pgb_general_height = 24<br/>
pgb_general_x = 44<br/>
pgb_general_y = 312<br/>
pgb_general_color_back = "0x17238C"<br/>
pgb_general_color_forg = "0x1E2DB7"<br/>
pgb_download_width = 630<br/>
pgb_download_height = 24<br/>
pgb_download_x = 44<br/>
pgb_download_y = 312<br/>
pgb_download_color_back = "0x8C3718"<br/>
pgb_download_color_forg = "0xCD4717"<br/>
pgb_install_width = 630<br/>
pgb_install_height = 24<br/>
pgb_install_x = 44<br/>
pgb_install_y = 350<br/>
pgb_install_color_back = "0x512025"<br/>
pgb_install_color_forg = "0x983D46"<br/>
text_x = 125<br/>
text_y = 226<br/>
text_h = 10<br/>
text_c = 48<br/>
text_default_color = "0xFFFFFF"<br/>
[INFO]<br/>
active_info = 1<br/>
activeurl = 1<br/>
urlinfo = "https://www.youtube.com/embed/9RXsOMARKLE"<br/>
name = "\data\info.html"<br/>
width = 336<br/>
height = 143<br/>
x = 344<br/>
y = 37<br/>
[sound]<br/>
mp3 = "data\O.Z.O.N._-_Cycle__2014_Remaster_.mp3"<br/>
[IMGOPT]<br/>
fname = "img"<br/>
mname = "mask"<br/>
mask1 = "Mlauncher.png"<br/>
mask2 = "Mlauncher2.png"<br/>
[IMG]<br/>
0 = "img_1.jpg"<br/>
1 = "img_2.jpg"<br/>
2 = "img_3.jpg"<br/>
3 = "img_4.jpg"<br/>
4 = "img_5.jpg"<br/>
5 = "img_6.jpg"<br/>
6 = "img_7.jpg"<br/>
7 = "img_8.jpg"<br/>
8 = "img_9.jpg"<br/>
9 = "img_10.jpg"<br/>
[URL]<br/>
urlftp = "url_of_my_arch"<br/>
indexfile = "index_files.txt"<br/>
downlauncher = 0<br/>
downloadall = 0<br/>
[exclusion]<br/>
0 = "test.ini"<br/>
[patch]<br/>
0 = "test.ini;%pseudo%,%login%,%password%;.\"
