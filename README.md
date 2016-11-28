# Instalación de Ionic


#Instalar nodejs
```
sudo apt-get install python-software-properties

curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -

sudo apt-get install nodejs
```

# Instalar cordova
```
sudo npm install -g cordova
```

# Instalar ionic
```
sudo npm install -g ionic
```

# Instalar java en ubuntu 
```
sudo add-apt-repository ppa:webupd8team/java

sudo apt-get update

sudo apt-get install oracle-java8-installer

sudo update-java-alternatives -s java-8-oracle

sudo apt-get install oracle-java8-set-default
```

# Instalar JDK android
```
# Descargar Android Studio
https://developer.android.com/studio/index.html

# Descomprimir en algun lugar de tu /home. Ej:
/home/pepe/Android
```

# Setear variable ANDROID_HOME
```
export ANDROID_HOME="/home/pepe/Android/Sdk"
```

# Crear el primer proyecto en ionic
```
ionic start --v2 myApp tabs

ionic platform add android

ionic build android
```

# Buscar tu primera apk
```
/home/chango/IonicProyects/demoIonic/platforms/android/build/outputs/apk
```