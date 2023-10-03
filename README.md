# Hormiguero

here are the steps to make this work:
1. create a new python environment:
    ```bash
    python3 -m venv <PROJECT_NAME>
    source <PROJECT_NAME>/bin/activate
    pip list --format freeze --outdated | sed 's/=.*//g' | xargs pip install --upgrade
    pip install -r requirements.txt
    
    ```