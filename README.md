# eda_carsales_excel
# 📌 Informe Halcón Viajes

## 📖 1. Contexto y Problema Actual
Halcón Viajes enfrenta varios desafíos en la gestión de sus reservas de viajes. A pesar de contar con una plataforma robusta, se han identificado problemas como:
- ❌ Alta tasa de cancelación de reservas.
- 🔍 Falta de visibilidad sobre las preferencias de los usuarios.
- 📉 Dificultad para personalizar ofertas y optimizar campañas promocionales.

💡 **Objetivo**: A través del análisis de datos, identificar patrones que reduzcan la tasa de cancelación y mejoren la experiencia del cliente, además de desarrollar dashboards visuales que faciliten el monitoreo de las métricas clave.

---

## 🎯 2. Objetivo del Proyecto
Crear dashboards interactivos que proporcionen insights estratégicos para:
✅ Identificar patrones de cancelación y comportamiento de usuarios.
✅ Evaluar la efectividad de promociones y campañas.
✅ Optimizar ofertas basadas en segmentos de clientes.

📊 **Beneficio**: Mejorar la eficiencia operativa y reducir la incertidumbre en la toma de decisiones.

---

## 📂 3. Descripción del Conjunto de Datos
El dataset incluye información clave sobre usuarios, reservas y comportamiento post-reserva.

### 🧑‍💼 Datos de los Usuarios:
- **`ID_Usuario`**: Identificador único.
- **`Edad`**: Edad del viajero.
- **`Género`**: Male, Female, Other.
- **`Ubicación`**: Ciudad o país.
- **`Tipo_Viajero`**: Turista, Negocios.

### 📅 Datos de la Reserva:
- **`ID_Reserva`**: Identificador único.
- **`Fecha_Reserva`** / **`Fecha_Viaje`**.
- **`Antelacion_Reserva`**: Días entre reserva y viaje.
- **`Duracion_Viaje`**: En días.
- **`Numero_Personas`**.
- **`Tipo_Paquete`**: Solo vuelo, Vuelo + Hotel, etc.
- **`Costo_Total`**.

### 🏨 Detalles del Viaje:
- **`Destino`**: Ciudad o país.
- **`Tipo_Alojamiento`**: Hotel, Airbnb, Resort.
- **`Clase_Vuelo`**: Económica, Ejecutiva, Primera clase.
- **`Actividades_Reservadas`**.
- **`Numero_Noches_Estancia`**.

### 🚀 Comportamiento y Estado de la Reserva:
- **`Promocion_Aplicada`**: Sí/No.
- **`Fuente_Reserva`**: Sitio web, App, Agente de viajes.
- **`Estado_Reserva`**: Confirmada, Pendiente, Cancelada.
- **`Cancelacion_Reserva`**: Sí/No.

### 📆 Información Temporal:
- **`Mes_Reserva`** / **`Mes_Viaje`**.
- **`Estacionalidad`**: Alta o baja.

### ⭐ Feedback del Usuario:
- **`Calificacion_Usuario`**: 1 a 5.
- **`Comentarios`**.

---

## 🔜 4. Próximos Pasos
1️⃣ **Recepción de Datos**: Reunir datos históricos.
2️⃣ **Análisis Exploratorio (EDA)**: Identificar patrones y limpiar datos.
3️⃣ **Diseño de Dashboards**: Creación de visualizaciones clave.
4️⃣ **Presentación de Resultados**: Informe con insights y recomendaciones.

---

## 🛠 5. Tecnologías Utilizadas
📌 **Lenguajes**: Python, SQL  
📌 **Bibliotecas**: Pandas, NumPy, Matplotlib, Seaborn  
📌 **Visualización**: Power BI, Tableau  
📌 **Plataformas**: Jupyter Notebook, Google Colab  

🚀 **Este proyecto busca transformar datos en decisiones estratégicas!**

