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
force_hash = 0 <br/>
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
[INFO]<br/>
active_info = 1<br/>
activeurl = 0<br/>
urlinfo = "http://"<br/>
name = "\data\info.html"<br/>
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
0 = "test.ini;%pseudo%,%login%,%password%;.\"<br/>
