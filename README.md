# PSR-TP3-Grupo3

Repositório usado para a partilha de ficheiros referentes ao Trabalho Prático Numero 3 da Unidade Curricular de Projeto de Sistemas Robóticos pela equipa:

Gil Viegas Nº99576 (https://github.com/gilviegas)

Gonçalo Ribeiro Nº93193 (https://github.com/GoncaloR00)

Pedro Ribeiro Nº94287 (https://github.com/PedroRibeiro37)

Tomás Borges Nº93121 (https://github.com/tomastjcb)


# Modos de Jogo
Condução Manual Turtlebot3 em Pista: https://youtu.be/OEAvULfRDtY

Para a condução manual foi usado o robô de Cor vermelha("Red1") com as suas respetivas câmaras conseguindo assim evitar os obtáculos através do ficheiro myteleop desenvolvido nas aulas teóricas.

Condução manual com uso do gmapping:https://youtu.be/Cv59HHV9rXU
Para o gmapping foi utilizado o robô de cor vermelha ("Red1") na Arena 3.

TeamHunt: Neste modo de jogo os robôs caçam e fogem de outros robôs, usando para isso um modo de condução automático.
Para inciar este modo de jogo, começa-se por abrir o Gazebo

    roslaunch p_g3_bringup gazebo.launch
De seguida carrega-se o jogo

    roslaunch p_g3_bringup game_bringup.launch

E por fim, inicia-se o árbitro

    rosrun th_referee th_referee

Opcionalmento é possivel ver o que cada robô está a fazer. Para isso basta iniciar o chatter

    rosrun p_g3_driver chatter
