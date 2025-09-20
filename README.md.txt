# 🏨 Sistema de Reservas de Hotel en Java

Este proyecto es un programa en **Java** que simula un sistema básico de administración de un hotel con 5 habitaciones.  
El usuario puede realizar reservas, cancelar reservas y consultar el estado de cada habitación mediante un menú en consola.  

---

## 📂 Estructura del proyecto

hotel/
├── Hotel.java # Código fuente principal
└── README.md # Documentación del proyecto

---

## 🚀 Ejecución

1. Clonar el repositorio:  

git clone https://github.com/tu-usuario/hotel.git
cd hotel

2. Compilar el programa:  

javac Hotel.java

3. Ejecutar el programa:  

java Hotel

---

## 📌 Funcionalidades

- **Reservar habitación**: asigna nombre del cliente, número de noches y calcula el costo.  
- **Cancelar reserva**: libera la habitación y elimina los datos asociados.  
- **Mostrar estado**: indica cuáles habitaciones están disponibles u ocupadas con detalle de cliente y precio.  
- **Salir**: cierra el programa.  

---

## 💰 Precios por habitación

| Habitación | Precio por noche |
|------------|------------------|
| 1          | $50.0            |
| 2          | $80.0            |
| 3          | $50.0            |
| 4          | $100.0           |
| 5          | $50.0            |

---

## 🖥️ Ejemplo en consola

--- Menú ---

Reservar habitación

Cancelar reserva

Mostrar estado del hotel

Salir
Elige una opción: 1
Número de habitación (1-5): 2
Nombre del cliente: Juan Pérez
Número de noches: 3
✅ Reserva realizada. Total a pagar: $240.0

---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas!  
1. Haz un fork del proyecto.  
2. Crea una nueva rama (`git checkout -b feature/nueva-funcion`).  
3. Haz tus cambios y haz commit (`git commit -m "Agrego nueva función"`).  
4. Haz push a la rama (`git push origin feature/nueva-funcion`).  
5. Abre un **Pull Request**.  

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT.  
Consulta el archivo LICENSE para más detalles.  