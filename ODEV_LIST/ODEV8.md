# Odev 8
1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```sql
CREATE TABLE employee (
  id INTEGER PRIMARY KEY,
  name VARCHAR(50) NOT NULL,
  birthday DATE,
  email VARCHAR(100) 
);
```
2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```sql
insert into employee (id, name, birthday, email) values (1, 'Errol Scholard', '1988/08/17', 'escholard0@sina.com.cn');
insert into employee (id, name, birthday, email) values (2, 'Clarke Agg', '1988/01/07', 'cagg1@mit.edu');
insert into employee (id, name, birthday, email) values (3, 'Natasha Kohrt', '1980/12/28', 'nkohrt2@statcounter.com');
insert into employee (id, name, birthday, email) values (4, 'Earle Locarno', '1983/05/29', 'elocarno3@psu.edu');
insert into employee (id, name, birthday, email) values (5, 'Alistair Betterton', '1986/03/13', 'abetterton4@linkedin.com');
insert into employee (id, name, birthday, email) values (6, 'Cayla Burge', '1988/05/03', 'cburge5@parallels.com');
insert into employee (id, name, birthday, email) values (7, 'Sterne Ebbett', '1994/09/07', 'sebbett6@yale.edu');
insert into employee (id, name, birthday, email) values (8, 'Caralie Motherwell', '1991/07/13', 'cmotherwell7@state.tx.us');
insert into employee (id, name, birthday, email) values (9, 'Olly Evershed', '1979/10/24', 'oevershed8@skype.com');
insert into employee (id, name, birthday, email) values (10, 'Gregorius Sandever', '1988/09/17', 'gsandever9@time.com');
insert into employee (id, name, birthday, email) values (11, 'Linnea Sirette', '1988/03/22', 'lsirettea@ehow.com');
insert into employee (id, name, birthday, email) values (12, 'Gerda Le Friec', '1987/08/27', 'gleb@who.int');
insert into employee (id, name, birthday, email) values (13, 'Caron Capron', '1996/01/13', 'ccapronc@stumbleupon.com');
insert into employee (id, name, birthday, email) values (14, 'Viviene Lubomirski', '1987/05/15', 'vlubomirskid@forbes.com');
insert into employee (id, name, birthday, email) values (15, 'Blinnie Statefield', '1994/06/08', 'bstatefielde@hubpages.com');
insert into employee (id, name, birthday, email) values (16, 'Morey Rowswell', '1984/03/04', 'mrowswellf@goodreads.com');
insert into employee (id, name, birthday, email) values (17, 'Trula MacPaike', '1983/02/28', 'tmacpaikeg@whitehouse.gov');
insert into employee (id, name, birthday, email) values (18, 'Olive Graalmans', '1988/12/11', 'ograalmansh@odnoklassniki.ru');
insert into employee (id, name, birthday, email) values (19, 'Gib Murphy', '1979/07/06', 'gmurphyi@chron.com');
insert into employee (id, name, birthday, email) values (20, 'Jerry Readshall', '1998/05/30', 'jreadshallj@gizmodo.com');
insert into employee (id, name, birthday, email) values (21, 'Lennie Santarelli', '1997/11/21', 'lsantarellik@homestead.com');
insert into employee (id, name, birthday, email) values (22, 'Kelley Pedersen', '1980/10/08', 'kpedersenl@oaic.gov.au');
insert into employee (id, name, birthday, email) values (23, 'Fran Hutcheson', '1986/04/28', 'fhutchesonm@bluehost.com');
insert into employee (id, name, birthday, email) values (24, 'Elisabeth Merriday', '1988/11/08', 'emerridayn@domainmarket.com');
insert into employee (id, name, birthday, email) values (25, 'Bradan Writer', '1980/09/06', 'bwritero@ycombinator.com');
insert into employee (id, name, birthday, email) values (26, 'Ric Gleasane', '1989/12/03', 'rgleasanep@e-recht24.de');
insert into employee (id, name, birthday, email) values (27, 'Aurore Tolmie', '1983/10/03', 'atolmieq@addthis.com');
insert into employee (id, name, birthday, email) values (28, 'Brewster Letford', '1987/02/21', 'bletfordr@spiegel.de');
insert into employee (id, name, birthday, email) values (29, 'Lew Parmley', '1988/05/15', 'lparmleys@gizmodo.com');
insert into employee (id, name, birthday, email) values (30, 'Zerk Crotty', '1991/09/16', 'zcrottyt@altervista.org');
insert into employee (id, name, birthday, email) values (31, 'Peterus Hatchman', '1997/05/26', 'phatchmanu@simplemachines.org');
insert into employee (id, name, birthday, email) values (32, 'Lamont Kittman', '1989/11/12', 'lkittmanv@ycombinator.com');
insert into employee (id, name, birthday, email) values (33, 'Mab Episcopi', '1979/02/08', 'mepiscopiw@php.net');
insert into employee (id, name, birthday, email) values (34, 'Kim Stansall', '1984/07/05', 'kstansallx@jimdo.com');
insert into employee (id, name, birthday, email) values (35, 'Vanya Welham', '1994/06/14', 'vwelhamy@wikia.com');
insert into employee (id, name, birthday, email) values (36, 'Anett Grinval', '1996/12/10', 'agrinvalz@slideshare.net');
insert into employee (id, name, birthday, email) values (37, 'Jarrad Tayt', '1980/08/09', 'jtayt10@opensource.org');
insert into employee (id, name, birthday, email) values (38, 'Johanna Wardale', '1988/08/16', 'jwardale11@foxnews.com');
insert into employee (id, name, birthday, email) values (39, 'Eloise Hendrichs', '1985/08/05', 'ehendrichs12@hud.gov');
insert into employee (id, name, birthday, email) values (40, 'Evered Geraldini', '1986/09/03', 'egeraldini13@newyorker.com');
insert into employee (id, name, birthday, email) values (41, 'Rosemonde Watford', '1999/02/27', 'rwatford14@yahoo.co.jp');
insert into employee (id, name, birthday, email) values (42, 'Fransisco Drake', '1995/08/28', 'fdrake15@1und1.de');
insert into employee (id, name, birthday, email) values (43, 'Rachelle Wogan', '1992/05/31', 'rwogan16@time.com');
insert into employee (id, name, birthday, email) values (44, 'Cairistiona Clemenzi', '1987/03/20', 'cclemenzi17@latimes.com');
insert into employee (id, name, birthday, email) values (45, 'Birch Mundie', '1988/07/03', 'bmundie18@google.ca');
insert into employee (id, name, birthday, email) values (46, 'Laney Twell', '1989/04/11', 'ltwell19@samsung.com');
insert into employee (id, name, birthday, email) values (47, 'Marylin Mucklestone', '1989/12/09', 'mmucklestone1a@ovh.net');
insert into employee (id, name, birthday, email) values (48, 'Ermina Groom', '1998/09/25', 'egroom1b@berkeley.edu');
insert into employee (id, name, birthday, email) values (49, 'Karlotte Casewell', '1980/08/02', 'kcasewell1c@is.gd');
insert into employee (id, name, birthday, email) values (50, 'Hadley Cardoso', '1997/04/18', 'hcardoso1d@purevolume.com');
```
3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```sql
UPDATE employee
SET name = 'Lebron James',
	birthday = '1988-03-22',
	email = 'leb@james.com.tr'
WHERE id = 5;

UPDATE employee
SET name = 'Lionel Messi',
	birthday = '1977-03-22',
	email = 'mess@ilionel.io'
WHERE id = 6;

UPDATE employee
SET name = 'Rafael Nadal',
	birthday = '1981-04-15',
	email = 'rafa@nad.com'
WHERE id = 7;

UPDATE employee
SET name = 'Usain Bolt',
	birthday = '1978-07-24',
	email = 'usa123@bolt.com.edu'
WHERE id = 8;

UPDATE employee
SET name = 'Micheal Phelps',
	birthday = '1969-01-15',
	email = 'micPhel@mail.com'
WHERE id = 9;
```
4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```sql
DELETE FROM employee
WHERE id = 22;

DELETE FROM employee
WHERE name = 'Earle Locarno';

DELETE FROM employee
WHERE birthday = '1987-05-15';

DELETE FROM employee
WHERE id = 23;

DELETE FROM employee
WHERE email = 'escholard0@sina.com.cn';
```