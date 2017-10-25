# MyWebSQL docker image

A docker image of mywebsql for easy db management

## MyWebSQL

MyWebSQL is a next generation web based application for database administration over the web.
It has a simple and intuitive interface, quick record addition/editing/saving features and plenty of tools to work with databases.

## Database Support

As of the current version, MyWebSQL works with MySQL4 / MySQL5 ,SQLite and PostgreSQL databases.
*BUT* this image only supports mysql5

## Features

- Application and context menus
- Multiple syntax highlighted sql editors
- Quick Inplace multi-record editing
- Zero configuration installation
- Multi dialog interface to allow multitasking
- Multiple server login supported
- Excellent support for major browsers
- WYSIWYG Table creator/editor
- Batch Import/Export modules
- Multilingual Interface
- UI Themes supported
- Other Datbaase tools (e.g. repair tables, alter indexes)

## How to run this image

```sh
docker run --link mysql:mysql -p 8080:80 -e REMOTE_ADDR=mysql -e SERVER_NAME=myserver ibandla/mywebsql
```
