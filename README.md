

<h1 align="center">📊👋 DataBye</h1>
<h2 align="center">CLI Database & File Anonymizer</h2>

<div align="center">

[![npm](https://img.shields.io/npm/v/databye)](https://www.npmjs.com/package/databye)
[![XO code style](https://img.shields.io/badge/code_style-XO-5ed9c7.svg)](https://github.com/xojs/xo)
[![GitHub Repo stars](https://img.shields.io/github/stars/nitzano/databye?style=flat)](https://github.com/nitzano/databye/stargazers)
![GitHub License](https://img.shields.io/github/license/nitzano/databye)
![npm](https://img.shields.io/npm/dw/databye)

</div>

Databye is a command-line tool to anonymize and transform sensitive data in databases, files, and datasets without writing a single line of code. It supports various databases types and file formats. 


# Usage

NPM:
```
npx databye <command> [options]
```

PNPM:
```
pnpm dlx databye <command> [options]
```

YARN:
```
yarn dlx databye <command> [options]
```

## Local install

You can also add `databye` locally

```
npm i --save-dev databye

yarn add -D databye

pnpm add -D databye
```

# CLI

## anon-col 

Anonymize a single column

```
Usage: databye anon-col [options] [command]

Anonymize a single column in a table

Options:
  -e --engine <engine>           Engine (choices: "postgres", "mongo", "mariadb", "mysql", "mssql")
  --confirm                      Confirm before running (default: true)
  --no-confirm                   skip confirmation
  -db --database <databaseName>  Database name
  -col --column <columnName>     Column name
  -t --table <tableName>         Table name
  -pass --password <password>    database password
  -srv --server <serverName>     server to connect to
  -u --uri <connectionString>    Connection string
  -usr --user <userName>         Username to use
  -h, --help                     display help for command

Commands:
  scramble                       scramble a single column
  mask [options]                 mask a single column
  help [command]                 display help for command
```

# ✅ Supported Databases

1. MongoDB 
2. PostgresSQL
3. MariaDB
4. MySQL
5. MSSQL
6. Neo4J (Coming Soon)
7. SQLite (Coming Soon)
8. DynamoDB (Coming Soon)
9. Redis (Coming Soon)

# ✅ Supported Files 

1. JSON (Coming Soon)
2. CSV (Coming Soon)
3. XML (Coming Soon)
4. XSLX (Coming Soon)
5. Parquet (Coming Soon)
6. YAML (Coming Soon)


# License

DataBye
Copyright (C) 2024 Nitzan Ohana

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.