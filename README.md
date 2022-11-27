# Proyecto_funda_utec
##dependiendo de tu espacio de trabajo
cd ~
source ~/lab_ws/devel/setup.bash
## visualizacion del robot
roslaunch proy display_irb5400_sliders.launch

### otra forma

roslaunch proy display_irb5400.launch

rosrun proy node_joints.py


## visualizar 
roslaunch proy display_irb5400.launch

## cinematica directa
rosrun proy test_fkine

## cinematica inversa
rosrun proy test_ikine

## control cinematico
rosrun proy control_cinematico

## control Dinamico
Descargar RBDL y asegurarse de que la libreria funcione correctamente.
### PD
rosrun proy control_pdg.py

### Feedforward linealization
rosrun proy control_feed.py
