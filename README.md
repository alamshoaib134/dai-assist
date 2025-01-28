# DAI-Assist

DAI-Assist is a chatbot designed to enhance information retrieval from internal data repositories. By leveraging Retrieval-Augmented Generation (RAG), it provides accurate and contextually relevant responses to user queries.

## Table of Contents

- [Introduction](#introduction)
- [Why DAI-Assist?](#why-dai-assist)
- [How It Works](#how-it-works)
- [What We Built](#what-we-built)
- [Drawbacks of the Current System](#drawbacks-of-the-current-system)
- [Benefits of the New Chatbot](#benefits-of-the-new-chatbot)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

DAI-Assist aims to streamline the process of retrieving information from various internal data sources. It uses advanced AI techniques to understand user queries and provide precise answers by accessing relevant documents and data.

## Why DAI-Assist?

Today, we face a significant challenge: efficiently retrieving the right information from our vast internal data repositories. Nike has an enormous amount of data stored in Confluence pages and internal documents. This data is sufficient to solve most user queries. However, the challenge lies in finding the right page and the right content that one is looking for. Our current system relies on keyword-based search and document retrieval, which often falls short in providing precise answers to user queries.

## How It Works

To tackle this challenge, we have developed a chatbot using Retrieval-Augmented Generation (RAG). This innovative approach leverages the power of semantic search and natural language understanding to provide more accurate and contextually relevant responses. Unlike traditional keyword-based search systems, our RAG-based chatbot can understand the intent behind user queries and retrieve the most pertinent information from our internal data sources. This transition from document retrieval to query response system marks a significant improvement in how we access and utilize our internal knowledge base.

## What We Built

Our chatbot integrates with Nike's internal data, including Confluence pages and internal documents, to provide users with precise answers to their queries. By using RAG, the chatbot can understand and process natural language queries, retrieve relevant information, and generate accurate responses. This not only enhances the user experience but also significantly reduces the time and effort required to find the right information. Our goal is to empower Nike employees with a tool that makes information retrieval seamless, efficient, and effective.

## Drawbacks of the Current System

- **Keyword Dependency:** Relies heavily on exact keyword matches, which can miss relevant documents that use different terminology.
- **Time-Consuming:** Users often spend a significant amount of time sifting through multiple documents to find the specific information they need.
- **Lack of Context:** The current system does not understand the context or intent behind user queries, leading to irrelevant search results.
- **Document Overload:** Users are often overwhelmed with a large number of search results, making it difficult to identify the most relevant information.
- **Static Results:** Provides static search results without the ability to dynamically generate answers based on the query context.
- **Limited User Interaction:** Does not support interactive or conversational queries, limiting the ability to refine searches based on follow-up questions.
- **Inefficiency in Handling Complex Queries:** Struggles with complex or multi-part queries that require understanding and synthesizing information from multiple sources.
- **No Personalization:** Lacks the ability to personalize search results based on the user's role, preferences, or previous interactions.
- **Feedback Mechanism:** Limited or no mechanism for users to provide feedback on search results to improve future searches.

## Benefits of the New Chatbot

- **Enhanced Search Accuracy:** Uses semantic search to understand the meaning and context of queries, providing more accurate and relevant results.
- **Time Efficiency:** Reduces the time users spend searching for information by providing direct answers to queries.
- **Contextual Understanding:** Understands the intent behind user queries, leading to more contextually appropriate responses.
- **Dynamic Responses:** Generates dynamic answers based on the query context, rather than just retrieving static documents.
- **Interactive Experience:** Supports multi-turn conversations, allowing users to ask follow-up questions and refine their searches interactively.
- **Handling Complex Queries:** Capable of synthesizing information from multiple sources to handle complex or multi-part queries effectively.
- **Personalization:** Personalizes responses based on the user's role, preferences, and previous interactions, enhancing the user experience.
- **Continuous Improvement:** Incorporates user feedback to continuously improve the accuracy and relevance of responses.
- **Streamlined Information Access:** Provides a streamlined and efficient way to access the right information, improving overall productivity.

## Features

- **Retrieval-Augmented Generation (RAG):** Combines retrieval-based and generation-based approaches for accurate responses.
- **Multi-source Data Access:** Integrates with multiple internal data repositories.
- **Contextual Understanding:** Provides contextually relevant answers based on the user's query.

## Installation

To install the necessary dependencies, run:

```sh
pip install -r requirements.txt
```

## Usage
To run the DAI-Assist chatbot, navigate to the appropriate directory and execute the main script. 

## Contribution
- **Manager -  Nithin Bellam Sukumar** : `nithin.bellamsukumar@nike.com`
- **Shoaib Alam** :  `shoaib.alam@nike.com`
- **Malay Rout**:  `malay.rout@nike.com`


