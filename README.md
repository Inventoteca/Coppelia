# Coppelia Sim
Es un simulador de robots desarrollado por Coppelia Robotics.  
Antes se llamaba V-Rep y fue creado por Toshiba R&D.  

Trabajar con CoppeliaSim versión EDU.  
La versión PRO necesita una licencia para guardar las escenas.  

Manual  
https://www.coppeliarobotics.com/helpFiles/index.html  
API Reference  
https://coppeliarobotics.com/helpFiles/index.html  

Diseño 3D Robot con 3 DOF  
https://grabcad.com/library/robot-scara-3-dof-1  

Extensión para exportar modelo de SolidWorks  
http://wiki.ros.org/sw_urdf_exporter  

Tutoriales  
https://www.youtube.com/watch?v=ElL6ocuTWjY  
https://www.youtube.com/watch?v=mv2_DlkfFPk  
https://www.youtube.com/watch?v=dKfmSvOajrs  

Editor matemático online  
http://www.imatheq.com/imatheq/com/imatheq/math-equation-editor.html  

Funciones para el control  
https://www.coppeliarobotics.com/helpFiles/en/regularApi/simSetJointMaxForce.htm  
https://www.coppeliarobotics.com/helpFiles/en/regularApi/simSetJointTargetPosition.htm  
https://www.coppeliarobotics.com/helpFiles/en/regularApi/simSetJointMode.htm  

Como aplicar torque a una unión  
https://forum.coppeliarobotics.com/viewtopic.php?t=497  

Para entender qué significa par motor  
https://es.wikipedia.org/wiki/Par_motor  

Curso ??
http://hades.mech.northwestern.edu/index.php/Getting_Started_with_the_CoppeliaSim_Simulator

## Definiciones
**Espacio de trabajo** - Son todos los puntos alcanzables por la herramienta de trabajo.
Por lo general se define con 3 valores de posición y 3 de orientación.  

**Espacio articular** - Ángulos o posiciones de todas las articulaciones.  

**Cinemática directa** convierte espacio articular a espacio de trabajo.  

**Cinemática inversa** convierte espacio de trabajo a espacio articular. Puede tener varias soluciones (redundante).  

**Exactitud** - Evaluación verdadera o falsa, menor diferencia con lo real.  

**Precisión** - Incertidumbre.  
