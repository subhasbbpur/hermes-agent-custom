# Hermes Agent Project Memory

## Environment
- **Platform:** Android (Termux)
- **API Level:** 33
- **Python:** 3.13
- **Status:** Setup in progress (installing dependencies with system-site-packages and Rust).

## Key Features & Customizations
- **Configurable API Retries:**
  - `agent.api_max_retries`: Total retry attempts for failed API calls.
  - `agent.api_retry_base_delay`: Initial delay for exponential backoff.
  - `agent.api_retry_max_delay`: Maximum delay cap.
  - `agent.api_retry_jitter_ratio`: Randomness factor for decorrelation.
- **Repository:** https://github.com/subhasbbpur/hermes-agent-custom.git

## Session Rules
- Log important architectural decisions and configuration changes here.
- Maintain a clean and focused context.
- Verify all changes on mobile (Termux) before finalizing.
