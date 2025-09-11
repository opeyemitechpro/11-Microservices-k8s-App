
## Dummy Secrets for Testing
This repository contains dummy API keys and secrets intentionally exposed.

These are not real credentials and are used solely for testing purposes, specifically to verify the effectiveness of tools like `Gitleaks` in detecting hardcoded secrets in my CI/CD pipeline.

Do not use these "credentials" in any production environment or for any real-world authentication purposes.


AWS_ACCESS_KEY_ID=AKIAIOSFODNN7EXAMPLE 

AWS_SECRET_ACCESS_KEY=wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY

GOOGLE_API_KEY=AIzaSyBdVgLhgyZexample_key_KE

STRIPE_SECRET_KEY=sk_test_51Hkexample_secret_key_7qB

SLACK_BOT_TOKEN=xoxb-123456789012-1234567890123-abc123def456

These dummy secrets are designed to trigger `Gitleaks` detection in my CI/CD pipeline, ensuring my security measures are working correctly.

See full CI-CD Documentation here: