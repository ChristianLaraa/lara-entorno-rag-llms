FROM python:3.11-slim

# Instalamos todas las librerías necesarias para el Notebook 3 y Gemma 4
RUN pip install --no-cache-dir --default-timeout=100 \
    jupyterlab \
    langchain-nvidia-ai-endpoints \
    langchain-core \
    langserve \
    sse-starlette \
    gradio \
    requests \
    rich

WORKDIR /workspace
CMD ["jupyter", "lab", "--ip=0.0.0.0", "--port=8888", "--no-browser", "--allow-root", "--NotebookApp.token=''"]





