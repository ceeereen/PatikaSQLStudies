## 1. SORU
```
CREATE TABLE TEST(
	ıd SERIAL PRIMARY KEY,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
)

```

## 2.SORU
```
insert into TEST (name, birthday, email) values ('Dimitri', '2022-06-09', 'dologan0@vimeo.com');
insert into TEST (name, birthday, email) values ('Gianni', '2022-11-01', 'gbalaisot1@mtv.com');
insert into TEST (name, birthday, email) values ('Elsworth', '2022-11-09', 'ecochrane2@scientificamerican.com');
insert into TEST (name, birthday, email) values ('Wildon', '2022-01-14', 'wdeakan3@stanford.edu');
insert into TEST (name, birthday, email) values ('Lisa', '2022-05-10', 'lcortese4@mac.com');
insert into TEST (name, birthday, email) values ('Kanya', '2022-07-01', 'kdooley5@wisc.edu');
insert into TEST (name, birthday, email) values ('Pete', '2022-09-04', 'pmallaby6@pinterest.com');
insert into TEST (name, birthday, email) values ('Chev', '2022-07-28', 'cjoyner7@yahoo.co.jp');
insert into TEST (name, birthday, email) values ('Louie', '2022-05-07', 'lelmar8@newyorker.com');
insert into TEST (name, birthday, email) values ('Regina', '2022-01-04', 'ritchingham9@storify.com');
insert into TEST (name, birthday, email) values ('Kally', '2022-05-15', 'kmcgillegholea@4shared.com');
insert into TEST (name, birthday, email) values ('Ludwig', '2022-06-01', 'landresenb@4shared.com');
insert into TEST (name, birthday, email) values ('Anthia', '2022-10-06', 'acadlec@usnews.com');
insert into TEST (name, birthday, email) values ('Jakie', '2022-01-03', 'jludovicod@vk.com');
insert into TEST (name, birthday, email) values ('Nance', '2022-05-14', 'nbagniuke@google.co.uk');
insert into TEST (name, birthday, email) values ('Vidovic', '2022-03-11', 'vboutellierf@irs.gov');
insert into TEST (name, birthday, email) values ('Letty', '2022-06-18', 'lguernerg@t.co');
insert into TEST (name, birthday, email) values ('Gilligan', '2022-10-23', 'ggermainh@vkontakte.ru');
insert into TEST (name, birthday, email) values ('Meg', '2022-04-23', 'mandreei@webnode.com');
insert into TEST (name, birthday, email) values ('Hyacintha', '2022-08-20', 'hdacresj@scribd.com');
insert into TEST (name, birthday, email) values ('Holli', '2022-05-29', 'hbraderk@ed.gov');
insert into TEST (name, birthday, email) values ('Arlena', '2022-01-10', 'aattenbarrowl@ow.ly');
insert into TEST (name, birthday, email) values ('Lucius', '2022-02-12', 'leagleshamm@e-recht24.de');
insert into TEST (name, birthday, email) values ('Porty', '2022-08-14', 'pguden@whitehouse.gov');
insert into TEST (name, birthday, email) values ('Rose', '2022-07-04', 'raymericho@google.de');
insert into TEST (name, birthday, email) values ('Brear', '2022-06-04', 'balbonep@nps.gov');
insert into TEST (name, birthday, email) values ('Rakel', '2022-07-19', 'rstakerq@epa.gov');
insert into TEST (name, birthday, email) values ('Tilly', '2022-09-29', 'theffernonr@fda.gov');
insert into TEST (name, birthday, email) values ('Pier', '2022-02-23', 'pmuinos@ca.gov');
insert into TEST (name, birthday, email) values ('Cyndia', '2022-07-07', 'ctimbridget@amazon.com');
insert into TEST (name, birthday, email) values ('Alonso', '2022-08-13', 'aseggesu@stumbleupon.com');
insert into TEST (name, birthday, email) values ('Estrella', '2022-01-28', 'eburdisv@gmpg.org');
insert into TEST (name, birthday, email) values ('Robby', '2022-09-14', 'rcicconew@tumblr.com');
insert into TEST (name, birthday, email) values ('Orelia', '2022-04-02', 'oelliotx@youtu.be');
insert into TEST (name, birthday, email) values ('Caro', '2022-05-10', 'caikiny@g.co');
insert into TEST (name, birthday, email) values ('Court', '2022-06-13', 'collivez@networksolutions.com');
insert into TEST (name, birthday, email) values ('Jolynn', '2022-05-17', 'jramshaw10@xrea.com');
insert into TEST (name, birthday, email) values ('Astra', '2022-08-04', 'awardingly11@forbes.com');
insert into TEST (name, birthday, email) values ('Salomo', '2022-07-25', 'senderlein12@cam.ac.uk');
insert into TEST (name, birthday, email) values ('Lolita', '2022-04-02', 'lcallaby13@ted.com');
insert into TEST (name, birthday, email) values ('Cahra', '2022-05-07', 'cullett14@nps.gov');
insert into TEST (name, birthday, email) values ('Cherrita', '2022-05-07', 'cheaphy15@51.la');
insert into TEST (name, birthday, email) values ('Gabbie', '2022-02-14', 'graysdale16@hostgator.com');
insert into TEST (name, birthday, email) values ('Jada', '2022-05-28', 'jsteeden17@sfgate.com');
insert into TEST (name, birthday, email) values ('Torrie', '2022-08-03', 'tmenichini18@prweb.com');
insert into TEST (name, birthday, email) values ('Glenn', '2022-05-05', 'gwohlers19@npr.org');
insert into TEST (name, birthday, email) values ('Joli', '2022-01-23', 'jminall1a@nasa.gov');
insert into TEST (name, birthday, email) values ('Korney', '2022-02-07', 'kmeneely1b@delicious.com');
insert into TEST (name, birthday, email) values ('Fara', '2022-02-25', 'ftibb1c@gmpg.org');
insert into TEST (name, birthday, email) values ('Reggie', '2022-03-01', 'rgloy1d@rakuten.co.jp');



```

## 3.SORU
```
UPDATE TEST SET birthday = '1998-06-17' WHERE ıd = 2;*/

UPDATE TEST SET name =  'Ceren' WHERE ıd=3;


UPDATE TEST SET email='cerenucar1998@gmail.com' WHERE ıd = 3;

UPDATE TEST SET name = 'Murat', birthday = '1989-03-21' WHERE ıd = 5;
UPDATE TEST SET name = 'Anna' WHERE ıd = 6;


```

## 4.SORU
```
DELETE FROM TEST WHERE ıd = 4;


```

