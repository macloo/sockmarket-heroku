# Example Heroku database app: sockmarket2

This is a fairly basic Flask app that started out with a SQLite database that has only one table.

The SQLite database was manually migrated to a PostgreSQL database hosted at Heroku. The Flask app file was then edited to read the remote database while running locally. (That part is easy, thanks to Flask-SQLAlchemy.)

The purpose of the app is to demonstrate how to build a simple database app with Flask. The app allows you to view records for a fictional collection of socks. Each sock has a name, color, price, quantity (in stock), and the date when the record was last updated. In the database, there's also a unique ID for each record.

## Heroku deployment

Instructions for getting started with Heroku, setting up PostgreSQL locally, migrating the database, and finally, deploying the Flask app to Heroku are explained in detail in this Google doc:

https://bit.ly/mm-heroku

This app is running on a free "Hobby"-level account at Heroku.

.
