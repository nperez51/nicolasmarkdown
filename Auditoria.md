# Botium Toys auditoria de seguridad
## _Esto corresponde a un escenario ficticio_



>Resumen: Realizar una auditoría del programa de ciberseguridad de Botium Toys con el propósito de alinear las políticas comerciales actuales con las prácticas recomendadas y los estándares de la industria. El objetivo de la auditoría es proporcionar recomendaciones de mitigación para las vulnerabilidades encontradas que sean clasificadas como de “alto riesgo” y presentar una estrategia general para mejorar la postura de seguridad de la organización. El equipo de auditoría se encargará de documentar los hallazgos, crear soluciones y comunicarse con las partes interesadas.

## Se utilizaran

- Categorías de control
- Lista de cumplimiento normativo


# __Categorias de control__


#### Activos actuales
Entre los activos administrados por el departamento de TI se encuentran los siguientes: 

- Equipos en las instalaciones para las necesidades comerciales en la oficina.  
- Equipos del personal: dispositivos de usuario final (computadoras de escritorio/portátiles, teléfonos inteligentes), estaciones de trabajo remotas, auriculares, cables, teclados, mouse, estaciones de acoplamiento, cámaras de vigilancia, etc.
- Gestión de sistemas, software y servicios: contabilidad, telecomunicaciones, bases de datos, seguridad, comercio electrónico y gestión de inventario.
- Acceso a Internet.
- Red interna.
- Gestión de acceso a proveedores.
- Servicios de alojamiento del centro de datos.  
- Retención y almacenamiento de datos.
- Lectores de tarjetas de identificación.
- Mantenimiento de sistemas heredados: sistemas obsoletos que requieren supervisión humana. 


|**Controles administrativos**||||
| :-: | :- | :- | :- |
|**Nombre de control**|**Tipo de control y explicación**|**Se tiene que implementar (X)**|**Prioridad**|
|Principio de mínimo privilegio|Preventivo. Reducir el riesgo asegurándose de que proveedores y el personal no autorizado solo tengan acceso a los activos/datos que necesitan para realizar su trabajo.|X|Alta|
|Planes de recuperación ante incidentes|Correctivo. Garantizar la continuidad del negocio, asegurando que los sistemas puedan ejecutarse en caso de incidentes, que no haya pérdida de productividad por tiempo de inactividad ni impacto en los componentes del sistema, que incluyen entorno de la sala de computadoras (aire acondicionado, fuentes de alimentación, etc.), hardware (servidores, equipos de empleados), conectividad (red interna, inalámbrica), aplicaciones (correo electrónico, datos electrónicos), así como datos y restauración.|X|Alta|
|Políticas de contraseñas|Preventivo. Establecer requisitos de seguridad de contraseñas para reducir la probabilidad de comprometer la cuenta debido a técnicas de ataque por fuerza bruta o diccionario.|X|Alta|
|Políticas de control de acceso|Preventivo. Aumentar la confidencialidad e integridad de los datos.|X|Alta|
|Políticas de gestión de cuentas|Preventivo. Reducir la superficie expuesta a ataques y limita el impacto general de ex empleados/as disconformes.|X|Media|
|Separación de funciones|Preventivo. Garantizar que nadie tenga tanto acceso que pueda abusar del sistema para obtener beneficios personales.|X|Alta|





|**Controles técnicos**||||
| :-: | :- | :- | :- |
|**Nombre de control**|**Tipo de control y explicación**|**Se tiene que implementar****(X)**|**Prioridad**|
|Cortafuegos (firewall)|Preventivo. Ya hay instalados firewalls para filtrar el tráfico no deseado/malicioso que ingresa a la red interna.|X|Alta|
|Sistema de detección de intrusiones (IDS)|De detección. Permitir al equipo de TI identificar posibles intrusiones (por ejemplo, tráfico anómalo) rápidamente.|X |Alta|
|Cifrado|Disuasivo. Garantizar que la información y los datos confidenciales sean más seguros (por ejemplo, transacciones de pago en el sitio web).|X|Alta|
|Copias de seguridad|Correctivo. Permitir la continuidad del negocio y mantener la productividad en caso de incidentes, al mantener los sistemas funcionando.|X|Alta|
|Gestión de contraseñas|Correctivo. Recuperar y restablecer contraseñas, bloqueo de notificaciones.|X|Medio|
|Software de antivirus (AV)|Correctivo. Detectar amenazas conocidas y aislarlas.|X|Medio|
|Monitoreo manual, mantenimiento e intervención|Preventivo/correctivo. Necesario para que los sistemas heredados identifiquen y mitiguen posibles amenazas, riesgos y vulnerabilidades.|X|Alta|







