# Zephion App

## Como compilar e executar o código

Em primeiro lugar, é necessário instalar o [Arduino IDE](https://www.arduino.cc/en/software), juntamente com as bibliotecas necessárias para o ESP32. Em seguida, deve-se modificar as variáveis `ssid` e `password` no arquivo [`esp32/project.ino`](./esp32/project.ino) para que correspondam à sua rede Wi-Fi.

Após fazer essas alterações, você pode compilar e enviar o código para o ESP32 usando o Arduino IDE.

Para rodar o aplicativo Zephion desenvolvido em Django, é necessário ter o Python instalado. Você pode baixar a versão mais recente do Python em [python.org](https://www.python.org/downloads/).

Depois de instalar o Python, você pode instalar as dependências do projeto executando o seguinte comando no terminal:

```bash
python -m venv venv
source venv/bin/activate  # No Windows, use `venv\Scripts\activate
pip install -r requirements.txt
```

Em seguida, devemos criar o banco de dados e aplicar as migrações necessárias. Execute os seguintes comandos:

```bash
python manage.py makemigrations
python manage.py migrate
```

Para criar um superusuário, execute o seguinte comando:

```bash
python manage.py createsuperuser
```

Agora, você pode iniciar o servidor de desenvolvimento do Django com o seguinte comando:

```bash
python manage.py runserver
```

O aplicativo estará disponível em [http://127.0.0.1:8000](http://127.0.0.1:8000/).

## Licença

Este projeto é licenciado sob a Licença MIT. Consulte o arquivo [LICENSE](./LICENSE) para obter mais detalhes.
