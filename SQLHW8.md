```sql

-- test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
CREATE TABLE employee (
 	id INTEGER,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
);

-- Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

insert into employee (id, name, birthday, email) values (1, 'Cristie', '1982-08-08', 'cmoorey0@studiopress.com');
insert into employee (id, name, birthday, email) values (2, 'Shane', '1981-12-31', 'slyon1@joomla.org');
insert into employee (id, name, birthday, email) values (3, 'Jade', '1984-07-21', 'jshakeshaft2@nba.com');
insert into employee (id, name, birthday, email) values (4, 'Babs', '1983-02-15', 'bpine3@booking.com');
insert into employee (id, name, birthday, email) values (5, 'Liane', '1983-05-25', 'lmatthieson4@gizmodo.com');
insert into employee (id, name, birthday, email) values (6, 'Willard', '1983-01-23', 'wbushen5@cisco.com');
insert into employee (id, name, birthday, email) values (7, 'Yankee', '1983-09-10', 'ylondsdale6@slashdot.org');
insert into employee (id, name, birthday, email) values (8, 'Lina', '2008-06-12', 'ltotman7@scientificamerican.com');
insert into employee (id, name, birthday, email) values (9, 'Danya', '2006-12-21', 'dreedy8@go.com');
insert into employee (id, name, birthday, email) values (10, 'Michaelina', '2019-12-09', 'mlapthorne9@qq.com');
insert into employee (id, name, birthday, email) values (11, 'Paulie', '2005-04-19', 'pbeedona@geocities.jp');
insert into employee (id, name, birthday, email) values (12, 'Rowe', null, null);
insert into employee (id, name, birthday, email) values (13, 'Witty', '1988-06-23', 'wtuddallc@e-recht24.de');
insert into employee (id, name, birthday, email) values (14, 'Yettie', '1991-05-22', 'yrabld@theguardian.com');
insert into employee (id, name, birthday, email) values (15, 'Katinka', '2007-03-04', 'kohartigane@yelp.com');
insert into employee (id, name, birthday, email) values (16, 'Manolo', '1982-09-28', 'mcubbinellif@tinypic.com');
insert into employee (id, name, birthday, email) values (17, 'Ginnifer', '1997-04-30', 'gslaneyg@slate.com');
insert into employee (id, name, birthday, email) values (18, 'Lorne', '2000-10-28', 'lsaggh@blogspot.com');
insert into employee (id, name, birthday, email) values (19, 'Shelagh', '1991-01-21', 'skunathi@who.int');
insert into employee (id, name, birthday, email) values (20, 'Larisa', '1996-09-01', 'lszachniewiczj@opensource.org');
insert into employee (id, name, birthday, email) values (21, 'Alisander', '1992-02-08', 'alaityk@github.io');
insert into employee (id, name, birthday, email) values (22, 'Elwyn', '1993-12-24', 'eprosekl@google.cn');
insert into employee (id, name, birthday, email) values (23, 'Debora', '1986-08-15', 'ddoucem@bbb.org');
insert into employee (id, name, birthday, email) values (24, 'Joelle', '2003-05-22', 'jrhucroftn@surveymonkey.com');
insert into employee (id, name, birthday, email) values (25, 'Quincy', '2008-07-23', 'qcowlishawo@phoca.cz');
insert into employee (id, name, birthday, email) values (26, 'Ford', '2018-04-28', 'fgandarp@spiegel.de');
insert into employee (id, name, birthday, email) values (27, 'Lishe', '2003-10-04', 'linsworthq@imgur.com');
insert into employee (id, name, birthday, email) values (28, 'Astra', '2008-02-01', 'awhapplesr@xrea.com');
insert into employee (id, name, birthday, email) values (29, 'Nola', '2016-01-06', 'nelgars@hhs.gov');
insert into employee (id, name, birthday, email) values (30, 'Dorelia', '1996-12-13', 'dbirchenheadt@hatena.ne.jp');
insert into employee (id, name, birthday, email) values (31, 'Aldin', '2013-09-06', 'awiddowfieldu@sitemeter.com');
insert into employee (id, name, birthday, email) values (32, 'Dore', '2018-10-24', 'dsowlev@pen.io');
insert into employee (id, name, birthday, email) values (33, 'Tripp', '1980-09-07', 'tvandrillw@sitemeter.com');
insert into employee (id, name, birthday, email) values (34, 'Windy', '1989-08-12', 'wdachsx@patch.com');
insert into employee (id, name, birthday, email) values (35, 'Chick', '1985-06-21', 'cwarrey@wired.com');
insert into employee (id, name, birthday, email) values (36, 'Sally', '2000-03-07', 'sstowgillz@tinypic.com');
insert into employee (id, name, birthday, email) values (37, 'Berna', '2000-06-05', 'bghost10@apache.org');
insert into employee (id, name, birthday, email) values (38, 'Jen', '1992-02-21', 'jbullivant11@ca.gov');
insert into employee (id, name, birthday, email) values (39, 'Chanda', '1991-07-14', 'csenussi12@rediff.com');
insert into employee (id, name, birthday, email) values (40, 'Dulsea', '2011-02-12', 'dchetwind13@nba.com');
insert into employee (id, name, birthday, email) values (41, 'Reinaldos', '1995-05-21', 'rtippin14@ibm.com');
insert into employee (id, name, birthday, email) values (42, 'Hazel', '2021-07-28', 'hdiruggiero15@mysql.com');
insert into employee (id, name, birthday, email) values (43, 'Melesa', '1994-04-12', 'mvogel16@reuters.com');
insert into employee (id, name, birthday, email) values (44, 'Tirrell', '2015-08-13', 'tberisford17@yahoo.com');
insert into employee (id, name, birthday, email) values (45, 'Kelsy', '2008-10-06', 'kcatonne18@unicef.org');
insert into employee (id, name, birthday, email) values (46, 'Rosanne', '2004-09-26', 'rbeedle19@vkontakte.ru');
insert into employee (id, name, birthday, email) values (47, 'Bernette', '1998-04-20', 'bscandrett1a@alexa.com');
insert into employee (id, name, birthday, email) values (48, 'Tate', '1993-02-12', 'tbartalot1b@1688.com');
insert into employee (id, name, birthday, email) values (49, 'Marge', '2007-08-24', 'mgager1c@uol.com.br');
insert into employee (id, name, birthday, email) values (50, 'Elly', '2010-06-23', 'etayspell1d@ehow.com');


-- Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
UPDATE employee
SET name = 'Ali'
WHERE id = 1
RETURNING *;

UPDATE employee
SET birthday = '1988-06-13'
WHERE id = 2
RETURNING *;

UPDATE employee
SET name = 'Mustafa Sinan'
WHERE birthday = '1988-06-13'
RETURNING *;

UPDATE employee
SET name = 'Ahmed'
WHERE name LIKE 'A%'
RETURNING *;

UPDATE employee
SET email = 'a@a.com'
WHERE name IN ('Ahmed','Ali')
RETURNING *;

-- Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
DELETE FROM employee
WHERE name ILIKE 'b%'
RETURNING *;

DELETE FROM employee
WHERE birthday > '1995-01-01'
RETURNING *;

DELETE FROM employee
WHERE name = 'Yankee'
RETURNING *;

DELETE FROM employee
WHERE id = 12
RETURNING *;

DELETE FROM employee
WHERE name = 'Mustafa Sinan'
RETURNING *;

```
