# RegistrAPP_Fuentes_Osorio_004D
Experiencia 3

Primero en la maquina local desinstalamos e instalamos nuevamente ionic
desintalamos --> npm uninstall -g ionic
instalamos --> npm install -g @ionic/cli@6
para luego instalar json -->  npm install -g json-server
dentro de DATA corremos el json ---> json-server --watch usuarios.json --host 0.0.0.0 --port 3300

--Ahora instalamos los componentes para la camara
npm install @capacitor/camera
ionic cap sync android
npm install @ionic/pwa-elements
npm install @capacitor-community/barcode-scanner
npx cap sync

---Instalamos para que funcione el qr
npm install angularx-qrcode --save
npm install -D @types/qrcode --save


abrimos servidor ---> ionic lab
