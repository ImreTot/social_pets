# Social pets
## _Social network for yout cat🐱, dog🐶 and every cute (or not) creature_🐰🐸🐍

### Powered by

[![N|Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org/)
[![N|Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=green)](https://www.djangoproject.com/)
[![N|DRF](https://img.shields.io/badge/django%20rest-ff1709?style=for-the-badge&logo=django&logoColor=white)](https://www.django-rest-framework.org/)
[![N|PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)  
[![N|HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://html.spec.whatwg.org/multipage/)
[![N|CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)
[![N|JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)](https://www.ecma-international.org/publications-and-standards/standards/ecma-262/)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)  
[![N|Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![N|Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)](https://nginx.org)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)

## Description
WEB application for publishing photos of pets. Users can create accounts, leave pictures of animals with descriptions, and view posts by other authors.

## Installation

Feel free to install and explore this project.  
If you want to get deep into code, you should clone repo. Run this command:
```sh
git clone git@github.com:ImreTot/social_pets.git
```
We recommend running the frontend and Nginx in Docker containers. In this case, execute the following command from the root directory:
```shell
docker compose up
```
However, you can run only the backend using the Django server.
First, create a virtual environment in the `backend/` directory.
>We use `Python3.9`
```shell
python3.9 - m venv .venv
```
Then, install the requirements:
```shell
pip install -r requirements.txt
```
Another option is to run the entire project using only Docker features. In that case, you need only docker-compose.production.yml. Don't forget to create an `.env` file in the root directory. Here is the list of variables:

- DJANGO_SECRET_KEY
- DJANGO_ALLOWED_HOSTS
- POSTGRES_USER
- POSTGRES_PASSWORD
- POSTGRES_DB
- DB_HOST
- DB_PORT

This project uses GitHub Actions. You can find the settings file kittygram_workflow.yml in the root directory. It now runs after any commit in the project's repository.

## About me
I'm Roman Kiyashko, a Python developer from the southern Russian city. I'm also a journalist. Technology, science, education, music, and extreme sports are the four pillars of my productive work.
You can contact me through one of these ways:

- Telegram: https://t.me/MDPaul
- Email: kiiashko.r@gmail.com
- Facebook: https://www.facebook.com/kiiashko.r/

## License

MIT

**Free Software, Hell Yeah!**
