# Copilot Instructions (Repo-Wide)

## Language & Style
- Always use Python 3.12+ with type hints
- Follow PEP 8
- Use f-strings, never .format() or %

## Architecture
- Use FastAPI for any API endpoints
- Use Pydantic v2 for data validation
- Prefer async/await patterns

## Testing
- Always suggest pytest tests alongside implementation
- Minimum: one happy path + one edge case per function

## Documentation
- Include Google-style docstrings on all public functions
