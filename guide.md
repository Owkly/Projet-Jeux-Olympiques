# Installation

```bash
sudo apt update && sudo apt upgrade -y
sudo apt install -y qtcreator qtbase5-dev qt5-qmake cmake

qmake -query
qmake --version
```
Puis allez avec alt+shift+p puis entrer c_cpp_properties.json et ajouter les lignes suivantes (si vous avez x86_64-linux-gnu) :

```json 
C/C++: Edit Configurations (UI)
    /usr/include/x86_64-linux-gnu/qt5
    /usr/include/x86_64-linux-gnu/qt5/QtWidgets
    /usr/include/x86_64-linux-gnu/qt5/QtGui
    /usr/include/x86_64-linux-gnu/qt5/QtCore
C/C++: Edit Configurations (JSON)
```


https://www.youtube.com/watch?v=w-IP-UD-OAE
