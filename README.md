# AlarconDaniPractExtra2425

## **Actividad: `git add` y Patrones**

---

### **Estructura Inicial del Proyecto**
1. Crea la siguiente estructura de archivos y directorios:
    ```bash
   mkdir -p proyecto-patrones/{docs,scripts,images,temp}
   touch proyecto-patrones/{docs/{manual.txt,guia.md,readme.txt},scripts/{app.js,utils.py,config.js},images/{logo.png,icon.jpg,banner.gif},temp/{pruebas.log,debug.txt,draft.md}}
   ```
   ![image](https://github.com/user-attachments/assets/cd2f5c30-4337-4509-9c8d-15c1f0e4403d)
2. Verifica que la estructura es la siguiente:
    ```bash
   tree proyecto-patrones/

   ```
   ![image](https://github.com/user-attachments/assets/de47f609-ef9f-440e-9947-879799465eaa)

   3. Inicializa el repositorio y haz un commit inicial.
  ![image](https://github.com/user-attachments/assets/d299bc9b-2612-45f5-8fb6-11e55abf9284)

 ```bash
   git init
git commit -m "Primer commit"

   ```
---

### **COMENZAMOS**

#### **1. Prepara archivos con patrones simples**

1. Añade  **solo** los archivos `.txt` que están en la carpeta `docs/` y muestra el estado.

2. Haz un commit.
   ![image](https://github.com/user-attachments/assets/e7ab447f-401f-4030-80d0-978bd8c32649)

    ```bash
   git add docs/*.txt
    git commit -m "Fitxeros txt"

   ```
---

#### **2. Trabaja con subdirectorios y extensiones**

1. Añade **todos los archivos `.js`** del directorio `scripts/` pero **excluye `config.js`** y muestra el estado.

2. Haz un commit con los cambios.

    ```bash
   git add scripts/app.js
    git commit -m "Fichero js"

   ```
    ![image](https://github.com/user-attachments/assets/5fc9207f-bf8c-450d-a363-466680807157)
---

#### **3. Máscaras en niveles**

1. Añade **todas las imágenes excepto las que terminan en `.gif`**

2. Confirma que los archivos `.png` y `.jpg` están en el área de preparación y muestra el estado.

3. Haz un commit.
 ```bash
   git add images/*
   git reset images/*.gif
   git s

   ```
   ![image](https://github.com/user-attachments/assets/d8f43b9f-e4c8-45b3-8045-fcc45e070548)

---

#### **4. Sube el repositorio Git Local al Remoto**

1. Ya sabes como hacerlo, si no te acuerdas tienes aquí la [guía de comandos](https://github.com/VelezBeatriz/ITB-M08-DAW1/blob/main/README.md)

   ```bash
   git remote add AlarconDaniPractExtra2425 https://github.com/Dani-Alarcon/AlarconDaniPractExtra2425.git

   ```
   ![image](https://github.com/user-attachments/assets/556bdff0-10b9-4c4e-b150-f773ba19fcc6)
   ![image](https://github.com/user-attachments/assets/3bd2a095-d671-4b4a-8cb1-baacfab335f9)


