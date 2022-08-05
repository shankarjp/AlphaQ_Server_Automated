# Task 2

## Normal Mode

AlphaQ wants to shift operations to the new headquarters. But manually shifting
operations is a very difficult task. Your manager Sakthi wants you to automate
this shifting process with Docker.

- You need to dockerise the server setup done in task 1.
- Using an appropriate base image (eg. Ubuntu), copy all the scripts to the
  appropriate locations and run them accordingly.

## Superuser Mode

- Create a database to store MoMs instead of files in the users' directory. Use
  only MySQL or PostgreSQL. SQLite is not allowed.
- You may use any programming language to do the above. Use raw SQL queries to
  do this, do not use ORMs (eg. SQLAlchemy).
- Dockerise the database along with the normal mode. Use docker-compose.
- Make sure restarting the docker container does not destroy the data.
- Add PHPMyAdmin service for viewing the database.
- Create an account with read-only permissions to read the MOMs present in the
  DB.

## Deadline

26th June 2021 | 11.59 pm

_NOTE: Normal mode is necessary to complete the task. Superuser mode is highly
encouraged_

## Resources

1. [Docker Docs](https://docs.docker.com/get-started/)
2. [Docker Compose Docs](https://docs.docker.com/compose/)
3. [Docker Compose Docs - TutorialsPoint](https://www.tutorialspoint.com/docker/docker_compose.htm)
4. [YouTube Tutorial for Docker](https://www.youtube.com/playlist?list=PLhW3qG5bs-L99pQsZ74f-LC-tOEsBp2rK)
5. [YouTube Tutorial for Docker Compose](https://www.youtube.com/playlist?list=PL_jn5jikluSKecZf55QbKmnN195HL-o78)
6. [SQL Tutorial by W3Schools](https://www.w3schools.com/sql/default.asp)
7. [MySQL Docs](https://dev.mysql.com/doc/refman/8.0/en/)
8. [PostgreSQL Docs](https://www.postgresql.org/docs/current/)
9. [PostgreSQL online resources](https://www.postgresql.org/docs/online-resources/)
