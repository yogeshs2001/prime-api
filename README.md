
# Prime Number Checker API (FastAPI)

Simple FastAPI app that returns whether a given number is prime.

## 🔧 Setup

1. Clone the repo:
```bash
git clone https://github.com/YOUR_USERNAME/prime-api.git
cd prime-api
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the API locally:
```bash
uvicorn main:app --reload
```

Open your browser to: [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs) to try the API with Swagger UI.

## 🧪 Test the API with curl

Use the following curl command to test if a number is prime:

```bash
curl -X POST http://127.0.0.1:8000/is-prime/ \
     -H "Content-Type: application/json" \
     -d '{"number": 19}'
```

Example response:

```json
{
  "number": 19,
  "is_prime": true
}
```

You can replace `19` with any integer you want to test.
