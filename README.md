# RunaOS.
#reflexion
#me parecio un buen proyecto , tuve que invertigar un poco mas. lo unico que no sabia si era en codigo en texto o como. pero en codigo es una simulacion ya que para hacer un sistema operativo se necesitan  mas cosas
#lo compare con linux ya que de codigo abierto, se utiliza mucho eso si , no tanto como windows o mac os. x eso me parecio un poco mas interesante y talvez el poder tener una mejor innovacion que con el resto de sistemas operativos
    #  Tipo de núcleo: Microkernel
    # Justificación: modularidad, seguridad, tolerancia a fallos. Servicios como drivers y seguridad se ejecutan fuera del núcleo.
    print(f"{self.nombre} iniciado con núcleo tipo Microkernel.")

#  Gestión de procesos
def crear_proceso(self, nombre, tipo="neuroactivo"):
    proceso = {"nombre": nombre, "estado": "listo", "tipo": tipo}
    self.procesos.append(proceso)
    self.logs.append(f"Proceso '{nombre}' creado.")
    print(f"Proceso '{nombre}' creado en estado 'listo'.")

def eliminar_proceso(self, nombre):
    self.procesos = [p for p in self.procesos if p["nombre"] != nombre]
    self.logs.append(f"Proceso '{nombre}' eliminado.")
    print(f"Proceso '{nombre}' eliminado.")

def planificar_procesos(self):
    print("Planificación MLQ en curso...")
    for proceso in self.procesos:
        proceso["estado"] = "ejecutando"
        self.logs.append(f"Proceso '{proceso['nombre']}' ejecutado.")
        print(f"Ejecutando proceso: {proceso['nombre']}")

#  Gestión de memoria
def asignar_memoria(self, proceso, segmento, tamaño):
    # Segmentación cognitiva + paginación inversa
    self.memoria[proceso] = {"segmento": segmento, "tamaño": tamaño}
    self.logs.append(f"Memoria asignada a '{proceso}': {segmento} ({tamaño}MB)")
    print(f"Memoria asignada a '{proceso}': {segmento} ({tamaño}MB)")

#  Seguridad
def autenticar_usuario(self, usuario, eeg_hash):
    # Autenticación por EEG
    self.usuarios[usuario] = eeg_hash
    self.logs.append(f"Usuario '{usuario}' autenticado.")
    print(f"Usuario '{usuario}' autenticado con EEG.")

def verificar_acceso(self, usuario, eeg_hash):
    if self.usuarios.get(usuario) == eeg_hash:
        self.logs.append(f"Acceso concedido a '{usuario}'.")
        print(f"Acceso concedido a '{usuario}'.")
    else:
        self.logs.append(f"Acceso denegado a '{usuario}'.")
        print(f"Acceso denegado a '{usuario}'.")

# Interfaz de usuario
def interfaz_usuario(self, modo="BCI"):
    # Modos disponibles: CLI, GUI, voz, gestos, BCI
    self.logs.append(f"Interfaz activada en modo: {modo}")
    print(f"Interfaz activada en modo: {modo}")

# Sistema de archivos: RunaFS
def sistema_archivos(self):
    # Estructura semántica, permisos adaptativos, jerarquía dinámica
    print("Sistema de archivos RunaFS activado.")
    print(" - Estructura: semántica por conceptos.")
    print(" - Permisos: adaptativos según estado mental.")
    print(" - Jerarquía: dinámica según contexto de uso.")
    self.logs.append("Sistema de archivos RunaFS activado.")

#  Estado del sistema
def mostrar_estado(self):
    print("\n Estado actual de RunaOS:")
    print("Procesos activos:", [p["nombre"] for p in self.procesos])
    print("Memoria asignada:", self.memoria)
    print("Usuarios registrados:", list(self.usuarios.keys()))
    print("Logs del sistema:")
    for log in self.logs:
        print(" -", log)
