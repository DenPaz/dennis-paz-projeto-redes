# Projeto Final

Este é um aplicativo web full-stack desenvolvido em Django, que serve como um projeto final para a disciplina de Redes sem Fio (DEC7563-07655) da Universidade Federal de Santa Catarina (UFSC).

## Estrutura do Projeto

```
dennis-paz-projeto-redes/
├── codigo/
│   ├── apps/               # Aplicativos Django
│   │   ├── core/           # Aplicativo com funções gerais
│   │   ├── dashboard/      # Aplicativo para o dashboard
│   │   ├── sensors/        # Aplicativo para sensores
│   │   └── users/          # Aplicativo para gerenciamento de usuários
│   ├── config/
│   │   ├── settings/       # Configurações do Django
│   │   ├── urls.py         # URLs do projeto
│   │   ├── api_routers.py  # Roteadores da API
│   │   └── wsgi.py         # Configuração WSGI do Django
│   ├── esp32/
│   │   └── project.ino     # Código do ESP32
│   ├── requirements/         # Dependências do projeto
│   ├── static/           # Arquivos estáticos (CSS, JS, imagens)
│   ├── templates/        # Templates HTML
│   ├── manage.py         # Script de gerenciamento do Django
│   ├── README.md         # Descrição do projeto
├── relatorio/
│   ├── relatorio.pdf     # Relatório do projeto
```

## Como Compilar e Executar o Código

Para entrar em detalhes sobre como compilar e executar o código, consulte o arquivo [`README.md`](codigo/README.md) localizado na pasta `codigo/`. Este arquivo contém instruções específicas sobre como configurar o ambiente, instalar dependências e executar o aplicativo.
