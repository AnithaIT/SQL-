# SQL-
insert into Product (Created_On,Modified_On)
values('2015-08-12','2015-08-12');

INSERT INTO Contact (ContactId,First_Name,Last_Name,Phone_Number,Address_1,Address_2,Suburb,Postcode,State,Country,Created_On)
VALUES( '03','Jenny','Souza','98765439','47','Oaktree Street','Darling','3167','VIC','Australia','2015-08-12');

ALTER TABLE Order
ALTER COLUMN Contact int;

Select * from Product;

insert into UI (AppId,Name)
Values(NEWID(),'ANI');          
