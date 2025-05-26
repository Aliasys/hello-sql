# Hello SQL

[![SQL](https://img.shields.io/badge/MySQL-8.0+-f29221?style=for-the-badge&logo=mysql&logoColor=white&labelColor=101010)](https://mysql.com)
[![SQL](https://img.shields.io/badge/PostgreSQL-16+-699eca?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=101010)](https://postgresql.org)

## E

![](./Images/header.jpg)

### 7 horas | +80 lecciones | +50 comandos | con código | desde cero | completo | gratis

### Proyecto realizado durante emisiones en directo desde [Twitch](https://twitch.tv/mouredev)
> ##### Si consideras útil el curso, apóyalo haciendo "★ Star" en el repositorio. ¡Gracias!

## Curso completo en vídeo

<a href="https://youtu.be/OuJerKzV5T0"><img src="http://i3.ytimg.com/vi/OuJerKzV5T0/maxresdefault.jpg" style="height: 50%; width:50%;"/></a>

**Este es el curso completo en [vídeo](https://youtu.be/OuJerKzV5T0) de 7 horas en YouTube asociado al código de este repositorio.**

## Lecciones y código

[INTRODUCCIÓN]

1. [Bases de datos SQL](
2. [Sistema de gestión de base de datos]
3. [Fundamentos de SQL y bases de datos]
4. [Configuración e instalación]
5. [Primeros pasos]
6. [Conexión y cliente SQL]
7. [Inicialización de datos]
8. [Consulta de datos: `SELECT`] ➔ [[Código]](./01_Reading/01_select.sql)
9. [Modificadores: Parte 1]
	1. [`DISTINCT`] ➔ [[Código]](./01_Reading/02_distinct.sql)
	2. [`WHERE`]➔ [[Código]](./01_Reading/03_where.sql)
	3. [`ORDER BY`] ➔ [[Código]](./01_Reading/04_order_by.sql)
	4. [`LIKE`] ➔ [[Código]](./01_Reading/05_like.sql)
	5. [`AND, OR, NOT`] ➔ [[Código]](./01_Reading/06_and_or_not.sql)
	6. [`LIMIT`] ➔ [[Código]](./01_Reading/07_limit.sql)
10. [Modificadores: Parte 2]
	1. [`COMMENTS`] ➔ [[Código]](./01_Reading/00_comments.sql)
	2. [`NULL`]➔ [[Código]](./01_Reading/08_null.sql)
	3. [`MIN, MAX`][MIN(..)FROM']➔ [[Código]](./01_Reading/09_min_max.sql)
	4. [`COUNT`]['COUNT(..)FROM' depues'WHERE'] ➔ [[Código]](./01_Reading/10_count.sql)
	5. [`SUM`]['(..)FROM'] ➔ [[Código]](./01_Reading/11_sum.sql)
	6. [`AVG`]['AVG(..)'FROM'..'WHERE'] ➔ [[Código]](./01_Reading/12_avg.sql)
	7. [`IN`] ➔ [[Código]](./01_Reading/13_in.sql)
	8. [`BETWEEN`]['AND, OR, NOT']➔ [[Código]](./01_Reading/14_between.sql)
	9. [`ALIAS`]['AS'.... 'FROM...] ➔ [[Código]](./01_Reading/15_alias.sql)
	10. [`CONCAT`]['CONCAT(...)'FROM..''] ➔ [[Código]](./01_Reading/16_concat.sql)
	11. [`GROUP BY`]['AGRUPA AL FINAL'] ➔ [[Código]](./01_Reading/17_group_by.sql)
	12. [`HAVING`]['AL FINAL Y PONERLE CRITERIO COMO ALGO <O> POR EJEMPLO'] ➔ [[Código]](./01_Reading/18_having.sql)
	13. [`CASE`][' es como un for pero en SQL: te pongo un ejemplo: ## SELECT *,/n CASE/n WHEN age < 17 THEN 'Es mayor de edad' /n ELSE 'Es menor de edad' /n END AS agetext /n FROM users; ## ➔ [[Código]](./01_Reading/19_case.sql)
	15. [`IFNULL`][(..., DATO QUE QUIERAS CAMBIAR POR NULO)'] ➔ [[Código]](./01_Reading/08_null.sql)
	16. [Otros modificadores] ➔ [[Código]](https://www.w3schools.com/)
11. [Escritura de datos]
	1. [`INSERT`] ➔ [[Código]](./02_Writing/01_insert.sql)
	2. [`UPDATE`] ➔ [[Código]](./02_Writing/02_update.sql)
	3. [`DELETE`] ➔ [[Código]](./02_Writing/03_delete.sql)
12. [Administración de la base de datos]
	1. [`CREATE DATABASE`] ➔ [[Código]](./03_Database/01_create_database.sql)
	2. [`DROP DATABASE`] ➔ [[Código]](./03_Database/02_drop_database.sql)
13. [Administración de tablas]
	1. [`CREATE TABLE`]➔ [[Código]](./04_Tables/01_create_table.sql)
	2. [`NOT NULL`] ➔ [[Código]](./04_Tables/01_create_table.sql)
	3. [`UNIQUE`]➔ [[Código]](./04_Tables/01_create_table.sql)
	4. [`PRIMARY KEY`] ➔ [[Código]](./04_Tables/01_create_table.sql)
	5. [`CHECK`]➔ [[Código]](./04_Tables/01_create_table.sql)
	6. [`DEFAULT`] ➔ [[Código]](./04_Tables/01_create_table.sql)
	7. [`AUTO INCREMENT`] ➔ [[Código]](./04_Tables/01_create_table.sql)
	8. [`DROP TABLE`]➔ [[Código]](./04_Tables/02_drop_table.sql)
	9. [`ALTER TABLE`] ➔ [[Código]](./04_Tables/03_alter_table.sql)
	10. [`ADD`] ➔ [[Código]](./04_Tables/03_alter_table.sql)
	11. [`RENAME COLUMN`] ➔ [[Código]](./04_Tables/03_alter_table.sql)
	12. [`MODIFY COLUMN`] ➔ [[Código]](./04_Tables/03_alter_table.sql)
	13. [`DROP COLUMN`] ➔ [[Código]](./04_Tables/03_alter_table.sql)
14. [Relaciones entre tablas]
	1. [RELACIÓN `1:1`]
	2. [RELACIÓN `1:N`]
	3. [RELACIÓN `N:M`]
	4. [AUTOREFERENCIA]
15. [Creación de tablas relacionadas]
	1. [TABLAS `1:1`] ➔ [[Código]](./04_Tables/04_relationships.sql)
	2. [TABLAS `1:N`] ➔ [[Código]](./04_Tables/04_relationships.sql)
	3. [TABLAS `N:M`] ➔ [[Código]](./04_Tables/04_relationships.sql)
16. [Almacenamiento de datos relacionados]
	1. [DATOS `1:1`] ➔ [[Código]](./04_Tables/04_relationships.sql)
	2. [DATOS `1:N`]) ➔ [[Código]](./04_Tables/04_relationships.sql)
	3. [DATOS `N:M`] ➔ [[Código]](./04_Tables/04_relationships.sql)
17. [Consulta de datos relacionados]
	1. [`INNER JOIN`] ➔ [[Código]](./05_Join/01_inner_join.sql)
	2. [`LEFT JOIN`] ➔ [[Código]](./05_Join/02_left_join.sql)
	3. [`RIGHT JOIN`] ➔ [[Código]](./05_Join/03_right_join.sql)
	4. [`UNION`] ➔ [[Código]](./05_Join/04_union.sql)
18. [Conceptos avanzados]
	1. [`INDEX`] ➔ [[Código]](./06_Advanced/01_index.sql)
	2. [`TRIGGER`] ➔ [[Código]](./06_Advanced/02_triggers.sql)
	3. [`VIEW`] ➔ [[Código]](./06_Advanced/03_views.sql)
	4. [`STORED PROCEDURE`] ➔ [[Código]](./06_Advanced/04_stored_procedures.sql)
	5. [TRANSACCIONES] ➔ [[Código]](./06_Advanced/05_transactions.sql)
	6. [CONCURRENCIA]
19. [Conexión desde código]
	1. [CONECTORES]➔ [[Código]](./06_Advanced/06_connectors.py)
	2. [SQL INJECTION] ➔ [[Código]](./06_Advanced/06_connectors.py)
20. [Otros clientes SQL]
21. [PostgresSQL]
22. [Despliegue en la nube]
23. [Próximos pasos]

[CONCLUSIONES]

Durante el curso aprenderemos los fundamentos del lenguaje SQL y las bases de datos relacionales con ejemplos prácticos.
Nos centraremos en MySQL para llevar a cabo las clases, ya que es uno de los más usados en enseñanza y a nivel profesional. También utilizaremos PostgreSQL, por ser una de las bases de datos más populares de la actualidad. De todas formas, no debe preocuparte el motor de bases de datos utilizado, ya que SQL es un lenguaje estándar, por lo que se utilizará prácticamente igual en todas ellas. Una vez lo conozcas no tendrá dificultad alguna llevar esos conocimientos a otros sistemas.  

Todo el código creado durante el curso está disponible para que puedas consultarlo junto a su explicación.

> En el servidor de la comunidad de [Discord](https://discord.gg/mouredev) dispones de un canal llamado "💾bases-de-datos" para que puedas comentar lo que quieras.

## Enlaces de interés

* [Documentación SQL](https://www.w3schools.com/sql/default.asp)
* [MySQL](https://mysql.com)
* [Descarga MySQL](https://dev.mysql.com/downloads/mysql/)
* [CLI MySQL](https://dev.mysql.com/doc/refman/8.0/en/mysql.html)
* [MySQL Workbench](https://dev.mysql.com/downloads/workbench)
* [PostgreSQL](https://www.postgresql.org)
* [Clever Cloud](https://www.clever-cloud.com)

## Únete al campus de programación de la comunidad

![https://mouredev.pro](./Images/pro.jpg)

#### Te presento [mouredev pro](https://mouredev.pro), mi proyecto más importante para ayudarte a estudiar programación y desarrollo de software de manera diferente.

> **¿Buscas un extra?** Aquí encontrarás mis cursos editados por lecciones individuales, para avanzar a tu ritmo y guardar el progreso. También dispondrás de ejercicios y correcciones, test para validar tus conocimientos, examen y certificado público de finalización, soporte, foro de estudiantes, reunionnes grupales, cursos exclusivos y mucho más.
> 
> Entra en **[mouredev.pro](https://mouredev.pro)** y utiliza el cupón **"PRO"** con un 10% de descuento en tu primera suscripción.

## ![https://mouredev.com](https://raw.githubusercontent.com/mouredev/mouredev/master/mouredev_emote.png) Hola, mi nombre es Brais Moure.
### Freelance full-stack iOS & Android engineer

[![YouTube Channel Subscribers](https://img.shields.io/youtube/channel/subscribers/UCxPD7bsocoAMq8Dj18kmGyQ?style=social)](https://youtube.com/mouredevapps?sub_confirmation=1)
[![Twitch Status](https://img.shields.io/twitch/status/mouredev?style=social)](https://twitch.com/mouredev)
[![Discord](https://img.shields.io/discord/729672926432985098?style=social&label=Discord&logo=discord)](https://mouredev.com/discord)
[![Twitter Follow](https://img.shields.io/twitter/follow/mouredev?style=social)](https://twitter.com/mouredev)
![GitHub Followers](https://img.shields.io/github/followers/mouredev?style=social)
![GitHub Followers](https://img.shields.io/github/stars/mouredev?style=social)

Soy ingeniero de software desde 2010. Desde 2018 combino mi trabajo desarrollando Apps con la creación de contenido formativo sobre programación y tecnología en diferentes redes sociales como **[@mouredev](https://moure.dev)**.

Si quieres unirte a nuestra comunidad de desarrollo, aprender programación, mejorar tus habilidades y ayudar a la continuidad del proyecto, puedes encontrarnos en:

[![Twitch](https://img.shields.io/badge/Twitch-Programación_en_directo-9146FF?style=for-the-badge&logo=twitch&logoColor=white&labelColor=101010)](https://twitch.tv/mouredev)
[![Discord](https://img.shields.io/badge/Discord-Servidor_de_la_comunidad-5865F2?style=for-the-badge&logo=discord&logoColor=white&labelColor=101010)](https://mouredev.com/discord) [![Pro](https://img.shields.io/badge/Cursos-mouredev.pro-FF5500?style=for-the-badge&logo=gnometerminal&logoColor=white&labelColor=101010)](https://moure.dev)
[![Link](https://img.shields.io/badge/Links_de_interés-moure.dev-14a1f0?style=for-the-badge&logo=Linktree&logoColor=white&labelColor=101010)](https://moure.dev) [![Web](https://img.shields.io/badge/GitHub-MoureDev-087ec4?style=for-the-badge&logo=github&logoColor=white&labelColor=101010)](https://github.com/mouredev)
