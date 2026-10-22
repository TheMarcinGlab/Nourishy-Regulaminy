# 🛡️ Política de Privacidad de la Aplicación Móvil Nourishy

**Fecha de la última actualización:** 23 de octubre de 2026

---

## 1. Disposiciones generales y Responsable del Tratamiento

* **1.1.** La presente Política de Privacidad establece las reglas, finalidades, bases jurídicas y plazos de tratamiento de los datos personales de los usuarios de la aplicación móvil Nourishy (identificador de la aplicación: `com.nourishy.app`), en adelante denominada la **«Aplicación»**.
* **1.2.** El responsable del tratamiento de los datos personales es una persona física que no ejerce una actividad económica registrada (actividad no registrada en el sentido de la Ley polaca de Empresarios): Marcin Głąb, en adelante denominado el «Responsable».
* **1.3.** Es posible contactar con el Responsable en la dirección de correo electrónico: support@nourishy.eu
* **1.4.** El Responsable declara que trata los datos personales de los usuarios de conformidad con el Reglamento (UE) 2016/679 del Parlamento Europeo y del Consejo, de 27 de abril de 2016 (RGPD), la ley polaca de protección de datos personales y la ley de prestación de servicios por vía electrónica.
* **1.5. Restricción de edad:** La Aplicación está destinada exclusivamente a personas mayores de edad que hayan cumplido **18 años**. El Responsable no recopila, trata ni almacena de forma consciente datos personales, incluidos datos relativos a la salud, de personas menores de 18 años. Si el Responsable tiene conocimiento de que se ha registrado una cuenta por parte de un menor, dicha cuenta, junto con todos los datos asociados, será eliminada de forma inmediata e irreversible de los sistemas de producción en tiempo real.

---

## 📊 2. Categorías y alcance de los datos personales recopilados

Con el fin de permitir el uso de todas las funciones avanzadas de la Aplicación, el Responsable recopila y trata las siguientes categorías de datos personales:

* **2.1. Datos de registro y autenticación:** dirección de correo electrónico, identificador de usuario generado por el sistema Auth0.
* **2.2. Datos de perfil e información sobre la salud (Datos de categoría especial – Art. 9 RGPD):** peso, altura, edad, sexo, nivel de actividad física, preferencias gustativas, cocinas del mundo seleccionadas, objetivos nutricionales (p. ej. reducción de peso, desarrollo muscular) y, sobre todo, **alergias alimentarias, intolerancias y exclusiones dietéticas**.
  > 🧬 **Aviso jurídico:** Estos datos constituyen datos relativos a la salud en el sentido del art. 9, apartado 1, del RGPD. Su tratamiento se realiza exclusivamente sobre la base del consentimiento explícito, separado e informado del usuario, recogido durante el proceso de incorporación (onboarding).
* **2.3. Contenidos del usuario:** las fotografías de comidas enviadas para su análisis por IA se tratan exclusivamente en tiempo real a efectos de la ejecución de la solicitud. El Responsable no utiliza las fotografías privadas de los usuarios para entrenar modelos públicos de IA. Los detalles se establecen en los Términos del Servicio de Nourishy, § 4.2.
* **2.4. Datos de uso y contenido de la aplicación:** información introducida en el marco de la función de nevera virtual (productos poseídos), listas de la compra, historial de planes de comidas generados, preferencias valoradas mediante el método «swipe» y estadísticas de consumo de macronutrientes.
* **2.5. Datos técnicos y de localización:** dirección IP, modelo del dispositivo móvil, versión del sistema operativo (iOS/Android), identificador anónimo de instalación (IDFV), idioma del sistema, token único de notificaciones push y geolocalización (para la sincronización del mercado, la moneda y el país del usuario).
* **2.6. Datos transaccionales y de compra:** estado de la suscripción Premium (p. ej. versión de prueba, suscripción mensual, anual), fecha de compra, fecha de vencimiento e identificador de la transacción generado por el sistema RevenueCat y la tienda móvil.
  > 💳 **Importante:** El Responsable no recopila, trata ni ve los datos de las tarjetas de pago ni los datos bancarios detallados del usuario: los pagos son gestionados íntegramente por Apple App Store o Google Play.

---

## ⚖️ 3. Finalidades y bases jurídicas del tratamiento de datos (RGPD)

Los datos personales de los usuarios son tratados por el Responsable para las siguientes finalidades, sobre la base de las disposiciones del RGPD indicadas:

