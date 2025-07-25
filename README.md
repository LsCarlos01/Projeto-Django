# Meu Projeto Django

Projeto de anotações e estudos feito com o Django, com auntenticação de usuários, criação de tópicos e anotações pessoais.
(Foi feito com base em um curso, com objetivo de aprender sobre o Django)

## Funcionalidades

- Cadastro e login de usuários
- Criação de tópicos personalizados
- Adição e edição de anotações
- Interface estilizada com Bootstrap 3

- ## Como rodar localmente

```bash
git clone https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git](https://github.com/LsCarlos01/Projeto-Django.git)
cd Projeto-Django
python -m venv venv
source venv/bin/activate  # ou venv\Scripts\activate no Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
