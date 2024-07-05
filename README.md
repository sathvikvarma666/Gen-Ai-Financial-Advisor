# AI-Powered Financial Advisor for Stock Markets 📈

Navigating the stock market as a retail investor can be daunting, especially without a solid background in finance. The intricate financial jargon and the depth of analysis required often lead me to rely on finance influencers' videos or various online blogs to bypass the complexity. This challenge sparked the idea of developing a sophisticated bot using LangChain and LLMs, designed to streamline the investment analysis process by leveraging both real-time and historical data.

Implementation
You can find all the necessary code and experimentation steps in the stock_analyzer_bot.ipynb notebook. To get started, simply add your openai_api_key in the initial cell.

Experimentation and Tools
I have defined a series of tools and functions for the agent that efficiently scrapes and aggregates real-time data for comprehensive stock analysis. These tools include:

Historical Stock Prices: Analyzes data spanning from one month to one year, tailored to the model's context length.
Company Financial Statements: Provides detailed insights into the company's financial health.
Latest Company News: Keeps track of current events and market sentiment impacting the stock.
This combination of historical performance data and real-time market sentiment creates a robust framework for making informed investment decisions. Additional tools can easily be integrated to enhance the analysis further, ensuring that investors have all the information they need at their fingertips.

 # Looking Forward to add these in the Future

a) Streamlit Showcase

b) Additional Quant Based or Ml based tools can be integrated. For example, a math tool for performing complex technical analysis.

c) Enhanced prompting for consistent results

d) Integration of other open-source LLMs

e) Note:- I am a student and this project is for educational purposes. Feel free to suggest any modifications or improvements.

