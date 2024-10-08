# 🚀 HITgram - N-gram Language Model

HITgram is a powerful Java-based N-gram model designed to process and analyze text data for tasks such as word prediction, text generation, and language modeling. The model supports multiple N-gram sizes and implements smoothing techniques to effectively handle unseen data.

---

## 📚 Table of Contents

- [🌟 Introduction](#-introduction)
- [🔧 Prerequisites](#-prerequisites)
- [📦 Installation](#-installation)
- [🚀 How to Run the Program](#-how-to-run-the-program)
- [⚙️ Usage](#-usage)
- [✨ Features](#-features)
- [🛠️ Technologies Used](#-technologies-used)
- [📏 Smoothing Techniques](#-smoothing-techniques)
- [🤝 Contributing](#-contributing)
- [📝 License](#-license)

---

## 🌟 Introduction

**HITgram** is an N-gram language model built for analyzing and processing text data in various natural language processing (NLP) tasks. With this tool, you can:
- Train the model on large text datasets.
- Generate text based on N-gram probabilities.
- Predict the next word in a sequence.

---

## 🔧 Prerequisites

Before you begin, ensure that you have the following software installed:

- **Java** (version 11 or higher)
- **Maven** (version 3.6.x or higher)

---

## 📦 Installation

Follow these steps to set up the project:

1. Clone the repository:
   ```bash
   git clone https://github.com/chandan789maity/HITgram.git
   cd HITgram


## How to run the program 

 1. Build the JAR:
- Use Maven to clean the project and build the JAR file:
    ```bash
     mvn clean install

 2. Run the JAR:
- Once the build is complete, you can run the JAR file using the following command:
    ```bash
    java -jar target/HITgram-1.0-SNAPSHOT.jar 

## Usage

- Training the Model:
    Provide a text file for training the N-gram model. The model will process the text and build N-gram probabilities.

- Text Generation:
    Input a starting word or phrase, and the model will generate the following words based on the trained N-gram probabilities.

- Word Prediction:
    Enter a sequence of words, and the model will predict the most probable next word.

- Evaluating Perplexity:
    Calculate the perplexity of a test dataset to measure how well the model predicts unseen text data.

## Features

- N-gram Support: Supports unigram, bigram, trigram, and higher-order N-grams.

- Text Generation: Generates text sequences based on trained N-gram probabilities.

- Word Prediction: Predicts the next word in a given phrase.

- Perplexity Calculation: Measures model performance on unseen data.

- Smoothing Techniques: Implements Add-One and Good-Turing smoothing to handle unseen N-grams.

## Technologies Used
- Java: Core programming language used for building the N-gram model.
- Maven: For dependency management and building the project.






