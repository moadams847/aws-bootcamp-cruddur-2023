# Week 2 — Distributed Tracing

## **Required Homework**

### **Distrbuted Tracing with Honeycomb**
1. Created a trial account at [honeycomb.io](https://ui.honeycomb.io/)
2. Created a new enviroment and attained the api key
3. Saved the Api key to my Codespaces secrets

!()[/journal/assets/tracing_wk2.png]

4. To ensure my key is propagated across all shells, the workspace was closed and a new one opened.
5. To ensure all dependencies(Open telemetry "OTEL") are met, thee following was added to the [requirements.txt](../backend-flask/requirements.txt) file:
    ```txt
    opentelemetry-api 
    opentelemetry-sdk 
    opentelemetry-exporter-otlp-proto-http 
    opentelemetry-instrumentation-flask 
    opentelemetry-instrumentation-requests
