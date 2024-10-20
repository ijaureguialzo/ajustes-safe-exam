# Ajustes para Safe Exam

Recopilación de ajustes para configurar Safe Exam Browser.

## IntelliJ IDEA Community Edition

### Aplicaciones permitidas

| Ajuste         | Valor                                                         |
|----------------|---------------------------------------------------------------|
| Título	        | IntelliJ IDEA                                                 |
| Ejecutable	    | `idea64.exe`                                                  |
| Ruta	          | `%LOCALAPPDATA%\programs\intellij idea community edition\bin` |
| Mostrar icono	 | Sí                                                            |
| Forzar cierre  | No                                                            |

Para permitir clonar repositorios desde IntelliJ hay que añadir los ajustes de Git Credential Manager.

Si queremos usar un enlace directo a un repositorio y que se abra el IntelliJ automáticamente, hay añadir también los de
JetBrains Toolbox.

## Git Credential Manager

### Aplicaciones permitidas

| Ajuste         | Valor                            |
|----------------|----------------------------------|
| Título	        | Git Credential Manager (admin)   |
| Ejecutable	    | `git-credential-manager.exe`     |
| Ruta	          | `%PROGRAMFILES%\Git\mingw64\bin` |
| Mostrar icono	 | No                               |
| Forzar cierre  | Sí                               |

| Ajuste         | Valor                                     |
|----------------|-------------------------------------------|
| Título	        | Git Credential Manager (user)             |
| Ejecutable	    | `git-credential-manager.exe`              |
| Ruta	          | `%LOCALAPPDATA%\Programs\Git\mingw64\bin` |
| Mostrar icono	 | No                                        |
| Forzar cierre  | Sí                                        |

Como no sabemos si el usuario es un admin (ordenador propio del alumno) o no (equipos de clase), hay que añadir las dos.

Al iniciar Safe Exam Browser la que falte dará error.

## JetBrains Toolbox

### Aplicaciones permitidas

| Ajuste         | Valor                                  |
|----------------|----------------------------------------|
| Título	        | JetBrains Toolbox                      |
| Ejecutable	    | `jetbrains-toolbox.exe`                |
| Ruta	          | `%LOCALAPPDATA%\jetbrains\toolbox\bin` |
| Mostrar icono	 | No                                     |
| Forzar cierre  | Sí                                     |

### URLs permitidas

| Ajuste | Valor           |
|--------|-----------------|
| URL	   | `jetbrains://*` |

## GitKraken

### Aplicaciones permitidas

| Ajuste         | Valor                      |
|----------------|----------------------------|
| Título	        | GitKraken                  |
| Ejecutable	    | `gitkraken.exe`            |
| Ruta	          | `%LOCALAPPDATA%\gitkraken` |
| Mostrar icono	 | Sí                         |
| Forzar cierre  | No                         |

### URLs permitidas

| Ajuste | Valor           |
|--------|-----------------|
| URL	   | `gitkraken://*` |
