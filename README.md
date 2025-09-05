📱 CryptoTrackerMVVM
Android application in development that shows the real-time value of cryptocurrencies and basic statistics,
using the CoinGecko API.

🚀 Technologies and architecture
Kotlin

MVVM (Model - View - ViewModel)

Hilt (dependency injection)

Retrofit (REST API consumption)

LiveData / Flow

Coroutines

ViewBinding

📂 Project structure
com.example.cryptotracker
├── data
│ ├── model # Data models
│ ├── remote # API calls (Retrofit)
│ └── repository # Repositories
├── di # Hilt modules
├── ui
│ ├── main # Main screen (Fragment + ViewModel)
│ ├── stats # Stats screen
└── utils # Helper classes

🌟 Planned features
[x] Initial project setup with MVVM and Hilt

[ ] Main screen with cryptocurrency list

[ ] Coin statistics screen

[ ] Integration with CoinGecko API

[ ] Charts with historical values

📌 Project status
In development 🚧
