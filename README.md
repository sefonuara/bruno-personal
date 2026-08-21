# bruno-personal
administrador de rutinas online

Cuentas y acceso
* Login con email y contraseña, con botón de mostrar/ocultar
* Registro propio de alumnos (nombre y apellido, email, contraseña con confirmación)
* Recuperar contraseña por mail ("Olvidé mi contraseña")
* Dos roles: profe y alumno, cada uno ve una app distinta
* Seguridad por fila (RLS): un alumno solo puede ver y tocar sus propios datos, aunque intente forzarlo desde afuera de la app

Rutinas — lado profe
Lista de todos los alumnos activos en la barra lateral
Días de rutina: crear, renombrar, eliminar
Reordenar días (subir/bajar) y ejercicios dentro de cada día
Colapsar/expandir cada día (se acuerda por navegador)
Ocultar/mostrar un día puntual al alumno (por si querés prepararlo antes de mostrarlo)
Duplicar un día suelto o la rutina completa a otro(s) alumno(s)
Buscador de ejercicios con gif de demostración (catálogo de ~1300 ejercicios, filtro por nombre / grupo muscular / equipamiento, nombre en español con el original en inglés al lado)
Biserie: unir dos ejercicios adyacentes (fondo distinto, opción de separar)
Campos por ejercicio: nombre, series x reps, peso (texto libre, con historial automático), notas/comentarios
Fecha de inicio de la rutina, editable solo por vos
Exportar la rutina a PDF

Rutinas — lado alumno
Ver solo su propia rutina (y solo los días que vos dejaste visibles)
Cargar su propio peso y notas en cada ejercicio (autoguardado)
Ver historial de peso por ejercicio
Exportar su rutina a PDF
Botón para contactarte por WhatsApp directo
Perfil del alumno (lo carga y edita solo él)
Sexo, fecha de nacimiento, altura, peso corporal, teléfono
Gimnasio al que va (opcional)
Tipo de rutina que le gustaría, con sugerencias (hipertrofia, fuerza, etc.)
Lesiones actuales o pasadas
Días de la semana que va a entrenar
Panel de Administración (solo vos)
Estadísticas generales: activos, al día, adeudan, adelantados, dados de baja
Dar de alta/baja a un alumno
Desplegable con toda la info personal de cada alumno (de solo lectura para vos)
Teléfono y una nota privada tuya por alumno (que el alumno nunca ve)
Gestión de pagos: historial completo por alumno, con estado calculado solo (al día / adeuda / adelantado) según la fecha de alta y los meses que le cargaste
Eliminar un alumno definitivamente (pide tu contraseña para confirmar; borra en cascada toda su rutina, pagos e historial)
General
Modo claro / oscuro, se acuerda la preferencia
Diseño adaptado a celular y a computadora
Deploy como sitio estático en GitHub Pages, con base de datos en Supabase (Postgres)
