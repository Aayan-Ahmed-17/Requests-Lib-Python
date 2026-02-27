# Requests-Lib-Python

### Python requests Library – Beginner Practice
A beginner-friendly notebook practicing the **requests** library in Python using Google Colab. Examples use real public APIs to keep things practical.

---

## 📓 Contents
The notebook covers the following topics:

1. **Fetching Data from a Real API** Making a basic `GET` request to NASA's Astronomy Picture of the Day (APOD) API and parsing the JSON response.
2. **Query Parameters** Passing parameters to an API endpoint using the `params` argument to filter or customize responses.
3. **Posting Data** Sending data to a server using `POST` requests with `json` or `data` payloads.
4. **Handling Headers** Setting custom request headers such as `User-Agent` and `Authorization` tokens.
5. **Timeouts and Errors** Handling network timeouts and HTTP errors gracefully using `timeout` and `raise_for_status()`.
6. **Working with Sessions** Using `requests.Session` to persist headers and cookies across multiple requests.
7. **Inspecting Responses** Exploring response properties like `status_code`, `headers`, `text`, `json()`, and `elapsed`.

---

## 🚀 Getting Started
Open the notebook directly in **Google Colab** or clone the repo and run it locally.

### Installation
```bash
# Clone the repository
git clone [https://github.com/Aayan-Ahmed-17/Requests-Lib-Python.git](https://github.com/Aayan-Ahmed-17/Requests-Lib-Python.git)

# Install the dependency
pip install requests
```

### 🔑 API Key
The NASA APOD example uses a free demo key (DEMO_KEY). For higher rate limits, get a free key at api.nasa.gov.

### 📦 Requirements
* Python: 3.x
* Library: requests
