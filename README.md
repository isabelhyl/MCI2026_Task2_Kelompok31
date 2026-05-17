# MCI2026_Task2_Kelompok31

# MCI2026_Task2_Kelompok31

how to run:

1. docker-compose build

2. docker-compose up airflow-init

3. docker-compose up -d

4. open http://localhost:8080 and login admin/admin

5. run "Trigger DAG" (the play button)
<img width="1846" height="325" alt="Screenshot 2026-05-17 202017" src="https://github.com/user-attachments/assets/4bb4a64e-d99d-4e6e-bb85-0265a3faabf0" />


7. docker exec -it mci2026_task2_kelompok31-clickhouse-server-1 clickhouse-client

8. check the database queries to see if everything works:
USE analytics;
SHOW TABLES;
SELECT * FROM top_products
<img width="1993" height="1375" alt="Screenshot 2026-05-17 201740" src="https://github.com/user-attachments/assets/92dfe106-4313-40f2-a5c2-5b535a3982f2" />
