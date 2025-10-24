#runaOS
#RunaOS: Sistema Operativo del Futuro
Propósito: RunaOS está diseñado para entornos educativos y científicos que integran interfaces cerebro-computadora (BCI). Su objetivo es facilitar una interacción directa entre el pensamiento humano y las máquinas, promoviendo accesibilidad, adaptabilidad y eficiencia cognitiva.

# Tipo de Núcleo: Microkernel
Justificación: El núcleo de RunaOS es de tipo microkernel, lo que significa que solo las funciones esenciales (como la gestión de memoria, procesos y comunicación) se ejecutan en el núcleo. Los servicios como drivers, sistema de archivos y seguridad se ejecutan en espacio de usuario. Esto mejora la modularidad, la seguridad y la tolerancia a fallos, permitiendo actualizaciones sin reiniciar el sistema completo.

#Gestión de Procesos
Creación de procesos: RunaOS permite crear procesos clasificados como “neuroactivos”, que responden a estímulos cognitivos.

#Planificación: Utiliza el algoritmo Multilevel Feedback Queue (MLQ), que adapta la prioridad de los procesos según su comportamiento y necesidades.

#Eliminación de procesos: Se pueden eliminar procesos activos para liberar recursos.

#Ejemplo: Se crean procesos como “AprendizajeInteractivo” y “SimulacionCognitiva”, que luego se ejecutan según la planificación MLQ.


![imagen.2](https://www.interactsolutions.com/wp-content/uploads/2020/03/bpm3.png)

# Gestión de Memoria
Segmentación cognitiva: La memoria se asigna según el tipo de tarea (visual, auditiva, motora, etc.).

#Paginación inversa: Optimiza el acceso predictivo a la memoria según patrones mentales.

#Asignación: Se asigna memoria a cada proceso con un tamaño específico, por ejemplo, 128MB al segmento visual de un proceso educativo.

#Seguridad
Autenticación por EEG: Los usuarios se autentican mediante patrones cerebrales únicos (hash EEG).

#Verificación de acceso: El sistema compara el EEG del usuario con el registrado para conceder o denegar acceso.

#Ejemplo: El usuario “Estudiante01” se autentica con su EEG y accede correctamente al sistema.

 #Interfaz de Usuario
Modos disponibles: CLI (línea de comandos), GUI (interfaz gráfica), comandos por voz, gestos y BCI.

#Adaptabilidad: La interfaz cambia según el nivel de atención, fatiga o emoción del usuario.

#Inclusividad: Pensada para usuarios con discapacidades motoras o del habla.

#Ejemplo: Se activa la interfaz en modo “voz + BCI” para una experiencia multimodal.

#Sistema de Archivos: RunaFS
Estructura semántica: Los archivos se organizan por conceptos y asociaciones mentales, no por carpetas tradicionales.

#Permisos adaptativos: El acceso a archivos depende del estado mental del usuario (ej. concentración).

#Jerarquía dinámica: La estructura del sistema de archivos se reorganiza según el contexto de uso (educativo, creativo, investigativo).

#Ejemplo: El sistema activa RunaFS y muestra sus características semánticas y adaptativas.

 #Estado del Sistema
#RunaOS puede mostrar su estado actual, incluyendo:

#Procesos activos.

#Memoria asignada por proceso.

#Usuarios registrados.

#Historial de acciones (logs del sistema).

#Comparación: RunaOS vs Linux
#Característica	RunaOS (Ficticio)	Linux (Real)
Propósito	Interacción humano-máquina con BCI en entornos educativos y científicos	Sistema operativo general para servidores, escritorios y móviles
Tipo de núcleo	Microkernel: modular, seguro, tolerante a fallos	Monolítico: alto rendimiento, menos modular
Gestión de procesos	Neurothreading + planificación MLQ adaptativa	Multithreading + algoritmos como Round Robin, CFS
Gestión de memoria	Segmentación cognitiva + paginación inversa	Segmentación + paginación tradicional
Sistema de archivos	RunaFS: semántico, adaptativo, jerarquía dinámica	ext4, Btrfs, XFS: jerárquicos, basados en bloques
Seguridad	Autenticación EEG + cifrado NeuroCrypt + control emocional-cognitivo	Contraseñas, certificados, SELinux, cifrado estándar
Interfaz de usuario	Multimodal: CLI, GUI, voz, gestos, BCI adaptativa	CLI + GUI (Gnome, KDE, etc.)
Innovación destacada	Interacción mental directa + adaptabilidad emocional	Estabilidad, rendimiento, personalización


#el xq lo compare con linux 

#Razones para elegir Linux como punto de comparación
Es de código abierto Linux permite estudiar su arquitectura, modificarla y adaptarla, lo que lo convierte en una excelente base para aprender cómo funciona un sistema operativo desde dentro.

 ![imagen.](https://t7m8e9c8.delivery.rocketcdn.me/wp-content/uploads/2020/12/linux-tux.jpg)

#reflexion
#me parecio un buen proyecto , tuve que invertigar un poco mas. lo unico que no sabia si era en codigo en texto o como. pero en codigo es una simulacion ya que para hacer un sistema operativo se necesitan  mas cosas



