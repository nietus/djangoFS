python -m venv env

.\env\Scripts\activate

pip install -r backend/requirements.txt

Ativar o front
cd frontend

npm install

npm run dev

Ativar o back
cd backend

python manage.py runserver

Env
É importante criar um arquivo .env dentro do frontend, com VITE_API_BASE_URL=http://localhost:8000/api/ para definir o caminho pro back

É importante criar um arquivo .env dentro do backend, com as credenciais de acesso ao banco.

Exemplo:

DB_NAME="teste"

DB_USER="postgres"

DB_PWD="1234"

DB_HOST="localhost"

DB_PORT="5432"
