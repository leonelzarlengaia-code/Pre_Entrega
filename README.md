Alertas por mail del valor actual del Bitcoin cada 1hs(Workflow configurado con horario de ARGENTINA UTC-3.)
 
El objetivo es el seguimiento del precio de Bitcoin para notificar vía email cuando el valor cae por debajo de un umbral crítico o sube. 
Teniendo como iniciador un nodo Schedule como Trigger. 
A un API PUBLICA de COINGECKO. Que luego pasa por un IF que evaluamos si el valor sube o desciende. 
Se pasa a otro IF y a un Switch. El Switch es de subida el cual tiene diferentes alertas con precios. El IF es para evaluar si la baja es critica. 
Luego están los mails de avisos que al no tener un agente de IA, lo configure con diferentes alertas y avisos. 
Pasan por un merge para generar la hora y tiempo exacto en el que se envia la alerta en un Google Sheet. 