* **3.1. Prestación de servicios por vía electrónica (Art. 6, apartado 1, letra b, del RGPD):** El tratamiento es necesario para la ejecución del contrato de prestación de servicios (aceptación de los Términos). Esto incluye el registro de la cuenta, el mantenimiento de la sesión (Auth0), el funcionamiento de la nevera virtual, el carrito de la compra, el escáner de códigos de barras y la sincronización lingüística y de mercado basada en la geolocalización.
* **3.2. Tratamiento de datos relativos a la salud (Art. 9, apartado 2, letra a, del RGPD):** El tratamiento de los datos de perfil relativos a la salud, parámetros físicos, alergias y objetivos dietéticos se realiza sobre la base del consentimiento explícito del Usuario, expresado durante el registro/onboarding. La facilitación de estos datos y la expresión del consentimiento son voluntarias, pero **constituyen una condición necesaria (indispensable) para la prestación de los servicios de la Aplicación**. La negativa a prestar el consentimiento impide la creación de la cuenta y el uso de la Aplicación. La retirada del consentimiento en cualquier momento equivale a la imposibilidad de que el Responsable continúe prestando los servicios y conlleva la necesidad de eliminar la Cuenta del Usuario.
* **3.3. Envío de notificaciones push y locales (Art. 6, apartado 1, letra a, del RGPD):** Tratamiento de tokens de dispositivos con el fin de enviar recordatorios sobre comidas, compras o notificaciones del sistema (widgets de la pantalla de inicio) sobre la base del consentimiento del usuario expresado en la configuración del sistema operativo del dispositivo.
* **3.4. Interés legítimo del Responsable (Art. 6, apartado 1, letra f, del RGPD):** Tratamiento de datos técnicos y analíticos con el fin de garantizar la seguridad informática de la Aplicación, detectar errores y fallos (_crash reporting_), optimizar el funcionamiento del sistema, elaborar estadísticas anónimas, así como defenderse frente a eventuales reclamaciones jurídicas (en particular relacionadas con la exclusión de responsabilidad médica) o ejercerlas.

---

## 🤝 4. Destinatarios de los datos y encargados del tratamiento (incluidos los módulos de IA)

Para garantizar el correcto y estable funcionamiento de la Aplicación, el Responsable recurre a proveedores externos especializados. Los datos de los usuarios se encomiendan sobre la base de rigurosos contratos de encargo del tratamiento (DPA) o se comunican a las siguientes entidades:

* **4.1. Auth0 (Okta, Inc.):** Entidad que gestiona el proceso seguro de registro, inicio de sesión, autenticación y gestión de sesiones de los usuarios.
* **4.2. Railway (Railway Corp.):** Entidad que proporciona una infraestructura en la nube segura y bases de datos en las que se aloja la API de la Aplicación y se almacenan los datos cifrados de los usuarios.
* **4.3. Google LLC (Firebase / Firebase Cloud Messaging):** Herramientas analíticas, crash reporting, optimización de UX e infraestructura para el envío de notificaciones push y la gestión de widgets de la pantalla de inicio.
* **4.4. RevenueCat, Inc.:** Entidad que proporciona la infraestructura técnica para la gestión de suscripciones Premium, la validación de recibos y la verificación del estado de los pagos con Apple App Store y Google Play.
* **4.5. Apple Inc. (App Store) y Google LLC (Google Play):** Operadores de las plataformas de distribución que tratan los datos transaccionales y de pago de los usuarios con el fin de realizar la compra de la suscripción Premium.
* **4.6. Proveedores externos de modelos de IA en la nube (p. ej. OpenAI, Anthropic):** Con el fin de analizar imágenes (fotografías de platos, productos alimenticios y tickets) enviadas por el Usuario, se transmiten datos de imagen seudonimizados a proveedores externos de modelos de IA.
  > 🤖 **Seguridad de la IA:** Los datos transmitidos a proveedores externos de IA para el análisis de fotografías están **seudonimizados** (no contienen la dirección de correo electrónico, el nombre ni el apellido del Usuario). Los proveedores externos tratan las imágenes enviadas exclusivamente en tiempo real a efectos de la ejecución de la solicitud y no las utilizan para entrenar sus propios modelos públicos.

---

## 🌐 5. Transferencia de datos fuera del Espacio Económico Europeo (EEE)

* **5.1.** Debido al uso de servicios de proveedores tecnológicos globales ubicados en los Estados Unidos (EE. UU.), los datos personales de los usuarios pueden transferirse y almacenarse fuera del EEE.
* **5.2.** El Responsable vela por que la transferencia de datos se realice de forma totalmente legal y segura. Las entidades ubicadas en EE. UU. cuyos servicios utiliza el Responsable (incluidos Okta/Auth0, Google, RevenueCat, OpenAI) participan en el programa *EU-U.S. Data Privacy Framework* (Marco de Protección de Datos), lo que significa que el grado de protección de los datos en dichas empresas ha sido reconocido por la Comisión Europea como adecuado y seguro.
* **5.3.** En los casos en que el programa *Data Privacy Framework* no sea de aplicación, la base de la transferencia son las Cláusulas Contractuales Tipo (SCC) aprobadas por la Comisión Europea, complementadas con medidas técnicas avanzadas (cifrado de datos en reposo y en tránsito).

---

## ⏱️ 6. Plazo de conservación de los datos personales

