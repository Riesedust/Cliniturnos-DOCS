### Símbolos:
- PRIMARY KEY: llave amarilla
- FOREIGN KEY: llave azul
- UNIQUE: rombo rosa
- AUTO INCREMENT: + verde
- ENUM: “E” amarilla
- NOT NULLABLE: ‘NN’ azul
- DEFAULT VALUE: “D” naranja

### Unique compuestos (no pude hacerlos en la app):
- pacientes(tipo_identificacion, num_identificacion)
- usuario_rol(usuario_id, rol_id)
- medico_especialidades(medico_id, especialidad_id)
- medico_pacientes(medico_id, paciente_id)
- rol_permisos(rol_id, permiso_id)
- turnos(medico_id, fecha, fecha_hora_inicio)
- (profesional_id, fecha, fecha_hora_inicio) 
