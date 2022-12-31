####[[SQL]]
Un triger es una funcion llamada automaticamente al ocurrir ciertos eventos:
+ **Antes** de intentar una operacion respecto a una tupla, **antes** de que las restricciones sean evaluadas y el ``INSERT``, ``UPDATE ``o ``DELETE`` es intentado
+ Cuando una operacion ha sido completada (luego de evaluar las restyricciones y realizar la operacion)
+ etc

## Crear un trigger
For creating a new PostgreSQL Trigger, you need to follow these steps:

-   First, you need to create a trigger function using **CREATE FUNCTION** statement.
-   Then you need to bind the trigger function to a table by using **CREATE TRIGGER** statement.

```ad-example

```
```plsql
create function SP_Test() returns Trigger
as
$$
begin
insert into "Log:Triggers" values (new.nombre)/(old.nombre)

end
$$
Language plpgsql

create trigger TR_Update before Update on planilla
for each row
execute procedure SP_Test();
```
```
```

```ad-example
```sql
CREATE FUNCTION check_valid_date_answer() RETURNS trigger
    LANGUAGE plpgsql
    AS $$BEGIN
  IF (SELECT "Content".date FROM "Content"
      WHERE "Content".id = NEW.idAnswer)
   < (SELECT "Content".date FROM "Content"
      WHERE "Content".id = NEW.idQuestion) 
  THEN
    RAISE NOTICE 'This Answer is an invalid date';
  END IF;
  RETURN NEW;
END;$$;
```
```sql
CREATE TRIGGER check_valid_answer 
AFTER INSERT ON "Answer"
FOR EACH ROW EXECUTE PROCEDURE check_valid_date_answer();
```


```ad-example
```
```sql
raise exception 'Say something useful about %', some_variable;
```

