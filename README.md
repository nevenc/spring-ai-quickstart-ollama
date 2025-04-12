# spring-ai-quickstart-ollama

This is an example of a simple Spring AI application that connects to
Ollama locally hosted LLMs.

## Requirements
* Installed Ollama endpoint, locally or elsewhere.
* Downloaded Ollama model, e.g. `llama3.2`

## Run Ollama

```
ollama start
```

```
ollama pull llama3.2
```

```
ollama run llama3.2
```

## Run the application

```
./mvnw spring-boot:run
```

## Test the application

```
http :8080

HTTP/1.1 200 
Connection: keep-alive
Content-Length: 101
Content-Type: text/plain;charset=UTF-8
Date: Tue, 11 Apr 2025 08:05:00 GMT
Keep-Alive: timeout=60

I'm an artificial intelligence model known as Llama. Llama stands for "Large Language Model Meta AI."
```

## References

* [Spring AI Ollama Chat](https://docs.spring.io/spring-ai/reference/api/chat/ollama-chat.html)
* [Ollama](https://ollama.com/)
* [Ollama Models](https://ollama.com/search)
* [Get started with Spring AI and Ollama](https://nevenc.com/get-started-with-spring-ai-and-ollama)
