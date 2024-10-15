# SportyBet_OddPickingBot
The objective of this Selenium automation project is to create a bot that efficiently selects a maximum of five games from the SportyBet bookmaker. The selection process focuses on identifying games with odds that are less than 1.2. By utilizing Selenium, the project automates the tedious task of manually browsing through numerous games and their corresponding odds. 

Games with lower odds indicate a higher likelihood of winning according to the bookmaker's assessment. Focusing on such games increases the chances of successful outcomes.

```diff
- Disclaimer: Bet responsibly. Gambling involves risk, and there's no guarantee of winning. Set limits, and only wager what you can afford to lose.
```

## Installation
Here’s how you can set up your project in **PyCharm**, along with the steps to run it smoothly using WebDriver Manager.

---

## Installation Guide for PyCharm

### 1. **Install PyCharm:**
   If you haven’t already, download and install PyCharm from [here](https://www.jetbrains.com/pycharm/download/).

### 2. **Clone the Repository:**
   You can either clone the repository using Git or directly from PyCharm.

   - **Option 1: Using Git (terminal or command prompt)**:
     ```bash
     git clone https://github.com/samuelbol/Mircosoft-Rewards-Farmer.git
     cd Mircosoft-Rewards-Farmer
     ```

   - **Option 2: Clone within PyCharm**:
     1. Open PyCharm.
     2. Click on **Get from VCS**.
     3. Paste the GitHub repository URL (`https://github.com/samuelbol/Mircosoft-Rewards-Farmer.git`) into the URL field and click **Clone**.

### 3. **Set Up the Project in PyCharm:**
   
   - Open the project by selecting the cloned directory.
   
   - Once opened, PyCharm will likely prompt you to **create a virtual environment**. This is recommended for managing dependencies. Follow the on-screen prompts to create a new virtual environment in the project folder.

   If not prompted, you can manually create one:
   - Go to **File > Settings > Project: <Your Project> > Python Interpreter**.
   - Click the gear icon and select **Add**.
   - Choose **New environment using Virtualenv**.
   - Click **OK**.

### 4. **Install Dependencies:**
   You will need to install the project’s dependencies, which are listed in the `requirements.txt` file. You can do this directly in PyCharm.

   - Right-click on the `requirements.txt` file in PyCharm.
   - Select **Install packages from requirements.txt**.
   
   Alternatively, you can install them manually by opening the terminal inside PyCharm and running:

   ```bash
   pip install -r requirements.txt
   ```

### 5. **Configure WebDriver Manager:**
   There’s no need to manually download WebDriver for Chrome because WebDriver Manager will handle it. You only need to ensure that Google Chrome is installed on your system.

### 6. **Edit the Script to Add Credentials:**
   In your PyCharm project, open the Python script (`main.py` or the relevant file) and find the placeholders for `"YOUR_USERNAME"` and `"YOUR_PASSWORD"`. Replace them with your Microsoft Rewards credentials.

   ```python
   username.send_keys("YOUR_USERNAME")
   password.send_keys("YOUR_PASSWORD")
   ```

### 7. **Run the Script in PyCharm:**
   To run the script:
   - Open `main.py` (or the script file you are working with).
   - Click the **Run** button (the green triangle in the top-right corner of PyCharm) or press `Shift + F10`.

   This will launch the Chrome browser, log in to the website, and execute the automated tasks you’ve configured in the script.

### 8. **Check Log Files:**
   After running the script, a log file (`logfile.txt`) will be generated in the project directory, summarizing the actions that were performed.

---

### Troubleshooting in PyCharm:

- **Interpreter Issues**:
   If you encounter an error saying that dependencies aren’t found, make sure that the correct **Python Interpreter** is selected:
   - Go to **File > Settings > Project: <Your Project> > Python Interpreter**.
   - Select the appropriate virtual environment that has the dependencies installed.

- **WebDriver Manager Errors**:
   If WebDriver Manager has trouble installing the ChromeDriver, ensure that:
   - **Google Chrome** is installed and up to date.
   - The installed version of Chrome matches the version of ChromeDriver that WebDriver Manager is downloading. If not, manually update Chrome or configure WebDriver Manager to download a specific version of ChromeDriver.

---

By following these steps, you should be able to successfully set up, configure, and run your project using PyCharm.
## Features
## Future Features
