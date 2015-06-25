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
 
 [config]
force_hash = 0
modedebug = 1
devtest = 1
active_login = 1
active_nick = 1
exec = "myexe_execute_after.exe"
pseudo = "My NickName"
login = " My Login "
icolauncher = "data\ML.ico"
passwordhas = "SHA1"
dir = "download"
[INFO]
active_info = 1
activeurl = 0
urlinfo = "http://"
name = "\data\info.html"
[sound]
mp3 = "data\O.Z.O.N._-_Cycle__2014_Remaster_.mp3"
[IMGOPT]
fname = "img"
mname = "mask"
mask1 = "Mlauncher.png"
mask2 = "Mlauncher2.png"
[IMG]
0 = "img_1.jpg"
1 = "img_2.jpg"
2 = "img_3.jpg"
3 = "img_4.jpg"
4 = "img_5.jpg"
5 = "img_6.jpg"
6 = "img_7.jpg"
7 = "img_8.jpg"
8 = "img_9.jpg"
9 = "img_10.jpg"
[URL]
urlftp = "url_of_my_arch"
indexfile = "index_files.txt"
downlauncher = 0
downloadall = 0
[exclusion]
0 = "test.ini"
[patch]
0 = "test.ini;%pseudo%,%login%,%password%;.\"