|**Controles físicos**||||
| :-: | :- | :- | :- |
|**Nombre de control**|**Tipo de control y explicación****Se tiene que implementar** **(X)**|**Prioridad**|
|Caja fuerte con control de tiempo|Disuasivo. Reducir la superficie expuesta a ataque y el impacto de las amenazas físicas.|N/A|N/A|
|Iluminación adecuada|Disuasivo. Limitar los lugares “ocultos” para disuadir las amenazas.|N/A|N/A|
|Vigilancia del circuito cerrado de televisión (CCTV)|Preventivo/De detección. Reducir el riesgo de ciertos eventos y ver qué sucedió, después del incidente al llevar a cabo una investigación.|X|Alto|
|Cerradura de gabinetes (para equipos de red)|Preventivo. Aumentar la integridad al evitar que personas no autorizadas accedan físicamente o modifiquen el equipo de infraestructura de la red.|X|Alto|
|Carteles que indican el nombre de la empresa proveedora del servicio de alarmas|Disuasivo. Reducir la probabilidad de éxito de ciertos tipos de amenazas al dar la apariencia de que un ataque exitoso es poco probable.|X|Alto|
|Cerraduras|Preventivo. Lograr que los activos físicos y digitales estén más seguros.|X|Alto|
|Detección y prevención de incendios (alarma de incendios, sistema de rociadores, entre otros)|De detección/Preventivo. Detectar incendios en la ubicación física de la juguetería para evitar daños en el inventario, servidores, entre otros.|X|Alto|




# __Lista de control de cumplimiento normativo__


**\_\_\_\_\_ La Comisión Federal de Regulación de Energía, Corporación de Confiabilidad Eléctrica América del Norte (FERC-NERC)**

La normativa FERC-NERC se aplica a organizaciones que trabajan con electricidad o que están involucradas con la red eléctrica de los Estados Unidos y América del Norte. Las empresas tienen la obligación de prepararse, mitigar y reportar cualquier incidente de seguridad potencial que pueda afectar negativamente a la red eléctrica. También están legalmente obligadas a cumplir con los Estándares de Confiabilidad de Protección de Infraestructura Crítica (CIP) definidos por la FERC. 

**Explicación:** El negocio es de otro rubro.

**\_\_\_X\_\_ Reglamento General de Protección de Datos (RGPD)**

El RGPD es una regulación general de datos de la Unión Europea (UE) que protege el procesamiento de los datos de sus residentes y su derecho a la privacidad dentro y fuera del territorio. Además, si se produce una filtración y los datos de una persona se ven comprometidos, esto debe ser informado en un plazo de 72 horas posteriores al incidente.

**Explicación:**  Debe adoptar el marco de seguridad que indica RGPD, debido al crecimiento del negocio, y con el fin de garantizar la continuidad de las operaciones.

**\_\_X\_\_\_ Estándares de seguridad de datos del sector de las tarjetas de pago (PCI DSS)**

PCI DSS es un estándar de seguridad internacional destinado a garantizar que las organizaciones que almacenan, aceptan, procesan y transmiten información de tarjetas de crédito lo hagan en un entorno seguro. 

**Explicación:** Debe adoptar este marco de seguridad con el fin de cumplir la normativa con los clientes europeos, y de esta forma tambien volver mas robusta la seguridad en la operacion.

**\_\_\_\_\_ Ley de Transferencia y Responsabilidad de los Seguros Médicos (HIPAA)**

La HIPAA es una ley federal de los Estados Unidos establecida en 1996 para proteger la información médica de las personas. Esta ley prohíbe que la información de un/a paciente sea compartida sin su consentimiento. Las organizaciones tienen la obligación legal de informar a los/las pacientes en caso de que esta información se filtre. 

**Explicación:** La empresa no está obligada a adoptar este marco de seguridad puesto que no manjea informacion medica de personas.

**\_\_\_X\_\_ Controles de Sistemas y Organizaciones (SOC tipo 1, SOC tipo 2)**

El SOC1 y el SOC2 se enfocan en las políticas de acceso de los usuarios y las usuarias de una organización en los diferentes niveles. Se utilizan para evaluar el cumplimiento financiero de una organización, así como los niveles de riesgo asociados. También abordan aspectos críticos como la confidencialidad, privacidad, integridad, disponibilidad, seguridad y protección general de los datos. Es importante destacar que cualquier falla en el control de estos aspectos puede resultar en posibles fraudes.

**Explicación:** Se debe adoptar este marco de seguridad con el fin de reducir el riesgo de ataques ciberneticos, para demostrar eficacia de controles internos con el fin de proyectar confianza a clientes, socios y reguladores.





