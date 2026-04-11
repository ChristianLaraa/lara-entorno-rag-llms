FROM python:3.11-slim

# Instalamos las librerías necesarias para el curso y Gemma 4
RUN pip install --no-cache-dir \
    jupyterlab \
    langchain-nvidia-ai-endpoints \
    langchain-core \
    requests \
    rich

WORKDIR /workspace

# Comando para iniciar Jupyter Lab
CMD ["jupyter", "lab", "--ip=0.0.0.0", "--port=8888", "--no-browser", "--allow-root", "--NotebookApp.token=''"]






