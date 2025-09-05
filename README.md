# 📱 CryptoTrackerMVVM

Aplicación Android en desarrollo que muestra el valor de criptomonedas en tiempo real y estadísticas básicas, 
utilizando la [CoinGecko API](https://www.coingecko.com/en/api).
## 🚀 Tecnologías y arquitectura
- Kotlin- MVVM (Model - View - ViewModel)- Hilt (inyección de dependencias)- Retrofit (consumo de API REST)- LiveData / Flow- Coroutines- ViewBinding
## 📂 Estructura del proyecto

com.example.cryptotracker
├── data
│ ├── model # Modelos de datos
│ ├── remote # Llamadas a la API (Retrofit)
│ └── repository # Repositorios
├── di # Módulos de Hilt
├── ui
│ ├── main # Pantalla principal (Fragment + ViewModel)
│ ├── stats # Pantalla de estadísticas
└── utils # Clases auxiliares

## 🌟 Funcionalidades planeadas

- [x] Configuración inicial del proyecto con MVVM y Hilt  
- [ ] Pantalla principal con listado de criptomonedas  
- [ ] Pantalla de estadísticas de monedas  
- [ ] Integración con API de CoinGecko  
- [ ] Gráficos con valores históricos  

## 📌 Estado del proyecto
En desarrollo 🚧
