# Database Backup and Restore

## Why Backup?

- Recover deleted data
- Disaster recovery
- Migration
- Testing

---

## Types

### Full Backup

Complete database backup.

### Incremental Backup

Only changed data.

### Differential Backup

Changes since last full backup.

---

## MySQL Backup

```bash
mysqldump -u root -p database_name > backup.sql
```

---

## Restore

```bash
mysql -u root -p database_name < backup.sql
```

---

## Best Practices

- Schedule backups
- Verify backups
- Store offsite copies
