# Book Shop Docker Deployment

## Run

git clone <https://github.com/AlHamediHammam/book_shop_docker-main/blob/main/Readme.md> 

cd book_shop

# copy enviroment variables template to add your own variables
cp .env.example .env


# building and starting the container
docker compose up --build

# stopping
docker compose down

## Access

http://localhost

## Services

- Django backend
- PostgreSQL database   
- Nginx reverse proxy

## Notes

- Uses PostgreSQL instead of SQLite
- Environment variables via .env
