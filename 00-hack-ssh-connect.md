# Connexion à votre instance KALI Linux :

Vos Credentials et IP respectives vous seront envoyés sur le chat.
Une clé SSH .pem vous sera transmise sur le chat.

:warning: Si vous êtes sur Windows :

- Installation de Mobaxterm :  
https://download.mobatek.net/2022020030522248/MobaXterm_Portable_v20.2.zip

- La clé SSH vous est fournie par le formateur au format .ppk sur teams. 
téléchargez  la en local sur votre machine et notez bien l'endroit ou elle a été sauvegardeé

Se connecter en SSH à un des workers du cluster :  

ATTENTION SVP :   
Ci dessous vous avez une capture d'écran, elle est là juste **à titre d'exemple**

Vous devez rentrer :
- VOTRE USER : *kali*  
- VOTRE CLE SSH : le chemin complet de la clé .ppk  
- VOTRE Adresse IP : L'adresse IP attribuée par le formateur  

### La capture d'écran ci dessous est fournie à titre indicatif
  (Ne copiez pas bêtement les informations, lisez les instructions ci dessous :). )

![alt text](https://i.ibb.co/tYL7W8y/Annotation-2020-05-08-135954.png)  


<!-- La clé est fournie au format .pem : Convertissez-la en .ppk 

Pour ce faire suivre le mini-tuto ce-dessous :

- Convert PEM to PPK :

1. Open PuTTYgen
3. Click "Load" on the right side about 3/4 down
4. Set the file type to *.*
5. Browse to, and Open your .pem file
6. PuTTY will auto-detect everything it needs, and you just need to click "Save private key" and you can save your ppk key for use with PuTTY



https://stackoverflow.com/questions/3190667/convert-pem-to-ppk-file-format --!>
