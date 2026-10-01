# Agent notes for pythinqconnect-oven

- Preserve API request/response and state-model compatibility. Mock external API responses in local tests; keep credentials out of fixtures and logs.
- Run focused `pytest` tests from `tests/`, then the broader suite when changing shared SDK behavior.
