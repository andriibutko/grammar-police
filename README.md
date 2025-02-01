# Grammar Police

# Web UI

If you want to run the app locally, start by creating the `secrets.toml` file:

```shell
touch ~/.streamlit/secrets.toml
```

You'll need to obtain a Groq API key, which you'll then provide in the "secrets.toml" file as a `GROQ_API_KEY`.

After specifying the API key in the secrets file, you can proceed to run the web UI locally:

```shell
streamlit run frontend.py
```
