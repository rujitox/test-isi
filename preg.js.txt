var PREGUNTAS_TEST = {
  "Tema 5": [
    {
      "question": "Si en una estación aumenta X y S no cambia, ¿qué pasa con U?",
      "answers": [
        "Aumenta en la misma proporción",
        "Disminuye por tener más flujo",
        "Permanece siempre constante",
        "Pasa a valer exactamente S del modelo"
      ],
      "correct": 0,
      "explanation": "Por la ley U = X * S, si S permanece fija, U crece cuando aumenta X."
    },
    {
      "question": "¿Qué mide mejor la productividad de un sistema?",
      "answers": [
        "Trabajos presentes en la cola en la red",
        "Trabajos completados por unidad de tiempo",
        "Segundos que dura una petición en la red",
        "Usuarios conectados sin responder"
      ],
      "correct": 1,
      "explanation": "La productividad mide salidas o completaciones por unidad de tiempo."
    },
    {
      "question": "¿Qué recurso será candidato a cuello de botella?",
      "answers": [
        "El de menor tiempo de visita del recurso",
        "El de menor utilización medida",
        "El de mayor demanda de servicio",
        "El de menor número de accesos"
      ],
      "correct": 2,
      "explanation": "El recurso con más demanda tiende a saturarse antes y limitar el sistema."
    },
    {
      "question": "En una red cerrada, ¿qué dato se fija normalmente?",
      "answers": [
        "La tasa externa de llegada",
        "El coste de explotación observada",
        "La disponibilidad pactada",
        "El número total de clientes N"
      ],
      "correct": 3,
      "explanation": "En redes cerradas se mantiene una población fija N dentro del sistema."
    },
    {
      "question": "¿Qué diferencia una red abierta de una cerrada?",
      "answers": [
        "Tiene entradas y salidas externas",
        "No contiene estaciones de cola",
        "No permite calcular respuesta",
        "Solo admite cargas batch del sistema"
      ],
      "correct": 0,
      "explanation": "En redes abiertas los trabajos llegan desde fuera y abandonan el sistema."
    },
    {
      "question": "¿Qué representa una estación de retardo?",
      "answers": [
        "Un disco con una cola larga",
        "Un tiempo sin espera en cola",
        "Una CPU siempre saturada en la estación",
        "Un servidor físico único"
      ],
      "correct": 1,
      "explanation": "Una estación de retardo se modela con infinitos servidores y no genera cola."
    },
    {
      "question": "¿Qué significa tiempo de residencia?",
      "answers": [
        "Llegadas menos salidas",
        "Productividad por visitas",
        "Espera más servicio recibido",
        "Usuarios por terminal del modelo"
      ],
      "correct": 2,
      "explanation": "La residencia incluye el tiempo esperando y el tiempo siendo atendido."
    },
    {
      "question": "¿Cuál es una variable operacional básica?",
      "answers": [
        "Productividad X",
        "Utilización U en la red",
        "Tiempo medio S",
        "Tiempo ocupado B"
      ],
      "correct": 3,
      "explanation": "B se mide directamente; X, U y S se deducen de variables básicas."
    },
    {
      "question": "Si A y C son parecidos durante T, ¿qué supuesto se cumple?",
      "answers": [
        "Flujo equilibrado",
        "Retardo infinito",
        "Saturación nula",
        "Predicción lineal"
      ],
      "correct": 0,
      "explanation": "El equilibrio de flujo supone que entradas y salidas coinciden aproximadamente."
    },
    {
      "question": "¿Qué calcula la ley de Little?",
      "answers": [
        "Coste medio desde SLA",
        "Clientes medios desde X y R",
        "Visitas desde disponibilidad",
        "Colas desde presupuesto"
      ],
      "correct": 1,
      "explanation": "Little relaciona número medio en el sistema, productividad y tiempo de residencia."
    },
    {
      "question": "En un sistema interactivo, ¿qué es Z?",
      "answers": [
        "Tiempo de servicio del disco del sistema",
        "Utilización media del servidor",
        "Tiempo de reflexión del usuario",
        "Llegadas externas al sistema"
      ],
      "correct": 2,
      "explanation": "Z es el tiempo entre dos interacciones consecutivas de un usuario."
    },
    {
      "question": "Si Z vale cero, una carga interactiva se parece a una carga...",
      "answers": [
        "transaccional",
        "mixta abierta",
        "estacional",
        "batch"
      ],
      "correct": 3,
      "explanation": "Sin tiempo de reflexión, la carga interactiva equivale a mantener trabajos activos como en batch."
    },
    {
      "question": "¿Qué caracteriza a una carga transaccional?",
      "answers": [
        "Clientes entran y salen",
        "Población total fija del modelo",
        "Terminales con Z fijo",
        "Trabajos reemplazados"
      ],
      "correct": 0,
      "explanation": "Las cargas transaccionales se modelan como abiertas: llegan, se atienden y salen."
    },
    {
      "question": "¿Para qué sirve la tasa de visita Vk?",
      "answers": [
        "Mide segundos de reflexión en la red",
        "Cuenta accesos medios a un recurso",
        "Fija el número de usuarios",
        "Calcula coste de propiedad"
      ],
      "correct": 1,
      "explanation": "Vk indica cuántas veces una interacción visita un recurso."
    },
    {
      "question": "¿Qué expresa la demanda Dk?",
      "answers": [
        "Llegadas externas por segundo",
        "Clientes totales del sistema",
        "Servicio total pedido a un recurso",
        "Coste de mantenimiento del recurso"
      ],
      "correct": 2,
      "explanation": "Dk agrega el servicio que una interacción exige a un recurso."
    },
    {
      "question": "¿Qué hace el modelo de servidor central?",
      "answers": [
        "Predice costes económicos observada",
        "Elimina estaciones de cola",
        "Define acuerdos SLA observada",
        "Representa CPU y E/S del sistema"
      ],
      "correct": 3,
      "explanation": "El modelo central describe trabajos que pasan por CPU y dispositivos de E/S."
    },
    {
      "question": "¿Qué ocurre tras una petición de disco en el modelo central?",
      "answers": [
        "El trabajo vuelve a la CPU",
        "El trabajo desaparece siempre",
        "Se reinicia el valor de N",
        "Se calcula una media móvil"
      ],
      "correct": 0,
      "explanation": "Después de la E/S, el trabajo suele regresar a la CPU."
    },
    {
      "question": "¿Qué significa que una estación tenga cola?",
      "answers": [
        "Tiene infinitos servidores libres",
        "Puede haber espera antes del servicio",
        "Solo mide reflexión humana",
        "No recibe trabajos reales en la estación"
      ],
      "correct": 1,
      "explanation": "Una estación de cola representa espera cuando el servidor no está disponible."
    },
    {
      "question": "¿Qué indica una utilización cercana a 1?",
      "answers": [
        "Recurso sin demanda real",
        "Sistema sin trabajos activos",
        "Recurso casi siempre ocupado",
        "Tiempo de servicio nulo"
      ],
      "correct": 2,
      "explanation": "Una utilización alta indica poco margen libre y posible saturación."
    },
    {
      "question": "¿Qué terapia cambia hardware para eliminar un cuello?",
      "answers": [
        "tuning",
        "forecasting",
        "smoothing",
        "upgrading"
      ],
      "correct": 3,
      "explanation": "El upgrading consiste en mejorar o sustituir componentes hardware."
    },
    {
      "question": "¿Qué terapia ajusta sin cambiar hardware base?",
      "answers": [
        "tuning",
        "upgrading",
        "regresión",
        "NFU"
      ],
      "correct": 0,
      "explanation": "El tuning modifica configuración u organización, normalmente a nivel de sistema."
    },
    {
      "question": "¿Cuándo no conviene hablar de un único cuello de botella?",
      "answers": [
        "Cuando solo falla la CPU",
        "Cuando muchos recursos saturan",
        "Cuando Dk es máximo observada",
        "Cuando existe una cola en la red"
      ],
      "correct": 1,
      "explanation": "Si el problema es generalizado, es más correcto hablar de sistema sobrecargado."
    },
    {
      "question": "¿Para qué sirven los límites asintóticos?",
      "answers": [
        "Medir cada paquete de red del recurso",
        "Sustituir todos los modelos",
        "Acotar prestaciones con poco cálculo",
        "Eliminar datos de carga del sistema"
      ],
      "correct": 2,
      "explanation": "Permiten estimar límites superiores e inferiores de rendimiento rápidamente."
    },
    {
      "question": "¿Cuál es un límite optimista?",
      "answers": [
        "Mayor R posible",
        "Menor disponibilidad",
        "Mayor coste total",
        "Mayor X posible"
      ],
      "correct": 3,
      "explanation": "Los límites optimistas son máxima productividad y mínimo tiempo de respuesta."
    },
    {
      "question": "¿Cuál es un límite pesimista?",
      "answers": [
        "Mayor R posible",
        "Menor tiempo de cola",
        "Mayor productividad",
        "Menor demanda"
      ],
      "correct": 0,
      "explanation": "Los límites pesimistas indican peor productividad o peor respuesta posible."
    },
    {
      "question": "En batch, ¿qué representa N*?",
      "answers": [
        "Llegadas externas máximas",
        "Trabajos procesables sin colas",
        "Usuarios desconectados",
        "Coste mínimo posible en la red"
      ],
      "correct": 1,
      "explanation": "N* marca cuántos trabajos pueden procesarse antes de que aparezcan colas."
    },
    {
      "question": "En interactivo, ¿qué representa N*?",
      "answers": [
        "Visitas medias al disco",
        "Segundos por petición",
        "Terminales hasta saturación",
        "Coste de arranque del recurso"
      ],
      "correct": 2,
      "explanation": "N* indica desde cuántos terminales al menos un recurso queda saturado."
    },
    {
      "question": "Si se reduce D del cuello de botella, ¿qué se busca?",
      "answers": [
        "Aumentar el tiempo de espera",
        "Eliminar todos los clientes observada",
        "Forzar más saturación observada",
        "Mejorar productividad o respuesta"
      ],
      "correct": 3,
      "explanation": "Reducir la demanda del cuello libera capacidad del sistema."
    },
    {
      "question": "¿Qué ley relaciona Xi con X mediante visitas?",
      "answers": [
        "Ley del flujo forzado",
        "Ley de Little",
        "Ley de medias móviles",
        "Ley de regresión"
      ],
      "correct": 0,
      "explanation": "El flujo forzado relaciona productividad global y productividades por dispositivo."
    },
    {
      "question": "¿Dónde puede aplicarse Little?",
      "answers": [
        "Solo a redes sin cola",
        "A recurso, subsistema o sistema",
        "Solo a presupuestos en la estación",
        "Solo a predicción NFU"
      ],
      "correct": 1,
      "explanation": "La ley de Little puede aplicarse a varios niveles del modelo."
    },
    {
      "question": "¿Qué asume el análisis MVA en redes cerradas?",
      "answers": [
        "Se conoce X0 y se ignora N",
        "No hay clientes internos",
        "Se conoce N y se estima X",
        "No hay tiempos de servicio"
      ],
      "correct": 2,
      "explanation": "En MVA se parte de la población cerrada y se estima el rendimiento."
    },
    {
      "question": "¿Qué hipótesis simplifica los trabajos del modelo?",
      "answers": [
        "Trabajos sin CPU en la red",
        "Trabajos sin visitas",
        "Trabajos infinitos",
        "Trabajos del mismo tipo"
      ],
      "correct": 3,
      "explanation": "El tema asume trabajos homogéneos para facilitar el análisis."
    },
    {
      "question": "¿Qué variable mide completaciones durante T?",
      "answers": [
        "C",
        "A",
        "B",
        "Z"
      ],
      "correct": 0,
      "explanation": "C cuenta las peticiones completadas en el intervalo de observación."
    },
    {
      "question": "¿Qué variable mide llegadas durante T?",
      "answers": [
        "C",
        "A",
        "B",
        "R"
      ],
      "correct": 1,
      "explanation": "A cuenta las llegadas o peticiones recibidas durante el intervalo."
    },
    {
      "question": "¿Qué variable mide ocupación del recurso?",
      "answers": [
        "N",
        "Z",
        "B",
        "Vk"
      ],
      "correct": 2,
      "explanation": "B es el tiempo durante el cual el recurso observado estuvo ocupado."
    },
    {
      "question": "Si C=200 y T=100, X vale...",
      "answers": [
        "0,5",
        "100",
        "300",
        "2"
      ],
      "correct": 3,
      "explanation": "X = C/T = 200/100 = 2 peticiones por segundo."
    },
    {
      "question": "Si B=40 y T=80, U vale...",
      "answers": [
        "0,5",
        "2",
        "40",
        "120"
      ],
      "correct": 0,
      "explanation": "U = B/T = 40/80 = 0,5."
    },
    {
      "question": "Si B=25 y C=50, S vale...",
      "answers": [
        "2",
        "0,5",
        "25",
        "75"
      ],
      "correct": 1,
      "explanation": "S = B/C = 25/50 = 0,5 segundos por petición."
    },
    {
      "question": "¿Qué significa R en Little?",
      "answers": [
        "Tasa media de visitas",
        "Número de recursos",
        "Tiempo medio de residencia",
        "Coste de arranque del recurso"
      ],
      "correct": 2,
      "explanation": "R representa el tiempo medio que una petición permanece en el ámbito analizado."
    },
    {
      "question": "¿Qué representa N en una carga batch?",
      "answers": [
        "Llegadas por segundo",
        "Coste total anual observada",
        "Tiempo de reflexión",
        "Trabajos activos medios"
      ],
      "correct": 3,
      "explanation": "En batch cerrado, N es el factor de multiprogramación o trabajos activos."
    },
    {
      "question": "¿Qué representa N en interactivo?",
      "answers": [
        "Terminales activos",
        "Peticiones completadas",
        "Segundos de CPU",
        "Visitas al disco"
      ],
      "correct": 0,
      "explanation": "En cargas interactivas, N es el número de usuarios o terminales activos."
    },
    {
      "question": "¿Qué ocurre si X se acerca al límite del cuello?",
      "answers": [
        "Baja siempre la cola",
        "Crece mucho la espera",
        "Desaparece la demanda",
        "Z se hace negativo"
      ],
      "correct": 1,
      "explanation": "Al aproximarse a saturación, las colas y los tiempos de respuesta aumentan."
    },
    {
      "question": "¿Qué mide el tiempo de servicio?",
      "answers": [
        "Espera antes de usarlo",
        "Reflexión del usuario",
        "Uso real del recurso",
        "Tasa de llegada"
      ],
      "correct": 2,
      "explanation": "El servicio es el tiempo durante el cual el recurso atiende al trabajo."
    },
    {
      "question": "¿Qué mide el tiempo de espera?",
      "answers": [
        "Uso efectivo del servidor",
        "Productividad total",
        "Coste de operación",
        "Demora antes del servicio"
      ],
      "correct": 3,
      "explanation": "La espera es el tiempo antes de comenzar a usar el recurso."
    },
    {
      "question": "¿Qué es evaluar analíticamente una red?",
      "answers": [
        "Obtener índices resolviendo el modelo",
        "Cambiar todos los servidores",
        "Medir solo satisfacción del modelo",
        "Comprar más capacidad del recurso"
      ],
      "correct": 0,
      "explanation": "La evaluación analítica obtiene prestaciones a partir de ecuaciones del modelo."
    },
    {
      "question": "¿Qué técnica no se desarrolla en el tema?",
      "answers": [
        "Ley de Little en la red",
        "Cadenas de Markov",
        "Flujo forzado",
        "MVA observada"
      ],
      "correct": 1,
      "explanation": "Las cadenas de Markov se citan como alternativa, pero no se estudian en detalle."
    },
    {
      "question": "¿Qué representa el cliente en una red de colas?",
      "answers": [
        "Dispositivo de CPU",
        "Acuerdo económico del sistema",
        "Usuario o trabajo del sistema",
        "Herramienta de predicción"
      ],
      "correct": 2,
      "explanation": "Los clientes modelan usuarios, trabajos o peticiones que demandan servicio."
    },
    {
      "question": "¿Qué representa el servidor?",
      "answers": [
        "Usuario que piensa",
        "Serie temporal en la estación",
        "Presupuesto fijo",
        "Recurso que presta servicio"
      ],
      "correct": 3,
      "explanation": "El servidor equivale a un recurso físico o lógico que atiende trabajos."
    },
    {
      "question": "¿Qué modelo conviene para población fija?",
      "answers": [
        "Red cerrada",
        "Red abierta",
        "Media móvil",
        "NFU"
      ],
      "correct": 0,
      "explanation": "Si la población total no cambia, se modela como red cerrada."
    },
    {
      "question": "¿Qué modelo conviene para llegadas externas?",
      "answers": [
        "Red cerrada",
        "Red abierta",
        "Carga batch",
        "Estación retardo"
      ],
      "correct": 1,
      "explanation": "Las llegadas externas son propias de redes abiertas."
    },
    {
      "question": "Si U sube pero S permanece igual, ¿qué ha cambiado necesariamente?",
      "answers": [
        "Ha bajado B",
        "Ha bajado C",
        "Ha aumentado X",
        "Ha aumentado Z"
      ],
      "correct": 2,
      "explanation": "Como U = X * S, si S no cambia, la subida de U implica una subida de X."
    },
    {
      "question": "Si X aumenta mucho y R también, ¿qué sospecha es razonable?",
      "answers": [
        "El sistema está más vacío",
        "Z se ha vuelto nulo observada",
        "No hay colas posibles",
        "Hay congestión en algún recurso"
      ],
      "correct": 3,
      "explanation": "Más productividad con más respuesta suele indicar que algún recurso empieza a formar colas."
    },
    {
      "question": "¿Qué dato distingue mejor una cola de un retardo?",
      "answers": [
        "La posibilidad de espera",
        "El número de temas",
        "La existencia de costes",
        "La técnica de predicción"
      ],
      "correct": 0,
      "explanation": "Una estación de cola puede hacer esperar; una de retardo no genera cola."
    },
    {
      "question": "Si un disco tiene muchas visitas pero servicio muy bajo, ¿qué falta mirar?",
      "answers": [
        "Solo su nombre",
        "Su demanda total",
        "El número de PDFs",
        "El coste del aula"
      ],
      "correct": 1,
      "explanation": "La demanda depende de visitas y servicio; muchas visitas no bastan para saber si limita."
    },
    {
      "question": "Si un recurso tiene S alto pero casi no se visita, ¿qué puede ocurrir?",
      "answers": [
        "Que siempre sea el cuello",
        "Que U sea siempre uno",
        "Que no sea el cuello",
        "Que X sea siempre cero"
      ],
      "correct": 2,
      "explanation": "La demanda total puede ser baja si la tasa de visita es pequeña."
    },
    {
      "question": "¿Qué recurso limita primero al crecer la carga?",
      "answers": [
        "El de menor nombre",
        "El de menor coste",
        "El de menor cola hoy",
        "El de mayor D"
      ],
      "correct": 3,
      "explanation": "El recurso con mayor demanda de servicio alcanza antes la saturación."
    },
    {
      "question": "¿Qué pasa con U si se duplica S y X no cambia?",
      "answers": [
        "Se duplica U",
        "Se anula U",
        "Se mantiene U",
        "Se divide U"
      ],
      "correct": 0,
      "explanation": "Por U = X * S, duplicar S duplica la utilización si X es constante."
    },
    {
      "question": "Si X=5 y S=0,3, ¿qué indica U=1,5?",
      "answers": [
        "Recurso totalmente libre",
        "Modelo por encima de capacidad",
        "Servicio nulo en la red",
        "Flujo cerrado estable"
      ],
      "correct": 1,
      "explanation": "Una utilización superior a 1 no es viable para un único servidor sin saturación."
    },
    {
      "question": "¿Qué lectura tiene U=0,95?",
      "answers": [
        "Recurso sin uso del recurso",
        "Predicción inválida",
        "Muy poco margen libre",
        "Carga inexistente"
      ],
      "correct": 2,
      "explanation": "Una utilización del 95% deja muy poco margen antes de congestionar."
    },
    {
      "question": "Si C<T pero B≈T, ¿qué indica el recurso?",
      "answers": [
        "Está sin carga",
        "Tiene retardo infinito",
        "No recibe visitas",
        "Está casi saturado"
      ],
      "correct": 3,
      "explanation": "Si B se aproxima a T, el recurso estuvo ocupado casi todo el intervalo."
    },
    {
      "question": "¿Qué fórmula deduce S desde medidas directas?",
      "answers": [
        "B dividido entre C",
        "C dividido entre A",
        "T dividido entre N",
        "Z dividido entre R"
      ],
      "correct": 0,
      "explanation": "El tiempo medio de servicio es el tiempo ocupado total entre completaciones."
    },
    {
      "question": "¿Qué fórmula deduce X desde medidas directas?",
      "answers": [
        "B dividido entre C",
        "C dividido entre T",
        "A dividido entre C",
        "R dividido entre N"
      ],
      "correct": 1,
      "explanation": "La productividad se obtiene como completaciones por unidad de tiempo."
    },
    {
      "question": "¿Qué fórmula deduce λ desde medidas directas?",
      "answers": [
        "T dividido entre A",
        "B dividido entre C",
        "A dividido entre T",
        "N dividido entre Z"
      ],
      "correct": 2,
      "explanation": "La tasa de llegada cuenta llegadas por unidad de tiempo."
    },
    {
      "question": "En equilibrio, si A>C durante mucho tiempo, ¿qué ocurre?",
      "answers": [
        "Baja la cola siempre",
        "Se anula la demanda",
        "Desaparece la CPU",
        "Crece la acumulación"
      ],
      "correct": 3,
      "explanation": "Si entran más trabajos de los que salen, el sistema acumula peticiones."
    },
    {
      "question": "¿Qué indica una diferencia persistente entre A y C?",
      "answers": [
        "No hay flujo estable",
        "Hay retardo infinito",
        "El SLA se cumple",
        "Z vale cero"
      ],
      "correct": 0,
      "explanation": "El equilibrio requiere que las entradas y salidas se compensen en el periodo observado."
    },
    {
      "question": "¿Qué dato convierte visitas en demanda?",
      "answers": [
        "Tiempo de arranque",
        "Tiempo de servicio",
        "Coste total",
        "Disponibilidad"
      ],
      "correct": 1,
      "explanation": "La demanda combina visitas al recurso con tiempo de servicio por visita."
    },
    {
      "question": "Si Vk=4 y Sk=0,1, ¿cuánto vale Dk?",
      "answers": [
        "4,1",
        "40",
        "0,4",
        "0,025"
      ],
      "correct": 2,
      "explanation": "Dk = Vk * Sk = 4 * 0,1 = 0,4 segundos."
    },
    {
      "question": "Si Dcpu=0,2 y Ddisco=0,8, ¿qué recurso limita más?",
      "answers": [
        "CPU",
        "Terminal",
        "Ninguno",
        "Disco"
      ],
      "correct": 3,
      "explanation": "La mayor demanda de servicio suele marcar el cuello potencial."
    },
    {
      "question": "¿Qué modelo encaja con usuarios siempre reemplazados?",
      "answers": [
        "Batch cerrado",
        "Abierto puro",
        "Retardo aislado",
        "Predicción NFU"
      ],
      "correct": 0,
      "explanation": "En batch cerrado, al terminar un trabajo entra otro para mantener N."
    },
    {
      "question": "¿Qué modelo encaja con peticiones HTTP independientes?",
      "answers": [
        "Batch cerrado",
        "Red abierta",
        "Solo retardo",
        "MVA cerrado"
      ],
      "correct": 1,
      "explanation": "Peticiones que llegan y salen se modelan como carga abierta."
    },
    {
      "question": "¿Qué modelo encaja con usuarios en terminales?",
      "answers": [
        "Abierto sin límite",
        "Batch sin Z",
        "Interactivo cerrado",
        "Solo disco del recurso"
      ],
      "correct": 2,
      "explanation": "Los sistemas interactivos tienen N usuarios y tiempo de reflexión Z."
    },
    {
      "question": "¿Qué cambia entre batch e interactivo?",
      "answers": [
        "Desaparece N",
        "No hay CPU",
        "No hay colas",
        "Aparece Z"
      ],
      "correct": 3,
      "explanation": "La carga interactiva añade tiempo de reflexión entre peticiones."
    },
    {
      "question": "Si Z aumenta con N fijo, ¿qué tiende a pasar con X?",
      "answers": [
        "Baja o se modera",
        "Sube siempre",
        "Se hace infinito",
        "Se vuelve coste"
      ],
      "correct": 0,
      "explanation": "Más reflexión reduce la frecuencia con la que los usuarios envían peticiones."
    },
    {
      "question": "Si R aumenta con N fijo y Z fijo, ¿qué ocurre con X interactiva?",
      "answers": [
        "Aumenta siempre",
        "Disminuye",
        "No cambia nunca",
        "Se vuelve D"
      ],
      "correct": 1,
      "explanation": "En N = X(R+Z), si R+Z crece con N fijo, X baja."
    },
    {
      "question": "Si N=30, R=4 y Z=6, ¿cuánto vale X?",
      "answers": [
        "10",
        "7,5",
        "3",
        "36"
      ],
      "correct": 2,
      "explanation": "X = N/(R+Z) = 30/(4+6) = 3 interacciones por segundo."
    },
    {
      "question": "Si N=40, X=4 y R=3, ¿cuánto vale Z?",
      "answers": [
        "10",
        "1",
        "43",
        "7"
      ],
      "correct": 3,
      "explanation": "R+Z = N/X = 10; por tanto Z = 10 - 3 = 7."
    },
    {
      "question": "Si N=10 y Z=0, ¿qué carga representa?",
      "answers": [
        "Batch equivalente",
        "Abierta pura del modelo",
        "Retardo infinito",
        "SLA económico"
      ],
      "correct": 0,
      "explanation": "Con Z nulo, el comportamiento interactivo equivale a batch."
    },
    {
      "question": "¿Qué significa que una red sea mixta?",
      "answers": [
        "No tiene servidores",
        "Combina cargas abiertas y cerradas",
        "Solo tiene costes",
        "No tiene visitas en la red"
      ],
      "correct": 1,
      "explanation": "Una red mixta representa unas cargas como abiertas y otras como cerradas."
    },
    {
      "question": "¿Qué dato no fija una red cerrada?",
      "answers": [
        "Número de clientes",
        "Demandas de servicio",
        "Llegada externa X0",
        "Visitas a recursos"
      ],
      "correct": 2,
      "explanation": "En redes cerradas no existe una tasa externa X0 que entre desde fuera."
    },
    {
      "question": "¿Qué dato sí fija una red abierta?",
      "answers": [
        "Número total fijo N",
        "Tiempo de reflexión fijo",
        "Clientes constantes",
        "Tasa de llegada externa"
      ],
      "correct": 3,
      "explanation": "En una red abierta se especifica la llegada externa o productividad de entrada."
    },
    {
      "question": "¿Qué error sería modelar una web pública como cerrada?",
      "answers": [
        "Fijar clientes sin límite real",
        "Usar tasa externa del modelo",
        "Medir productividad",
        "Calcular respuesta"
      ],
      "correct": 0,
      "explanation": "Una web pública suele recibir llegadas externas variables, más propia de red abierta."
    },
    {
      "question": "¿Qué error sería modelar terminales como abierta pura?",
      "answers": [
        "Incluir tiempo de respuesta",
        "Perder el límite N",
        "Medir utilización",
        "Usar estaciones"
      ],
      "correct": 1,
      "explanation": "Los sistemas interactivos tienen población total limitada por terminales activos."
    },
    {
      "question": "¿Qué se estima en una red abierta simple?",
      "answers": [
        "Llegada desde N fijo",
        "Coste desde disponibilidad",
        "Rendimiento desde llegada conocida",
        "Z desde TCO del recurso"
      ],
      "correct": 2,
      "explanation": "Con la tasa de llegada dada, se calculan tiempos y demás prestaciones."
    },
    {
      "question": "¿Qué se estima en una red cerrada?",
      "answers": [
        "X0 desde coste",
        "SLA desde color",
        "TCO desde visitas",
        "X y R desde N"
      ],
      "correct": 3,
      "explanation": "En cerradas se conoce la población N y se estima la productividad y respuesta."
    },
    {
      "question": "¿Qué significa tiempo entre llegadas exponencial?",
      "answers": [
        "Llegadas sin memoria",
        "Llegadas fijas exactas",
        "Llegadas siempre nulas",
        "Llegadas por coste"
      ],
      "correct": 0,
      "explanation": "La hipótesis exponencial implica independencia respecto al instante anterior."
    },
    {
      "question": "¿Qué significa servicio exponencial?",
      "answers": [
        "Servicio siempre constante",
        "Resto de servicio sin memoria",
        "Servicio sin duración en la red",
        "Servicio solo económico"
      ],
      "correct": 1,
      "explanation": "El tiempo restante no depende de cuánto lleve ya en servicio."
    },
    {
      "question": "¿Qué algoritmo resuelve redes cerradas sencillas?",
      "answers": [
        "TCO",
        "SLA",
        "MVA",
        "NFU"
      ],
      "correct": 2,
      "explanation": "El análisis del valor medio se aplica a redes cerradas."
    },
    {
      "question": "¿Qué dato complica resolver cerradas frente a abiertas?",
      "answers": [
        "N nunca existe observada",
        "No hay demandas",
        "No hay recursos",
        "X no se conoce al inicio"
      ],
      "correct": 3,
      "explanation": "En cerradas hay que estimar la productividad del sistema."
    },
    {
      "question": "¿Qué detectan las medidas a posteriori?",
      "answers": [
        "Cuellos reales observados",
        "Costes futuros seguros",
        "Z de mercado",
        "Alfa óptimo del modelo"
      ],
      "correct": 0,
      "explanation": "La detección habitual de cuellos interpreta medidas tomadas del sistema."
    },
    {
      "question": "¿Qué señal apunta a cuello de CPU?",
      "answers": [
        "Disco sin uso",
        "CPU con U muy alta",
        "Z muy alto",
        "TCO bajo en la red"
      ],
      "correct": 1,
      "explanation": "Una utilización muy alta de CPU puede señalarla como recurso limitante."
    },
    {
      "question": "¿Qué señal apunta a cuello de E/S?",
      "answers": [
        "CPU sin carga",
        "Z nulo del recurso",
        "Disco con colas elevadas",
        "SLA escrito"
      ],
      "correct": 2,
      "explanation": "Colas y utilización altas en disco apuntan a cuello de E/S."
    },
    {
      "question": "¿Qué mejora es tuning?",
      "answers": [
        "Comprar disco nuevo",
        "Añadir memoria física",
        "Sustituir CPU observada",
        "Cambiar política del SO"
      ],
      "correct": 3,
      "explanation": "El tuning ajusta configuración u organización sin cambiar hardware principal."
    },
    {
      "question": "¿Qué mejora es upgrading?",
      "answers": [
        "Instalar CPU más rápida",
        "Cambiar prioridad de procesos",
        "Reordenar colas del SO",
        "Ajustar parámetros"
      ],
      "correct": 0,
      "explanation": "El upgrading implica actualización o reposición de hardware."
    },
    {
      "question": "¿Qué límite optimista interesa para X?",
      "answers": [
        "Inferior",
        "Superior",
        "Medio móvil",
        "Cualitativo"
      ],
      "correct": 1,
      "explanation": "La mejor productividad posible corresponde al límite superior."
    },
    {
      "question": "¿Qué límite optimista interesa para R?",
      "answers": [
        "Superior",
        "Externo",
        "Inferior",
        "Cíclico"
      ],
      "correct": 2,
      "explanation": "La mejor respuesta posible corresponde al menor tiempo de respuesta."
    },
    {
      "question": "¿Qué límite pesimista interesa para R?",
      "answers": [
        "Inferior",
        "Lineal",
        "Estacional",
        "Superior"
      ],
      "correct": 3,
      "explanation": "El peor tiempo de respuesta corresponde al límite superior."
    },
    {
      "question": "¿Qué pasa al superar el punto de saturación?",
      "answers": [
        "Aparecen colas",
        "Desaparecen trabajos",
        "Baja U a cero",
        "Se elimina D"
      ],
      "correct": 0,
      "explanation": "Al superar N* el cuello ya no puede procesar todo sin espera."
    },
    {
      "question": "¿Qué supuesto exige el análisis asintótico?",
      "answers": [
        "Costes sin límite",
        "Demandas independientes de N",
        "Clientes infinitos siempre",
        "SLA inexistente en la red"
      ],
      "correct": 1,
      "explanation": "Los límites suponen que la demanda no cambia por la concurrencia."
    },
    {
      "question": "Si una demanda cambia al aumentar N, ¿qué se debilita?",
      "answers": [
        "Existencia de CPU",
        "Medición de T del recurso",
        "Validez de límites",
        "Definición de C"
      ],
      "correct": 2,
      "explanation": "Los límites asintóticos dependen de demandas estables frente a la concurrencia."
    },
    {
      "question": "¿Qué gráfico ayuda a comparar configuraciones?",
      "answers": [
        "Colores del servidor",
        "Lista de usuarios",
        "Ruta del archivo",
        "Límites de X y R"
      ],
      "correct": 3,
      "explanation": "Los límites muestran rangos posibles de productividad y respuesta."
    },
    {
      "question": "¿Qué indica que R crece sin gran mejora en X?",
      "answers": [
        "Saturación cercana",
        "Capacidad infinita",
        "Retardo puro",
        "Coste menor"
      ],
      "correct": 0,
      "explanation": "Cuando X apenas sube y R crece, el sistema se aproxima al cuello."
    },
    {
      "question": "¿Qué se obtiene al resolver el modelo?",
      "answers": [
        "Coste legal exacto",
        "Índices de prestaciones",
        "Número de PDFs en la red",
        "Nombre del SLA"
      ],
      "correct": 1,
      "explanation": "Resolver el modelo permite estimar rendimiento, productividad y tiempos."
    },
    {
      "question": "¿Qué representa un cliente en espera?",
      "answers": [
        "Servidor atendiendo",
        "Coste de compra del recurso",
        "Trabajo aguardando recurso",
        "Variable de negocio"
      ],
      "correct": 2,
      "explanation": "La cola contiene clientes que esperan recibir servicio."
    },
    {
      "question": "¿Qué provoca aumentar visitas a un recurso lento?",
      "answers": [
        "Menor tiempo siempre",
        "Menor utilización",
        "Cero colas",
        "Mayor demanda total"
      ],
      "correct": 3,
      "explanation": "Más visitas a un recurso lento incrementan su demanda y riesgo de cuello."
    },
    {
      "question": "Si al aumentar N en una red cerrada X apenas crece y R aumenta mucho, ¿qué diagnóstico encaja mejor?",
      "answers": [
        "El sistema está cerca de saturación",
        "La red se ha vuelto abierta",
        "Z ha aumentado necesariamente",
        "No existe cuello de botella"
      ],
      "correct": 0,
      "explanation": "Cuando añadir clientes no aumenta casi la productividad pero sí la respuesta, el cuello limita el sistema."
    },
    {
      "question": "En una red abierta, si λ se aproxima a la capacidad del cuello, ¿qué comportamiento esperas?",
      "answers": [
        "R tiende siempre a cero",
        "R crece de forma acusada",
        "X se vuelve menor que cero",
        "U baja automáticamente"
      ],
      "correct": 1,
      "explanation": "Al acercarse a saturación, las colas crecen y el tiempo de respuesta se dispara."
    },
    {
      "question": "Si dos recursos tienen la misma U, ¿cuál es más peligroso como cuello futuro?",
      "answers": [
        "El de menor nombre",
        "El de menor coste",
        "El de mayor demanda D",
        "El de menor número de letras"
      ],
      "correct": 2,
      "explanation": "La demanda de servicio indica cuánto limita el recurso por interacción; U actual no basta para decidir."
    },
    {
      "question": "Si un recurso reduce su S a la mitad y X no cambia, ¿qué ocurre con U?",
      "answers": [
        "Se duplica",
        "No cambia",
        "Se hace negativa",
        "Se reduce a la mitad"
      ],
      "correct": 3,
      "explanation": "Como U = X * S, al reducir S a la mitad también se reduce U a la mitad."
    },
    {
      "question": "Si en una estación C=0 pero B>0 durante T, ¿qué indica la medida?",
      "answers": [
        "No se puede deducir S con B/C",
        "S vale exactamente cero",
        "X es infinito",
        "No hubo ocupación"
      ],
      "correct": 0,
      "explanation": "S = B/C no puede calcularse si no hubo completaciones."
    },
    {
      "question": "Si A es mucho mayor que C en el intervalo observado, ¿qué problema tiene asumir equilibrio?",
      "answers": [
        "La red es cerrada perfecta",
        "El sistema acumula trabajo",
        "No hay llegadas reales",
        "La cola no puede crecer"
      ],
      "correct": 1,
      "explanation": "El equilibrio exige que entradas y salidas se compensen; si no, hay acumulación."
    },
    {
      "question": "En una red cerrada, ¿por qué no se fija una λ externa?",
      "answers": [
        "No existen estaciones",
        "No puede haber CPU",
        "Los clientes no entran desde fuera",
        "S siempre vale cero"
      ],
      "correct": 2,
      "explanation": "La población circula dentro del sistema; no hay una corriente externa de llegadas."
    },
    {
      "question": "Si una carga interactiva tiene N alto pero Z también alto, ¿qué evita Z?",
      "answers": [
        "Que exista tiempo de respuesta",
        "Que haya estaciones de retardo",
        "Que se calcule productividad",
        "Que todos pidan servicio a la vez"
      ],
      "correct": 3,
      "explanation": "El tiempo de reflexión separa las peticiones y reduce presión sobre el subsistema central."
    },
    {
      "question": "Si un usuario interactivo está en periodo de reflexión, ¿dónde está respecto al subsistema central?",
      "answers": [
        "Fuera del subsistema central",
        "Siempre en la CPU",
        "Siempre en el disco",
        "En la cola del cuello"
      ],
      "correct": 0,
      "explanation": "Durante Z el subsistema central no trabaja para ese usuario."
    },
    {
      "question": "Si N=50, Z=5 y X=5, ¿cuánto vale R?",
      "answers": [
        "10",
        "5",
        "45",
        "55"
      ],
      "correct": 1,
      "explanation": "R = N/X - Z = 50/5 - 5 = 5 segundos."
    },
    {
      "question": "Si R=3, Z=7 y X=4, ¿cuántos usuarios N hay?",
      "answers": [
        "10",
        "28",
        "40",
        "14"
      ],
      "correct": 2,
      "explanation": "N = X(R+Z) = 4*(3+7) = 40 usuarios."
    },
    {
      "question": "Si un recurso tiene Vk=8 y Sk=0,02, ¿cuál es Dk?",
      "answers": [
        "8,02",
        "400",
        "0,0025",
        "0,16"
      ],
      "correct": 3,
      "explanation": "Dk = Vk * Sk = 8 * 0,02 = 0,16 segundos."
    },
    {
      "question": "Si Dmax=0,25 s, ¿cuál es la cota aproximada de X máxima por el cuello?",
      "answers": [
        "4 trabajos/s",
        "0,25 trabajos/s",
        "25 trabajos/s",
        "1 trabajo/s"
      ],
      "correct": 0,
      "explanation": "La productividad máxima queda acotada por 1/Dmax = 1/0,25 = 4 trabajos/s."
    },
    {
      "question": "Si Dtotal=1 s y N=3 en batch sin colas ideal, ¿qué límite de R tiene sentido?",
      "answers": [
        "Exactamente 0 s",
        "Al menos 1 s",
        "Menos que cualquier D",
        "Siempre infinito"
      ],
      "correct": 1,
      "explanation": "El tiempo de respuesta no puede ser menor que la suma de demandas sin esperas."
    },
    {
      "question": "¿Qué recurso conviene optimizar primero para elevar X máxima?",
      "answers": [
        "El de menor Vk",
        "El de menor Sk siempre",
        "El de mayor Dk",
        "El de menor utilización histórica"
      ],
      "correct": 2,
      "explanation": "La productividad máxima está limitada por el recurso con mayor demanda."
    },
    {
      "question": "Si reduces una demanda que no es la máxima, ¿qué puede pasar con X máxima?",
      "answers": [
        "Mejora siempre igual",
        "Se duplica seguro",
        "Se vuelve infinita",
        "Puede no mejorar"
      ],
      "correct": 3,
      "explanation": "Si el cuello sigue siendo otro recurso, la productividad máxima puede no cambiar."
    },
    {
      "question": "¿Qué diferencia hay entre servidor lento y recurso cuello?",
      "answers": [
        "El cuello depende de demanda total",
        "Todo servidor lento es cuello",
        "El cuello no recibe visitas",
        "La lentitud no importa nunca"
      ],
      "correct": 0,
      "explanation": "Un recurso lento solo limita si su demanda total lo hace dominante."
    },
    {
      "question": "Si una estación de retardo tiene muchos clientes, ¿por qué no genera cola?",
      "answers": [
        "Los clientes desaparecen",
        "Hay servidores infinitos modelados",
        "S vale siempre cero",
        "No existe tiempo de residencia"
      ],
      "correct": 1,
      "explanation": "El modelo de retardo asigna un servidor a cada cliente, por eso no espera."
    },
    {
      "question": "¿Qué error conceptual hay en confundir tasa de llegada y productividad?",
      "answers": [
        "Siempre son opuestas",
        "Una mide coste",
        "Solo coinciden en equilibrio",
        "Nunca tienen unidades"
      ],
      "correct": 2,
      "explanation": "λ y X pueden igualarse bajo flujo equilibrado, pero conceptualmente no son lo mismo."
    },
    {
      "question": "Si X del sistema sube, ¿qué pasa necesariamente con Xi de un recurso visitado Vk veces?",
      "answers": [
        "Baja siempre",
        "Se hace cero",
        "Depende solo de Z",
        "Sube proporcionalmente a Vk"
      ],
      "correct": 3,
      "explanation": "Por flujo forzado, la productividad del recurso depende de las visitas y del flujo global."
    },
    {
      "question": "Si una interacción visita dos veces el disco, ¿cómo afecta a la demanda del disco?",
      "answers": [
        "Duplica el servicio acumulado",
        "Elimina la cola",
        "Reduce S a cero",
        "No afecta a D"
      ],
      "correct": 0,
      "explanation": "Más visitas multiplican el tiempo total que se exige al recurso."
    },
    {
      "question": "¿Qué conclusión es más fuerte si CPU y disco están ambos al 95%?",
      "answers": [
        "Solo CPU es cuello",
        "Puede ser sobrecarga general",
        "Solo disco es cuello",
        "No hay saturación"
      ],
      "correct": 1,
      "explanation": "Si varios recursos están muy cargados, puede no haber un único cuello claro."
    },
    {
      "question": "Si una mejora de CPU no cambia R, ¿qué hipótesis gana fuerza?",
      "answers": [
        "CPU era el único cuello",
        "No había E/S",
        "El cuello estaba en otro recurso",
        "N era cero"
      ],
      "correct": 2,
      "explanation": "Si mejorar un recurso no mejora respuesta, probablemente no era el limitante principal."
    },
    {
      "question": "Si al mejorar disco baja R y sube X, ¿qué sugiere?",
      "answers": [
        "Z era demasiado alto",
        "La red era abierta imposible",
        "No existían colas",
        "Disco era cuello relevante"
      ],
      "correct": 3,
      "explanation": "Mejorar el recurso limitante debe reducir esperas y permitir más flujo."
    },
    {
      "question": "¿Qué significa que el análisis asintótico sea preliminar?",
      "answers": [
        "Da cotas, no detalle exacto",
        "Sustituye toda medición",
        "Evita modelar demandas",
        "Solo sirve para costes"
      ],
      "correct": 0,
      "explanation": "Los límites orientan rápidamente, pero no reemplazan un análisis detallado."
    },
    {
      "question": "¿Qué trampa hay en usar solo utilización para decidir upgrades?",
      "answers": [
        "Siempre identifica el cuello",
        "No muestra demanda futura",
        "No se puede medir",
        "Es una variable económica"
      ],
      "correct": 1,
      "explanation": "Una U actual alta ayuda, pero la planificación debe mirar demandas y crecimiento."
    },
    {
      "question": "Si una estación tiene U baja pero D alta en una carga que crecerá, ¿qué conviene vigilar?",
      "answers": [
        "No puede saturarse",
        "Debe eliminarse",
        "Puede ser cuello futuro",
        "No recibe trabajos"
      ],
      "correct": 2,
      "explanation": "Con más carga, una demanda alta puede convertirla en limitante aunque hoy no lo sea."
    },
    {
      "question": "¿Qué ocurre si todos los trabajos no son homogéneos como asume el modelo?",
      "answers": [
        "El modelo mejora solo",
        "Little deja de existir",
        "X se vuelve coste",
        "El modelo pierde precisión"
      ],
      "correct": 3,
      "explanation": "La hipótesis de trabajos similares simplifica; si no se cumple, el modelo aproxima peor."
    },
    {
      "question": "Si un sistema mezcla batch y transacciones web, ¿qué modelo encaja?",
      "answers": [
        "Red mixta",
        "Solo cerrada",
        "Solo retardo",
        "Solo batch"
      ],
      "correct": 0,
      "explanation": "Batch es cerrado y transacciones son abiertas, por lo que encaja una red mixta."
    },
    {
      "question": "¿Qué significa que un modelo cerrado no tenga salidas externas reales?",
      "answers": [
        "No se completan nunca",
        "Los trabajos recirculan",
        "No hay productividad",
        "No hay respuesta"
      ],
      "correct": 1,
      "explanation": "Los trabajos completan ciclos y vuelven a entrar conceptualmente."
    },
    {
      "question": "Si en batch N aumenta por debajo de N*, ¿qué suele dominar R?",
      "answers": [
        "Coste del SLA",
        "Predicción cualitativa",
        "Demandas sin colas",
        "Alfa de suavizado"
      ],
      "correct": 2,
      "explanation": "Antes de saturar, el tiempo se aproxima al servicio requerido sin esperas importantes."
    },
    {
      "question": "Si N supera mucho N*, ¿qué domina R?",
      "answers": [
        "Tiempo de reflexión",
        "Coste de compra",
        "Media móvil",
        "Esperas en el cuello"
      ],
      "correct": 3,
      "explanation": "Tras saturación, las colas del recurso limitante dominan el tiempo de respuesta."
    },
    {
      "question": "Si el cuello tiene D=0,5, ¿cuál es el máximo flujo ideal?",
      "answers": [
        "2 trabajos/s",
        "0,5 trabajos/s",
        "5 trabajos/s",
        "50 trabajos/s"
      ],
      "correct": 0,
      "explanation": "El flujo máximo ideal por cuello es aproximadamente 1/D = 2."
    },
    {
      "question": "¿Qué indica que el límite superior de X sea plano?",
      "answers": [
        "No hay demanda",
        "Hay cuello que fija máximo",
        "Z es infinito",
        "No hay recursos"
      ],
      "correct": 1,
      "explanation": "La meseta de productividad indica capacidad máxima limitada por el cuello."
    },
    {
      "question": "¿Qué indica que el límite inferior de R crezca con N?",
      "answers": [
        "Baja la demanda",
        "No hay clientes",
        "Aumenta el trabajo total",
        "X es negativo"
      ],
      "correct": 2,
      "explanation": "Con más clientes, incluso las cotas de respuesta pueden crecer por reparto de capacidad."
    },
    {
      "question": "¿Cuál es la trampa en 'más servidores siempre mejora'?",
      "answers": [
        "Siempre duplica X",
        "Siempre reduce Dtotal",
        "Nunca afecta R",
        "Solo mejora si toca el cuello"
      ],
      "correct": 3,
      "explanation": "Añadir capacidad a un recurso no limitante puede no mejorar el rendimiento global."
    },
    {
      "question": "Si CPU es cuello, ¿qué opción no ataca directamente el cuello?",
      "answers": [
        "Mejorar solo el disco",
        "CPU más rápida",
        "Reducir servicio CPU",
        "Mover trabajo de CPU"
      ],
      "correct": 0,
      "explanation": "Mejorar un recurso que no limita no resuelve directamente el cuello."
    },
    {
      "question": "Si un sistema tiene muchos usuarios pensando, ¿por qué X puede ser bajo?",
      "answers": [
        "CPU siempre falla",
        "Z reduce demanda activa",
        "Disco siempre satura",
        "Little no aplica"
      ],
      "correct": 1,
      "explanation": "El tiempo de reflexión baja la frecuencia de peticiones al sistema."
    },
    {
      "question": "¿Qué dato necesitas para pasar de Xi a Ui?",
      "answers": [
        "Z del usuario",
        "TCO total",
        "Si del recurso",
        "SLA escrito"
      ],
      "correct": 2,
      "explanation": "La utilización del recurso se calcula como Ui = Xi * Si."
    },
    {
      "question": "¿Qué dato necesitas para pasar de X global a Xi?",
      "answers": [
        "B del intervalo",
        "Coste anual",
        "Nivel de gestión",
        "Vk del recurso"
      ],
      "correct": 3,
      "explanation": "Por flujo forzado, Xi depende del número de visitas Vk."
    }
  ],
  "Tema 6": [
    {
      "question": "¿Qué busca la planificación de capacidad?",
      "answers": [
        "Eliminar la medición del sistema",
        "Aumentar colas deliberadamente",
        "Preparar recursos para carga futura",
        "Ignorar los SLA pactados del sistema"
      ],
      "correct": 2,
      "explanation": "Planificar capacidad consiste en dimensionar recursos para cargas futuras."
    },
    {
      "question": "¿Cómo define el tema la capacidad?",
      "answers": [
        "Número de usuarios satisfechos",
        "Coste mínimo de compra de capacidad",
        "Tiempo medio de reflexión",
        "Productividad máxima del sistema"
      ],
      "correct": 3,
      "explanation": "La capacidad se entiende como la productividad máxima que puede ofrecer el sistema."
    },
    {
      "question": "¿Qué se intenta anticipar con la planificación?",
      "answers": [
        "La futura saturación del sistema",
        "La desaparición de usuarios",
        "La ausencia total de carga",
        "La eliminación de costes en la planificación"
      ],
      "correct": 0,
      "explanation": "La planificación predice cuándo la carga futura puede saturar el sistema."
    },
    {
      "question": "¿Qué fase va antes de monitorizar?",
      "answers": [
        "Seleccionar alternativa final",
        "Dotar de instrumentación",
        "Facturar bajo demanda",
        "Aplicar media móvil"
      ],
      "correct": 1,
      "explanation": "Primero hay que instrumentar el sistema para poder medirlo."
    },
    {
      "question": "¿Qué se hace al caracterizar la carga?",
      "answers": [
        "Cambiar toda la arquitectura",
        "Eliminar variables históricas",
        "Describir patrones de uso",
        "Fijar siempre alfa a 1"
      ],
      "correct": 2,
      "explanation": "Caracterizar la carga significa entender cómo se usa el sistema."
    },
    {
      "question": "¿Qué alternativa se selecciona al final?",
      "answers": [
        "La más cara disponible",
        "La que no cumple SLA del proceso",
        "La primera sin comparar",
        "Mejor coste y/o rendimiento"
      ],
      "correct": 3,
      "explanation": "El proceso compara opciones y escoge la mejor según coste y prestaciones."
    },
    {
      "question": "¿De qué depende la capacidad adecuada?",
      "answers": [
        "SLA, arquitectura y coste",
        "Solo de la CPU del sistema",
        "Solo del número de PDFs",
        "Solo de la regresión"
      ],
      "correct": 0,
      "explanation": "La capacidad adecuada combina servicio, tecnología y restricciones económicas."
    },
    {
      "question": "¿Qué fija un SLA?",
      "answers": [
        "El algoritmo MVA del proceso",
        "Umbrales de servicio pactados",
        "La tasa de visita",
        "El valor de Z de capacidad"
      ],
      "correct": 1,
      "explanation": "Los SLA fijan umbrales de productividad, rendimiento y disponibilidad."
    },
    {
      "question": "¿Qué métrica puede aparecer en un SLA?",
      "answers": [
        "Color de la interfaz",
        "Número de preguntas",
        "Tiempo de respuesta máximo",
        "Ruta del archivo en la planificación"
      ],
      "correct": 2,
      "explanation": "Los SLA pueden incluir límites de respuesta aceptables para los usuarios."
    },
    {
      "question": "¿Qué es el TCO?",
      "answers": [
        "Tiempo calculado operativo",
        "Tasa central observada",
        "Tipo cerrado operacional",
        "Coste total de propiedad"
      ],
      "correct": 3,
      "explanation": "El TCO incluye costes de arranque y operación durante un periodo."
    },
    {
      "question": "¿Qué coste es de arranque?",
      "answers": [
        "Compra e instalación",
        "Consumo diario",
        "Mantenimiento mensual",
        "Monitorización continua"
      ],
      "correct": 0,
      "explanation": "La compra e instalación forman parte de los costes iniciales."
    },
    {
      "question": "¿Qué coste es de operación?",
      "answers": [
        "Compra inicial del proceso",
        "Mantenimiento del sistema",
        "Instalación física",
        "Diseño del SLA"
      ],
      "correct": 1,
      "explanation": "El mantenimiento aparece durante la explotación del sistema."
    },
    {
      "question": "¿Qué condiciona la arquitectura elegida?",
      "answers": [
        "Solo la nota del examen del sistema",
        "Solo el tamaño del aula",
        "Aplicación, experiencia y administración",
        "Solo el valor de alfa del sistema"
      ],
      "correct": 2,
      "explanation": "La arquitectura depende de requisitos técnicos y factores operativos."
    },
    {
      "question": "¿Qué método usa datos históricos?",
      "answers": [
        "Cualitativo",
        "Tuning de capacidad",
        "Upgrading",
        "Cuantitativo"
      ],
      "correct": 3,
      "explanation": "Los métodos cuantitativos se apoyan en series y datos históricos."
    },
    {
      "question": "¿Qué método usa juicio experto?",
      "answers": [
        "Cualitativo",
        "Cuantitativo",
        "MVA",
        "Little"
      ],
      "correct": 0,
      "explanation": "Los métodos cualitativos se basan en análisis subjetivo, expertos y contexto."
    },
    {
      "question": "¿Qué patrón favorece regresión lineal?",
      "answers": [
        "Ruido sin tendencia",
        "Tendencia lineal",
        "Cola infinita",
        "SLA incumplido"
      ],
      "correct": 1,
      "explanation": "La regresión lineal simple se aplica cuando hay tendencia aproximadamente lineal."
    },
    {
      "question": "¿Qué predice una regresión?",
      "answers": [
        "Variable independiente",
        "Tiempo de reflexión fijo",
        "Variable dependiente",
        "Utilización adimensional"
      ],
      "correct": 2,
      "explanation": "La variable dependiente es la que se estima en el modelo."
    },
    {
      "question": "¿Qué papel tiene una variable independiente?",
      "answers": [
        "Es siempre el resultado final",
        "Mide coste total del proceso",
        "Es un servidor físico con datos",
        "Ayuda a explicar la dependiente"
      ],
      "correct": 3,
      "explanation": "Las independientes se usan como entradas para predecir otra variable."
    },
    {
      "question": "¿Cuándo convienen medias móviles?",
      "answers": [
        "Datos casi estacionarios",
        "Tendencia lineal fuerte",
        "Sin datos históricos del sistema",
        "Solo opiniones expertas"
      ],
      "correct": 0,
      "explanation": "Las medias móviles funcionan bien con series casi estacionarias."
    },
    {
      "question": "¿Qué predicen las medias móviles?",
      "answers": [
        "Máximo coste posible",
        "Media de observaciones previas",
        "Número de terminales",
        "Demanda del cuello de capacidad"
      ],
      "correct": 1,
      "explanation": "La predicción se basa en promediar valores recientes."
    },
    {
      "question": "¿Para qué horizonte son útiles medias móviles?",
      "answers": [
        "Décadas sin datos",
        "Solo tiempo real",
        "Corto plazo",
        "Nunca se usan"
      ],
      "correct": 2,
      "explanation": "Son técnicas simples adecuadas para previsiones de corto plazo."
    },
    {
      "question": "¿Qué parámetro se ajusta en medias móviles?",
      "answers": [
        "N de terminales",
        "Z de reflexión del servicio",
        "B de ocupación",
        "n de observaciones"
      ],
      "correct": 3,
      "explanation": "Se prueba el tamaño de ventana n para reducir el error."
    },
    {
      "question": "¿Qué mide el error cuadrático medio?",
      "answers": [
        "Calidad de predicción",
        "Uso de CPU directo con datos",
        "Disponibilidad legal",
        "Número de servidores"
      ],
      "correct": 0,
      "explanation": "Sirve para comparar errores de predicción al ajustar modelos."
    },
    {
      "question": "¿Cuándo conviene suavizado exponencial?",
      "answers": [
        "Con crecimiento lineal claro",
        "Sin tendencia sistemática",
        "Sin observaciones",
        "Con población fija"
      ],
      "correct": 1,
      "explanation": "El suavizado simple se usa con datos no estacionales y sin tendencia marcada."
    },
    {
      "question": "¿Qué observaciones pesan más en suavizado?",
      "answers": [
        "Las más antiguas",
        "Las inexistentes",
        "Las recientes",
        "Las más largas"
      ],
      "correct": 2,
      "explanation": "El suavizado exponencial da más peso a los datos recientes."
    },
    {
      "question": "¿Qué rango de alfa se cita?",
      "answers": [
        "1 a 10 de capacidad",
        "10 a 30",
        "Siempre 0",
        "0,05 a 0,30"
      ],
      "correct": 3,
      "explanation": "El resumen indica que alfa suele estar entre 0,05 y 0,30."
    },
    {
      "question": "¿Qué es una NFU?",
      "answers": [
        "Variable de negocio ligada a recursos",
        "Recurso con infinitos servidores",
        "Ley de colas cerradas",
        "Coste de instalación en la planificación"
      ],
      "correct": 0,
      "explanation": "Una NFU traduce actividad de negocio en demanda técnica."
    },
    {
      "question": "¿Qué ejemplo encaja con NFU?",
      "answers": [
        "Color del servidor del servicio",
        "Número de empleados en nómina",
        "Letra de la respuesta",
        "Número de temas PDF"
      ],
      "correct": 1,
      "explanation": "El número de empleados puede anticipar uso de una aplicación de nómina."
    },
    {
      "question": "¿Qué hace capacidad bajo demanda?",
      "answers": [
        "Impide compartir recursos del sistema",
        "Elimina los SLA con datos",
        "Asigna recursos automáticamente",
        "Evita medir en tiempo real"
      ],
      "correct": 2,
      "explanation": "La capacidad bajo demanda ajusta recursos para cumplir el nivel de servicio."
    },
    {
      "question": "¿En qué se apoya capacidad bajo demanda?",
      "answers": [
        "Solo intuición humana",
        "Datos borrados del proceso",
        "Colas eliminadas",
        "Medidas en tiempo real"
      ],
      "correct": 3,
      "explanation": "Necesita análisis y predicción a partir de medidas actuales."
    },
    {
      "question": "¿Qué beneficio aporta bajo demanda?",
      "answers": [
        "Pago según consumo",
        "Compra máxima fija",
        "Sin monitorización",
        "Sin acuerdos SLA"
      ],
      "correct": 0,
      "explanation": "Permite facturar hardware y software según el consumo real."
    },
    {
      "question": "¿Qué favorece la externalización?",
      "answers": [
        "Ausencia de contratos",
        "SLA garantizados por proveedor",
        "Datos sin medir del proceso",
        "Costes ocultos de capacidad"
      ],
      "correct": 1,
      "explanation": "Si se garantizan los SLA, los sistemas pueden estar gestionados externamente."
    },
    {
      "question": "¿Qué ahorra la automatización bajo demanda?",
      "answers": [
        "Todos los costes posibles",
        "La necesidad de SLA",
        "Trabajo manual de gestión",
        "La caracterización de carga"
      ],
      "correct": 2,
      "explanation": "La automatización reduce tareas manuales de asignación y ajuste."
    },
    {
      "question": "¿Qué significa gestionar recursos compartidos?",
      "answers": [
        "Dedicarlos fijos siempre",
        "No medir su uso del servicio",
        "Bloquearlos por usuario",
        "Asignarlos según necesidad"
      ],
      "correct": 3,
      "explanation": "La capacidad bajo demanda permite repartir recursos entre cargas cambiantes."
    },
    {
      "question": "¿Qué factor importa al elegir herramienta?",
      "answers": [
        "Tiempo de anticipación al umbral",
        "Longitud de respuestas",
        "Número de colores del servicio",
        "Nombre del PDF con datos"
      ],
      "correct": 0,
      "explanation": "Importa saber con cuánto margen se quiere detectar que una métrica alcanzará su límite."
    },
    {
      "question": "¿Qué se valida antes de predecir?",
      "answers": [
        "El color de la gráfica",
        "La técnica cuantitativa elegida",
        "El número de letras del proceso",
        "El orden de opciones"
      ],
      "correct": 1,
      "explanation": "Se valida el modelo con datos disponibles antes de confiar en sus predicciones."
    },
    {
      "question": "¿Cómo se valida una técnica?",
      "answers": [
        "Eliminando las mediciones",
        "Forzando alfa a cero del sistema",
        "Probando con datos históricos",
        "Usando solo el presupuesto"
      ],
      "correct": 2,
      "explanation": "Se reservan datos históricos para comprobar el error de la técnica."
    },
    {
      "question": "¿Qué patrón es estacionario?",
      "answers": [
        "Crecimiento lineal seguro",
        "Picos por temporada fija",
        "Coste siempre creciente",
        "Media y varianza estables"
      ],
      "correct": 3,
      "explanation": "Una serie estacionaria no presenta cambios sistemáticos en media ni varianza."
    },
    {
      "question": "¿Qué patrón es estacional?",
      "answers": [
        "Se repite por periodos",
        "No cambia nunca",
        "Crece siempre lineal",
        "No tiene datos en la planificación"
      ],
      "correct": 0,
      "explanation": "La estacionalidad aparece cuando hay variaciones periódicas reconocibles."
    },
    {
      "question": "¿Qué patrón muestra tendencia?",
      "answers": [
        "Ruido sin dirección",
        "Cambio sostenido en el nivel",
        "Media constante perfecta",
        "Ausencia de datos del servicio"
      ],
      "correct": 1,
      "explanation": "Una tendencia indica evolución creciente o decreciente sostenida."
    },
    {
      "question": "¿Qué limita una organización?",
      "answers": [
        "Ley de Little con datos",
        "Existencia de colas",
        "Presupuesto disponible",
        "Número de PDFs"
      ],
      "correct": 2,
      "explanation": "Las restricciones económicas limitan la capacidad que puede adquirirse o mantenerse."
    },
    {
      "question": "¿Cuándo hay capacidad adecuada?",
      "answers": [
        "CPU siempre al 100% del proceso",
        "Sin datos históricos",
        "Sin arquitectura definida",
        "SLA cumplidos con coste pactado"
      ],
      "correct": 3,
      "explanation": "La capacidad es adecuada si cumple servicio, tecnología y límites económicos."
    },
    {
      "question": "¿Qué monitoriza el proceso?",
      "answers": [
        "Utilización del sistema",
        "Solo el precio inicial",
        "Solo opiniones expertas",
        "Solo rutas de archivo"
      ],
      "correct": 0,
      "explanation": "Monitorizar utilización permite saber cómo se están usando los recursos."
    },
    {
      "question": "¿Qué se predice bajo alternativas?",
      "answers": [
        "Color de interfaz",
        "Rendimiento esperado",
        "Texto del SLA de capacidad",
        "Orden alfabético"
      ],
      "correct": 1,
      "explanation": "Se evalúa cómo rendiría el sistema con diferentes configuraciones."
    },
    {
      "question": "¿Qué evita planificar tarde?",
      "answers": [
        "Tener datos históricos",
        "Comparar alternativas",
        "Actuar después de saturar",
        "Medir utilización en la planificación"
      ],
      "correct": 2,
      "explanation": "La planificación anticipada busca actuar antes de que la saturación ya sea un problema."
    },
    {
      "question": "Si una métrica se acerca al umbral SLA, ¿qué toca hacer?",
      "answers": [
        "Ignorar la señal con datos",
        "Planificar una acción",
        "Borrar el histórico",
        "Reducir medición"
      ],
      "correct": 1,
      "explanation": "Los umbrales existen para actuar antes de incumplir el servicio."
    },
    {
      "question": "¿Qué pregunta responde la planificación de capacidad?",
      "answers": [
        "Qué opción es más larga",
        "Qué archivo pesa menos",
        "Cuándo y cómo ampliar recursos",
        "Qué color usar del servicio"
      ],
      "correct": 2,
      "explanation": "Busca anticipar saturación y decidir cómo retrasarla o evitarla."
    },
    {
      "question": "¿Qué pasa si se dimensiona solo con la carga actual?",
      "answers": [
        "Siempre sobra capacidad",
        "Nunca hay coste del proceso",
        "No hacen falta SLA",
        "Puede fallar ante carga futura"
      ],
      "correct": 3,
      "explanation": "La planificación debe considerar cargas futuras proyectadas, no solo el presente."
    },
    {
      "question": "¿Qué fase convierte negocio en carga técnica?",
      "answers": [
        "Caracterización de carga",
        "Compra directa",
        "Borrado de datos",
        "Diseño visual del sistema"
      ],
      "correct": 0,
      "explanation": "Caracterizar carga traduce el uso del sistema a patrones medibles."
    },
    {
      "question": "¿Qué fase compara configuraciones candidatas?",
      "answers": [
        "Instrumentación inicial",
        "Predicción de rendimiento",
        "Definición de letra",
        "Lectura de PDF con datos"
      ],
      "correct": 1,
      "explanation": "Se predice cómo rendirá cada alternativa antes de elegir."
    },
    {
      "question": "¿Qué significa mejor coste/rendimiento?",
      "answers": [
        "Comprar lo máximo siempre",
        "Evitar medir rendimiento",
        "Compromiso entre precio y servicio",
        "Elegir al azar del servicio"
      ],
      "correct": 2,
      "explanation": "La mejor alternativa no siempre es la más potente, sino la más conveniente."
    },
    {
      "question": "¿Qué riesgo hay si no se instrumenta?",
      "answers": [
        "Sobra toda capacidad",
        "El SLA mejora solo del proceso",
        "La carga desaparece",
        "No hay medidas fiables"
      ],
      "correct": 3,
      "explanation": "Sin instrumentación no se puede monitorizar ni validar el estado del sistema."
    },
    {
      "question": "¿Qué indica monitorizar utilización?",
      "answers": [
        "Qué recursos están cargados",
        "Qué usuarios aprueban",
        "Qué opción es correcta",
        "Qué PDF es mayor del sistema"
      ],
      "correct": 0,
      "explanation": "La utilización revela qué recursos consumen capacidad y cuánto margen queda."
    },
    {
      "question": "¿Qué incluye una alternativa de capacidad?",
      "answers": [
        "Solo el texto del SLA",
        "Configuración de recursos",
        "Solo el histórico bruto",
        "Solo el color de UI con datos"
      ],
      "correct": 1,
      "explanation": "Las alternativas suelen ser configuraciones hardware/software posibles."
    },
    {
      "question": "¿Qué factor limita aunque el rendimiento sea bueno?",
      "answers": [
        "Ley de Little",
        "Número de temas",
        "Presupuesto disponible",
        "Valor de Z del servicio"
      ],
      "correct": 2,
      "explanation": "Las limitaciones económicas pueden impedir elegir la opción más potente."
    },
    {
      "question": "¿Qué significa cumplir SLA continuamente?",
      "answers": [
        "Cumplir solo al inicio",
        "Medir una vez al año del proceso",
        "Comprar siempre nuevo",
        "No superar umbrales pactados"
      ],
      "correct": 3,
      "explanation": "La capacidad adecuada exige mantener el servicio dentro de umbrales pactados."
    },
    {
      "question": "¿Qué diferencia SLA de QoS?",
      "answers": [
        "SLA concreta umbrales pactados",
        "QoS es siempre coste",
        "SLA es una fórmula MVA",
        "QoS es una cola del sistema"
      ],
      "correct": 0,
      "explanation": "El SLA formaliza objetivos de calidad de servicio en umbrales exigibles."
    },
    {
      "question": "¿Qué factor de SLA depende del usuario remoto?",
      "answers": [
        "Coste de instalación",
        "Tiempo máximo tolerable",
        "Tasa de visita con datos",
        "Alfa de suavizado"
      ],
      "correct": 1,
      "explanation": "Los usuarios remotos pueden desconectarse si la respuesta supera cierto límite."
    },
    {
      "question": "¿Qué factor de SLA mide percepción?",
      "answers": [
        "Número de CPUs del servicio",
        "Tamaño del PDF",
        "Satisfacción de uso",
        "Tipo de variable"
      ],
      "correct": 2,
      "explanation": "La satisfacción del usuario forma parte de los factores considerados en el acuerdo."
    },
    {
      "question": "¿Por qué la arquitectura no se elige solo por benchmarks?",
      "answers": [
        "Los benchmarks no existen",
        "El coste no influye",
        "El SLA se ignora del proceso",
        "También importa administración"
      ],
      "correct": 3,
      "explanation": "Facilidad de administración, experiencia y requisitos también condicionan la elección."
    },
    {
      "question": "¿Qué significa madurez en explotación?",
      "answers": [
        "Experiencia usando esa tecnología",
        "Número de opciones del sistema",
        "Valor de utilización",
        "Tiempo de servicio"
      ],
      "correct": 0,
      "explanation": "La experiencia de operación puede influir en la arquitectura seleccionada."
    },
    {
      "question": "¿Qué coste aparece después del arranque?",
      "answers": [
        "Compra inicial",
        "Consumo energético",
        "Instalación inicial",
        "Adquisición base"
      ],
      "correct": 1,
      "explanation": "El consumo energético pertenece a la operación del sistema."
    },
    {
      "question": "¿Qué coste pertenece al arranque?",
      "answers": [
        "Mantenimiento",
        "Electricidad diaria",
        "Instalación",
        "Soporte recurrente"
      ],
      "correct": 2,
      "explanation": "La instalación es un coste inicial de puesta en marcha."
    },
    {
      "question": "¿Por qué usar TCO en vez de precio?",
      "answers": [
        "Ignora mantenimiento",
        "Evita comparar",
        "Elimina SLA del proceso",
        "Incluye vida operativa"
      ],
      "correct": 3,
      "explanation": "El coste total refleja tanto inicio como explotación durante un periodo."
    },
    {
      "question": "¿Qué herramienta conviene si se necesita anticipación temprana?",
      "answers": [
        "Una con predicción suficiente",
        "Una sin históricos del sistema",
        "Una sin integración",
        "Una manual sin datos"
      ],
      "correct": 0,
      "explanation": "El tiempo de anticipación requerido condiciona la herramienta de planificación."
    },
    {
      "question": "¿Qué importa del sistema operativo al elegir herramienta?",
      "answers": [
        "Color del escritorio",
        "Compatibilidad e integración",
        "Número de preguntas",
        "Nombre del tema con datos"
      ],
      "correct": 1,
      "explanation": "La herramienta debe encajar con el entorno tecnológico existente."
    },
    {
      "question": "¿Qué implica gestión automática de capacidad?",
      "answers": [
        "Sin medidas de rendimiento",
        "Sin políticas de servicio",
        "Decisiones con menos intervención",
        "Sin datos históricos del servicio"
      ],
      "correct": 2,
      "explanation": "La automatización reduce trabajo manual y puede reaccionar antes."
    },
    {
      "question": "¿Qué técnica usarías con datos lineales?",
      "answers": [
        "Media móvil simple",
        "Opinión experta sola",
        "Upgrading",
        "Regresión lineal"
      ],
      "correct": 3,
      "explanation": "La regresión lineal encaja con tendencia aproximadamente lineal."
    },
    {
      "question": "¿Qué técnica usarías con serie estable?",
      "answers": [
        "Media móvil",
        "Regresión forzada",
        "MVA cerrado",
        "Tuning"
      ],
      "correct": 0,
      "explanation": "Una serie casi estacionaria es buena candidata para medias móviles."
    },
    {
      "question": "¿Qué técnica usarías sin tendencia clara?",
      "answers": [
        "Regresión lineal simple",
        "Suavizado exponencial",
        "Upgrading hardware",
        "Ley de Little"
      ],
      "correct": 1,
      "explanation": "El suavizado simple se recomienda cuando no hay tendencia sistemática."
    },
    {
      "question": "¿Qué técnica usarías sin datos históricos?",
      "answers": [
        "Regresión lineal",
        "Media móvil",
        "Cualitativa",
        "Suavizado simple"
      ],
      "correct": 2,
      "explanation": "Sin histórico fiable, las técnicas cualitativas pueden ser la opción viable."
    },
    {
      "question": "¿Qué dato exige una técnica cuantitativa?",
      "answers": [
        "Opinión única",
        "Servidor nuevo",
        "Z nulo del proceso",
        "Histórico fiable"
      ],
      "correct": 3,
      "explanation": "Las técnicas cuantitativas dependen de datos históricos adecuados."
    },
    {
      "question": "¿Qué problema causa histórico poco fiable?",
      "answers": [
        "Predicción débil",
        "Más exactitud segura",
        "SLA automático",
        "Capacidad infinita"
      ],
      "correct": 0,
      "explanation": "Datos malos producen modelos poco confiables."
    },
    {
      "question": "¿Qué significa horizonte de planificación?",
      "answers": [
        "Tiempo de servicio",
        "Tiempo futuro a cubrir",
        "Intervalo de CPU",
        "Tiempo de cola con datos"
      ],
      "correct": 1,
      "explanation": "El horizonte indica hasta cuándo se quiere proyectar la demanda."
    },
    {
      "question": "¿Qué patrón exige cuidado con medias móviles?",
      "answers": [
        "Estabilidad",
        "Ruido bajo del servicio",
        "Tendencia marcada",
        "Media constante"
      ],
      "correct": 2,
      "explanation": "Las medias móviles simples pueden retrasarse ante tendencias fuertes."
    },
    {
      "question": "¿Qué patrón exige cuidado con regresión simple?",
      "answers": [
        "Tendencia lineal",
        "Datos crecientes",
        "Relación clara del proceso",
        "Estacionalidad fuerte"
      ],
      "correct": 3,
      "explanation": "La regresión lineal simple no modela bien estacionalidad sin ajustes."
    },
    {
      "question": "¿Qué patrón exige técnica estacional?",
      "answers": [
        "Picos repetidos",
        "Media constante",
        "Sin cambio",
        "Datos ausentes"
      ],
      "correct": 0,
      "explanation": "Si hay picos periódicos, se necesita considerar estacionalidad."
    },
    {
      "question": "¿Qué es validar con datos antiguos?",
      "answers": [
        "Borrar el entrenamiento",
        "Probar antes de predecir",
        "Fijar SLA a cero con datos",
        "Comprar hardware"
      ],
      "correct": 1,
      "explanation": "Se comprueba si el modelo reproduce datos conocidos antes de usarlo."
    },
    {
      "question": "¿Qué ocurre si el error de validación es alto?",
      "answers": [
        "El modelo es perfecto",
        "No hay carga futura",
        "No conviene confiar aún",
        "Sobra capacidad del servicio"
      ],
      "correct": 2,
      "explanation": "Un error alto indica que la técnica elegida puede no ser adecuada."
    },
    {
      "question": "¿Qué representa alfa en suavizado?",
      "answers": [
        "Número de terminales",
        "Coste de arranque",
        "Tasa de visita del proceso",
        "Peso de observaciones"
      ],
      "correct": 3,
      "explanation": "Alfa controla cuánto pesan datos recientes frente al pasado."
    },
    {
      "question": "Si alfa es mayor, ¿qué efecto suele tener?",
      "answers": [
        "Más reacción al cambio",
        "Más olvido del presente",
        "Menos peso reciente",
        "Cero predicción"
      ],
      "correct": 0,
      "explanation": "Un alfa mayor hace que la predicción responda más a datos recientes."
    },
    {
      "question": "Si alfa es muy pequeño, ¿qué efecto suele tener?",
      "answers": [
        "Cambio brusco siempre",
        "Predicción más suave",
        "Sin histórico",
        "SLA infinito"
      ],
      "correct": 1,
      "explanation": "Un alfa pequeño amortigua cambios y da más estabilidad."
    },
    {
      "question": "¿Qué riesgo tiene elegir n muy grande en medias móviles?",
      "answers": [
        "Eliminar el histórico",
        "Aumentar alfa",
        "Responder tarde a cambios",
        "Fijar N del servicio"
      ],
      "correct": 2,
      "explanation": "Una ventana grande suaviza mucho y puede retrasar la reacción."
    },
    {
      "question": "¿Qué riesgo tiene elegir n muy pequeño?",
      "answers": [
        "No usar datos recientes",
        "Eliminar tendencia",
        "Bloquear CPU del proceso",
        "Más sensibilidad al ruido"
      ],
      "correct": 3,
      "explanation": "Una ventana pequeña reacciona rápido pero puede variar demasiado."
    },
    {
      "question": "¿Qué variable de negocio sería NFU para ecommerce?",
      "answers": [
        "Pedidos por día",
        "Color del logo",
        "Nombre del servidor",
        "Ruta del HTML"
      ],
      "correct": 0,
      "explanation": "Pedidos por día se relaciona con consumo de recursos de la tienda."
    },
    {
      "question": "¿Qué variable sería NFU para universidad?",
      "answers": [
        "Marca del monitor",
        "Matrículas activas",
        "Tipo de teclado",
        "Color del aula con datos"
      ],
      "correct": 1,
      "explanation": "El número de matrículas puede anticipar carga de sistemas académicos."
    },
    {
      "question": "¿Por qué NFU ayuda a directivos y técnicos?",
      "answers": [
        "Elimina todo coste",
        "Evita medir sistemas",
        "Conecta negocio y recursos",
        "Sustituye SLA del servicio"
      ],
      "correct": 2,
      "explanation": "NFU traduce previsiones de negocio a demanda técnica."
    },
    {
      "question": "Si NFU prevista crece 30%, ¿qué revisar?",
      "answers": [
        "Solo color de UI del proceso",
        "Solo nombre del SLA",
        "Número de respuestas",
        "Necesidades de recursos"
      ],
      "correct": 3,
      "explanation": "Un crecimiento de variable de negocio puede aumentar carga y consumo técnico."
    },
    {
      "question": "¿Qué requisito tiene capacidad bajo demanda?",
      "answers": [
        "Monitorización en tiempo real",
        "Sin métricas del sistema",
        "Sin automatización",
        "Sin niveles de servicio"
      ],
      "correct": 0,
      "explanation": "Para actuar automáticamente necesita observar el rendimiento actual."
    },
    {
      "question": "¿Qué dispara una acción bajo demanda?",
      "answers": [
        "Archivo más largo con datos",
        "Predicción de incumplimiento",
        "Respuesta más corta",
        "Tema seleccionado"
      ],
      "correct": 1,
      "explanation": "El sistema actúa cuando prevé que el servicio puede degradarse."
    },
    {
      "question": "¿Qué acción bajo demanda es plausible?",
      "answers": [
        "Borrar usuarios del servicio",
        "Ignorar alertas",
        "Añadir capacidad temporal",
        "Quitar mediciones"
      ],
      "correct": 2,
      "explanation": "Puede asignar recursos adicionales para cumplir el nivel acordado."
    },
    {
      "question": "¿Qué ventaja tiene pago por consumo?",
      "answers": [
        "Obliga a comprar máximo",
        "Impide compartir",
        "Elimina SLA del proceso",
        "Reduce sobredimensionamiento"
      ],
      "correct": 3,
      "explanation": "Pagar por uso evita adquirir capacidad fija excesiva."
    },
    {
      "question": "¿Qué riesgo controla la capacidad bajo demanda?",
      "answers": [
        "Picos de carga",
        "Ausencia de datos",
        "Coste de papel",
        "Longitud de opción"
      ],
      "correct": 0,
      "explanation": "La asignación dinámica ayuda a absorber variaciones de demanda."
    },
    {
      "question": "¿Por qué externalizar exige SLA claros?",
      "answers": [
        "Para no medir nada con datos",
        "Para garantizar servicio",
        "Para evitar contratos",
        "Para eliminar costes"
      ],
      "correct": 1,
      "explanation": "Si el sistema no pertenece a la empresa, los SLA garantizan el nivel esperado."
    },
    {
      "question": "¿Qué métrica vigilarías para autoscaling?",
      "answers": [
        "Número de temas",
        "Color de botón del servicio",
        "Utilización de recursos",
        "Longitud del texto"
      ],
      "correct": 2,
      "explanation": "La utilización ayuda a decidir cuándo asignar más o menos capacidad."
    },
    {
      "question": "¿Qué métrica vigilarías para experiencia?",
      "answers": [
        "Coste inicial",
        "Ruta local del proceso",
        "Nombre del PDF",
        "Tiempo de respuesta"
      ],
      "correct": 3,
      "explanation": "El tiempo de respuesta se vincula directamente con la experiencia del usuario."
    },
    {
      "question": "¿Qué decisión toma capacidad bajo demanda?",
      "answers": [
        "Cuánta capacidad asignar",
        "Qué tema estudiar",
        "Qué PDF abrir del sistema",
        "Qué opción alargar"
      ],
      "correct": 0,
      "explanation": "Su objetivo es ajustar capacidad a la carga para cumplir servicio."
    },
    {
      "question": "¿Qué evita la planificación proactiva?",
      "answers": [
        "Datos históricos",
        "Saturación imprevista",
        "Medidas de uso",
        "Comparación de alternativas"
      ],
      "correct": 1,
      "explanation": "Actuar antes reduce el riesgo de saturación inesperada."
    },
    {
      "question": "¿Qué se debe hacer si cambia el patrón de carga?",
      "answers": [
        "Mantener modelo fijo",
        "Borrar el SLA del servicio",
        "Revalidar la predicción",
        "Ignorar el cambio"
      ],
      "correct": 2,
      "explanation": "Un cambio de patrón puede invalidar una técnica previamente adecuada."
    },
    {
      "question": "¿Qué pasa si el negocio lanza una campaña?",
      "answers": [
        "Baja siempre X",
        "Desaparece U del proceso",
        "Se anula TCO",
        "Puede subir la carga"
      ],
      "correct": 3,
      "explanation": "Eventos de negocio pueden alterar la demanda futura."
    },
    {
      "question": "¿Qué predicción conviene para decisiones de compra?",
      "answers": [
        "Horizonte suficiente",
        "Solo último minuto",
        "Sin datos del sistema",
        "Sin coste"
      ],
      "correct": 0,
      "explanation": "Comprar capacidad requiere prever con tiempo suficiente para actuar."
    },
    {
      "question": "¿Qué predicción conviene para autoscaling?",
      "answers": [
        "Solo anual con datos",
        "Muy cercana al tiempo real",
        "Sin monitorización",
        "Solo cualitativa"
      ],
      "correct": 1,
      "explanation": "La capacidad bajo demanda necesita reacción rápida ante cambios recientes."
    },
    {
      "question": "¿Qué caracteriza al nivel 0 de gestión de capacidad?",
      "answers": [
        "Hay predicción automática",
        "Se predicen SLA",
        "No hay programa formal",
        "Se usan modelos de negocio"
      ],
      "correct": 2,
      "explanation": "En nivel 0 no existe un programa de gestión de capacidad; se gestiona solo ocasionalmente."
    },
    {
      "question": "¿Cómo se realiza la capacidad en el nivel 0?",
      "answers": [
        "Con revisiones pico",
        "Con análisis automático",
        "Con modelo de negocio",
        "De forma ocasional"
      ],
      "correct": 3,
      "explanation": "El nivel 0 describe una gestión esporádica, sin programa estable."
    },
    {
      "question": "¿Qué caracteriza al nivel 1?",
      "answers": [
        "Tendencias y picos",
        "Sin gestión alguna",
        "SLA automáticos",
        "Criterios de negocio"
      ],
      "correct": 0,
      "explanation": "En nivel 1 se miden tendencias y se predice utilización en periodos pico."
    },
    {
      "question": "¿Qué planificación aparece en el nivel 1?",
      "answers": [
        "Tiempo real continuo",
        "Revisiones periódicas",
        "Modelo de negocio",
        "Sin mediciones"
      ],
      "correct": 1,
      "explanation": "El nivel 1 planifica recursos mediante revisiones periódicas."
    },
    {
      "question": "¿Qué se conoce en el nivel 2?",
      "answers": [
        "Solo costes iniciales",
        "SLA del negocio",
        "Utilización por carga",
        "Alfa óptimo"
      ],
      "correct": 2,
      "explanation": "En nivel 2 se conocen las utilizaciones de cada recurso debidas a cargas significativas."
    },
    {
      "question": "¿Qué añade el nivel 2 frente al nivel 1?",
      "answers": [
        "Ausencia de medición",
        "Solo intuición",
        "Pago por consumo",
        "Detalle por recurso y carga"
      ],
      "correct": 3,
      "explanation": "El nivel 2 baja al detalle de recursos y cargas de trabajo relevantes."
    },
    {
      "question": "¿Qué caracteriza al nivel 3?",
      "answers": [
        "Análisis y predicción automáticos",
        "Gestión ocasional",
        "Solo revisiones manuales",
        "SLA desde negocio"
      ],
      "correct": 0,
      "explanation": "En nivel 3 existe un sistema automático de análisis y predicción de la carga."
    },
    {
      "question": "¿Con qué se relaciona el nivel 3 en el tema?",
      "answers": [
        "Coste total de propiedad",
        "Capacidad bajo demanda",
        "Redes batch",
        "Media móvil manual"
      ],
      "correct": 1,
      "explanation": "La capacidad bajo demanda se presenta como aplicación durante la ejecución en nivel 3."
    },
    {
      "question": "¿Qué predice automáticamente el nivel 4?",
      "answers": [
        "Solo utilización pico",
        "Solo coste de compra",
        "Niveles de servicio",
        "Solo tasa de visita"
      ],
      "correct": 2,
      "explanation": "En nivel 4 se predicen automáticamente los niveles de servicio desde predicciones de capacidad."
    },
    {
      "question": "¿Qué entrada usa el nivel 4 para predecir servicio?",
      "answers": [
        "Color de interfaz",
        "Nombre de usuario",
        "Coste de instalación",
        "Predicciones de capacidad"
      ],
      "correct": 3,
      "explanation": "El nivel 4 conecta predicciones de capacidad con niveles de servicio."
    },
    {
      "question": "¿Qué caracteriza al nivel 5?",
      "answers": [
        "Criterios de negocio",
        "Gestión ocasional",
        "Solo datos pico",
        "Sin modelo"
      ],
      "correct": 0,
      "explanation": "En nivel 5 se usan criterios de aplicaciones de negocio mediante un modelo."
    },
    {
      "question": "¿Para qué sirve el modelo del nivel 5?",
      "answers": [
        "Medir solo B",
        "Predecir niveles de servicio",
        "Elegir color UI",
        "Eliminar SLA"
      ],
      "correct": 1,
      "explanation": "El modelo usa criterios de negocio para predecir niveles de servicio."
    },
    {
      "question": "¿Cuál es el orden correcto de sofisticación?",
      "answers": [
        "5, 3, 1, 0, 2, 4",
        "1, 0, 2, 5, 3, 4",
        "0, 1, 2, 3, 4, 5",
        "2, 0, 5, 1, 4, 3"
      ],
      "correct": 2,
      "explanation": "Los niveles se ordenan de menor a mayor sofisticación desde 0 hasta 5."
    },
    {
      "question": "¿Qué nivel es el menos maduro?",
      "answers": [
        "Nivel 2",
        "Nivel 4",
        "Nivel 5",
        "Nivel 0"
      ],
      "correct": 3,
      "explanation": "El nivel 0 no tiene programa formal de gestión de capacidad."
    },
    {
      "question": "¿Qué nivel es el más sofisticado?",
      "answers": [
        "Nivel 5",
        "Nivel 0",
        "Nivel 1",
        "Nivel 2"
      ],
      "correct": 0,
      "explanation": "El nivel 5 incorpora criterios de negocio mediante modelos para predecir servicio."
    },
    {
      "question": "¿En qué nivel aparece por primera vez la automatización de análisis?",
      "answers": [
        "Nivel 0",
        "Nivel 3",
        "Nivel 1",
        "Nivel 2"
      ],
      "correct": 1,
      "explanation": "El nivel 3 introduce sistema automático de análisis y predicción de carga."
    },
    {
      "question": "¿En qué nivel se predice utilización en periodos pico?",
      "answers": [
        "Nivel 0",
        "Nivel 4",
        "Nivel 1",
        "Nivel 5"
      ],
      "correct": 2,
      "explanation": "El nivel 1 realiza medidas de tendencia y predicción de utilización en picos."
    },
    {
      "question": "¿En qué nivel se conocen utilizaciones por cargas significativas?",
      "answers": [
        "Nivel 1",
        "Nivel 3",
        "Nivel 5",
        "Nivel 2"
      ],
      "correct": 3,
      "explanation": "El nivel 2 conoce exactamente las utilizaciones causadas por cargas importantes."
    },
    {
      "question": "¿En qué nivel se predicen automáticamente los SLA o niveles de servicio?",
      "answers": [
        "Nivel 4",
        "Nivel 1",
        "Nivel 2",
        "Nivel 3"
      ],
      "correct": 0,
      "explanation": "El nivel 4 predice niveles de servicio a partir de predicciones de capacidad."
    },
    {
      "question": "¿En qué nivel entran criterios de aplicaciones de negocio?",
      "answers": [
        "Nivel 2",
        "Nivel 5",
        "Nivel 3",
        "Nivel 4"
      ],
      "correct": 1,
      "explanation": "El nivel 5 incorpora criterios de aplicaciones de negocio mediante un modelo."
    },
    {
      "question": "Si una empresa solo revisa recursos cada cierto tiempo con picos, ¿qué nivel encaja?",
      "answers": [
        "Nivel 0",
        "Nivel 4",
        "Nivel 1",
        "Nivel 5"
      ],
      "correct": 2,
      "explanation": "Las revisiones periódicas con medidas de tendencia corresponden al nivel 1."
    },
    {
      "question": "Si una empresa sabe qué carga consume cada recurso, ¿qué nivel encaja?",
      "answers": [
        "Nivel 0",
        "Nivel 1",
        "Nivel 5",
        "Nivel 2"
      ],
      "correct": 3,
      "explanation": "Conocer utilizaciones por carga significativa corresponde al nivel 2."
    },
    {
      "question": "Si una empresa analiza carga en tiempo real y actúa, ¿qué nivel encaja?",
      "answers": [
        "Nivel 3",
        "Nivel 1",
        "Nivel 2",
        "Nivel 5"
      ],
      "correct": 0,
      "explanation": "El análisis automático de carga en ejecución encaja con el nivel 3."
    },
    {
      "question": "Si una empresa traduce capacidad prevista a SLA previstos, ¿qué nivel encaja?",
      "answers": [
        "Nivel 0",
        "Nivel 4",
        "Nivel 1",
        "Nivel 2"
      ],
      "correct": 1,
      "explanation": "El nivel 4 automatiza la predicción de niveles de servicio desde capacidad."
    },
    {
      "question": "Si una empresa usa objetivos del negocio en el modelo, ¿qué nivel encaja?",
      "answers": [
        "Nivel 1",
        "Nivel 2",
        "Nivel 5",
        "Nivel 3"
      ],
      "correct": 2,
      "explanation": "El nivel 5 conecta criterios de negocio con predicción de niveles de servicio."
    },
    {
      "question": "¿Qué idea general reflejan los seis niveles?",
      "answers": [
        "Más coste siempre",
        "Menos medición progresiva",
        "Menos automatización",
        "Mayor sofisticación progresiva"
      ],
      "correct": 3,
      "explanation": "Los niveles ordenan la madurez de la gestión y planificación de capacidad."
    },
    {
      "question": "Si una organización no mide nada y solo reacciona a crisis, ¿qué nivel encaja?",
      "answers": [
        "Nivel 0",
        "Nivel 2",
        "Nivel 4",
        "Nivel 5"
      ],
      "correct": 0,
      "explanation": "El nivel 0 carece de programa formal y la gestión es ocasional."
    },
    {
      "question": "Si una organización revisa picos cada trimestre, ¿qué nivel encaja?",
      "answers": [
        "Nivel 0",
        "Nivel 1",
        "Nivel 4",
        "Nivel 5"
      ],
      "correct": 1,
      "explanation": "El nivel 1 incluye medidas de tendencia, picos y revisiones periódicas."
    },
    {
      "question": "Si una organización sabe qué aplicación consume cada servidor, ¿qué nivel encaja?",
      "answers": [
        "Nivel 1",
        "Nivel 4",
        "Nivel 2",
        "Nivel 5"
      ],
      "correct": 2,
      "explanation": "El nivel 2 conoce utilizaciones exactas por recurso y carga significativa."
    },
    {
      "question": "Si hay análisis automático de carga pero no predicción automática de SLA, ¿qué nivel encaja mejor?",
      "answers": [
        "Nivel 2",
        "Nivel 4",
        "Nivel 5",
        "Nivel 3"
      ],
      "correct": 3,
      "explanation": "El nivel 3 introduce análisis y predicción automática de la carga."
    },
    {
      "question": "Si el sistema predice si incumplirá el tiempo de respuesta, ¿qué nivel encaja?",
      "answers": [
        "Nivel 4",
        "Nivel 1",
        "Nivel 2",
        "Nivel 3"
      ],
      "correct": 0,
      "explanation": "El nivel 4 predice niveles de servicio desde capacidad prevista."
    },
    {
      "question": "Si el modelo usa prioridades del negocio, ¿qué nivel encaja?",
      "answers": [
        "Nivel 2",
        "Nivel 5",
        "Nivel 3",
        "Nivel 4"
      ],
      "correct": 1,
      "explanation": "El nivel 5 incorpora criterios de aplicaciones de negocio."
    },
    {
      "question": "¿Qué salto conceptual hay de nivel 3 a nivel 4?",
      "answers": [
        "De nada a picos",
        "De negocio a coste",
        "De carga a servicio",
        "De SLA a PDF"
      ],
      "correct": 2,
      "explanation": "Nivel 3 predice carga; nivel 4 predice niveles de servicio."
    },
    {
      "question": "¿Qué salto conceptual hay de nivel 4 a nivel 5?",
      "answers": [
        "De medición a nada",
        "De picos a revisiones",
        "De coste a CPU",
        "De servicio técnico a negocio"
      ],
      "correct": 3,
      "explanation": "Nivel 5 añade criterios de aplicaciones de negocio al modelo."
    },
    {
      "question": "Si un SLA exige 99% disponibilidad, ¿qué decisión de capacidad implica?",
      "answers": [
        "Dimensionar para cumplirlo",
        "Ignorarlo si X sube",
        "Usar solo opiniones",
        "Evitar monitorizar"
      ],
      "correct": 0,
      "explanation": "Los SLA son objetivos que condicionan configuración y capacidad."
    },
    {
      "question": "Si una alternativa cumple SLA pero cuesta el doble, ¿qué falta evaluar?",
      "answers": [
        "Solo color de la web",
        "Coste total frente a beneficio",
        "Número de opciones",
        "Longitud del PDF"
      ],
      "correct": 1,
      "explanation": "La capacidad adecuada también debe respetar límites económicos."
    },
    {
      "question": "Si una alternativa barata incumple R, ¿por qué no es adecuada?",
      "answers": [
        "Tiene menor TCO siempre",
        "Usa pocos datos",
        "No cumple nivel de servicio",
        "Tiene menos opciones"
      ],
      "correct": 2,
      "explanation": "La capacidad adecuada exige cumplir los SLA continuamente."
    },
    {
      "question": "¿Qué trampa hay en mirar solo coste inicial?",
      "answers": [
        "Mide demasiado servicio",
        "Incluye mantenimiento",
        "Predice mejor la carga",
        "Ignora costes de operación"
      ],
      "correct": 3,
      "explanation": "El TCO incluye costes de arranque y de explotación."
    },
    {
      "question": "Si dos arquitecturas rinden igual, ¿qué criterio puede decidir?",
      "answers": [
        "Facilidad de administración",
        "Longitud del nombre",
        "Número de preguntas",
        "Orden del temario"
      ],
      "correct": 0,
      "explanation": "La arquitectura depende también de experiencia, madurez y administración."
    },
    {
      "question": "Si el aplicativo exige una tecnología concreta, ¿qué factor domina?",
      "answers": [
        "Media móvil",
        "Arquitectura compatible",
        "Nivel 0",
        "Respuesta aleatoria"
      ],
      "correct": 1,
      "explanation": "Las exigencias de la aplicación condicionan la arquitectura seleccionada."
    },
    {
      "question": "Si no hay datos históricos fiables, ¿qué predicción es más defendible?",
      "answers": [
        "Regresión exacta",
        "Media móvil precisa",
        "Cualitativa apoyada en expertos",
        "Suavizado seguro"
      ],
      "correct": 2,
      "explanation": "Sin histórico fiable, las técnicas cuantitativas pierden base."
    },
    {
      "question": "Si hay tendencia lineal clara y datos fiables, ¿qué técnica probarías?",
      "answers": [
        "Solo Delphi",
        "Upgrading",
        "MVA cerrado",
        "Regresión lineal"
      ],
      "correct": 3,
      "explanation": "La regresión lineal es apropiada para datos no estacionales con tendencia lineal."
    },
    {
      "question": "Si hay datos estacionarios con poco ruido, ¿qué técnica simple probarías?",
      "answers": [
        "Medias móviles",
        "Regresión forzada",
        "Nivel 5",
        "TCO"
      ],
      "correct": 0,
      "explanation": "Las medias móviles encajan con datos casi estacionarios."
    },
    {
      "question": "Si los datos recientes importan más que los antiguos, ¿qué técnica encaja?",
      "answers": [
        "Regresión sin tendencia",
        "Suavizado exponencial",
        "Upgrading",
        "Ley de Little"
      ],
      "correct": 1,
      "explanation": "El suavizado exponencial pondera más las observaciones recientes."
    },
    {
      "question": "Si una serie tiene estacionalidad semanal, ¿qué riesgo hay con media móvil simple?",
      "answers": [
        "Mejorar siempre",
        "Eliminar ruido exacto",
        "Ocultar el patrón",
        "Convertirla en SLA"
      ],
      "correct": 2,
      "explanation": "Una media móvil simple puede suavizar y ocultar patrones estacionales importantes."
    },
    {
      "question": "Si la campaña de marketing cambia el patrón histórico, ¿qué debes hacer?",
      "answers": [
        "Mantenerlo sin mirar",
        "Borrar el SLA",
        "Usar N*",
        "Revalidar el modelo"
      ],
      "correct": 3,
      "explanation": "Un cambio de patrón puede invalidar predicciones basadas en datos antiguos."
    },
    {
      "question": "Si el ECM baja al cambiar n, ¿qué indica?",
      "answers": [
        "Mejor ajuste histórico",
        "Peor predicción segura",
        "Sin datos suficientes",
        "Saturación automática"
      ],
      "correct": 0,
      "explanation": "Menor error cuadrático medio indica mejor comportamiento sobre los datos de validación."
    },
    {
      "question": "Si n es muy pequeño en media móvil, ¿qué problema aparece?",
      "answers": [
        "Respuesta muy lenta",
        "Exceso de sensibilidad",
        "Sin datos recientes",
        "No hay predicción"
      ],
      "correct": 1,
      "explanation": "Una ventana pequeña sigue demasiado el ruido."
    },
    {
      "question": "Si n es muy grande, ¿qué problema aparece?",
      "answers": [
        "Ruido máximo",
        "Sin histórico",
        "Reacción lenta",
        "Más SLA"
      ],
      "correct": 2,
      "explanation": "Una ventana grande suaviza, pero tarda en adaptarse a cambios."
    },
    {
      "question": "Si alfa es alto, ¿qué ocurre ante un pico reciente?",
      "answers": [
        "La predicción ignora el pico",
        "La serie se vuelve lineal",
        "El SLA desaparece",
        "La predicción cambia más"
      ],
      "correct": 3,
      "explanation": "Un alfa alto da mucho peso a observaciones recientes."
    },
    {
      "question": "Si alfa es bajo, ¿qué ocurre ante un pico aislado?",
      "answers": [
        "Se amortigua más",
        "Domina totalmente",
        "Anula el histórico",
        "Crea nivel 5"
      ],
      "correct": 0,
      "explanation": "Un alfa bajo suaviza más y reduce el efecto de cambios bruscos."
    },
    {
      "question": "Si una NFU crece pero el consumo por NFU baja, ¿qué no puedes asumir?",
      "answers": [
        "Que no habrá carga",
        "Que recursos crecen igual",
        "Que SLA no importa",
        "Que no hay predicción"
      ],
      "correct": 1,
      "explanation": "La relación entre NFU y recursos debe cuantificarse, no asumirse lineal siempre."
    },
    {
      "question": "Si empleados suben 20%, ¿qué pregunta técnica haces?",
      "answers": [
        "Color de nómina",
        "Número de letras",
        "Consumo por empleado",
        "Nivel del PDF"
      ],
      "correct": 2,
      "explanation": "La NFU debe traducirse a demanda de recursos mediante una relación de consumo."
    },
    {
      "question": "Si pedidos/día es NFU, ¿qué carga derivada interesa?",
      "answers": [
        "Coste del monitor",
        "Tamaño del aula",
        "Color de botones",
        "Transacciones de la app"
      ],
      "correct": 3,
      "explanation": "La variable de negocio debe conectarse con actividad técnica del sistema."
    },
    {
      "question": "Si autoscaling tarda demasiado en actuar, ¿qué SLA peligra?",
      "answers": [
        "Tiempo de respuesta",
        "Nombre del modelo",
        "Número de niveles",
        "Coste inicial"
      ],
      "correct": 0,
      "explanation": "Si se asigna capacidad tarde, los usuarios pueden sufrir respuesta excesiva."
    },
    {
      "question": "Si capacidad bajo demanda añade recursos ante picos, ¿qué busca mantener?",
      "answers": [
        "Número de opciones",
        "Nivel de servicio",
        "Coste inicial fijo",
        "Tasa de visita"
      ],
      "correct": 1,
      "explanation": "La asignación dinámica intenta cumplir los acuerdos de servicio."
    },
    {
      "question": "Si varias apps comparten servidores, ¿qué ventaja aparece?",
      "answers": [
        "Más aislamiento rígido",
        "Menos flexibilidad",
        "Mejor uso de infrautilizados",
        "Sin necesidad de SLA"
      ],
      "correct": 2,
      "explanation": "La gestión compartida puede reasignar recursos ociosos a cargas con demanda."
    },
    {
      "question": "¿Qué riesgo tiene aislar siempre aplicaciones en servidores fijos?",
      "answers": [
        "Más elasticidad",
        "Pago exacto",
        "Predicción perfecta",
        "Infrautilización"
      ],
      "correct": 3,
      "explanation": "La rigidez puede dejar servidores ociosos mientras otros necesitan capacidad."
    },
    {
      "question": "Si se paga por consumo, ¿qué problema se reduce?",
      "answers": [
        "Sobredimensionamiento inicial",
        "Necesidad de medir",
        "Existencia de SLA",
        "Variación de carga"
      ],
      "correct": 0,
      "explanation": "El pago bajo demanda evita comprar toda la capacidad máxima por adelantado."
    },
    {
      "question": "Si el proveedor externo no garantiza SLA, ¿qué falla?",
      "answers": [
        "Necesidad de datos",
        "Confianza en externalización",
        "Existencia de carga",
        "Uso de predicción"
      ],
      "correct": 1,
      "explanation": "La externalización es aceptable si se garantiza el cumplimiento de niveles de servicio."
    },
    {
      "question": "Si la herramienta no se integra con gestión existente, ¿qué riesgo hay?",
      "answers": [
        "Más exactitud segura",
        "SLA automático",
        "Operación más difícil",
        "Menor necesidad de datos"
      ],
      "correct": 2,
      "explanation": "La integración con otras herramientas es un criterio de selección."
    },
    {
      "question": "Si quieres saber un umbral con meses de antelación, ¿qué importa?",
      "answers": [
        "Solo alfa actual",
        "Z de usuarios",
        "Dmax del disco",
        "Horizonte de predicción"
      ],
      "correct": 3,
      "explanation": "La herramienta debe anticipar con el margen temporal requerido."
    },
    {
      "question": "Si solo necesitas reaccionar en ejecución, ¿qué enfoque encaja?",
      "answers": [
        "Capacidad bajo demanda",
        "Plan anual manual",
        "Nivel 0",
        "TCO estático"
      ],
      "correct": 0,
      "explanation": "La capacidad bajo demanda determina rendimiento y actúa durante la ejecución."
    },
    {
      "question": "Si una predicción cumple capacidad pero incumple SLA, ¿qué conclusión sacas?",
      "answers": [
        "La alternativa es adecuada",
        "La capacidad técnica no basta",
        "No hace falta servicio",
        "El coste desaparece"
      ],
      "correct": 1,
      "explanation": "La planificación debe garantizar niveles de servicio, no solo recursos disponibles."
    },
    {
      "question": "Si el rendimiento mejora pero el coste rompe presupuesto, ¿qué conclusión sacas?",
      "answers": [
        "Siempre debe elegirse",
        "El SLA sobra",
        "No es capacidad adecuada",
        "No hay alternativa"
      ],
      "correct": 2,
      "explanation": "La capacidad adecuada exige cumplir servicio dentro de límites de coste."
    },
    {
      "question": "Si se mide utilización solo en horas valle, ¿qué se subestima?",
      "answers": [
        "Coste inicial",
        "Número de niveles",
        "Valor de alfa",
        "Riesgo en periodos pico"
      ],
      "correct": 3,
      "explanation": "La planificación debe considerar cargas pico, no solo momentos tranquilos."
    }
  ],
  "Temas 5 y 6 juntos": [
    {
      "question": "Si en una estación aumenta X y S no cambia, ¿qué pasa con U?",
      "answers": [
        "Aumenta en la misma proporción",
        "Disminuye por tener más flujo",
        "Permanece siempre constante",
        "Pasa a valer exactamente S del modelo"
      ],
      "correct": 0,
      "explanation": "Por la ley U = X * S, si S permanece fija, U crece cuando aumenta X."
    },
    {
      "question": "¿Qué busca la planificación de capacidad?",
      "answers": [
        "Eliminar la medición del sistema",
        "Aumentar colas deliberadamente",
        "Preparar recursos para carga futura",
        "Ignorar los SLA pactados del sistema"
      ],
      "correct": 2,
      "explanation": "Planificar capacidad consiste en dimensionar recursos para cargas futuras."
    },
    {
      "question": "¿Qué mide mejor la productividad de un sistema?",
      "answers": [
        "Trabajos presentes en la cola en la red",
        "Trabajos completados por unidad de tiempo",
        "Segundos que dura una petición en la red",
        "Usuarios conectados sin responder"
      ],
      "correct": 1,
      "explanation": "La productividad mide salidas o completaciones por unidad de tiempo."
    },
    {
      "question": "¿Cómo define el tema la capacidad?",
      "answers": [
        "Número de usuarios satisfechos",
        "Coste mínimo de compra de capacidad",
        "Tiempo medio de reflexión",
        "Productividad máxima del sistema"
      ],
      "correct": 3,
      "explanation": "La capacidad se entiende como la productividad máxima que puede ofrecer el sistema."
    },
    {
      "question": "¿Qué recurso será candidato a cuello de botella?",
      "answers": [
        "El de menor tiempo de visita del recurso",
        "El de menor utilización medida",
        "El de mayor demanda de servicio",
        "El de menor número de accesos"
      ],
      "correct": 2,
      "explanation": "El recurso con más demanda tiende a saturarse antes y limitar el sistema."
    },
    {
      "question": "¿Qué se intenta anticipar con la planificación?",
      "answers": [
        "La futura saturación del sistema",
        "La desaparición de usuarios",
        "La ausencia total de carga",
        "La eliminación de costes en la planificación"
      ],
      "correct": 0,
      "explanation": "La planificación predice cuándo la carga futura puede saturar el sistema."
    },
    {
      "question": "En una red cerrada, ¿qué dato se fija normalmente?",
      "answers": [
        "La tasa externa de llegada",
        "El coste de explotación observada",
        "La disponibilidad pactada",
        "El número total de clientes N"
      ],
      "correct": 3,
      "explanation": "En redes cerradas se mantiene una población fija N dentro del sistema."
    },
    {
      "question": "¿Qué fase va antes de monitorizar?",
      "answers": [
        "Seleccionar alternativa final",
        "Dotar de instrumentación",
        "Facturar bajo demanda",
        "Aplicar media móvil"
      ],
      "correct": 1,
      "explanation": "Primero hay que instrumentar el sistema para poder medirlo."
    },
    {
      "question": "¿Qué diferencia una red abierta de una cerrada?",
      "answers": [
        "Tiene entradas y salidas externas",
        "No contiene estaciones de cola",
        "No permite calcular respuesta",
        "Solo admite cargas batch del sistema"
      ],
      "correct": 0,
      "explanation": "En redes abiertas los trabajos llegan desde fuera y abandonan el sistema."
    },
    {
      "question": "¿Qué se hace al caracterizar la carga?",
      "answers": [
        "Cambiar toda la arquitectura",
        "Eliminar variables históricas",
        "Describir patrones de uso",
        "Fijar siempre alfa a 1"
      ],
      "correct": 2,
      "explanation": "Caracterizar la carga significa entender cómo se usa el sistema."
    },
    {
      "question": "¿Qué representa una estación de retardo?",
      "answers": [
        "Un disco con una cola larga",
        "Un tiempo sin espera en cola",
        "Una CPU siempre saturada en la estación",
        "Un servidor físico único"
      ],
      "correct": 1,
      "explanation": "Una estación de retardo se modela con infinitos servidores y no genera cola."
    },
    {
      "question": "¿Qué alternativa se selecciona al final?",
      "answers": [
        "La más cara disponible",
        "La que no cumple SLA del proceso",
        "La primera sin comparar",
        "Mejor coste y/o rendimiento"
      ],
      "correct": 3,
      "explanation": "El proceso compara opciones y escoge la mejor según coste y prestaciones."
    },
    {
      "question": "¿Qué significa tiempo de residencia?",
      "answers": [
        "Llegadas menos salidas",
        "Productividad por visitas",
        "Espera más servicio recibido",
        "Usuarios por terminal del modelo"
      ],
      "correct": 2,
      "explanation": "La residencia incluye el tiempo esperando y el tiempo siendo atendido."
    },
    {
      "question": "¿De qué depende la capacidad adecuada?",
      "answers": [
        "SLA, arquitectura y coste",
        "Solo de la CPU del sistema",
        "Solo del número de PDFs",
        "Solo de la regresión"
      ],
      "correct": 0,
      "explanation": "La capacidad adecuada combina servicio, tecnología y restricciones económicas."
    },
    {
      "question": "¿Cuál es una variable operacional básica?",
      "answers": [
        "Productividad X",
        "Utilización U en la red",
        "Tiempo medio S",
        "Tiempo ocupado B"
      ],
      "correct": 3,
      "explanation": "B se mide directamente; X, U y S se deducen de variables básicas."
    },
    {
      "question": "¿Qué fija un SLA?",
      "answers": [
        "El algoritmo MVA del proceso",
        "Umbrales de servicio pactados",
        "La tasa de visita",
        "El valor de Z de capacidad"
      ],
      "correct": 1,
      "explanation": "Los SLA fijan umbrales de productividad, rendimiento y disponibilidad."
    },
    {
      "question": "Si A y C son parecidos durante T, ¿qué supuesto se cumple?",
      "answers": [
        "Flujo equilibrado",
        "Retardo infinito",
        "Saturación nula",
        "Predicción lineal"
      ],
      "correct": 0,
      "explanation": "El equilibrio de flujo supone que entradas y salidas coinciden aproximadamente."
    },
    {
      "question": "¿Qué métrica puede aparecer en un SLA?",
      "answers": [
        "Color de la interfaz",
        "Número de preguntas",
        "Tiempo de respuesta máximo",
        "Ruta del archivo en la planificación"
      ],
      "correct": 2,
      "explanation": "Los SLA pueden incluir límites de respuesta aceptables para los usuarios."
    },
    {
      "question": "¿Qué calcula la ley de Little?",
      "answers": [
        "Coste medio desde SLA",
        "Clientes medios desde X y R",
        "Visitas desde disponibilidad",
        "Colas desde presupuesto"
      ],
      "correct": 1,
      "explanation": "Little relaciona número medio en el sistema, productividad y tiempo de residencia."
    },
    {
      "question": "¿Qué es el TCO?",
      "answers": [
        "Tiempo calculado operativo",
        "Tasa central observada",
        "Tipo cerrado operacional",
        "Coste total de propiedad"
      ],
      "correct": 3,
      "explanation": "El TCO incluye costes de arranque y operación durante un periodo."
    },
    {
      "question": "En un sistema interactivo, ¿qué es Z?",
      "answers": [
        "Tiempo de servicio del disco del sistema",
        "Utilización media del servidor",
        "Tiempo de reflexión del usuario",
        "Llegadas externas al sistema"
      ],
      "correct": 2,
      "explanation": "Z es el tiempo entre dos interacciones consecutivas de un usuario."
    },
    {
      "question": "¿Qué coste es de arranque?",
      "answers": [
        "Compra e instalación",
        "Consumo diario",
        "Mantenimiento mensual",
        "Monitorización continua"
      ],
      "correct": 0,
      "explanation": "La compra e instalación forman parte de los costes iniciales."
    },
    {
      "question": "Si Z vale cero, una carga interactiva se parece a una carga...",
      "answers": [
        "transaccional",
        "mixta abierta",
        "estacional",
        "batch"
      ],
      "correct": 3,
      "explanation": "Sin tiempo de reflexión, la carga interactiva equivale a mantener trabajos activos como en batch."
    },
    {
      "question": "¿Qué coste es de operación?",
      "answers": [
        "Compra inicial del proceso",
        "Mantenimiento del sistema",
        "Instalación física",
        "Diseño del SLA"
      ],
      "correct": 1,
      "explanation": "El mantenimiento aparece durante la explotación del sistema."
    },
    {
      "question": "¿Qué caracteriza a una carga transaccional?",
      "answers": [
        "Clientes entran y salen",
        "Población total fija del modelo",
        "Terminales con Z fijo",
        "Trabajos reemplazados"
      ],
      "correct": 0,
      "explanation": "Las cargas transaccionales se modelan como abiertas: llegan, se atienden y salen."
    },
    {
      "question": "¿Qué condiciona la arquitectura elegida?",
      "answers": [
        "Solo la nota del examen del sistema",
        "Solo el tamaño del aula",
        "Aplicación, experiencia y administración",
        "Solo el valor de alfa del sistema"
      ],
      "correct": 2,
      "explanation": "La arquitectura depende de requisitos técnicos y factores operativos."
    },
    {
      "question": "¿Para qué sirve la tasa de visita Vk?",
      "answers": [
        "Mide segundos de reflexión en la red",
        "Cuenta accesos medios a un recurso",
        "Fija el número de usuarios",
        "Calcula coste de propiedad"
      ],
      "correct": 1,
      "explanation": "Vk indica cuántas veces una interacción visita un recurso."
    },
    {
      "question": "¿Qué método usa datos históricos?",
      "answers": [
        "Cualitativo",
        "Tuning de capacidad",
        "Upgrading",
        "Cuantitativo"
      ],
      "correct": 3,
      "explanation": "Los métodos cuantitativos se apoyan en series y datos históricos."
    },
    {
      "question": "¿Qué expresa la demanda Dk?",
      "answers": [
        "Llegadas externas por segundo",
        "Clientes totales del sistema",
        "Servicio total pedido a un recurso",
        "Coste de mantenimiento del recurso"
      ],
      "correct": 2,
      "explanation": "Dk agrega el servicio que una interacción exige a un recurso."
    },
    {
      "question": "¿Qué método usa juicio experto?",
      "answers": [
        "Cualitativo",
        "Cuantitativo",
        "MVA",
        "Little"
      ],
      "correct": 0,
      "explanation": "Los métodos cualitativos se basan en análisis subjetivo, expertos y contexto."
    },
    {
      "question": "¿Qué hace el modelo de servidor central?",
      "answers": [
        "Predice costes económicos observada",
        "Elimina estaciones de cola",
        "Define acuerdos SLA observada",
        "Representa CPU y E/S del sistema"
      ],
      "correct": 3,
      "explanation": "El modelo central describe trabajos que pasan por CPU y dispositivos de E/S."
    },
    {
      "question": "¿Qué patrón favorece regresión lineal?",
      "answers": [
        "Ruido sin tendencia",
        "Tendencia lineal",
        "Cola infinita",
        "SLA incumplido"
      ],
      "correct": 1,
      "explanation": "La regresión lineal simple se aplica cuando hay tendencia aproximadamente lineal."
    },
    {
      "question": "¿Qué ocurre tras una petición de disco en el modelo central?",
      "answers": [
        "El trabajo vuelve a la CPU",
        "El trabajo desaparece siempre",
        "Se reinicia el valor de N",
        "Se calcula una media móvil"
      ],
      "correct": 0,
      "explanation": "Después de la E/S, el trabajo suele regresar a la CPU."
    },
    {
      "question": "¿Qué predice una regresión?",
      "answers": [
        "Variable independiente",
        "Tiempo de reflexión fijo",
        "Variable dependiente",
        "Utilización adimensional"
      ],
      "correct": 2,
      "explanation": "La variable dependiente es la que se estima en el modelo."
    },
    {
      "question": "¿Qué significa que una estación tenga cola?",
      "answers": [
        "Tiene infinitos servidores libres",
        "Puede haber espera antes del servicio",
        "Solo mide reflexión humana",
        "No recibe trabajos reales en la estación"
      ],
      "correct": 1,
      "explanation": "Una estación de cola representa espera cuando el servidor no está disponible."
    },
    {
      "question": "¿Qué papel tiene una variable independiente?",
      "answers": [
        "Es siempre el resultado final",
        "Mide coste total del proceso",
        "Es un servidor físico con datos",
        "Ayuda a explicar la dependiente"
      ],
      "correct": 3,
      "explanation": "Las independientes se usan como entradas para predecir otra variable."
    },
    {
      "question": "¿Qué indica una utilización cercana a 1?",
      "answers": [
        "Recurso sin demanda real",
        "Sistema sin trabajos activos",
        "Recurso casi siempre ocupado",
        "Tiempo de servicio nulo"
      ],
      "correct": 2,
      "explanation": "Una utilización alta indica poco margen libre y posible saturación."
    },
    {
      "question": "¿Cuándo convienen medias móviles?",
      "answers": [
        "Datos casi estacionarios",
        "Tendencia lineal fuerte",
        "Sin datos históricos del sistema",
        "Solo opiniones expertas"
      ],
      "correct": 0,
      "explanation": "Las medias móviles funcionan bien con series casi estacionarias."
    },
    {
      "question": "¿Qué terapia cambia hardware para eliminar un cuello?",
      "answers": [
        "tuning",
        "forecasting",
        "smoothing",
        "upgrading"
      ],
      "correct": 3,
      "explanation": "El upgrading consiste en mejorar o sustituir componentes hardware."
    },
    {
      "question": "¿Qué predicen las medias móviles?",
      "answers": [
        "Máximo coste posible",
        "Media de observaciones previas",
        "Número de terminales",
        "Demanda del cuello de capacidad"
      ],
      "correct": 1,
      "explanation": "La predicción se basa en promediar valores recientes."
    },
    {
      "question": "¿Qué terapia ajusta sin cambiar hardware base?",
      "answers": [
        "tuning",
        "upgrading",
        "regresión",
        "NFU"
      ],
      "correct": 0,
      "explanation": "El tuning modifica configuración u organización, normalmente a nivel de sistema."
    },
    {
      "question": "¿Para qué horizonte son útiles medias móviles?",
      "answers": [
        "Décadas sin datos",
        "Solo tiempo real",
        "Corto plazo",
        "Nunca se usan"
      ],
      "correct": 2,
      "explanation": "Son técnicas simples adecuadas para previsiones de corto plazo."
    },
    {
      "question": "¿Cuándo no conviene hablar de un único cuello de botella?",
      "answers": [
        "Cuando solo falla la CPU",
        "Cuando muchos recursos saturan",
        "Cuando Dk es máximo observada",
        "Cuando existe una cola en la red"
      ],
      "correct": 1,
      "explanation": "Si el problema es generalizado, es más correcto hablar de sistema sobrecargado."
    },
    {
      "question": "¿Qué parámetro se ajusta en medias móviles?",
      "answers": [
        "N de terminales",
        "Z de reflexión del servicio",
        "B de ocupación",
        "n de observaciones"
      ],
      "correct": 3,
      "explanation": "Se prueba el tamaño de ventana n para reducir el error."
    },
    {
      "question": "¿Para qué sirven los límites asintóticos?",
      "answers": [
        "Medir cada paquete de red del recurso",
        "Sustituir todos los modelos",
        "Acotar prestaciones con poco cálculo",
        "Eliminar datos de carga del sistema"
      ],
      "correct": 2,
      "explanation": "Permiten estimar límites superiores e inferiores de rendimiento rápidamente."
    },
    {
      "question": "¿Qué mide el error cuadrático medio?",
      "answers": [
        "Calidad de predicción",
        "Uso de CPU directo con datos",
        "Disponibilidad legal",
        "Número de servidores"
      ],
      "correct": 0,
      "explanation": "Sirve para comparar errores de predicción al ajustar modelos."
    },
    {
      "question": "¿Cuál es un límite optimista?",
      "answers": [
        "Mayor R posible",
        "Menor disponibilidad",
        "Mayor coste total",
        "Mayor X posible"
      ],
      "correct": 3,
      "explanation": "Los límites optimistas son máxima productividad y mínimo tiempo de respuesta."
    },
    {
      "question": "¿Cuándo conviene suavizado exponencial?",
      "answers": [
        "Con crecimiento lineal claro",
        "Sin tendencia sistemática",
        "Sin observaciones",
        "Con población fija"
      ],
      "correct": 1,
      "explanation": "El suavizado simple se usa con datos no estacionales y sin tendencia marcada."
    },
    {
      "question": "¿Cuál es un límite pesimista?",
      "answers": [
        "Mayor R posible",
        "Menor tiempo de cola",
        "Mayor productividad",
        "Menor demanda"
      ],
      "correct": 0,
      "explanation": "Los límites pesimistas indican peor productividad o peor respuesta posible."
    },
    {
      "question": "¿Qué observaciones pesan más en suavizado?",
      "answers": [
        "Las más antiguas",
        "Las inexistentes",
        "Las recientes",
        "Las más largas"
      ],
      "correct": 2,
      "explanation": "El suavizado exponencial da más peso a los datos recientes."
    },
    {
      "question": "En batch, ¿qué representa N*?",
      "answers": [
        "Llegadas externas máximas",
        "Trabajos procesables sin colas",
        "Usuarios desconectados",
        "Coste mínimo posible en la red"
      ],
      "correct": 1,
      "explanation": "N* marca cuántos trabajos pueden procesarse antes de que aparezcan colas."
    },
    {
      "question": "¿Qué rango de alfa se cita?",
      "answers": [
        "1 a 10 de capacidad",
        "10 a 30",
        "Siempre 0",
        "0,05 a 0,30"
      ],
      "correct": 3,
      "explanation": "El resumen indica que alfa suele estar entre 0,05 y 0,30."
    },
    {
      "question": "En interactivo, ¿qué representa N*?",
      "answers": [
        "Visitas medias al disco",
        "Segundos por petición",
        "Terminales hasta saturación",
        "Coste de arranque del recurso"
      ],
      "correct": 2,
      "explanation": "N* indica desde cuántos terminales al menos un recurso queda saturado."
    },
    {
      "question": "¿Qué es una NFU?",
      "answers": [
        "Variable de negocio ligada a recursos",
        "Recurso con infinitos servidores",
        "Ley de colas cerradas",
        "Coste de instalación en la planificación"
      ],
      "correct": 0,
      "explanation": "Una NFU traduce actividad de negocio en demanda técnica."
    },
    {
      "question": "Si se reduce D del cuello de botella, ¿qué se busca?",
      "answers": [
        "Aumentar el tiempo de espera",
        "Eliminar todos los clientes observada",
        "Forzar más saturación observada",
        "Mejorar productividad o respuesta"
      ],
      "correct": 3,
      "explanation": "Reducir la demanda del cuello libera capacidad del sistema."
    },
    {
      "question": "¿Qué ejemplo encaja con NFU?",
      "answers": [
        "Color del servidor del servicio",
        "Número de empleados en nómina",
        "Letra de la respuesta",
        "Número de temas PDF"
      ],
      "correct": 1,
      "explanation": "El número de empleados puede anticipar uso de una aplicación de nómina."
    },
    {
      "question": "¿Qué ley relaciona Xi con X mediante visitas?",
      "answers": [
        "Ley del flujo forzado",
        "Ley de Little",
        "Ley de medias móviles",
        "Ley de regresión"
      ],
      "correct": 0,
      "explanation": "El flujo forzado relaciona productividad global y productividades por dispositivo."
    },
    {
      "question": "¿Qué hace capacidad bajo demanda?",
      "answers": [
        "Impide compartir recursos del sistema",
        "Elimina los SLA con datos",
        "Asigna recursos automáticamente",
        "Evita medir en tiempo real"
      ],
      "correct": 2,
      "explanation": "La capacidad bajo demanda ajusta recursos para cumplir el nivel de servicio."
    },
    {
      "question": "¿Dónde puede aplicarse Little?",
      "answers": [
        "Solo a redes sin cola",
        "A recurso, subsistema o sistema",
        "Solo a presupuestos en la estación",
        "Solo a predicción NFU"
      ],
      "correct": 1,
      "explanation": "La ley de Little puede aplicarse a varios niveles del modelo."
    },
    {
      "question": "¿En qué se apoya capacidad bajo demanda?",
      "answers": [
        "Solo intuición humana",
        "Datos borrados del proceso",
        "Colas eliminadas",
        "Medidas en tiempo real"
      ],
      "correct": 3,
      "explanation": "Necesita análisis y predicción a partir de medidas actuales."
    },
    {
      "question": "¿Qué asume el análisis MVA en redes cerradas?",
      "answers": [
        "Se conoce X0 y se ignora N",
        "No hay clientes internos",
        "Se conoce N y se estima X",
        "No hay tiempos de servicio"
      ],
      "correct": 2,
      "explanation": "En MVA se parte de la población cerrada y se estima el rendimiento."
    },
    {
      "question": "¿Qué beneficio aporta bajo demanda?",
      "answers": [
        "Pago según consumo",
        "Compra máxima fija",
        "Sin monitorización",
        "Sin acuerdos SLA"
      ],
      "correct": 0,
      "explanation": "Permite facturar hardware y software según el consumo real."
    },
    {
      "question": "¿Qué hipótesis simplifica los trabajos del modelo?",
      "answers": [
        "Trabajos sin CPU en la red",
        "Trabajos sin visitas",
        "Trabajos infinitos",
        "Trabajos del mismo tipo"
      ],
      "correct": 3,
      "explanation": "El tema asume trabajos homogéneos para facilitar el análisis."
    },
    {
      "question": "¿Qué favorece la externalización?",
      "answers": [
        "Ausencia de contratos",
        "SLA garantizados por proveedor",
        "Datos sin medir del proceso",
        "Costes ocultos de capacidad"
      ],
      "correct": 1,
      "explanation": "Si se garantizan los SLA, los sistemas pueden estar gestionados externamente."
    },
    {
      "question": "¿Qué variable mide completaciones durante T?",
      "answers": [
        "C",
        "A",
        "B",
        "Z"
      ],
      "correct": 0,
      "explanation": "C cuenta las peticiones completadas en el intervalo de observación."
    },
    {
      "question": "¿Qué ahorra la automatización bajo demanda?",
      "answers": [
        "Todos los costes posibles",
        "La necesidad de SLA",
        "Trabajo manual de gestión",
        "La caracterización de carga"
      ],
      "correct": 2,
      "explanation": "La automatización reduce tareas manuales de asignación y ajuste."
    },
    {
      "question": "¿Qué variable mide llegadas durante T?",
      "answers": [
        "C",
        "A",
        "B",
        "R"
      ],
      "correct": 1,
      "explanation": "A cuenta las llegadas o peticiones recibidas durante el intervalo."
    },
    {
      "question": "¿Qué significa gestionar recursos compartidos?",
      "answers": [
        "Dedicarlos fijos siempre",
        "No medir su uso del servicio",
        "Bloquearlos por usuario",
        "Asignarlos según necesidad"
      ],
      "correct": 3,
      "explanation": "La capacidad bajo demanda permite repartir recursos entre cargas cambiantes."
    },
    {
      "question": "¿Qué variable mide ocupación del recurso?",
      "answers": [
        "N",
        "Z",
        "B",
        "Vk"
      ],
      "correct": 2,
      "explanation": "B es el tiempo durante el cual el recurso observado estuvo ocupado."
    },
    {
      "question": "¿Qué factor importa al elegir herramienta?",
      "answers": [
        "Tiempo de anticipación al umbral",
        "Longitud de respuestas",
        "Número de colores del servicio",
        "Nombre del PDF con datos"
      ],
      "correct": 0,
      "explanation": "Importa saber con cuánto margen se quiere detectar que una métrica alcanzará su límite."
    },
    {
      "question": "Si C=200 y T=100, X vale...",
      "answers": [
        "0,5",
        "100",
        "300",
        "2"
      ],
      "correct": 3,
      "explanation": "X = C/T = 200/100 = 2 peticiones por segundo."
    },
    {
      "question": "¿Qué se valida antes de predecir?",
      "answers": [
        "El color de la gráfica",
        "La técnica cuantitativa elegida",
        "El número de letras del proceso",
        "El orden de opciones"
      ],
      "correct": 1,
      "explanation": "Se valida el modelo con datos disponibles antes de confiar en sus predicciones."
    },
    {
      "question": "Si B=40 y T=80, U vale...",
      "answers": [
        "0,5",
        "2",
        "40",
        "120"
      ],
      "correct": 0,
      "explanation": "U = B/T = 40/80 = 0,5."
    },
    {
      "question": "¿Cómo se valida una técnica?",
      "answers": [
        "Eliminando las mediciones",
        "Forzando alfa a cero del sistema",
        "Probando con datos históricos",
        "Usando solo el presupuesto"
      ],
      "correct": 2,
      "explanation": "Se reservan datos históricos para comprobar el error de la técnica."
    },
    {
      "question": "Si B=25 y C=50, S vale...",
      "answers": [
        "2",
        "0,5",
        "25",
        "75"
      ],
      "correct": 1,
      "explanation": "S = B/C = 25/50 = 0,5 segundos por petición."
    },
    {
      "question": "¿Qué patrón es estacionario?",
      "answers": [
        "Crecimiento lineal seguro",
        "Picos por temporada fija",
        "Coste siempre creciente",
        "Media y varianza estables"
      ],
      "correct": 3,
      "explanation": "Una serie estacionaria no presenta cambios sistemáticos en media ni varianza."
    },
    {
      "question": "¿Qué significa R en Little?",
      "answers": [
        "Tasa media de visitas",
        "Número de recursos",
        "Tiempo medio de residencia",
        "Coste de arranque del recurso"
      ],
      "correct": 2,
      "explanation": "R representa el tiempo medio que una petición permanece en el ámbito analizado."
    },
    {
      "question": "¿Qué patrón es estacional?",
      "answers": [
        "Se repite por periodos",
        "No cambia nunca",
        "Crece siempre lineal",
        "No tiene datos en la planificación"
      ],
      "correct": 0,
      "explanation": "La estacionalidad aparece cuando hay variaciones periódicas reconocibles."
    },
    {
      "question": "¿Qué representa N en una carga batch?",
      "answers": [
        "Llegadas por segundo",
        "Coste total anual observada",
        "Tiempo de reflexión",
        "Trabajos activos medios"
      ],
      "correct": 3,
      "explanation": "En batch cerrado, N es el factor de multiprogramación o trabajos activos."
    },
    {
      "question": "¿Qué patrón muestra tendencia?",
      "answers": [
        "Ruido sin dirección",
        "Cambio sostenido en el nivel",
        "Media constante perfecta",
        "Ausencia de datos del servicio"
      ],
      "correct": 1,
      "explanation": "Una tendencia indica evolución creciente o decreciente sostenida."
    },
    {
      "question": "¿Qué representa N en interactivo?",
      "answers": [
        "Terminales activos",
        "Peticiones completadas",
        "Segundos de CPU",
        "Visitas al disco"
      ],
      "correct": 0,
      "explanation": "En cargas interactivas, N es el número de usuarios o terminales activos."
    },
    {
      "question": "¿Qué limita una organización?",
      "answers": [
        "Ley de Little con datos",
        "Existencia de colas",
        "Presupuesto disponible",
        "Número de PDFs"
      ],
      "correct": 2,
      "explanation": "Las restricciones económicas limitan la capacidad que puede adquirirse o mantenerse."
    },
    {
      "question": "¿Qué ocurre si X se acerca al límite del cuello?",
      "answers": [
        "Baja siempre la cola",
        "Crece mucho la espera",
        "Desaparece la demanda",
        "Z se hace negativo"
      ],
      "correct": 1,
      "explanation": "Al aproximarse a saturación, las colas y los tiempos de respuesta aumentan."
    },
    {
      "question": "¿Cuándo hay capacidad adecuada?",
      "answers": [
        "CPU siempre al 100% del proceso",
        "Sin datos históricos",
        "Sin arquitectura definida",
        "SLA cumplidos con coste pactado"
      ],
      "correct": 3,
      "explanation": "La capacidad es adecuada si cumple servicio, tecnología y límites económicos."
    },
    {
      "question": "¿Qué mide el tiempo de servicio?",
      "answers": [
        "Espera antes de usarlo",
        "Reflexión del usuario",
        "Uso real del recurso",
        "Tasa de llegada"
      ],
      "correct": 2,
      "explanation": "El servicio es el tiempo durante el cual el recurso atiende al trabajo."
    },
    {
      "question": "¿Qué monitoriza el proceso?",
      "answers": [
        "Utilización del sistema",
        "Solo el precio inicial",
        "Solo opiniones expertas",
        "Solo rutas de archivo"
      ],
      "correct": 0,
      "explanation": "Monitorizar utilización permite saber cómo se están usando los recursos."
    },
    {
      "question": "¿Qué mide el tiempo de espera?",
      "answers": [
        "Uso efectivo del servidor",
        "Productividad total",
        "Coste de operación",
        "Demora antes del servicio"
      ],
      "correct": 3,
      "explanation": "La espera es el tiempo antes de comenzar a usar el recurso."
    },
    {
      "question": "¿Qué se predice bajo alternativas?",
      "answers": [
        "Color de interfaz",
        "Rendimiento esperado",
        "Texto del SLA de capacidad",
        "Orden alfabético"
      ],
      "correct": 1,
      "explanation": "Se evalúa cómo rendiría el sistema con diferentes configuraciones."
    },
    {
      "question": "¿Qué es evaluar analíticamente una red?",
      "answers": [
        "Obtener índices resolviendo el modelo",
        "Cambiar todos los servidores",
        "Medir solo satisfacción del modelo",
        "Comprar más capacidad del recurso"
      ],
      "correct": 0,
      "explanation": "La evaluación analítica obtiene prestaciones a partir de ecuaciones del modelo."
    },
    {
      "question": "¿Qué evita planificar tarde?",
      "answers": [
        "Tener datos históricos",
        "Comparar alternativas",
        "Actuar después de saturar",
        "Medir utilización en la planificación"
      ],
      "correct": 2,
      "explanation": "La planificación anticipada busca actuar antes de que la saturación ya sea un problema."
    },
    {
      "question": "¿Qué técnica no se desarrolla en el tema?",
      "answers": [
        "Ley de Little en la red",
        "Cadenas de Markov",
        "Flujo forzado",
        "MVA observada"
      ],
      "correct": 1,
      "explanation": "Las cadenas de Markov se citan como alternativa, pero no se estudian en detalle."
    },
    {
      "question": "Si una métrica se acerca al umbral SLA, ¿qué toca hacer?",
      "answers": [
        "Ignorar la señal con datos",
        "Planificar una acción",
        "Borrar el histórico",
        "Reducir medición"
      ],
      "correct": 1,
      "explanation": "Los umbrales existen para actuar antes de incumplir el servicio."
    },
    {
      "question": "¿Qué representa el cliente en una red de colas?",
      "answers": [
        "Dispositivo de CPU",
        "Acuerdo económico del sistema",
        "Usuario o trabajo del sistema",
        "Herramienta de predicción"
      ],
      "correct": 2,
      "explanation": "Los clientes modelan usuarios, trabajos o peticiones que demandan servicio."
    },
    {
      "question": "¿Qué pregunta responde la planificación de capacidad?",
      "answers": [
        "Qué opción es más larga",
        "Qué archivo pesa menos",
        "Cuándo y cómo ampliar recursos",
        "Qué color usar del servicio"
      ],
      "correct": 2,
      "explanation": "Busca anticipar saturación y decidir cómo retrasarla o evitarla."
    },
    {
      "question": "¿Qué representa el servidor?",
      "answers": [
        "Usuario que piensa",
        "Serie temporal en la estación",
        "Presupuesto fijo",
        "Recurso que presta servicio"
      ],
      "correct": 3,
      "explanation": "El servidor equivale a un recurso físico o lógico que atiende trabajos."
    },
    {
      "question": "¿Qué pasa si se dimensiona solo con la carga actual?",
      "answers": [
        "Siempre sobra capacidad",
        "Nunca hay coste del proceso",
        "No hacen falta SLA",
        "Puede fallar ante carga futura"
      ],
      "correct": 3,
      "explanation": "La planificación debe considerar cargas futuras proyectadas, no solo el presente."
    },
    {
      "question": "¿Qué modelo conviene para población fija?",
      "answers": [
        "Red cerrada",
        "Red abierta",
        "Media móvil",
        "NFU"
      ],
      "correct": 0,
      "explanation": "Si la población total no cambia, se modela como red cerrada."
    },
    {
      "question": "¿Qué fase convierte negocio en carga técnica?",
      "answers": [
        "Caracterización de carga",
        "Compra directa",
        "Borrado de datos",
        "Diseño visual del sistema"
      ],
      "correct": 0,
      "explanation": "Caracterizar carga traduce el uso del sistema a patrones medibles."
    },
    {
      "question": "¿Qué modelo conviene para llegadas externas?",
      "answers": [
        "Red cerrada",
        "Red abierta",
        "Carga batch",
        "Estación retardo"
      ],
      "correct": 1,
      "explanation": "Las llegadas externas son propias de redes abiertas."
    },
    {
      "question": "¿Qué fase compara configuraciones candidatas?",
      "answers": [
        "Instrumentación inicial",
        "Predicción de rendimiento",
        "Definición de letra",
        "Lectura de PDF con datos"
      ],
      "correct": 1,
      "explanation": "Se predice cómo rendirá cada alternativa antes de elegir."
    },
    {
      "question": "Si U sube pero S permanece igual, ¿qué ha cambiado necesariamente?",
      "answers": [
        "Ha bajado B",
        "Ha bajado C",
        "Ha aumentado X",
        "Ha aumentado Z"
      ],
      "correct": 2,
      "explanation": "Como U = X * S, si S no cambia, la subida de U implica una subida de X."
    },
    {
      "question": "¿Qué significa mejor coste/rendimiento?",
      "answers": [
        "Comprar lo máximo siempre",
        "Evitar medir rendimiento",
        "Compromiso entre precio y servicio",
        "Elegir al azar del servicio"
      ],
      "correct": 2,
      "explanation": "La mejor alternativa no siempre es la más potente, sino la más conveniente."
    },
    {
      "question": "Si X aumenta mucho y R también, ¿qué sospecha es razonable?",
      "answers": [
        "El sistema está más vacío",
        "Z se ha vuelto nulo observada",
        "No hay colas posibles",
        "Hay congestión en algún recurso"
      ],
      "correct": 3,
      "explanation": "Más productividad con más respuesta suele indicar que algún recurso empieza a formar colas."
    },
    {
      "question": "¿Qué riesgo hay si no se instrumenta?",
      "answers": [
        "Sobra toda capacidad",
        "El SLA mejora solo del proceso",
        "La carga desaparece",
        "No hay medidas fiables"
      ],
      "correct": 3,
      "explanation": "Sin instrumentación no se puede monitorizar ni validar el estado del sistema."
    },
    {
      "question": "¿Qué dato distingue mejor una cola de un retardo?",
      "answers": [
        "La posibilidad de espera",
        "El número de temas",
        "La existencia de costes",
        "La técnica de predicción"
      ],
      "correct": 0,
      "explanation": "Una estación de cola puede hacer esperar; una de retardo no genera cola."
    },
    {
      "question": "¿Qué indica monitorizar utilización?",
      "answers": [
        "Qué recursos están cargados",
        "Qué usuarios aprueban",
        "Qué opción es correcta",
        "Qué PDF es mayor del sistema"
      ],
      "correct": 0,
      "explanation": "La utilización revela qué recursos consumen capacidad y cuánto margen queda."
    },
    {
      "question": "Si un disco tiene muchas visitas pero servicio muy bajo, ¿qué falta mirar?",
      "answers": [
        "Solo su nombre",
        "Su demanda total",
        "El número de PDFs",
        "El coste del aula"
      ],
      "correct": 1,
      "explanation": "La demanda depende de visitas y servicio; muchas visitas no bastan para saber si limita."
    },
    {
      "question": "¿Qué incluye una alternativa de capacidad?",
      "answers": [
        "Solo el texto del SLA",
        "Configuración de recursos",
        "Solo el histórico bruto",
        "Solo el color de UI con datos"
      ],
      "correct": 1,
      "explanation": "Las alternativas suelen ser configuraciones hardware/software posibles."
    },
    {
      "question": "Si un recurso tiene S alto pero casi no se visita, ¿qué puede ocurrir?",
      "answers": [
        "Que siempre sea el cuello",
        "Que U sea siempre uno",
        "Que no sea el cuello",
        "Que X sea siempre cero"
      ],
      "correct": 2,
      "explanation": "La demanda total puede ser baja si la tasa de visita es pequeña."
    },
    {
      "question": "¿Qué factor limita aunque el rendimiento sea bueno?",
      "answers": [
        "Ley de Little",
        "Número de temas",
        "Presupuesto disponible",
        "Valor de Z del servicio"
      ],
      "correct": 2,
      "explanation": "Las limitaciones económicas pueden impedir elegir la opción más potente."
    },
    {
      "question": "¿Qué recurso limita primero al crecer la carga?",
      "answers": [
        "El de menor nombre",
        "El de menor coste",
        "El de menor cola hoy",
        "El de mayor D"
      ],
      "correct": 3,
      "explanation": "El recurso con mayor demanda de servicio alcanza antes la saturación."
    },
    {
      "question": "¿Qué significa cumplir SLA continuamente?",
      "answers": [
        "Cumplir solo al inicio",
        "Medir una vez al año del proceso",
        "Comprar siempre nuevo",
        "No superar umbrales pactados"
      ],
      "correct": 3,
      "explanation": "La capacidad adecuada exige mantener el servicio dentro de umbrales pactados."
    },
    {
      "question": "¿Qué pasa con U si se duplica S y X no cambia?",
      "answers": [
        "Se duplica U",
        "Se anula U",
        "Se mantiene U",
        "Se divide U"
      ],
      "correct": 0,
      "explanation": "Por U = X * S, duplicar S duplica la utilización si X es constante."
    },
    {
      "question": "¿Qué diferencia SLA de QoS?",
      "answers": [
        "SLA concreta umbrales pactados",
        "QoS es siempre coste",
        "SLA es una fórmula MVA",
        "QoS es una cola del sistema"
      ],
      "correct": 0,
      "explanation": "El SLA formaliza objetivos de calidad de servicio en umbrales exigibles."
    },
    {
      "question": "Si X=5 y S=0,3, ¿qué indica U=1,5?",
      "answers": [
        "Recurso totalmente libre",
        "Modelo por encima de capacidad",
        "Servicio nulo en la red",
        "Flujo cerrado estable"
      ],
      "correct": 1,
      "explanation": "Una utilización superior a 1 no es viable para un único servidor sin saturación."
    },
    {
      "question": "¿Qué factor de SLA depende del usuario remoto?",
      "answers": [
        "Coste de instalación",
        "Tiempo máximo tolerable",
        "Tasa de visita con datos",
        "Alfa de suavizado"
      ],
      "correct": 1,
      "explanation": "Los usuarios remotos pueden desconectarse si la respuesta supera cierto límite."
    },
    {
      "question": "¿Qué lectura tiene U=0,95?",
      "answers": [
        "Recurso sin uso del recurso",
        "Predicción inválida",
        "Muy poco margen libre",
        "Carga inexistente"
      ],
      "correct": 2,
      "explanation": "Una utilización del 95% deja muy poco margen antes de congestionar."
    },
    {
      "question": "¿Qué factor de SLA mide percepción?",
      "answers": [
        "Número de CPUs del servicio",
        "Tamaño del PDF",
        "Satisfacción de uso",
        "Tipo de variable"
      ],
      "correct": 2,
      "explanation": "La satisfacción del usuario forma parte de los factores considerados en el acuerdo."
    },
    {
      "question": "Si C<T pero B≈T, ¿qué indica el recurso?",
      "answers": [
        "Está sin carga",
        "Tiene retardo infinito",
        "No recibe visitas",
        "Está casi saturado"
      ],
      "correct": 3,
      "explanation": "Si B se aproxima a T, el recurso estuvo ocupado casi todo el intervalo."
    },
    {
      "question": "¿Por qué la arquitectura no se elige solo por benchmarks?",
      "answers": [
        "Los benchmarks no existen",
        "El coste no influye",
        "El SLA se ignora del proceso",
        "También importa administración"
      ],
      "correct": 3,
      "explanation": "Facilidad de administración, experiencia y requisitos también condicionan la elección."
    },
    {
      "question": "¿Qué fórmula deduce S desde medidas directas?",
      "answers": [
        "B dividido entre C",
        "C dividido entre A",
        "T dividido entre N",
        "Z dividido entre R"
      ],
      "correct": 0,
      "explanation": "El tiempo medio de servicio es el tiempo ocupado total entre completaciones."
    },
    {
      "question": "¿Qué significa madurez en explotación?",
      "answers": [
        "Experiencia usando esa tecnología",
        "Número de opciones del sistema",
        "Valor de utilización",
        "Tiempo de servicio"
      ],
      "correct": 0,
      "explanation": "La experiencia de operación puede influir en la arquitectura seleccionada."
    },
    {
      "question": "¿Qué fórmula deduce X desde medidas directas?",
      "answers": [
        "B dividido entre C",
        "C dividido entre T",
        "A dividido entre C",
        "R dividido entre N"
      ],
      "correct": 1,
      "explanation": "La productividad se obtiene como completaciones por unidad de tiempo."
    },
    {
      "question": "¿Qué coste aparece después del arranque?",
      "answers": [
        "Compra inicial",
        "Consumo energético",
        "Instalación inicial",
        "Adquisición base"
      ],
      "correct": 1,
      "explanation": "El consumo energético pertenece a la operación del sistema."
    },
    {
      "question": "¿Qué fórmula deduce λ desde medidas directas?",
      "answers": [
        "T dividido entre A",
        "B dividido entre C",
        "A dividido entre T",
        "N dividido entre Z"
      ],
      "correct": 2,
      "explanation": "La tasa de llegada cuenta llegadas por unidad de tiempo."
    },
    {
      "question": "¿Qué coste pertenece al arranque?",
      "answers": [
        "Mantenimiento",
        "Electricidad diaria",
        "Instalación",
        "Soporte recurrente"
      ],
      "correct": 2,
      "explanation": "La instalación es un coste inicial de puesta en marcha."
    },
    {
      "question": "En equilibrio, si A>C durante mucho tiempo, ¿qué ocurre?",
      "answers": [
        "Baja la cola siempre",
        "Se anula la demanda",
        "Desaparece la CPU",
        "Crece la acumulación"
      ],
      "correct": 3,
      "explanation": "Si entran más trabajos de los que salen, el sistema acumula peticiones."
    },
    {
      "question": "¿Por qué usar TCO en vez de precio?",
      "answers": [
        "Ignora mantenimiento",
        "Evita comparar",
        "Elimina SLA del proceso",
        "Incluye vida operativa"
      ],
      "correct": 3,
      "explanation": "El coste total refleja tanto inicio como explotación durante un periodo."
    },
    {
      "question": "¿Qué indica una diferencia persistente entre A y C?",
      "answers": [
        "No hay flujo estable",
        "Hay retardo infinito",
        "El SLA se cumple",
        "Z vale cero"
      ],
      "correct": 0,
      "explanation": "El equilibrio requiere que las entradas y salidas se compensen en el periodo observado."
    },
    {
      "question": "¿Qué herramienta conviene si se necesita anticipación temprana?",
      "answers": [
        "Una con predicción suficiente",
        "Una sin históricos del sistema",
        "Una sin integración",
        "Una manual sin datos"
      ],
      "correct": 0,
      "explanation": "El tiempo de anticipación requerido condiciona la herramienta de planificación."
    },
    {
      "question": "¿Qué dato convierte visitas en demanda?",
      "answers": [
        "Tiempo de arranque",
        "Tiempo de servicio",
        "Coste total",
        "Disponibilidad"
      ],
      "correct": 1,
      "explanation": "La demanda combina visitas al recurso con tiempo de servicio por visita."
    },
    {
      "question": "¿Qué importa del sistema operativo al elegir herramienta?",
      "answers": [
        "Color del escritorio",
        "Compatibilidad e integración",
        "Número de preguntas",
        "Nombre del tema con datos"
      ],
      "correct": 1,
      "explanation": "La herramienta debe encajar con el entorno tecnológico existente."
    },
    {
      "question": "Si Vk=4 y Sk=0,1, ¿cuánto vale Dk?",
      "answers": [
        "4,1",
        "40",
        "0,4",
        "0,025"
      ],
      "correct": 2,
      "explanation": "Dk = Vk * Sk = 4 * 0,1 = 0,4 segundos."
    },
    {
      "question": "¿Qué implica gestión automática de capacidad?",
      "answers": [
        "Sin medidas de rendimiento",
        "Sin políticas de servicio",
        "Decisiones con menos intervención",
        "Sin datos históricos del servicio"
      ],
      "correct": 2,
      "explanation": "La automatización reduce trabajo manual y puede reaccionar antes."
    },
    {
      "question": "Si Dcpu=0,2 y Ddisco=0,8, ¿qué recurso limita más?",
      "answers": [
        "CPU",
        "Terminal",
        "Ninguno",
        "Disco"
      ],
      "correct": 3,
      "explanation": "La mayor demanda de servicio suele marcar el cuello potencial."
    },
    {
      "question": "¿Qué técnica usarías con datos lineales?",
      "answers": [
        "Media móvil simple",
        "Opinión experta sola",
        "Upgrading",
        "Regresión lineal"
      ],
      "correct": 3,
      "explanation": "La regresión lineal encaja con tendencia aproximadamente lineal."
    },
    {
      "question": "¿Qué modelo encaja con usuarios siempre reemplazados?",
      "answers": [
        "Batch cerrado",
        "Abierto puro",
        "Retardo aislado",
        "Predicción NFU"
      ],
      "correct": 0,
      "explanation": "En batch cerrado, al terminar un trabajo entra otro para mantener N."
    },
    {
      "question": "¿Qué técnica usarías con serie estable?",
      "answers": [
        "Media móvil",
        "Regresión forzada",
        "MVA cerrado",
        "Tuning"
      ],
      "correct": 0,
      "explanation": "Una serie casi estacionaria es buena candidata para medias móviles."
    },
    {
      "question": "¿Qué modelo encaja con peticiones HTTP independientes?",
      "answers": [
        "Batch cerrado",
        "Red abierta",
        "Solo retardo",
        "MVA cerrado"
      ],
      "correct": 1,
      "explanation": "Peticiones que llegan y salen se modelan como carga abierta."
    },
    {
      "question": "¿Qué técnica usarías sin tendencia clara?",
      "answers": [
        "Regresión lineal simple",
        "Suavizado exponencial",
        "Upgrading hardware",
        "Ley de Little"
      ],
      "correct": 1,
      "explanation": "El suavizado simple se recomienda cuando no hay tendencia sistemática."
    },
    {
      "question": "¿Qué modelo encaja con usuarios en terminales?",
      "answers": [
        "Abierto sin límite",
        "Batch sin Z",
        "Interactivo cerrado",
        "Solo disco del recurso"
      ],
      "correct": 2,
      "explanation": "Los sistemas interactivos tienen N usuarios y tiempo de reflexión Z."
    },
    {
      "question": "¿Qué técnica usarías sin datos históricos?",
      "answers": [
        "Regresión lineal",
        "Media móvil",
        "Cualitativa",
        "Suavizado simple"
      ],
      "correct": 2,
      "explanation": "Sin histórico fiable, las técnicas cualitativas pueden ser la opción viable."
    },
    {
      "question": "¿Qué cambia entre batch e interactivo?",
      "answers": [
        "Desaparece N",
        "No hay CPU",
        "No hay colas",
        "Aparece Z"
      ],
      "correct": 3,
      "explanation": "La carga interactiva añade tiempo de reflexión entre peticiones."
    },
    {
      "question": "¿Qué dato exige una técnica cuantitativa?",
      "answers": [
        "Opinión única",
        "Servidor nuevo",
        "Z nulo del proceso",
        "Histórico fiable"
      ],
      "correct": 3,
      "explanation": "Las técnicas cuantitativas dependen de datos históricos adecuados."
    },
    {
      "question": "Si Z aumenta con N fijo, ¿qué tiende a pasar con X?",
      "answers": [
        "Baja o se modera",
        "Sube siempre",
        "Se hace infinito",
        "Se vuelve coste"
      ],
      "correct": 0,
      "explanation": "Más reflexión reduce la frecuencia con la que los usuarios envían peticiones."
    },
    {
      "question": "¿Qué problema causa histórico poco fiable?",
      "answers": [
        "Predicción débil",
        "Más exactitud segura",
        "SLA automático",
        "Capacidad infinita"
      ],
      "correct": 0,
      "explanation": "Datos malos producen modelos poco confiables."
    },
    {
      "question": "Si R aumenta con N fijo y Z fijo, ¿qué ocurre con X interactiva?",
      "answers": [
        "Aumenta siempre",
        "Disminuye",
        "No cambia nunca",
        "Se vuelve D"
      ],
      "correct": 1,
      "explanation": "En N = X(R+Z), si R+Z crece con N fijo, X baja."
    },
    {
      "question": "¿Qué significa horizonte de planificación?",
      "answers": [
        "Tiempo de servicio",
        "Tiempo futuro a cubrir",
        "Intervalo de CPU",
        "Tiempo de cola con datos"
      ],
      "correct": 1,
      "explanation": "El horizonte indica hasta cuándo se quiere proyectar la demanda."
    },
    {
      "question": "Si N=30, R=4 y Z=6, ¿cuánto vale X?",
      "answers": [
        "10",
        "7,5",
        "3",
        "36"
      ],
      "correct": 2,
      "explanation": "X = N/(R+Z) = 30/(4+6) = 3 interacciones por segundo."
    },
    {
      "question": "¿Qué patrón exige cuidado con medias móviles?",
      "answers": [
        "Estabilidad",
        "Ruido bajo del servicio",
        "Tendencia marcada",
        "Media constante"
      ],
      "correct": 2,
      "explanation": "Las medias móviles simples pueden retrasarse ante tendencias fuertes."
    },
    {
      "question": "Si N=40, X=4 y R=3, ¿cuánto vale Z?",
      "answers": [
        "10",
        "1",
        "43",
        "7"
      ],
      "correct": 3,
      "explanation": "R+Z = N/X = 10; por tanto Z = 10 - 3 = 7."
    },
    {
      "question": "¿Qué patrón exige cuidado con regresión simple?",
      "answers": [
        "Tendencia lineal",
        "Datos crecientes",
        "Relación clara del proceso",
        "Estacionalidad fuerte"
      ],
      "correct": 3,
      "explanation": "La regresión lineal simple no modela bien estacionalidad sin ajustes."
    },
    {
      "question": "Si N=10 y Z=0, ¿qué carga representa?",
      "answers": [
        "Batch equivalente",
        "Abierta pura del modelo",
        "Retardo infinito",
        "SLA económico"
      ],
      "correct": 0,
      "explanation": "Con Z nulo, el comportamiento interactivo equivale a batch."
    },
    {
      "question": "¿Qué patrón exige técnica estacional?",
      "answers": [
        "Picos repetidos",
        "Media constante",
        "Sin cambio",
        "Datos ausentes"
      ],
      "correct": 0,
      "explanation": "Si hay picos periódicos, se necesita considerar estacionalidad."
    },
    {
      "question": "¿Qué significa que una red sea mixta?",
      "answers": [
        "No tiene servidores",
        "Combina cargas abiertas y cerradas",
        "Solo tiene costes",
        "No tiene visitas en la red"
      ],
      "correct": 1,
      "explanation": "Una red mixta representa unas cargas como abiertas y otras como cerradas."
    },
    {
      "question": "¿Qué es validar con datos antiguos?",
      "answers": [
        "Borrar el entrenamiento",
        "Probar antes de predecir",
        "Fijar SLA a cero con datos",
        "Comprar hardware"
      ],
      "correct": 1,
      "explanation": "Se comprueba si el modelo reproduce datos conocidos antes de usarlo."
    },
    {
      "question": "¿Qué dato no fija una red cerrada?",
      "answers": [
        "Número de clientes",
        "Demandas de servicio",
        "Llegada externa X0",
        "Visitas a recursos"
      ],
      "correct": 2,
      "explanation": "En redes cerradas no existe una tasa externa X0 que entre desde fuera."
    },
    {
      "question": "¿Qué ocurre si el error de validación es alto?",
      "answers": [
        "El modelo es perfecto",
        "No hay carga futura",
        "No conviene confiar aún",
        "Sobra capacidad del servicio"
      ],
      "correct": 2,
      "explanation": "Un error alto indica que la técnica elegida puede no ser adecuada."
    },
    {
      "question": "¿Qué dato sí fija una red abierta?",
      "answers": [
        "Número total fijo N",
        "Tiempo de reflexión fijo",
        "Clientes constantes",
        "Tasa de llegada externa"
      ],
      "correct": 3,
      "explanation": "En una red abierta se especifica la llegada externa o productividad de entrada."
    },
    {
      "question": "¿Qué representa alfa en suavizado?",
      "answers": [
        "Número de terminales",
        "Coste de arranque",
        "Tasa de visita del proceso",
        "Peso de observaciones"
      ],
      "correct": 3,
      "explanation": "Alfa controla cuánto pesan datos recientes frente al pasado."
    },
    {
      "question": "¿Qué error sería modelar una web pública como cerrada?",
      "answers": [
        "Fijar clientes sin límite real",
        "Usar tasa externa del modelo",
        "Medir productividad",
        "Calcular respuesta"
      ],
      "correct": 0,
      "explanation": "Una web pública suele recibir llegadas externas variables, más propia de red abierta."
    },
    {
      "question": "Si alfa es mayor, ¿qué efecto suele tener?",
      "answers": [
        "Más reacción al cambio",
        "Más olvido del presente",
        "Menos peso reciente",
        "Cero predicción"
      ],
      "correct": 0,
      "explanation": "Un alfa mayor hace que la predicción responda más a datos recientes."
    },
    {
      "question": "¿Qué error sería modelar terminales como abierta pura?",
      "answers": [
        "Incluir tiempo de respuesta",
        "Perder el límite N",
        "Medir utilización",
        "Usar estaciones"
      ],
      "correct": 1,
      "explanation": "Los sistemas interactivos tienen población total limitada por terminales activos."
    },
    {
      "question": "Si alfa es muy pequeño, ¿qué efecto suele tener?",
      "answers": [
        "Cambio brusco siempre",
        "Predicción más suave",
        "Sin histórico",
        "SLA infinito"
      ],
      "correct": 1,
      "explanation": "Un alfa pequeño amortigua cambios y da más estabilidad."
    },
    {
      "question": "¿Qué se estima en una red abierta simple?",
      "answers": [
        "Llegada desde N fijo",
        "Coste desde disponibilidad",
        "Rendimiento desde llegada conocida",
        "Z desde TCO del recurso"
      ],
      "correct": 2,
      "explanation": "Con la tasa de llegada dada, se calculan tiempos y demás prestaciones."
    },
    {
      "question": "¿Qué riesgo tiene elegir n muy grande en medias móviles?",
      "answers": [
        "Eliminar el histórico",
        "Aumentar alfa",
        "Responder tarde a cambios",
        "Fijar N del servicio"
      ],
      "correct": 2,
      "explanation": "Una ventana grande suaviza mucho y puede retrasar la reacción."
    },
    {
      "question": "¿Qué se estima en una red cerrada?",
      "answers": [
        "X0 desde coste",
        "SLA desde color",
        "TCO desde visitas",
        "X y R desde N"
      ],
      "correct": 3,
      "explanation": "En cerradas se conoce la población N y se estima la productividad y respuesta."
    },
    {
      "question": "¿Qué riesgo tiene elegir n muy pequeño?",
      "answers": [
        "No usar datos recientes",
        "Eliminar tendencia",
        "Bloquear CPU del proceso",
        "Más sensibilidad al ruido"
      ],
      "correct": 3,
      "explanation": "Una ventana pequeña reacciona rápido pero puede variar demasiado."
    },
    {
      "question": "¿Qué significa tiempo entre llegadas exponencial?",
      "answers": [
        "Llegadas sin memoria",
        "Llegadas fijas exactas",
        "Llegadas siempre nulas",
        "Llegadas por coste"
      ],
      "correct": 0,
      "explanation": "La hipótesis exponencial implica independencia respecto al instante anterior."
    },
    {
      "question": "¿Qué variable de negocio sería NFU para ecommerce?",
      "answers": [
        "Pedidos por día",
        "Color del logo",
        "Nombre del servidor",
        "Ruta del HTML"
      ],
      "correct": 0,
      "explanation": "Pedidos por día se relaciona con consumo de recursos de la tienda."
    },
    {
      "question": "¿Qué significa servicio exponencial?",
      "answers": [
        "Servicio siempre constante",
        "Resto de servicio sin memoria",
        "Servicio sin duración en la red",
        "Servicio solo económico"
      ],
      "correct": 1,
      "explanation": "El tiempo restante no depende de cuánto lleve ya en servicio."
    },
    {
      "question": "¿Qué variable sería NFU para universidad?",
      "answers": [
        "Marca del monitor",
        "Matrículas activas",
        "Tipo de teclado",
        "Color del aula con datos"
      ],
      "correct": 1,
      "explanation": "El número de matrículas puede anticipar carga de sistemas académicos."
    },
    {
      "question": "¿Qué algoritmo resuelve redes cerradas sencillas?",
      "answers": [
        "TCO",
        "SLA",
        "MVA",
        "NFU"
      ],
      "correct": 2,
      "explanation": "El análisis del valor medio se aplica a redes cerradas."
    },
    {
      "question": "¿Por qué NFU ayuda a directivos y técnicos?",
      "answers": [
        "Elimina todo coste",
        "Evita medir sistemas",
        "Conecta negocio y recursos",
        "Sustituye SLA del servicio"
      ],
      "correct": 2,
      "explanation": "NFU traduce previsiones de negocio a demanda técnica."
    },
    {
      "question": "¿Qué dato complica resolver cerradas frente a abiertas?",
      "answers": [
        "N nunca existe observada",
        "No hay demandas",
        "No hay recursos",
        "X no se conoce al inicio"
      ],
      "correct": 3,
      "explanation": "En cerradas hay que estimar la productividad del sistema."
    },
    {
      "question": "Si NFU prevista crece 30%, ¿qué revisar?",
      "answers": [
        "Solo color de UI del proceso",
        "Solo nombre del SLA",
        "Número de respuestas",
        "Necesidades de recursos"
      ],
      "correct": 3,
      "explanation": "Un crecimiento de variable de negocio puede aumentar carga y consumo técnico."
    },
    {
      "question": "¿Qué detectan las medidas a posteriori?",
      "answers": [
        "Cuellos reales observados",
        "Costes futuros seguros",
        "Z de mercado",
        "Alfa óptimo del modelo"
      ],
      "correct": 0,
      "explanation": "La detección habitual de cuellos interpreta medidas tomadas del sistema."
    },
    {
      "question": "¿Qué requisito tiene capacidad bajo demanda?",
      "answers": [
        "Monitorización en tiempo real",
        "Sin métricas del sistema",
        "Sin automatización",
        "Sin niveles de servicio"
      ],
      "correct": 0,
      "explanation": "Para actuar automáticamente necesita observar el rendimiento actual."
    },
    {
      "question": "¿Qué señal apunta a cuello de CPU?",
      "answers": [
        "Disco sin uso",
        "CPU con U muy alta",
        "Z muy alto",
        "TCO bajo en la red"
      ],
      "correct": 1,
      "explanation": "Una utilización muy alta de CPU puede señalarla como recurso limitante."
    },
    {
      "question": "¿Qué dispara una acción bajo demanda?",
      "answers": [
        "Archivo más largo con datos",
        "Predicción de incumplimiento",
        "Respuesta más corta",
        "Tema seleccionado"
      ],
      "correct": 1,
      "explanation": "El sistema actúa cuando prevé que el servicio puede degradarse."
    },
    {
      "question": "¿Qué señal apunta a cuello de E/S?",
      "answers": [
        "CPU sin carga",
        "Z nulo del recurso",
        "Disco con colas elevadas",
        "SLA escrito"
      ],
      "correct": 2,
      "explanation": "Colas y utilización altas en disco apuntan a cuello de E/S."
    },
    {
      "question": "¿Qué acción bajo demanda es plausible?",
      "answers": [
        "Borrar usuarios del servicio",
        "Ignorar alertas",
        "Añadir capacidad temporal",
        "Quitar mediciones"
      ],
      "correct": 2,
      "explanation": "Puede asignar recursos adicionales para cumplir el nivel acordado."
    },
    {
      "question": "¿Qué mejora es tuning?",
      "answers": [
        "Comprar disco nuevo",
        "Añadir memoria física",
        "Sustituir CPU observada",
        "Cambiar política del SO"
      ],
      "correct": 3,
      "explanation": "El tuning ajusta configuración u organización sin cambiar hardware principal."
    },
    {
      "question": "¿Qué ventaja tiene pago por consumo?",
      "answers": [
        "Obliga a comprar máximo",
        "Impide compartir",
        "Elimina SLA del proceso",
        "Reduce sobredimensionamiento"
      ],
      "correct": 3,
      "explanation": "Pagar por uso evita adquirir capacidad fija excesiva."
    },
    {
      "question": "¿Qué mejora es upgrading?",
      "answers": [
        "Instalar CPU más rápida",
        "Cambiar prioridad de procesos",
        "Reordenar colas del SO",
        "Ajustar parámetros"
      ],
      "correct": 0,
      "explanation": "El upgrading implica actualización o reposición de hardware."
    },
    {
      "question": "¿Qué riesgo controla la capacidad bajo demanda?",
      "answers": [
        "Picos de carga",
        "Ausencia de datos",
        "Coste de papel",
        "Longitud de opción"
      ],
      "correct": 0,
      "explanation": "La asignación dinámica ayuda a absorber variaciones de demanda."
    },
    {
      "question": "¿Qué límite optimista interesa para X?",
      "answers": [
        "Inferior",
        "Superior",
        "Medio móvil",
        "Cualitativo"
      ],
      "correct": 1,
      "explanation": "La mejor productividad posible corresponde al límite superior."
    },
    {
      "question": "¿Por qué externalizar exige SLA claros?",
      "answers": [
        "Para no medir nada con datos",
        "Para garantizar servicio",
        "Para evitar contratos",
        "Para eliminar costes"
      ],
      "correct": 1,
      "explanation": "Si el sistema no pertenece a la empresa, los SLA garantizan el nivel esperado."
    },
    {
      "question": "¿Qué límite optimista interesa para R?",
      "answers": [
        "Superior",
        "Externo",
        "Inferior",
        "Cíclico"
      ],
      "correct": 2,
      "explanation": "La mejor respuesta posible corresponde al menor tiempo de respuesta."
    },
    {
      "question": "¿Qué métrica vigilarías para autoscaling?",
      "answers": [
        "Número de temas",
        "Color de botón del servicio",
        "Utilización de recursos",
        "Longitud del texto"
      ],
      "correct": 2,
      "explanation": "La utilización ayuda a decidir cuándo asignar más o menos capacidad."
    },
    {
      "question": "¿Qué límite pesimista interesa para R?",
      "answers": [
        "Inferior",
        "Lineal",
        "Estacional",
        "Superior"
      ],
      "correct": 3,
      "explanation": "El peor tiempo de respuesta corresponde al límite superior."
    },
    {
      "question": "¿Qué métrica vigilarías para experiencia?",
      "answers": [
        "Coste inicial",
        "Ruta local del proceso",
        "Nombre del PDF",
        "Tiempo de respuesta"
      ],
      "correct": 3,
      "explanation": "El tiempo de respuesta se vincula directamente con la experiencia del usuario."
    },
    {
      "question": "¿Qué pasa al superar el punto de saturación?",
      "answers": [
        "Aparecen colas",
        "Desaparecen trabajos",
        "Baja U a cero",
        "Se elimina D"
      ],
      "correct": 0,
      "explanation": "Al superar N* el cuello ya no puede procesar todo sin espera."
    },
    {
      "question": "¿Qué decisión toma capacidad bajo demanda?",
      "answers": [
        "Cuánta capacidad asignar",
        "Qué tema estudiar",
        "Qué PDF abrir del sistema",
        "Qué opción alargar"
      ],
      "correct": 0,
      "explanation": "Su objetivo es ajustar capacidad a la carga para cumplir servicio."
    },
    {
      "question": "¿Qué supuesto exige el análisis asintótico?",
      "answers": [
        "Costes sin límite",
        "Demandas independientes de N",
        "Clientes infinitos siempre",
        "SLA inexistente en la red"
      ],
      "correct": 1,
      "explanation": "Los límites suponen que la demanda no cambia por la concurrencia."
    },
    {
      "question": "¿Qué evita la planificación proactiva?",
      "answers": [
        "Datos históricos",
        "Saturación imprevista",
        "Medidas de uso",
        "Comparación de alternativas"
      ],
      "correct": 1,
      "explanation": "Actuar antes reduce el riesgo de saturación inesperada."
    },
    {
      "question": "Si una demanda cambia al aumentar N, ¿qué se debilita?",
      "answers": [
        "Existencia de CPU",
        "Medición de T del recurso",
        "Validez de límites",
        "Definición de C"
      ],
      "correct": 2,
      "explanation": "Los límites asintóticos dependen de demandas estables frente a la concurrencia."
    },
    {
      "question": "¿Qué se debe hacer si cambia el patrón de carga?",
      "answers": [
        "Mantener modelo fijo",
        "Borrar el SLA del servicio",
        "Revalidar la predicción",
        "Ignorar el cambio"
      ],
      "correct": 2,
      "explanation": "Un cambio de patrón puede invalidar una técnica previamente adecuada."
    },
    {
      "question": "¿Qué gráfico ayuda a comparar configuraciones?",
      "answers": [
        "Colores del servidor",
        "Lista de usuarios",
        "Ruta del archivo",
        "Límites de X y R"
      ],
      "correct": 3,
      "explanation": "Los límites muestran rangos posibles de productividad y respuesta."
    },
    {
      "question": "¿Qué pasa si el negocio lanza una campaña?",
      "answers": [
        "Baja siempre X",
        "Desaparece U del proceso",
        "Se anula TCO",
        "Puede subir la carga"
      ],
      "correct": 3,
      "explanation": "Eventos de negocio pueden alterar la demanda futura."
    },
    {
      "question": "¿Qué indica que R crece sin gran mejora en X?",
      "answers": [
        "Saturación cercana",
        "Capacidad infinita",
        "Retardo puro",
        "Coste menor"
      ],
      "correct": 0,
      "explanation": "Cuando X apenas sube y R crece, el sistema se aproxima al cuello."
    },
    {
      "question": "¿Qué predicción conviene para decisiones de compra?",
      "answers": [
        "Horizonte suficiente",
        "Solo último minuto",
        "Sin datos del sistema",
        "Sin coste"
      ],
      "correct": 0,
      "explanation": "Comprar capacidad requiere prever con tiempo suficiente para actuar."
    },
    {
      "question": "¿Qué se obtiene al resolver el modelo?",
      "answers": [
        "Coste legal exacto",
        "Índices de prestaciones",
        "Número de PDFs en la red",
        "Nombre del SLA"
      ],
      "correct": 1,
      "explanation": "Resolver el modelo permite estimar rendimiento, productividad y tiempos."
    },
    {
      "question": "¿Qué predicción conviene para autoscaling?",
      "answers": [
        "Solo anual con datos",
        "Muy cercana al tiempo real",
        "Sin monitorización",
        "Solo cualitativa"
      ],
      "correct": 1,
      "explanation": "La capacidad bajo demanda necesita reacción rápida ante cambios recientes."
    },
    {
      "question": "¿Qué representa un cliente en espera?",
      "answers": [
        "Servidor atendiendo",
        "Coste de compra del recurso",
        "Trabajo aguardando recurso",
        "Variable de negocio"
      ],
      "correct": 2,
      "explanation": "La cola contiene clientes que esperan recibir servicio."
    },
    {
      "question": "¿Qué caracteriza al nivel 0 de gestión de capacidad?",
      "answers": [
        "Hay predicción automática",
        "Se predicen SLA",
        "No hay programa formal",
        "Se usan modelos de negocio"
      ],
      "correct": 2,
      "explanation": "En nivel 0 no existe un programa de gestión de capacidad; se gestiona solo ocasionalmente."
    },
    {
      "question": "¿Qué provoca aumentar visitas a un recurso lento?",
      "answers": [
        "Menor tiempo siempre",
        "Menor utilización",
        "Cero colas",
        "Mayor demanda total"
      ],
      "correct": 3,
      "explanation": "Más visitas a un recurso lento incrementan su demanda y riesgo de cuello."
    },
    {
      "question": "¿Cómo se realiza la capacidad en el nivel 0?",
      "answers": [
        "Con revisiones pico",
        "Con análisis automático",
        "Con modelo de negocio",
        "De forma ocasional"
      ],
      "correct": 3,
      "explanation": "El nivel 0 describe una gestión esporádica, sin programa estable."
    },
    {
      "question": "Si al aumentar N en una red cerrada X apenas crece y R aumenta mucho, ¿qué diagnóstico encaja mejor?",
      "answers": [
        "El sistema está cerca de saturación",
        "La red se ha vuelto abierta",
        "Z ha aumentado necesariamente",
        "No existe cuello de botella"
      ],
      "correct": 0,
      "explanation": "Cuando añadir clientes no aumenta casi la productividad pero sí la respuesta, el cuello limita el sistema."
    },
    {
      "question": "¿Qué caracteriza al nivel 1?",
      "answers": [
        "Tendencias y picos",
        "Sin gestión alguna",
        "SLA automáticos",
        "Criterios de negocio"
      ],
      "correct": 0,
      "explanation": "En nivel 1 se miden tendencias y se predice utilización en periodos pico."
    },
    {
      "question": "En una red abierta, si λ se aproxima a la capacidad del cuello, ¿qué comportamiento esperas?",
      "answers": [
        "R tiende siempre a cero",
        "R crece de forma acusada",
        "X se vuelve menor que cero",
        "U baja automáticamente"
      ],
      "correct": 1,
      "explanation": "Al acercarse a saturación, las colas crecen y el tiempo de respuesta se dispara."
    },
    {
      "question": "¿Qué planificación aparece en el nivel 1?",
      "answers": [
        "Tiempo real continuo",
        "Revisiones periódicas",
        "Modelo de negocio",
        "Sin mediciones"
      ],
      "correct": 1,
      "explanation": "El nivel 1 planifica recursos mediante revisiones periódicas."
    },
    {
      "question": "Si dos recursos tienen la misma U, ¿cuál es más peligroso como cuello futuro?",
      "answers": [
        "El de menor nombre",
        "El de menor coste",
        "El de mayor demanda D",
        "El de menor número de letras"
      ],
      "correct": 2,
      "explanation": "La demanda de servicio indica cuánto limita el recurso por interacción; U actual no basta para decidir."
    },
    {
      "question": "¿Qué se conoce en el nivel 2?",
      "answers": [
        "Solo costes iniciales",
        "SLA del negocio",
        "Utilización por carga",
        "Alfa óptimo"
      ],
      "correct": 2,
      "explanation": "En nivel 2 se conocen las utilizaciones de cada recurso debidas a cargas significativas."
    },
    {
      "question": "Si un recurso reduce su S a la mitad y X no cambia, ¿qué ocurre con U?",
      "answers": [
        "Se duplica",
        "No cambia",
        "Se hace negativa",
        "Se reduce a la mitad"
      ],
      "correct": 3,
      "explanation": "Como U = X * S, al reducir S a la mitad también se reduce U a la mitad."
    },
    {
      "question": "¿Qué añade el nivel 2 frente al nivel 1?",
      "answers": [
        "Ausencia de medición",
        "Solo intuición",
        "Pago por consumo",
        "Detalle por recurso y carga"
      ],
      "correct": 3,
      "explanation": "El nivel 2 baja al detalle de recursos y cargas de trabajo relevantes."
    },
    {
      "question": "Si en una estación C=0 pero B>0 durante T, ¿qué indica la medida?",
      "answers": [
        "No se puede deducir S con B/C",
        "S vale exactamente cero",
        "X es infinito",
        "No hubo ocupación"
      ],
      "correct": 0,
      "explanation": "S = B/C no puede calcularse si no hubo completaciones."
    },
    {
      "question": "¿Qué caracteriza al nivel 3?",
      "answers": [
        "Análisis y predicción automáticos",
        "Gestión ocasional",
        "Solo revisiones manuales",
        "SLA desde negocio"
      ],
      "correct": 0,
      "explanation": "En nivel 3 existe un sistema automático de análisis y predicción de la carga."
    },
    {
      "question": "Si A es mucho mayor que C en el intervalo observado, ¿qué problema tiene asumir equilibrio?",
      "answers": [
        "La red es cerrada perfecta",
        "El sistema acumula trabajo",
        "No hay llegadas reales",
        "La cola no puede crecer"
      ],
      "correct": 1,
      "explanation": "El equilibrio exige que entradas y salidas se compensen; si no, hay acumulación."
    },
    {
      "question": "¿Con qué se relaciona el nivel 3 en el tema?",
      "answers": [
        "Coste total de propiedad",
        "Capacidad bajo demanda",
        "Redes batch",
        "Media móvil manual"
      ],
      "correct": 1,
      "explanation": "La capacidad bajo demanda se presenta como aplicación durante la ejecución en nivel 3."
    },
    {
      "question": "En una red cerrada, ¿por qué no se fija una λ externa?",
      "answers": [
        "No existen estaciones",
        "No puede haber CPU",
        "Los clientes no entran desde fuera",
        "S siempre vale cero"
      ],
      "correct": 2,
      "explanation": "La población circula dentro del sistema; no hay una corriente externa de llegadas."
    },
    {
      "question": "¿Qué predice automáticamente el nivel 4?",
      "answers": [
        "Solo utilización pico",
        "Solo coste de compra",
        "Niveles de servicio",
        "Solo tasa de visita"
      ],
      "correct": 2,
      "explanation": "En nivel 4 se predicen automáticamente los niveles de servicio desde predicciones de capacidad."
    },
    {
      "question": "Si una carga interactiva tiene N alto pero Z también alto, ¿qué evita Z?",
      "answers": [
        "Que exista tiempo de respuesta",
        "Que haya estaciones de retardo",
        "Que se calcule productividad",
        "Que todos pidan servicio a la vez"
      ],
      "correct": 3,
      "explanation": "El tiempo de reflexión separa las peticiones y reduce presión sobre el subsistema central."
    },
    {
      "question": "¿Qué entrada usa el nivel 4 para predecir servicio?",
      "answers": [
        "Color de interfaz",
        "Nombre de usuario",
        "Coste de instalación",
        "Predicciones de capacidad"
      ],
      "correct": 3,
      "explanation": "El nivel 4 conecta predicciones de capacidad con niveles de servicio."
    },
    {
      "question": "Si un usuario interactivo está en periodo de reflexión, ¿dónde está respecto al subsistema central?",
      "answers": [
        "Fuera del subsistema central",
        "Siempre en la CPU",
        "Siempre en el disco",
        "En la cola del cuello"
      ],
      "correct": 0,
      "explanation": "Durante Z el subsistema central no trabaja para ese usuario."
    },
    {
      "question": "¿Qué caracteriza al nivel 5?",
      "answers": [
        "Criterios de negocio",
        "Gestión ocasional",
        "Solo datos pico",
        "Sin modelo"
      ],
      "correct": 0,
      "explanation": "En nivel 5 se usan criterios de aplicaciones de negocio mediante un modelo."
    },
    {
      "question": "Si N=50, Z=5 y X=5, ¿cuánto vale R?",
      "answers": [
        "10",
        "5",
        "45",
        "55"
      ],
      "correct": 1,
      "explanation": "R = N/X - Z = 50/5 - 5 = 5 segundos."
    },
    {
      "question": "¿Para qué sirve el modelo del nivel 5?",
      "answers": [
        "Medir solo B",
        "Predecir niveles de servicio",
        "Elegir color UI",
        "Eliminar SLA"
      ],
      "correct": 1,
      "explanation": "El modelo usa criterios de negocio para predecir niveles de servicio."
    },
    {
      "question": "Si R=3, Z=7 y X=4, ¿cuántos usuarios N hay?",
      "answers": [
        "10",
        "28",
        "40",
        "14"
      ],
      "correct": 2,
      "explanation": "N = X(R+Z) = 4*(3+7) = 40 usuarios."
    },
    {
      "question": "¿Cuál es el orden correcto de sofisticación?",
      "answers": [
        "5, 3, 1, 0, 2, 4",
        "1, 0, 2, 5, 3, 4",
        "0, 1, 2, 3, 4, 5",
        "2, 0, 5, 1, 4, 3"
      ],
      "correct": 2,
      "explanation": "Los niveles se ordenan de menor a mayor sofisticación desde 0 hasta 5."
    },
    {
      "question": "Si un recurso tiene Vk=8 y Sk=0,02, ¿cuál es Dk?",
      "answers": [
        "8,02",
        "400",
        "0,0025",
        "0,16"
      ],
      "correct": 3,
      "explanation": "Dk = Vk * Sk = 8 * 0,02 = 0,16 segundos."
    },
    {
      "question": "¿Qué nivel es el menos maduro?",
      "answers": [
        "Nivel 2",
        "Nivel 4",
        "Nivel 5",
        "Nivel 0"
      ],
      "correct": 3,
      "explanation": "El nivel 0 no tiene programa formal de gestión de capacidad."
    },
    {
      "question": "Si Dmax=0,25 s, ¿cuál es la cota aproximada de X máxima por el cuello?",
      "answers": [
        "4 trabajos/s",
        "0,25 trabajos/s",
        "25 trabajos/s",
        "1 trabajo/s"
      ],
      "correct": 0,
      "explanation": "La productividad máxima queda acotada por 1/Dmax = 1/0,25 = 4 trabajos/s."
    },
    {
      "question": "¿Qué nivel es el más sofisticado?",
      "answers": [
        "Nivel 5",
        "Nivel 0",
        "Nivel 1",
        "Nivel 2"
      ],
      "correct": 0,
      "explanation": "El nivel 5 incorpora criterios de negocio mediante modelos para predecir servicio."
    },
    {
      "question": "Si Dtotal=1 s y N=3 en batch sin colas ideal, ¿qué límite de R tiene sentido?",
      "answers": [
        "Exactamente 0 s",
        "Al menos 1 s",
        "Menos que cualquier D",
        "Siempre infinito"
      ],
      "correct": 1,
      "explanation": "El tiempo de respuesta no puede ser menor que la suma de demandas sin esperas."
    },
    {
      "question": "¿En qué nivel aparece por primera vez la automatización de análisis?",
      "answers": [
        "Nivel 0",
        "Nivel 3",
        "Nivel 1",
        "Nivel 2"
      ],
      "correct": 1,
      "explanation": "El nivel 3 introduce sistema automático de análisis y predicción de carga."
    },
    {
      "question": "¿Qué recurso conviene optimizar primero para elevar X máxima?",
      "answers": [
        "El de menor Vk",
        "El de menor Sk siempre",
        "El de mayor Dk",
        "El de menor utilización histórica"
      ],
      "correct": 2,
      "explanation": "La productividad máxima está limitada por el recurso con mayor demanda."
    },
    {
      "question": "¿En qué nivel se predice utilización en periodos pico?",
      "answers": [
        "Nivel 0",
        "Nivel 4",
        "Nivel 1",
        "Nivel 5"
      ],
      "correct": 2,
      "explanation": "El nivel 1 realiza medidas de tendencia y predicción de utilización en picos."
    },
    {
      "question": "Si reduces una demanda que no es la máxima, ¿qué puede pasar con X máxima?",
      "answers": [
        "Mejora siempre igual",
        "Se duplica seguro",
        "Se vuelve infinita",
        "Puede no mejorar"
      ],
      "correct": 3,
      "explanation": "Si el cuello sigue siendo otro recurso, la productividad máxima puede no cambiar."
    },
    {
      "question": "¿En qué nivel se conocen utilizaciones por cargas significativas?",
      "answers": [
        "Nivel 1",
        "Nivel 3",
        "Nivel 5",
        "Nivel 2"
      ],
      "correct": 3,
      "explanation": "El nivel 2 conoce exactamente las utilizaciones causadas por cargas importantes."
    },
    {
      "question": "¿Qué diferencia hay entre servidor lento y recurso cuello?",
      "answers": [
        "El cuello depende de demanda total",
        "Todo servidor lento es cuello",
        "El cuello no recibe visitas",
        "La lentitud no importa nunca"
      ],
      "correct": 0,
      "explanation": "Un recurso lento solo limita si su demanda total lo hace dominante."
    },
    {
      "question": "¿En qué nivel se predicen automáticamente los SLA o niveles de servicio?",
      "answers": [
        "Nivel 4",
        "Nivel 1",
        "Nivel 2",
        "Nivel 3"
      ],
      "correct": 0,
      "explanation": "El nivel 4 predice niveles de servicio a partir de predicciones de capacidad."
    },
    {
      "question": "Si una estación de retardo tiene muchos clientes, ¿por qué no genera cola?",
      "answers": [
        "Los clientes desaparecen",
        "Hay servidores infinitos modelados",
        "S vale siempre cero",
        "No existe tiempo de residencia"
      ],
      "correct": 1,
      "explanation": "El modelo de retardo asigna un servidor a cada cliente, por eso no espera."
    },
    {
      "question": "¿En qué nivel entran criterios de aplicaciones de negocio?",
      "answers": [
        "Nivel 2",
        "Nivel 5",
        "Nivel 3",
        "Nivel 4"
      ],
      "correct": 1,
      "explanation": "El nivel 5 incorpora criterios de aplicaciones de negocio mediante un modelo."
    },
    {
      "question": "¿Qué error conceptual hay en confundir tasa de llegada y productividad?",
      "answers": [
        "Siempre son opuestas",
        "Una mide coste",
        "Solo coinciden en equilibrio",
        "Nunca tienen unidades"
      ],
      "correct": 2,
      "explanation": "λ y X pueden igualarse bajo flujo equilibrado, pero conceptualmente no son lo mismo."
    },
    {
      "question": "Si una empresa solo revisa recursos cada cierto tiempo con picos, ¿qué nivel encaja?",
      "answers": [
        "Nivel 0",
        "Nivel 4",
        "Nivel 1",
        "Nivel 5"
      ],
      "correct": 2,
      "explanation": "Las revisiones periódicas con medidas de tendencia corresponden al nivel 1."
    },
    {
      "question": "Si X del sistema sube, ¿qué pasa necesariamente con Xi de un recurso visitado Vk veces?",
      "answers": [
        "Baja siempre",
        "Se hace cero",
        "Depende solo de Z",
        "Sube proporcionalmente a Vk"
      ],
      "correct": 3,
      "explanation": "Por flujo forzado, la productividad del recurso depende de las visitas y del flujo global."
    },
    {
      "question": "Si una empresa sabe qué carga consume cada recurso, ¿qué nivel encaja?",
      "answers": [
        "Nivel 0",
        "Nivel 1",
        "Nivel 5",
        "Nivel 2"
      ],
      "correct": 3,
      "explanation": "Conocer utilizaciones por carga significativa corresponde al nivel 2."
    },
    {
      "question": "Si una interacción visita dos veces el disco, ¿cómo afecta a la demanda del disco?",
      "answers": [
        "Duplica el servicio acumulado",
        "Elimina la cola",
        "Reduce S a cero",
        "No afecta a D"
      ],
      "correct": 0,
      "explanation": "Más visitas multiplican el tiempo total que se exige al recurso."
    },
    {
      "question": "Si una empresa analiza carga en tiempo real y actúa, ¿qué nivel encaja?",
      "answers": [
        "Nivel 3",
        "Nivel 1",
        "Nivel 2",
        "Nivel 5"
      ],
      "correct": 0,
      "explanation": "El análisis automático de carga en ejecución encaja con el nivel 3."
    },
    {
      "question": "¿Qué conclusión es más fuerte si CPU y disco están ambos al 95%?",
      "answers": [
        "Solo CPU es cuello",
        "Puede ser sobrecarga general",
        "Solo disco es cuello",
        "No hay saturación"
      ],
      "correct": 1,
      "explanation": "Si varios recursos están muy cargados, puede no haber un único cuello claro."
    },
    {
      "question": "Si una empresa traduce capacidad prevista a SLA previstos, ¿qué nivel encaja?",
      "answers": [
        "Nivel 0",
        "Nivel 4",
        "Nivel 1",
        "Nivel 2"
      ],
      "correct": 1,
      "explanation": "El nivel 4 automatiza la predicción de niveles de servicio desde capacidad."
    },
    {
      "question": "Si una mejora de CPU no cambia R, ¿qué hipótesis gana fuerza?",
      "answers": [
        "CPU era el único cuello",
        "No había E/S",
        "El cuello estaba en otro recurso",
        "N era cero"
      ],
      "correct": 2,
      "explanation": "Si mejorar un recurso no mejora respuesta, probablemente no era el limitante principal."
    },
    {
      "question": "Si una empresa usa objetivos del negocio en el modelo, ¿qué nivel encaja?",
      "answers": [
        "Nivel 1",
        "Nivel 2",
        "Nivel 5",
        "Nivel 3"
      ],
      "correct": 2,
      "explanation": "El nivel 5 conecta criterios de negocio con predicción de niveles de servicio."
    },
    {
      "question": "Si al mejorar disco baja R y sube X, ¿qué sugiere?",
      "answers": [
        "Z era demasiado alto",
        "La red era abierta imposible",
        "No existían colas",
        "Disco era cuello relevante"
      ],
      "correct": 3,
      "explanation": "Mejorar el recurso limitante debe reducir esperas y permitir más flujo."
    },
    {
      "question": "¿Qué idea general reflejan los seis niveles?",
      "answers": [
        "Más coste siempre",
        "Menos medición progresiva",
        "Menos automatización",
        "Mayor sofisticación progresiva"
      ],
      "correct": 3,
      "explanation": "Los niveles ordenan la madurez de la gestión y planificación de capacidad."
    },
    {
      "question": "¿Qué significa que el análisis asintótico sea preliminar?",
      "answers": [
        "Da cotas, no detalle exacto",
        "Sustituye toda medición",
        "Evita modelar demandas",
        "Solo sirve para costes"
      ],
      "correct": 0,
      "explanation": "Los límites orientan rápidamente, pero no reemplazan un análisis detallado."
    },
    {
      "question": "Si una organización no mide nada y solo reacciona a crisis, ¿qué nivel encaja?",
      "answers": [
        "Nivel 0",
        "Nivel 2",
        "Nivel 4",
        "Nivel 5"
      ],
      "correct": 0,
      "explanation": "El nivel 0 carece de programa formal y la gestión es ocasional."
    },
    {
      "question": "¿Qué trampa hay en usar solo utilización para decidir upgrades?",
      "answers": [
        "Siempre identifica el cuello",
        "No muestra demanda futura",
        "No se puede medir",
        "Es una variable económica"
      ],
      "correct": 1,
      "explanation": "Una U actual alta ayuda, pero la planificación debe mirar demandas y crecimiento."
    },
    {
      "question": "Si una organización revisa picos cada trimestre, ¿qué nivel encaja?",
      "answers": [
        "Nivel 0",
        "Nivel 1",
        "Nivel 4",
        "Nivel 5"
      ],
      "correct": 1,
      "explanation": "El nivel 1 incluye medidas de tendencia, picos y revisiones periódicas."
    },
    {
      "question": "Si una estación tiene U baja pero D alta en una carga que crecerá, ¿qué conviene vigilar?",
      "answers": [
        "No puede saturarse",
        "Debe eliminarse",
        "Puede ser cuello futuro",
        "No recibe trabajos"
      ],
      "correct": 2,
      "explanation": "Con más carga, una demanda alta puede convertirla en limitante aunque hoy no lo sea."
    },
    {
      "question": "Si una organización sabe qué aplicación consume cada servidor, ¿qué nivel encaja?",
      "answers": [
        "Nivel 1",
        "Nivel 4",
        "Nivel 2",
        "Nivel 5"
      ],
      "correct": 2,
      "explanation": "El nivel 2 conoce utilizaciones exactas por recurso y carga significativa."
    },
    {
      "question": "¿Qué ocurre si todos los trabajos no son homogéneos como asume el modelo?",
      "answers": [
        "El modelo mejora solo",
        "Little deja de existir",
        "X se vuelve coste",
        "El modelo pierde precisión"
      ],
      "correct": 3,
      "explanation": "La hipótesis de trabajos similares simplifica; si no se cumple, el modelo aproxima peor."
    },
    {
      "question": "Si hay análisis automático de carga pero no predicción automática de SLA, ¿qué nivel encaja mejor?",
      "answers": [
        "Nivel 2",
        "Nivel 4",
        "Nivel 5",
        "Nivel 3"
      ],
      "correct": 3,
      "explanation": "El nivel 3 introduce análisis y predicción automática de la carga."
    },
    {
      "question": "Si un sistema mezcla batch y transacciones web, ¿qué modelo encaja?",
      "answers": [
        "Red mixta",
        "Solo cerrada",
        "Solo retardo",
        "Solo batch"
      ],
      "correct": 0,
      "explanation": "Batch es cerrado y transacciones son abiertas, por lo que encaja una red mixta."
    },
    {
      "question": "Si el sistema predice si incumplirá el tiempo de respuesta, ¿qué nivel encaja?",
      "answers": [
        "Nivel 4",
        "Nivel 1",
        "Nivel 2",
        "Nivel 3"
      ],
      "correct": 0,
      "explanation": "El nivel 4 predice niveles de servicio desde capacidad prevista."
    },
    {
      "question": "¿Qué significa que un modelo cerrado no tenga salidas externas reales?",
      "answers": [
        "No se completan nunca",
        "Los trabajos recirculan",
        "No hay productividad",
        "No hay respuesta"
      ],
      "correct": 1,
      "explanation": "Los trabajos completan ciclos y vuelven a entrar conceptualmente."
    },
    {
      "question": "Si el modelo usa prioridades del negocio, ¿qué nivel encaja?",
      "answers": [
        "Nivel 2",
        "Nivel 5",
        "Nivel 3",
        "Nivel 4"
      ],
      "correct": 1,
      "explanation": "El nivel 5 incorpora criterios de aplicaciones de negocio."
    },
    {
      "question": "Si en batch N aumenta por debajo de N*, ¿qué suele dominar R?",
      "answers": [
        "Coste del SLA",
        "Predicción cualitativa",
        "Demandas sin colas",
        "Alfa de suavizado"
      ],
      "correct": 2,
      "explanation": "Antes de saturar, el tiempo se aproxima al servicio requerido sin esperas importantes."
    },
    {
      "question": "¿Qué salto conceptual hay de nivel 3 a nivel 4?",
      "answers": [
        "De nada a picos",
        "De negocio a coste",
        "De carga a servicio",
        "De SLA a PDF"
      ],
      "correct": 2,
      "explanation": "Nivel 3 predice carga; nivel 4 predice niveles de servicio."
    },
    {
      "question": "Si N supera mucho N*, ¿qué domina R?",
      "answers": [
        "Tiempo de reflexión",
        "Coste de compra",
        "Media móvil",
        "Esperas en el cuello"
      ],
      "correct": 3,
      "explanation": "Tras saturación, las colas del recurso limitante dominan el tiempo de respuesta."
    },
    {
      "question": "¿Qué salto conceptual hay de nivel 4 a nivel 5?",
      "answers": [
        "De medición a nada",
        "De picos a revisiones",
        "De coste a CPU",
        "De servicio técnico a negocio"
      ],
      "correct": 3,
      "explanation": "Nivel 5 añade criterios de aplicaciones de negocio al modelo."
    },
    {
      "question": "Si el cuello tiene D=0,5, ¿cuál es el máximo flujo ideal?",
      "answers": [
        "2 trabajos/s",
        "0,5 trabajos/s",
        "5 trabajos/s",
        "50 trabajos/s"
      ],
      "correct": 0,
      "explanation": "El flujo máximo ideal por cuello es aproximadamente 1/D = 2."
    },
    {
      "question": "Si un SLA exige 99% disponibilidad, ¿qué decisión de capacidad implica?",
      "answers": [
        "Dimensionar para cumplirlo",
        "Ignorarlo si X sube",
        "Usar solo opiniones",
        "Evitar monitorizar"
      ],
      "correct": 0,
      "explanation": "Los SLA son objetivos que condicionan configuración y capacidad."
    },
    {
      "question": "¿Qué indica que el límite superior de X sea plano?",
      "answers": [
        "No hay demanda",
        "Hay cuello que fija máximo",
        "Z es infinito",
        "No hay recursos"
      ],
      "correct": 1,
      "explanation": "La meseta de productividad indica capacidad máxima limitada por el cuello."
    },
    {
      "question": "Si una alternativa cumple SLA pero cuesta el doble, ¿qué falta evaluar?",
      "answers": [
        "Solo color de la web",
        "Coste total frente a beneficio",
        "Número de opciones",
        "Longitud del PDF"
      ],
      "correct": 1,
      "explanation": "La capacidad adecuada también debe respetar límites económicos."
    },
    {
      "question": "¿Qué indica que el límite inferior de R crezca con N?",
      "answers": [
        "Baja la demanda",
        "No hay clientes",
        "Aumenta el trabajo total",
        "X es negativo"
      ],
      "correct": 2,
      "explanation": "Con más clientes, incluso las cotas de respuesta pueden crecer por reparto de capacidad."
    },
    {
      "question": "Si una alternativa barata incumple R, ¿por qué no es adecuada?",
      "answers": [
        "Tiene menor TCO siempre",
        "Usa pocos datos",
        "No cumple nivel de servicio",
        "Tiene menos opciones"
      ],
      "correct": 2,
      "explanation": "La capacidad adecuada exige cumplir los SLA continuamente."
    },
    {
      "question": "¿Cuál es la trampa en 'más servidores siempre mejora'?",
      "answers": [
        "Siempre duplica X",
        "Siempre reduce Dtotal",
        "Nunca afecta R",
        "Solo mejora si toca el cuello"
      ],
      "correct": 3,
      "explanation": "Añadir capacidad a un recurso no limitante puede no mejorar el rendimiento global."
    },
    {
      "question": "¿Qué trampa hay en mirar solo coste inicial?",
      "answers": [
        "Mide demasiado servicio",
        "Incluye mantenimiento",
        "Predice mejor la carga",
        "Ignora costes de operación"
      ],
      "correct": 3,
      "explanation": "El TCO incluye costes de arranque y de explotación."
    },
    {
      "question": "Si CPU es cuello, ¿qué opción no ataca directamente el cuello?",
      "answers": [
        "Mejorar solo el disco",
        "CPU más rápida",
        "Reducir servicio CPU",
        "Mover trabajo de CPU"
      ],
      "correct": 0,
      "explanation": "Mejorar un recurso que no limita no resuelve directamente el cuello."
    },
    {
      "question": "Si dos arquitecturas rinden igual, ¿qué criterio puede decidir?",
      "answers": [
        "Facilidad de administración",
        "Longitud del nombre",
        "Número de preguntas",
        "Orden del temario"
      ],
      "correct": 0,
      "explanation": "La arquitectura depende también de experiencia, madurez y administración."
    },
    {
      "question": "Si un sistema tiene muchos usuarios pensando, ¿por qué X puede ser bajo?",
      "answers": [
        "CPU siempre falla",
        "Z reduce demanda activa",
        "Disco siempre satura",
        "Little no aplica"
      ],
      "correct": 1,
      "explanation": "El tiempo de reflexión baja la frecuencia de peticiones al sistema."
    },
    {
      "question": "Si el aplicativo exige una tecnología concreta, ¿qué factor domina?",
      "answers": [
        "Media móvil",
        "Arquitectura compatible",
        "Nivel 0",
        "Respuesta aleatoria"
      ],
      "correct": 1,
      "explanation": "Las exigencias de la aplicación condicionan la arquitectura seleccionada."
    },
    {
      "question": "¿Qué dato necesitas para pasar de Xi a Ui?",
      "answers": [
        "Z del usuario",
        "TCO total",
        "Si del recurso",
        "SLA escrito"
      ],
      "correct": 2,
      "explanation": "La utilización del recurso se calcula como Ui = Xi * Si."
    },
    {
      "question": "Si no hay datos históricos fiables, ¿qué predicción es más defendible?",
      "answers": [
        "Regresión exacta",
        "Media móvil precisa",
        "Cualitativa apoyada en expertos",
        "Suavizado seguro"
      ],
      "correct": 2,
      "explanation": "Sin histórico fiable, las técnicas cuantitativas pierden base."
    },
    {
      "question": "¿Qué dato necesitas para pasar de X global a Xi?",
      "answers": [
        "B del intervalo",
        "Coste anual",
        "Nivel de gestión",
        "Vk del recurso"
      ],
      "correct": 3,
      "explanation": "Por flujo forzado, Xi depende del número de visitas Vk."
    },
    {
      "question": "Si hay tendencia lineal clara y datos fiables, ¿qué técnica probarías?",
      "answers": [
        "Solo Delphi",
        "Upgrading",
        "MVA cerrado",
        "Regresión lineal"
      ],
      "correct": 3,
      "explanation": "La regresión lineal es apropiada para datos no estacionales con tendencia lineal."
    },
    {
      "question": "Si hay datos estacionarios con poco ruido, ¿qué técnica simple probarías?",
      "answers": [
        "Medias móviles",
        "Regresión forzada",
        "Nivel 5",
        "TCO"
      ],
      "correct": 0,
      "explanation": "Las medias móviles encajan con datos casi estacionarios."
    },
    {
      "question": "Si los datos recientes importan más que los antiguos, ¿qué técnica encaja?",
      "answers": [
        "Regresión sin tendencia",
        "Suavizado exponencial",
        "Upgrading",
        "Ley de Little"
      ],
      "correct": 1,
      "explanation": "El suavizado exponencial pondera más las observaciones recientes."
    },
    {
      "question": "Si una serie tiene estacionalidad semanal, ¿qué riesgo hay con media móvil simple?",
      "answers": [
        "Mejorar siempre",
        "Eliminar ruido exacto",
        "Ocultar el patrón",
        "Convertirla en SLA"
      ],
      "correct": 2,
      "explanation": "Una media móvil simple puede suavizar y ocultar patrones estacionales importantes."
    },
    {
      "question": "Si la campaña de marketing cambia el patrón histórico, ¿qué debes hacer?",
      "answers": [
        "Mantenerlo sin mirar",
        "Borrar el SLA",
        "Usar N*",
        "Revalidar el modelo"
      ],
      "correct": 3,
      "explanation": "Un cambio de patrón puede invalidar predicciones basadas en datos antiguos."
    },
    {
      "question": "Si el ECM baja al cambiar n, ¿qué indica?",
      "answers": [
        "Mejor ajuste histórico",
        "Peor predicción segura",
        "Sin datos suficientes",
        "Saturación automática"
      ],
      "correct": 0,
      "explanation": "Menor error cuadrático medio indica mejor comportamiento sobre los datos de validación."
    },
    {
      "question": "Si n es muy pequeño en media móvil, ¿qué problema aparece?",
      "answers": [
        "Respuesta muy lenta",
        "Exceso de sensibilidad",
        "Sin datos recientes",
        "No hay predicción"
      ],
      "correct": 1,
      "explanation": "Una ventana pequeña sigue demasiado el ruido."
    },
    {
      "question": "Si n es muy grande, ¿qué problema aparece?",
      "answers": [
        "Ruido máximo",
        "Sin histórico",
        "Reacción lenta",
        "Más SLA"
      ],
      "correct": 2,
      "explanation": "Una ventana grande suaviza, pero tarda en adaptarse a cambios."
    },
    {
      "question": "Si alfa es alto, ¿qué ocurre ante un pico reciente?",
      "answers": [
        "La predicción ignora el pico",
        "La serie se vuelve lineal",
        "El SLA desaparece",
        "La predicción cambia más"
      ],
      "correct": 3,
      "explanation": "Un alfa alto da mucho peso a observaciones recientes."
    },
    {
      "question": "Si alfa es bajo, ¿qué ocurre ante un pico aislado?",
      "answers": [
        "Se amortigua más",
        "Domina totalmente",
        "Anula el histórico",
        "Crea nivel 5"
      ],
      "correct": 0,
      "explanation": "Un alfa bajo suaviza más y reduce el efecto de cambios bruscos."
    },
    {
      "question": "Si una NFU crece pero el consumo por NFU baja, ¿qué no puedes asumir?",
      "answers": [
        "Que no habrá carga",
        "Que recursos crecen igual",
        "Que SLA no importa",
        "Que no hay predicción"
      ],
      "correct": 1,
      "explanation": "La relación entre NFU y recursos debe cuantificarse, no asumirse lineal siempre."
    },
    {
      "question": "Si empleados suben 20%, ¿qué pregunta técnica haces?",
      "answers": [
        "Color de nómina",
        "Número de letras",
        "Consumo por empleado",
        "Nivel del PDF"
      ],
      "correct": 2,
      "explanation": "La NFU debe traducirse a demanda de recursos mediante una relación de consumo."
    },
    {
      "question": "Si pedidos/día es NFU, ¿qué carga derivada interesa?",
      "answers": [
        "Coste del monitor",
        "Tamaño del aula",
        "Color de botones",
        "Transacciones de la app"
      ],
      "correct": 3,
      "explanation": "La variable de negocio debe conectarse con actividad técnica del sistema."
    },
    {
      "question": "Si autoscaling tarda demasiado en actuar, ¿qué SLA peligra?",
      "answers": [
        "Tiempo de respuesta",
        "Nombre del modelo",
        "Número de niveles",
        "Coste inicial"
      ],
      "correct": 0,
      "explanation": "Si se asigna capacidad tarde, los usuarios pueden sufrir respuesta excesiva."
    },
    {
      "question": "Si capacidad bajo demanda añade recursos ante picos, ¿qué busca mantener?",
      "answers": [
        "Número de opciones",
        "Nivel de servicio",
        "Coste inicial fijo",
        "Tasa de visita"
      ],
      "correct": 1,
      "explanation": "La asignación dinámica intenta cumplir los acuerdos de servicio."
    },
    {
      "question": "Si varias apps comparten servidores, ¿qué ventaja aparece?",
      "answers": [
        "Más aislamiento rígido",
        "Menos flexibilidad",
        "Mejor uso de infrautilizados",
        "Sin necesidad de SLA"
      ],
      "correct": 2,
      "explanation": "La gestión compartida puede reasignar recursos ociosos a cargas con demanda."
    },
    {
      "question": "¿Qué riesgo tiene aislar siempre aplicaciones en servidores fijos?",
      "answers": [
        "Más elasticidad",
        "Pago exacto",
        "Predicción perfecta",
        "Infrautilización"
      ],
      "correct": 3,
      "explanation": "La rigidez puede dejar servidores ociosos mientras otros necesitan capacidad."
    },
    {
      "question": "Si se paga por consumo, ¿qué problema se reduce?",
      "answers": [
        "Sobredimensionamiento inicial",
        "Necesidad de medir",
        "Existencia de SLA",
        "Variación de carga"
      ],
      "correct": 0,
      "explanation": "El pago bajo demanda evita comprar toda la capacidad máxima por adelantado."
    },
    {
      "question": "Si el proveedor externo no garantiza SLA, ¿qué falla?",
      "answers": [
        "Necesidad de datos",
        "Confianza en externalización",
        "Existencia de carga",
        "Uso de predicción"
      ],
      "correct": 1,
      "explanation": "La externalización es aceptable si se garantiza el cumplimiento de niveles de servicio."
    },
    {
      "question": "Si la herramienta no se integra con gestión existente, ¿qué riesgo hay?",
      "answers": [
        "Más exactitud segura",
        "SLA automático",
        "Operación más difícil",
        "Menor necesidad de datos"
      ],
      "correct": 2,
      "explanation": "La integración con otras herramientas es un criterio de selección."
    },
    {
      "question": "Si quieres saber un umbral con meses de antelación, ¿qué importa?",
      "answers": [
        "Solo alfa actual",
        "Z de usuarios",
        "Dmax del disco",
        "Horizonte de predicción"
      ],
      "correct": 3,
      "explanation": "La herramienta debe anticipar con el margen temporal requerido."
    },
    {
      "question": "Si solo necesitas reaccionar en ejecución, ¿qué enfoque encaja?",
      "answers": [
        "Capacidad bajo demanda",
        "Plan anual manual",
        "Nivel 0",
        "TCO estático"
      ],
      "correct": 0,
      "explanation": "La capacidad bajo demanda determina rendimiento y actúa durante la ejecución."
    },
    {
      "question": "Si una predicción cumple capacidad pero incumple SLA, ¿qué conclusión sacas?",
      "answers": [
        "La alternativa es adecuada",
        "La capacidad técnica no basta",
        "No hace falta servicio",
        "El coste desaparece"
      ],
      "correct": 1,
      "explanation": "La planificación debe garantizar niveles de servicio, no solo recursos disponibles."
    },
    {
      "question": "Si el rendimiento mejora pero el coste rompe presupuesto, ¿qué conclusión sacas?",
      "answers": [
        "Siempre debe elegirse",
        "El SLA sobra",
        "No es capacidad adecuada",
        "No hay alternativa"
      ],
      "correct": 2,
      "explanation": "La capacidad adecuada exige cumplir servicio dentro de límites de coste."
    },
    {
      "question": "Si se mide utilización solo en horas valle, ¿qué se subestima?",
      "answers": [
        "Coste inicial",
        "Número de niveles",
        "Valor de alfa",
        "Riesgo en periodos pico"
      ],
      "correct": 3,
      "explanation": "La planificación debe considerar cargas pico, no solo momentos tranquilos."
    }
  ]
};
