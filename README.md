# Carpeta-descargas-para-Pyton
repositorio con fines didácticos
import os 
import shutil 
file_types = { 
    'Imágenes' : [ '.jpg' , '.jpeg' , '.png' , '.gif' ], 
    'Documentos' : [ '.pdf' , '.docx' , '.txt' , '.xls' ], 
    'Vídeos' : [ '.mp4' , '.avi' , '.mkv' ], 
} 
path = 'Descargas' 
para nombre de archivo en os.listdir(ruta): 
    para carpeta, extensiones en file_types.items(): 
        si  las hay (filename.endswith(ext) para ext en extensiones): 
            os.makedirs( f" {ruta} / {carpeta} " , exist_ok= True ) 
            shutil.move( f" {ruta} / {nombre de archivo} " , f" {ruta} / {carpeta} " )
![image](https://github.com/user-attachments/assets/f860310a-5c63-45cb-94dc-9f6c506d1b4f)
