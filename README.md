# UNIDAD-2-BASE-DE-DATOS-EJERCICIO-16
Se pide diseñar un Modelo Entidad-Relación (MER) para una inmobiliaria, que permita administrar a los propietarios, inquilinos, propiedades, operaciones inmobiliarias, contratos de alquiler y pagos mensuales.

El modelo debe contemplar:

- Personas: registrar DNI/CUIT, nombre y apellido, teléfono y correo electrónico de propietarios e inquilinos.
- Propiedades: almacenar código catastral, dirección, ciudad, tipo de propiedad, superficie, cantidad de ambientes y precio de tasación o alquiler. Cada propiedad pertenece a un único propietario.
- Operaciones inmobiliarias: distinguir entre alquileres (temporarios o permanentes) y ventas.
- Contratos de alquiler: vincular una propiedad con un inquilino, registrando fechas de inicio y finalización, canon mensual, depósito en garantía y agente inmobiliario responsable.
- Agentes inmobiliarios: representar a los empleados que intervienen en las operaciones y cobran comisiones.
- Pagos de alquiler: registrar el período abonado, fecha de pago, monto, medio de pago (transferencia, efectivo o tarjeta) y recargo por mora, si corresponde.

Finalmente, se deben identificar las entidades, sus atributos, las relaciones y las cardinalidades, asegurando que cada propiedad tenga un único propietario y que un contrato de alquiler pueda tener múltiples pagos mensuales asociados.
<img width="1932" height="1352" alt="EJERCICIO 16 drawio" src="https://github.com/user-attachments/assets/6c0c04fc-5b6a-4b48-9c59-7d7c1858ccb0" />

