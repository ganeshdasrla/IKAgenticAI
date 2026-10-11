# IKAgenticAI

## Local setup

Install the notebook dependencies:

```powershell
python -m pip install -r requirements.txt
```

For local use, put your key in a root-level `.env` file (it is ignored by Git):

```text
OPENAI_API_KEY=your_api_key
```

Do not commit your `.env` file or share its contents. In Google Colab, add
`OPENAI_API_KEY` to Colab Secrets instead.