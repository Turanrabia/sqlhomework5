# sqlhomework5
- film tablosunda bulunan ve film ismi (başlık) 'n' karakteri ile biten en uzun (uzunluk) 5 film sıralayınız.
-- film tablosunda bulunan ve film ismi (başlık) 'n' karakteri ile biten en kısa (uzunluk) ikinci(6,7,8,9,10) 5 filmi(6,7,8,9,10) sıralayınız.
-- müşteri tablosunda bulunan soyadı sütununa göre azalan yapılanma sıralamasında mağaza_id 1 olmak sıralamayla ilk 4 veriyi sıralayınız.

SEÇİN  *  FROM FROM WHERE başlık LIKE  ' %n  ' LIKE BY BY BY DESC  LIMIT  5 ;
SEÇİN  *  FROM FROM WHERE başlık LIKE '  % n '  LIKE BY BY BY ASC OFFSET 6 LİMİT 10 ;  
SELECT  *  FROM müşteri NEREDE store_id = 1  SİPARİŞ BY lastn_name DESC  LIMIT  4 ;
