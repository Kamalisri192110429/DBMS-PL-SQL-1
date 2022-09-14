# DBMS-PL-SQL-1
REATE DEFINER=`root`@`localhost` PROCEDURE `proc1`()
BEGIN
declare name varchar(20);
declare str varchar(20);
set name='navya';
set str=concat('hello ',name);
select str;
END
