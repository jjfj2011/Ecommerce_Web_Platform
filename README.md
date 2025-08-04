
# 🛒 Fashion Store Ecommerce App

Una aplicación de **e-commerce moderna y elegante** desarrollada con **Streamlit**, que ofrece una experiencia de compra premium con autenticación, carrito inteligente y pagos seguros.

🔗 **[Accede a la demo en Streamlit Cloud](https://fashion-store-app.streamlit.app/)**

---

## ✨ Características Principales

- 🔐 **Autenticación OAuth con Google**: Inicio de sesión seguro y sin fricciones.
- 🛒 **Carrito de Compras Inteligente**: Gestión de productos con persistencia en tiempo real.
- 💳 **Procesamiento de Pagos**: Integración con **Stripe API** para pagos seguros.
- 📱 **Diseño Responsive**: Interfaz moderna adaptada a todos los dispositivos.
- 🔥 **Base de Datos Firebase**: Almacenamiento seguro de usuarios, productos y órdenes.
- 📊 **Gestión de Inventario**: Control automático de stock tras cada compra.
- 🎨 **UI/UX Premium**: Estilos personalizados con CSS.

---

## 🛠️ Tecnologías Utilizadas

- **Frontend**: Streamlit + HTML/CSS personalizado
- **Backend**: Python
- **Base de Datos**: Firebase Firestore
- **Autenticación**: Google OAuth 2.0
- **Pagos**: Stripe API
- **Almacenamiento**: Firebase Storage
- **Deployment**: Streamlit Cloud

---

## 📁 Estructura del Proyecto

```
fashion-store/
├── app.py                 # Página principal y autenticación
├── pages/
│   ├── catalogo.py       # Catálogo de productos y carrito
│   └── compraok.py       # Confirmación de compra
├── estilos/
│   ├── css_login.html    # Estilos para login
│   ├── css_catalogo.html # Estilos para catálogo
│   └── css_compra.html   # Estilos para compra
├── serviceAccountKey.json # Credenciales Firebase
├── payment_utils.py       # Lógica de pagos (Stripe)
├── .env                  # Variables de entorno
├── requirements.txt      # Dependencias Python
└── README.md              # Documentación del proyecto
```

---

## 🚀 Instalación y Ejecución Local

1. Clona este repositorio:
   ```bash
   git clone https://github.com/<tu_usuario>/<tu_repositorio>.git
   cd fashion-store
   ```

2. Crea un entorno virtual e instala las dependencias:
   ```bash
   python -m venv venv
   source venv/bin/activate  # en Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. Configura tu archivo `.env` con las claves necesarias:
   ```
   STRIPE_SECRET_KEY=tu_clave
   STRIPE_PUBLIC_KEY=tu_clave
   GOOGLE_CLIENT_ID=tu_clave
   GOOGLE_CLIENT_SECRET=tu_clave
   ```

4. Ejecuta la aplicación:
   ```bash
   streamlit run app.py
   ```

---

## 🌐 Despliegue en Streamlit Cloud

El proyecto está desplegado en **Streamlit Cloud**.  
👉 [Ver demo aquí](https://fashion-store-app.streamlit.app/)

---

## 📸 Capturas de pantalla (opcional)

Puedes agregar imágenes aquí para mostrar:
- Página de inicio / login
- Catálogo de productos
- Checkout en Stripe
- Confirmación de compra

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT.
