### Requerimientos previos

Esta CFG fue creada para funcionar correctamente con el clientMOD eternal JKA:
- https://github.com/eternalcodes/EternalJK

### Instalación
Los siguientes archivos deben ser colocados en la carpeta base del juego: master.cfg, sabering.cfg, jedimode.cfg, sithmode.cfg and racemode.cfg `\Star Wars Jedi Knight Jedi Academy\GameData\base`. Dentro del juego ejecutar el comando`exec master.cfg'.

### Controles
- F1 = name to Padawan
- F2 = name "yourName1"
- F3 = name "yourName2"
- F4 = ejecuta master.cfg
- f5 = ejecuta sabering.cfg
- f6 = ejecuta jedimode.cfg
- f7 = ejecuta sithmode.cfg
- f8 = ejecuta racemode.cfg
- f10 = record
- f11 = stoprecord
- f12 = screenshot
- ctrl = Amtelemark (para straffe)
- alt = Amtele (para straffe)
- 7, 8 y 9 = cambia sable: Single, double and staff.
- H y J = Zoom in y out respectivamente.

### Base commands Documentation
- `com_maxfps` Esto altera tu nivel de salto: 142=muy bajo, 200=bajo 125=medio 333=alto
- `cl_timenudge` Se considera este comando un hack actualmente, pero a nivel de código solo es realmente hack si es mayor a 30 o menor a -30
- `cg_rendertotexturefx 0;` Desactiva efecto del push y pull
- `cg_fov` Se considera hack si es mayor a 97
- `cg_thirdPersonRange` tpr > 80 = hack

### Ja+ commands Documentation
- `amdropsaber` drop saber
- `pluginDisable 13;` SP/MP-style for cartwheel move

### eternalJKA commands Documentation
- Eternal no requiere mayores configuraciones para records de demos
```
bind f10 record;
bind f11 stoprecord;
```
- `cg_defaultModelRandom 0;` anti-bugmodel.
- `stylePlayer 0;` Modelos muy brillantes
