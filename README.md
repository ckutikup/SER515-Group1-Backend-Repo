# SER515-Group1-Backend-Repo

Environment Configuration

Before running the backend server, you must create a `.env` file in the project root directory.

### Required Environment Variables

Create a file named **`.env`** and add the following:

```env
DB_USER=root
DB_PASSWORD=your_mysql_password
DB_HOST=127.0.0.1
DB_PORT=3306
DB_NAME=agile_db

SECRET_KEY=supersecretlocalkey123
ALGORITHM=HS256
ACCESS_TOKEN_EXPIRE_MINUTES=30
