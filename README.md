# 🧠 AI Research Assistant

A Spring Boot-based AI-powered Research Assistant that helps users summarize, generate, and manage research content using language models.

## 🚀 Features

- 📄 Accepts research queries via REST API
- 🤖 Integrates with a Language Model (e.g., Google Gemini)
- 🔍 Returns intelligent summaries/responses
- 🧪 Unit tested with Spring Boot Test

## 🛠️ Technologies Used

- Java 17+
- Spring Boot
- RESTful APIs
- Google Gemini API (or OpenAI/Gemini integration)
- Maven

## 📁 Project Structure

```
.
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com.lazydazycoder.Research.Assistant
│   │   │       ├── ResearchAssistantApplication.java
│   │   │       ├── ResearchController.java
│   │   │       ├── ResearchService.java
│   │   │       ├── ResearchRequest.java
│   │   │       └── GeminiResponse.java
│   │   └── resources
│   │       └── application.properties
│   └── test
│       └── java
│           └── com.lazydazycoder.Research.Assistant
│               └── ResearchAssistantApplicationTests.java
```

## 🔧 Setup and Run

1. **Clone the repository**

```
git clone https://github.com/Prajwal4648/AI-Research-Assistance.git
cd AI-Research-Assistance
```

2. **Configure API keys**
    - Add your Gemini/OpenAI API key to `application.properties`:
      ```
      gemini.api.key=your-api-key-here
      ```

3. **Run the app**

```
./mvnw spring-boot:run
```

4. **Access the API**
    - `POST /research` with JSON body:
      ```json
      {
        "query": "What is reinforcement learning?"
      }
      ```

## 📌 To Do

- [ ] Add frontend UI
- [ ] Save research history
- [ ] Add authentication

## 🙌 Author

Made with ❤️ by [Prajwal4648](https://github.com/Prajwal4648)


