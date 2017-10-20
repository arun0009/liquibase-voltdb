### liquibase-voltdb

Liquibase VoltDB support.

##### To deploy VoltDB procedure jar via liquibase, include below changeSet in your deployment xml.

```xml
    <changeSet id="2" author="arung">
        <customChange class="liquibase.ext.voltdb.change.UpdateClasses" jarFile="path/to/procedure.jar" />
    </changeSet>
```
