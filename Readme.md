Bibliotecas para serem instaladas:

pip install streamlit
pip install psycopg2
pip install python-dotenv

Para Rodar :

1° Ligar o Docker
(Se precisar criar outro Docker esse é o comando:
docker run --name my-postgres -e POSTGRES_PASSWORD=mysecretpassword -p 5433:5432 -d postgres:latest
)
2° Abrir o Postrges no Dbear e vê se está conectado e se as tabelas estão normais
3° Rodar o arquivo ligar_connect na pasta services, para conectar com o postgres