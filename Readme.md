#### Use llm's api deepseek to create powerpoint presentations.

# AI PowerDeck: Your Dynamic Presentation Partner

## Overview
This developer is a dyslexic who developed this program in the hopes of helping others. This program is not intended for sale or profit.

This program is designed for creating prototypes of content for presentation work using ai deepseek api. It is only for creating basic content of the work. It is suitable for use as a guideline for creating presentations.


## Tech Stack Used
The following technologies and libraries were used in the development of this chatbot:

[Python](https://www.python.org/): Programming language used for the implementation.

API Used: Deepseek api (https://platform.deepseek.com/)

![image](https://github.com/nanofatdog/Generate_PPT_using_deepseek_api/blob/master/imags/20250512_215813.png)


## Getting Started

To get started with the Open-source AI equipped PowerPoint Generator, follow these steps:

0. conda and python 3.10 (recommend)
```py
 conda create -n aippt python=3.10 -y 
```
1. Clone the repository
```py
git clone https://github.com/nanofatdog/Generate_PPT_using_deepseek_api.git
```
2. Install the required dependencies:

```py
cd Generate_PPT_using_deepseek_api
pip install -r requirements.txt
```
3. open .env (linux use nano .env)
```
 DEEPSEEK_API_KEY=your_api_key_here  << input your deepseek api
```
4. Run the Streamlit application 
```py
streamlit run FINAL_app.py
```

## Usage
The application uses a simple command-line interface. Enter your topic, and the application will generate a Power point presentation for you. 

```py
  http://localhost:8501  # your pc IP  port 8501
```

## Contributing
Contributions to this project are welcome! If you have ideas for improvements, bug fixes, or new features, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.






