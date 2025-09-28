🚀 Currency Converter

I built the Currency Converter, a web application that allows users to convert between different currencies using the latest exchange rates. The app fetches real-time exchange rates from an external API using JavaScript's Fetch API and provides a simple, intuitive interface for quick conversions.

🖼️ Screenshots

🔹 Initial Interface: Currency Converter UI
(screenshot/ui.png)

✨ Features I Implemented

✅ Real-Time Exchange Rates: Dynamically fetches updated exchange rates.
✅ User-Friendly Interface: Designed a simple and intuitive layout for easy interaction.
✅ Custom Currency Selection: Users can select both the base and target currency.
✅ Interactive UI Elements: Displays flags next to the selected currencies.
✅ Fast & Lightweight: Built using only HTML, CSS, and JavaScript with no extra dependencies.

📂 My Implementation Overview

index.html → Structured the web page with input fields and dropdowns.

style.css → Styled the UI to give it a modern and responsive look.

codes.js → Wrote functions to fetch exchange rates and update the interface dynamically.

app.js → Handled all user interactions and conversion logic.

🛠️ Technologies I Used

HTML → Defined the webpage structure.

CSS → Styled and enhanced the user experience.

JavaScript → Implemented the logic for fetching exchange rates and conversions.

Fetch API → Integrated real-time API requests to get updated currency rates.

🚀 How I Set It Up Locally

Follow these steps to run the project on your own machine:

1️⃣ Clone the Repository:

git clone https://github.com/Mithcodes007/Currency-Converter-API.git


2️⃣ Navigate into the Project Folder:

cd Currency-Converter-API 


3️⃣ Open the Project with Live Server:

If you have Live Server installed in VS Code, right-click index.html → Open with Live Server.

Or open index.html manually in your browser.

4️⃣ Use the Currency Converter:

Enter the amount to convert.

Select the "From" currency.

Select the "To" currency.

Click Get Exchange Rate to see the conversion.

🌐 API Endpoint I Used

The application fetches exchange rates from:

https://2024-03-06.currency-api.pages.dev/v1/currencies/${currency}.json

Replace ${currency} with currency codes like usd, inr, eur, etc.
