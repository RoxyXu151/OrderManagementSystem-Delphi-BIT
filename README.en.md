# OrderManagementSystem-Delphi-BIT

[简体中文](README.md) | **English**

BIT database-design coursework: a Delphi VCL food-order management client backed by PostgreSQL, covering customer, restaurant, rider, and administrator roles.

## Requirements

Windows, Delphi, PostgreSQL, and a PostgreSQL ODBC driver matching the application bitness. Confirm exact versions against the course manual and source environment.

## Get the repository

```bash
git clone https://github.com/RoxyXu151/OrderManagementSystem-Delphi-BIT.git
cd OrderManagementSystem-Delphi-BIT
```

Private repositories require GitHub authentication. Relative paths and steps below start from this repository.

## Setup and entry point

Use the editor or reading tools described below; there is no shared command-line launch sequence.

## Configuration and preparation

Read 使用说明书.pdf and 设计文档.pdf first. Create a test database and review SQL脚本.sql before importing it. Set your own endpoint, database, and account in connection.ini and the ODBC data source. Physical backups can require a matching PostgreSQL version.

## Usage and outputs

Locate the Delphi .dpr project in the source directory and build it, or use the existing coursework demonstration executable. Log in with a role and check ordering, acceptance, delivery, and administration. Initialization can create or overwrite objects, so use an isolated test database.

## Repository map

- [SQL脚本.sql](SQL%E8%84%9A%E6%9C%AC.sql)
- [使用说明书.pdf](%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E%E4%B9%A6.pdf)
- [设计文档.pdf](%E8%AE%BE%E8%AE%A1%E6%96%87%E6%A1%A3.pdf)
- [Original detailed material](README.reference.md): historical design, screenshots, and notes are retained; use the checked setup guidance above where it differs.

## Verification and troubleshooting

Check client/ODBC bitness, connectivity, role permissions, and order state transitions. No unified automated test script or portable installer is supplied.

## Maintenance and contributions

Keep both READMEs in sync when functionality or usage changes. Report reproducible steps, environment versions, and sanitized logs. Describe the verification actually performed with each change.

## License and attribution

No standalone license file is present at the root; do not infer an open-source redistribution grant. Third-party material remains subject to its own terms.
