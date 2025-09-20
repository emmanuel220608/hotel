# 🏨 Sistema de Reservas de Hotel en Java

Este proyecto es un programa en **Java** que simula un sistema básico de administración de un hotel con **5 habitaciones**.  
El usuario puede realizar reservas, cancelar reservas y consultar el estado de cada habitación mediante un menú en consola.

---

## 📂 Estructura del proyecto

```
hotel/
├── Hotel.java   # Código fuente principal
└── README.md    # Documentación del proyecto
```

---

## 🚀 Ejecución

Clonar el repositorio:

```bash
git clone https://github.com/emmanuel220608/hotel.git
cd hotel
```

Compilar el programa:

```bash
javac Hotel.java
```

Ejecutar el programa:

```bash
java Hotel
```

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

```
--- Menú ---
1. Reservar habitación
2. Cancelar reserva
3. Mostrar estado del hotel
4. Salir

Elige una opción: 1
Número de habitación (1-5): 2
Nombre del cliente: Juan Pérez
Número de noches: 3
✅ Reserva realizada. Total a pagar: $240.0
```

---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas!  

1. Haz un fork del proyecto.  
2. Crea una nueva rama:  

   ```bash
   git checkout -b feature/nueva-funcion
   ```

3. Haz tus cambios y commit:  

   ```bash
   git commit -m "Agrego nueva función"
   ```

4. Haz push a la rama:  

   ```bash
   git push origin feature/nueva-funcion
   ```

5. Abre un **Pull Request**.  

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT.  
Consulta el archivo [LICENSE](LICENSE) para más detalles.
