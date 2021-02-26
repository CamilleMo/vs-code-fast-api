FROM tiangolo/uvicorn-gunicorn-fastapi:python3.8

RUN apt-get update && \
    apt-get install -y zsh && \
    apt-get install -y curl && \
    curl -L https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh | sh && \
    chsh -s $(which zsh)