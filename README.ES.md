# Politicas-de-seguridad-DLP

#Primera parte-Informe
Dentro de este repositorio se encuentra el informe "Políticas de Seguridad DLP" que corresponde para el proyecto "Implementa Políticas de Seguridad DLP a dispositivos de almacenamiento externo".
#Segunda parte-Bloqueo de USB's en windows 10
Para la parte del taller que solicita configurar dispositivos USB, se hace uso de la maquina virtual Windows 10. La idea era utilizar el sw "gpedit.msc" para bloquear el acceso a dispositivos USB "Acceso de almacenamiento removible" se habilitan las siguientes configuraciones:
-Discos extraíbles: denegar acceso de lectura.
-Discos extraíbles: denegar acceso de escritura.

Ver imagen "1.png" 

Sin embargo, no fue posible bloquear los dispositivos USB en dos tipos de usuarios disponibles.

Por lo tanto se ingresa al editor de registros y se bloquea el el registro que permite inicar USB's dentro de windows 10. 
Ver imagen "2.png"
