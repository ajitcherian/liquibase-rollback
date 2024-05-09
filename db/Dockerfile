FROM liquibase/liquibase:4.18.0
COPY migration/*.xml /liquibase/migration/
COPY *.xml /liquibase/changelog/
COPY db.changelog_root.xml /liquibase/changelog/db.changelog_root.xml
COPY drivers/*.jar  /liquibase/internal/lib/
COPY drivers/*.jar  /liquibase/lib/
COPY drivers/*.jar  /liquibase/classpath/