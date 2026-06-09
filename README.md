# Proyecto: [nombre de tu dominio]

**Alumno:** Tu Nombre Completo  
**Dominio elegido:** restaurante / farmacia / libreria / renta de equipos / ...  
**Curso:** Fundamentos de Sistemas Operativos -- IN235  
**Semestre:** 2026A  
**Instructor:** karlos.espinoza@academicos.udg.mx

---

## Descripcion del dominio

*(Escribe aqui en 2-3 oraciones que tipo de negocio simulara tu servidor
y que tipo de pedidos procesara. Ejemplo: "Mi servidor simula el sistema
de pedidos de una farmacia. Recibe solicitudes de medicamentos desde
multiples cajas registradoras y gestiona el inventario compartido.")*

---

## Como compilar y ejecutar

```bash
cd src
javac ServidorPedidos.java
java ServidorPedidos
```

Debe imprimir `Servidor listo.`

---

## Estructura del proyecto

```
src/
  ServidorPedidos.java   <- servidor principal, crece con cada unidad del curso
catalogo.txt             <- catalogo de productos/servicios de tu dominio
BITACORA.md              <- explicacion semanal de lo aprendido
README.md                <- este archivo
```

---

## Avance por unidad

| Unidad | Tema | Estado |
|---|---|---|
| U1 | El servidor existe como proceso en el SO | pendiente |
| U2 | Hilos y sincronizacion: multiples cajeros simultaneos | pendiente |
| U3 | Cache del catalogo en memoria | pendiente |
| U4 | Lectura del catalogo desde archivo al arrancar | pendiente |
| U5 | Log persistente de pedidos | pendiente |
| U6 | Cajero como cliente que se conecta por socket | pendiente |
