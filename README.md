# CAP-теорема и СУБД

Согласно теореме CAP, системы распределенных баз данных могут обеспечить только два из трех свойств - согласованность (consistency), доступность (availability) и устойчивость к разделению (partition tolerance).

### DragonFly 
DragonFly является децентрализованной СУБД, поддерживающей различные комбинации свойств CAP в зависимости от конфигурации.

### ScyllaDB 
ScyllaDB - распределенная NoSQL СУБД, ориентированная на обеспечение высокой доступности, что указывает на вероятную ориентацию на свойства доступности и устойчивости к разделению (AP).

### ArenadataDB 
ArenadataDB ориентирована на обеспечение согласованности данных в распределенной среде, что указывает на вероятную ориентацию на свойства согласованности и устойчивости к разделению (CP).

Таким образом, при проектировании и архитектуре распределенных баз данных важно учитывать теорему CAP и свойства каждой конкретной СУБД.
