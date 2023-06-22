# Streamlit OpenAI Functions Prototype App

## Introduction
Welcome to the Streamlit Functions App repository! This repository houses a Streamlit application that allows users to automatically generate functions using the OpenAI API. The main file to run the application is `Home.py`. Streamlit Functions App aims to simplify the process of utilizing the OpenAI API by providing an interface for creating and managing functions. 

## OpenAI Functions Feature
The Functions feature is a relatively new addition to the OpenAI suite of tools. It allows developers to create, manage, and execute functions that perform tasks using the OpenAI models. These functions can be used in a wide variety of scenarios such as drafting emails, writing code, answering questions, creating conversational agents, tutoring, translating languages, simulating characters for video games, and much more. In short, if you can define it as a function, you can have the OpenAI model perform that task.

## Installation and Running the App

### Prerequisites
Before you can run the Streamlit Functions App, you need to have Python installed on your machine. You can download Python from the [official website](https://www.python.org/downloads/).

### Installation
To use the Streamlit Functions App, you will need to install Streamlit. This can be done by running the following command in your terminal:

```bash
pip install streamlit
```

Once you've installed Streamlit, you will need to clone this repository to your local machine. You can do this with the following command:

```bash
git clone https://github.com/wjbmattingly/streamlit-openai-functions.git
```

You will also need to install the latest version of OpenAI:

```bash
pip install openai --upgrade
```

### Running the Application
To run the application locally, navigate to the directory that contains the cloned repository and run the following command:

```bash
streamlit run Home.py
```

After running this command, Streamlit should start a local server and provide a URL that you can open in your web browser to view the app.

### OpenAI API Key
To use the OpenAI functionality, you will need to provide your OpenAI API Key. This can be found in your OpenAI account dashboard. Be sure to store this key securely and never share it with others. The key should be added to your environment variables or placed within a `.env` file within the root directory.

## Contributing
Contributions to the Streamlit Functions App are welcome. Please create a pull request, and ensure that your code has been properly formatted and tested before submission.

## License
This project is licensed under the MIT License - see the [MIT](https://opensource.org/licenses/MIT) file for details.

MIT License

Copyright (c) [2023] [W.J.B. Mattingly]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
