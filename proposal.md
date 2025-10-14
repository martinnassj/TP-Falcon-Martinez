# **Propuesta TP DSW**

## **Grupo**

### **Integrantes**

* 48033 \- Fernández Martina 				  
* 51550	\- Falcon Ramiro 

### **Repositorios**

* [https://github.com/RamiroFalcon/TP-DSW-Front-End.git](https://github.com/RamiroFalcon/TP-DSW-Front-End.git)  
* https://github.com/RamiroFalcon/TPD-DSW-Back-End.git

**Tema**

**Gestor de alquiler de canchas para deportes**

### **Descripción**

*El sistema te permite ver y reservar canchas de distintos deportes de manera rápida y sencilla. Podés registrar clientes, canchas y servicios extras, como así también manejar las reservas. Todo queda organizado para que no haya choques de horarios y los administradores puedan controlar todo sin problemas.*

### **Modelo**

## **Alcance Funcional**

---

### **Alcance Mínimo**

Regularidad:

| Req | Detalle |
| ----- | ----- |
| CRUD simple | 1\. CRUD Tipo de Cancha 2\. CRUD Localidad |
| CRUD dependiente | 1\. CRUD Cancha {depende de} CRUD Tipo de Cancha 2\. CRUD Cliente {depende de} CRUD Localidad 3\. CRUD Reserva {depende de} CRUD Cancha y CRUD Cliente |
| Listado \+ detalle | 1\. Listado de canchas filtradas por tipo de cancha, muestra nro y tipo de cancha  \=\> detalle CRUD cancha 2\. Listado de reservas filtrado por rango de fecha, muestra nro de cancha,  hora de  inicio y fin y nombre del cliente   |
| CUU/Epic | 1\. Reservar una cancha. 2\. Realizar el pago de la reserva. |

Adicionales para Aprobación

| Req | Detalle |
| ----- | ----- |
| CRUD | 1\. CRUD Tipo Cancha 2\. CRUD Servicio 3\. CRUD Localidad 4\. CRUD Provincia 5\. CRUD Cancha 6\. CRUD Usuario |
| CUU/Epic | 1\. Reservar una cancha. 2\. Realizar el pago de la reserva. 3\. Agregar servicios adicionales a la reserva. |

### 

### 

### 

### 

### 

### 

### **Alcance Adicional Voluntario**

| Req | Detalle |
| ----- | ----- |
| Listados | 1\. Listado de canchas reservadas para un determinado dia con hora de inicio y fin, cliente y servicios adicionales. 2\. Listado de clientes mas frecuentes y la cantidad de veces que realizo reservas. |
| CUU/Epic | 1\. Consumir servicios 2\. Cancelación de reserva |
| Otros | 1\. Envío de recordatorio de reserva por email |

