# hello-world
Just another repository from HELP

-- Select all user's names of databases from server 
SELECT name
FROM sys.databases

--Select all tables from DB
SELECT * 
FROM sys.objects
WHERE type in (N'U')
