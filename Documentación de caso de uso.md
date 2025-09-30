## Caso de Uso: C1 Reportar perdida
- **Actor principal**: Persona que perdió un objeto
-  **Actores involucrados e intereses:**
	- Persona que perdión el objeto: Ante un perdida, la persona quiere reportarlo, para poder poder si alguién lo encontro.
- **Precondiciónes**: La persona tiene que haber perdido el objeto dentro del campus o debe estar relacionado con la universidad.
- **Postcondiciones**: La persona genera un informe, con sus datos para notificarlo.
- **Escenario principal de éxito** (Flujo Básico):
	1. La persona accede al sistema o acude al centro para notificar el objeto perdido.  
	2. La persona registra sus datos personales y los del objeto perdido (descripción, lugar, fecha).  
	3. El sistema genera un informe del objeto perdido y entrega una copia al solicitante.  
	4. El sistema registra automáticamente el informe en su base de datos.  
	5. El sistema revisa si existe un objeto similar en la base de “objetos encontrados”.  
	6. Si hay coincidencia, se notifica a la persona y se le indica cómo recuperarlo.  
	7. La persona acude al centro y retira el objeto.  
- **Extensiones (Flujos Alternativos)**:
- 2' 
- **3’.** Se detecta que ya existe un informe similar o duplicado; el sistema muestra la coincidencia y pregunta, y se pregunta si es el mismo objeto
- 4' El objeto no fue encontrado durante mucho tiempo
## Caso de Uso: C1 – Reportar pérdida  

**Actor Principal:**  
- Persona que perdió un objeto  

**Actores Involucrados e Intereses:**  
- **Persona que perdió el objeto:** quiere reportar el objeto perdido para aumentar las posibilidades de recuperarlo si alguien lo encuentra.  
- **Sistema / Centro de objetos perdidos:** recibe, registra y gestiona los reportes e informes para su seguimiento.  

**Precondiciones:**  
- El objeto se perdió dentro del campus o está relacionado con la universidad.  
- El sistema o centro de objetos perdidos se encuentra disponible.  

**Postcondiciones:**  
- Se genera un informe con los datos del objeto y del solicitante.  
- El informe queda registrado en el sistema.  
- La persona recibe confirmación del reporte (copia del informe).  

### Escenario Principal de Éxito (Flujo Básico):  

1. La persona accede al sistema o acude al centro para notificar el objeto perdido.  
2. La persona registra sus datos personales y los del objeto perdido (descripción, lugar, fecha).  
3. El sistema genera un informe del objeto perdido y entrega una copia al solicitante.  
4. El sistema registra automáticamente el informe en su base de datos.  
5. El sistema revisa si existe un objeto similar en la base de “objetos encontrados”.  
6. Si hay coincidencia, se notifica a la persona y se le indica cómo recuperarlo.  
7. La persona acude al centro y retira el objeto.  

### Extensiones (Flujos Alternativos):  

- **2’.** La persona no tiene toda la información del objeto; el sistema permite guardar un reporte parcial para completarlo más tarde.  

- **3’.** Se detecta que ya existe un informe similar o duplicado; el sistema muestra la coincidencia y pregunta si desea vincularse a ese reporte existente.  

- **4’.** Si el objeto no se encuentra durante un periodo prolongado, el sistema envía notificaciones periódicas al solicitante o cierra el caso automáticamente después de cierto tiempo.  

- **6’.** El objeto fue encontrado antes de tiempo por la propia persona, entonces el usario usuario puede cancelar el informe.
**Documentación de caso de uso:**

**Caso de uso:** CU2: Generar informe

**Actor principal:** Administrador de objetos perdidos

**Actores involucrados e intereses:**

- Administrador de objetos perdidos: Ante un reporte de pérdida exitoso, el administrador deja constancia de la situación y documenta lo proporcionado por la persona que perdió un objeto.
    
- Persona que perdió un objeto: proporciona información y detalle de la pérdida a dejar en constancia. Recibe una copia del informe que acredita la situación ante una eventual respuesta.
    

**Precondiciones:** Tener información disponible a documentar.

**Postcondiciones:** Se genera un informe con información del objeto y situación de pérdida/encuentro. La persona que perdió un objeto recibe un informe que acredite su pérdida.

**Escenario principal de éxito (flujo básico):**

1. El administrador de objetos perdidos solicita generar informe.
    
2. El sistema muestra un mensaje de éxito y adjunta informe.
    
3. Se agrega el informe a una lista visible para el administrador.
    

**Extensiones (Flujos alternativos):**

1´. El informe no puede ser generado por datos incorrectos