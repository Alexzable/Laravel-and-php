! Toate comenziile se ruleaza din comand promt din itneriorul proiectul 'restservices'

1. # install framework laraval

Comanda: composer global require laravel/installer

https://www.mynotepaper.com/install-laravel-and-basic-configurations - primul articol pentru configurari ce l-am urmarit
https://www.mynotepaper.com/build-laravel-restful-api-crud-with-authentication-using-passport/ - al doilea pentru creearea serviciului.

- in fisierul .env seteaza-ti in functie de baza ta de date
- numele la baza de date, username la mysql si parola la mysql.
- creeaza baza de date, cand se da run la aplicatie laravel se uita daca e creeata si aplica migrariile

2. We require to run the migration command. After migration, we will see some tables in the database:

Comanda: php artisan migrate

3. Rulezi aplicatia

Comanda: php artisan serve

- acum poti sa te loghezi si cu token sa faci requesturi cu postman sa-ti verifici
- http://localhost:8000/api/

General Info

a. .env - setariile la baza de date
b. folderul routes , fisierul 'api.php' sunt declarate toate rutele, ca sa stii cum sa apelezi
c. fisierul database/migrations ai fisierele comentariu si user care vor genera tabelele
d. fisierul app are cele 2 fisiere coment si user care reprezinta clasele(modelele)
e. fisierul app/Http/Controllers/API ai cele doua controllere pt comment si user unde este
	scrisa logica pentru functionalitati.
