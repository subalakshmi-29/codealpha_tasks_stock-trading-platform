#  📈 **Stock Trading Platform**

Stock Trading Platforms is a Java-based console application that simulates basic stock trading. Users can view market data, buy stocks, sell stocks, and review their portfolio. The project demonstrates fundamental Java programming concepts such as:

* Object-Oriented Design
* Collections (`ArrayList` and `HashMap`)
* Handling user input with the `Scanner` class

# 🚀 **Features**

✅ **View Market Data** – Display a list of available stocks with their current prices.
✅ **Buy Stocks** – Purchase stocks if you have enough balance.
✅ **Sell Stocks** – Sell owned stocks if you have sufficient shares.
✅ **View Portfolio** – Check your current stock holdings and remaining balance.
✅ **Interactive Menu** – Simple, text-based navigation through the application.

# 🛠️ **Technologies Used**

* **Java** (JDK 8 or higher)
* **Collections**: `ArrayList`, `HashMap`
* **Scanner**: For handling console input

# 📦 **Installation & Setup**

Follow these steps to run the application on your local machine:

1️⃣ **Clone the repository**:

```bash
git clone https://github.com/your-username/stock-trading-platform.git
```

2️⃣ **Navigate to the project directory**:

```bash
cd stock-trading-platform
```

3️⃣ **Compile the Java source file**:

```bash
javac StockTradingPlatform.java
```

4️⃣ **Run the application**:

```bash
java StockTradingPlatform
```

# 🧭 **Usage Instructions**

Upon running the application, you will see a menu like this:

```
1. View Market Data
2. Buy Stock
3. Sell Stock
4. View Portfolio
5. Exit
```

Options:

* **1. View Market Data** – Lists stocks along with their prices.
* **2. Buy Stock** – Prompts for a stock symbol and quantity. If you have enough balance, the stock is purchased.
* **3. Sell Stock** – Prompts for a stock symbol and quantity. If you own enough shares, the sale is executed.
* **4. View Portfolio** – Displays your current stock holdings and cash balance.
* **5. Exit** – Closes the application.

# 🏗️ **Code Structure**

* **`Stock` Class** – Represents a stock with its symbol and price.
* **`Portfolio` Class** – Manages owned stocks using a `HashMap`, tracks the cash balance, and contains methods to buy/sell stocks.
* **`StockTradingPlatform` (Main Class)** – Entry point of the program. Manages user interaction through a menu interface and integrates the other classes.

