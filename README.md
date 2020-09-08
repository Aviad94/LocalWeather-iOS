# LocalWeather-iOS
<div style="width: 100px; height 60px;"><img src="https://github.com/Aviad94/LocalWeather-iOS/blob/master/Screenshot/Screenshot-1.png" width="20%" height="20%" align="right"></div>



## Overview

`LocalWeather-iOS` is a local weather app, you can get current weather & details, get hourly forecast weather and get daily forecast. But detail not fully same because limited feature free plan from Openweathermap API.

### Keyword
- Swift
- Auto Layout
- JSON & Codable
- MVC


## Getting Started

### Prerequisites

- A valid API key from Openweathermap
- A Mac running macOS Catalina 
- Xcode 11.3.1
- An iphone if you would like to run it on your iphone

### Installation

1. Clone or download the project to your local machine
2. Open the project in Xcode
3. Replace `YOURAPIKEY` with your valid Openweathermap API key in `NetworkManager.swift`

```swift
struct NetworkManager {

    ```
    private let weatherURL = "YOURAPIKEY"
```



5. Run the simulator

## Thanks to

Open API from [OpenWeatherMap](https://openweathermap.org/api)

Inspiring project from 
