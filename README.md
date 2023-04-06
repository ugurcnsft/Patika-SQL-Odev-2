1#SORU - film tablosunda bulunan tüm sütunlardaki verileri replacement cost değeri 12.99 dan büyük eşit ve 16.99 küçük olma koşuluyla sıralayınız ( BETWEEN - AND yapısını kullanınız.)

1#CEVAP - SELECT * FROM film
WHERE replacement_cost BETWEEN 12.99 AND 16.99;

1#<img width="960" alt="1" src="https://user-images.githubusercontent.com/129968939/230353851-d52cff10-8c07-46e4-9a24-1d3823329c62.png">

2#SORU - .actor tablosunda bulunan first_name ve last_name sütunlardaki verileri first_name 'Penelope' veya 'Nick' veya 'Ed' değerleri olması koşuluyla sıralayınız. ( IN operatörünü kullanınız.)

2#CEVAP - SELECT first_name, last_name FROM actor
WHERE first_name IN ('Penelope', 'Nick', 'Ed');

2#<img width="960" alt="2" src="https://user-images.githubusercontent.com/129968939/230355864-fd572d6f-289f-444d-85f4-eaed14084025.png">

3#SORU - film tablosunda bulunan tüm sütunlardaki verileri rental_rate 0.99, 2.99, 4.99 VE replacement_cost 12.99, 15.99, 28.99 olma koşullarıyla sıralayınız. ( IN operatörünü kullanınız.)

3#CEVAP - SELECT * FROM film
WHERE (rental_rate IN (0.99, 2.99, 4.99)) AND (replacement_cost IN (12.99, 15.99, 28.99) )

3#<img width="960" alt="3" src="https://user-images.githubusercontent.com/129968939/230431956-8e412e56-c977-4a08-946c-fa13f1efaad5.png">
