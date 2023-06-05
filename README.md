# Weather_Forecasting
Create a command-line tool that accepts a city's name and returns the current weather forecast. Leverage OpenWeatherMap API to fetch weather data and parse it using Python. Your solution should demonstrate how GitHub Copilot can help you with API usage, data parsing, and error handling.
<!DOCTYPE html>
<html>
<body>
  <h1>Weather Forecast CLI</h1>

  <p>This is a command-line tool written in Python that fetches the weather forecast using the OpenWeatherMap API.</p>

  <h2>Installation</h2>

  <p>To use the Weather Forecast CLI, follow these steps:</p>

  <ol>
    <li>Clone the repository:</li>
    <pre><code>git clone https://github.com/your-username/weather-forecast-cli.git</code></pre>
    <li>Install the required libraries:</li>
    <pre><code>pip install requests</code></pre>
    <li>Update the API key:</li>
    <p>Obtain an API key from <a href="https://openweathermap.org/" target="_blank">OpenWeatherMap</a> by signing up for an account. Replace the empty string <code>api_key = ""</code> in the <code>weather_forecast.py</code> file with your actual API key.</p>
    <li>Execute the script:</li>
    <pre><code>python weather_forecast.py</code></pre>
  </ol>

  <h2>Usage</h2>

  <p>When prompted, enter the name of a city to get the weather forecast.</p>

  <h2>Requirements</h2>

  <ul>
    <li>Python 3.x</li>
    <li>requests library</li>
  </ul>
To create a GitHub command-line tool with the given code, you need to follow these steps:

1. Set up a new repository on GitHub: 
   - Create a new repository on GitHub (e.g., "weather-forecast-cli").
   - Initialize the repository with a README.md file.

2. Clone the repository:
   - Open a terminal or command prompt.
   - Navigate to the directory where you want to clone the repository.
   - Run the following command to clone the repository:
     ```
     git clone https://github.com/your-username/weather-forecast-cli.git
     ```
   - Change to the cloned repository's directory:
     ```
     cd weather-forecast-cli
     ```

3. Create a new Python file:
   - Create a new file in the repository's directory, for example, `weather_forecast.py`.
   - Copy and paste the provided code into the `weather_forecast.py` file.

4. Install the requests library:
   - In your terminal or command prompt, run the following command to install the requests library:
     ```
     pip install requests
     ```

5. Commit and push the changes:
   - Add the new file to the repository:
     ```
     git add weather_forecast.py
     ```
   - Commit the changes:
     ```
     git commit -m "Add weather_forecast.py file"
     ```
   - Push the changes to GitHub:
     ```
     git push origin main
     ```

6. Make the Python script executable:
   - Modify the permissions of the Python file to make it executable:
     ```
     chmod +x weather_forecast.py
     ```

7. Update the API key:
   - Obtain an API key from OpenWeatherMap by signing up for an account at https://openweathermap.org/.
   - Replace the empty string `api_key = ""` with your actual API key in the `weather_forecast.py` file.

8. Test the command-line tool:
   - In your terminal or command prompt, run the following command to execute the script:
     ```
     ./weather_forecast.py
     ```
   - Enter a city name when prompted.

The script will fetch the weather forecast for the specified city using the OpenWeatherMap API and display the results on the command line.

Remember to keep your API key confidential and avoid committing it to a public repository. You can use environment variables or configuration files to securely store the API key and load it into your script.
 <footer>
    <p>&copy; 2023 Ayush Siloiya. All rights reserved.</p>
  <p>
     
        Notice: All content on this website, including text, graphics, logos, images, audio clips, and software, is the property of Ayush Siloiya and is protected by international copyright laws.

Unauthorized use, reproduction, modification, distribution, or duplication of any content on this website is strictly prohibited and may result in legal action.

Visitors to this website may not download, copy, or distribute any materials on this site without prior written permission from Ayush Siloiya.
        
  </p>
  </footer>
  </body>
</html>