* **6.1.** Los datos personales vinculados a la Cuenta del Usuario se tratan durante todo el período de actividad de la cuenta, es decir, durante la vigencia del contrato de prestación de servicios por vía electrónica.
* **6.2.** En caso de que el usuario decida eliminar la cuenta (mediante la opción en la sección Perfil → Ajustes → Eliminar cuenta), sus datos personales se eliminan de forma permanente e irreversible en tiempo real de la base de datos de producción.
* **6.3.** Tras la eliminación de la cuenta, el Responsable se reserva el derecho de conservar únicamente un alcance estrictamente limitado y anonimizado de datos (p. ej. identificador de la transacción RevenueCat, fecha de inicio de sesión) exclusivamente con el fin de defenderse frente a eventuales reclamaciones jurídicas o fiscales, durante el plazo de prescripción de las reclamaciones derivado de las disposiciones del Código Civil polaco (máximo 6 años).
* **6.4.** Los datos tratados sobre la base del consentimiento (p. ej. datos sobre salud y alergias, notificaciones push) se eliminan inmediatamente tras la retirada de dicho consentimiento por el usuario o la eliminación de la cuenta.

---

## 🔑 7. Derechos del usuario en virtud del RGPD

A todo usuario de la Aplicación le asisten los plenos derechos derivados de las disposiciones del RGPD, que se ejercen contactando con la dirección **support@nourishy.eu**:

* **7.1. Derecho de acceso a los datos y a recibir una copia (Art. 15 RGPD).**
* **7.2. Derecho de rectificación y corrección de los datos (Art. 16 RGPD).**
* **7.3. Derecho de supresión de los datos / «derecho al olvido» (Art. 17 RGPD).**
* **7.4. Derecho a la limitación del tratamiento (Art. 18 RGPD).**
* **7.5. Derecho a la portabilidad de los datos en un formato estructurado (Art. 20 RGPD).**
* **7.6. Derecho de oposición al tratamiento basado en el interés legítimo (Art. 21 RGPD).**
* **7.7. Derecho a retirar el consentimiento para el tratamiento de datos sensibles (Art. 9) en cualquier momento, sin que ello afecte a la licitud del tratamiento anterior a su retirada.**
* **7.8. Derecho a presentar una reclamación ante la autoridad de control.** En Polonia, dicha autoridad es el **Presidente de la Oficina de Protección de Datos Personales (PUODO)**, ul. Stawki 2, 00-193 Varsovia.

---

## ⚙️ 8. Procedimiento de eliminación de la cuenta y Suscripciones

* **8.1.** El inicio del procedimiento de eliminación de la cuenta en la aplicación provoca la eliminación automática, inmediata e irreversible de la dirección de correo electrónico, los datos de perfil (incluidas las alergias y los parámetros de salud), el historial de planes de comidas y las fotografías de los servidores y bases de datos asociados a la Aplicación.
* **8.2.**
  > ⚠️ **Información clave para el consumidor:** La eliminación autónoma de la cuenta en la Aplicación **no provoca la cancelación automática de una suscripción Premium activa** en Apple App Store o Google Play. Por motivos técnicos y jurídicos dependientes de los operadores de las tiendas móviles, el usuario tiene la obligación absoluta de cancelar la suscripción de forma independiente en la configuración de su dispositivo antes de eliminar la cuenta. En caso contrario, Apple/Google seguirán cobrando las cuotas. Para evitar la renovación automática de la suscripción en dispositivos iOS, se debe acceder a: Ajustes del sistema iOS → [Tu Nombre y Apellido / Cuenta de Apple] → Suscripciones → Nourishy → Cancelar suscripción, al menos 24 horas antes del final del período de facturación actual.

---

## 🔒 9. Seguridad de los datos personales

* **9.1.** El Responsable aplica medidas técnicas y organizativas avanzadas para garantizar un grado de seguridad adecuado al riesgo de vulneración de los derechos o libertades de los usuarios.
* **9.2.** Toda la comunicación entre la Aplicación móvil y la infraestructura de servidores (API alojada en Railway) está plenamente cifrada mediante el protocolo moderno SSL/TLS (HTTPS).
* **9.3.** Los procesos de autenticación, registro e inicio de sesión están aislados y plenamente protegidos por la plataforma dedicada Auth0, lo que impide el acceso no autorizado a las cuentas de los usuarios.
* **9.4.** Los datos relativos a la salud (alergias, peso, altura) están sujetos a una seudonimización adicional dentro de la base de datos, y el acceso a ellos lo tienen exclusivamente las personas autorizadas vinculadas por la obligación de plena confidencialidad.

---

## 🔄 10. Cambios en la Política de Privacidad

* **10.1.** La presente Política de Privacidad puede actualizarse periódicamente para adaptarla a cambios tecnológicos, nuevas funciones de la Aplicación (p. ej. actualizaciones de modelos de IA), cambios en los proveedores de servicios en la nube o cambios en la legislación internacional (incluido el próximo Reglamento de IA de la UE).
* **10.2.** Los usuarios serán notificados de cualquier modificación sustancial de la Política de Privacidad directamente dentro de la Aplicación (mediante un mensaje dedicado) o a través de un mensaje de correo electrónico.
* **10.3.** El uso de la Aplicación tras la entrada en vigor de los cambios implica su plena aceptación. En caso de desacuerdo con el nuevo contenido de la política, el usuario deberá dejar de utilizar la Aplicación y eliminar su cuenta.
