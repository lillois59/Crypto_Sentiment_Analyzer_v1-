🚀 Crypto Sentiment Analyzer v1 - Keep an Eye on the Market Without Touching Your Phone!

Hey makers and crypto enthusiasts!

I'm super excited to share my latest IoT project: the Crypto Sentiment Analyzer v1. Imagine having essential information about your favorite cryptocurrencies (PEPE, BTC, ETH) right in front of you, on a sleek little screen, without having to pull out your phone, open an app, or turn on your PC. That’s exactly what this small ESP32-based device offers you!

Why this project? The Narrative of Hands-Free Crypto Tracking

As crypto enthusiasts, we know how dynamic the ecosystem is. Prices fluctuate, market sentiment constantly changes, and it's easy to find yourself compulsively checking your phone every five minutes. My goal with the Crypto Sentiment Analyzer is to break that cycle.

This device is not just a price ticker; it performs a form of AI-powered sentiment analysis. By processing news and votes from CryptoPanic, it gives you a quick and accurate sense of the market's "mood"—Bullish, Bearish, or Neutral—without you having to read a single article.

Free your hands: No more unlocking your smartphone or interrupting your work on the computer. A quick glance at the screen gives you the essentials.

Near real-time information: Get the latest prices and market trends (bullish/bearish) directly from CoinMarketCap.

The market "feeling": Thanks to the CryptoPanic integration, the device analyzes the overall sentiment around your favorite cryptos. This is invaluable information for understanding the market's vibe.

Visual history: Mini-graphs give you a quick view of price changes, allowing you to spot patterns or significant shifts over time.
Simple and efficient: Designed to be autonomous and easy to use, it's perfect for any desk, shelf, or trading corner.

How it Works (The Magic Under the Hood)

The core of this project is a powerful and versatile ESP32, which handles all operations:

WiFi Connectivity: It connects to your home WiFi network to access online data.
CoinMarketCap API: It periodically queries the CoinMarketCap API to get the current prices of PEPE, BTC, and ETH. It even tracks previous prices to determine trends (up or down).

CryptoPanic API: It communicates with the CryptoPanic API to retrieve news and analyze market sentiment based on users' "bullish" and "bearish" votes. This is where the sentiment analysis part comes into play.

TFT Display: All this data is beautifully rendered on a color TFT screen, including prices, trends, sentiment, and historical mini-graphs.

Smart Management: The system handles WiFi disconnections, API errors, and update delays to ensure a smooth and reliable experience.

Here is a schematic of the architecture to better understand the flow:
<img width="700" height="700" alt="Gemini_Generated_Image_k6hawok6hawok6ha" src="https://github.com/user-attachments/assets/fad98300-e784-4748-918c-5a53898e5bf9" />

Technologies Used

Hardware: ESP32, TFT Display CYD-2USB

Arduino Libraries: WiFi, WiFiClientSecure, HTTPClient, ArduinoJson, TFT_eSPI

External APIs: CoinMarketCap (for prices), CryptoPanic (for sentiment)

Getting Started (DIY):

1: Clone the repository: git clone https://github.com/lillois59/Crypto_Sentiment_Analyzer_v1-.git

2: Open main.cpp in vscode and lauch platform.io 

3: in main.cpp Configure your API Keys: Replace cmcApiKey and cryptoPanicApiKey with your own API keys in main.cpp. Configure WiFi: Update the ssid and password with your network credentials.

4: Install the Libraries by build main.cpp using vscode 

5: upload on your CYD-2USB aka Marauder esp32 by @Espressif

<img width="700" height="700" alt="Gemini_Generated_Image_tohje0tohje0tohj" src="https://github.com/user-attachments/assets/bfc8b576-57eb-491d-aba3-816584780402" />

This project is a first version, and I'm always open to ideas for improvement!

![485863850-44f1031e-f5cb-42d6-90b9-fb21723d6e91](https://github.com/user-attachments/assets/cb9eb155-82e9-4fae-81e2-286d73b2d0ad)


I hope this Crypto Sentiment Analyzer v1 will be as useful to you as it is to me. Forget your phone and let the ESP32 do the work!

@Sw6lnd - IoT - Web3 - Offensive R&D Labs since 2010
