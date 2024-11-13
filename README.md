## database name :

-   CRUDtest

## commande:

php artisan migrate
php artisan serv

## api :

## (without auth):

http://127.0.0.1:8000/api(

-   post('/register')
-   post('/login')
-   get('/products')
-   get('/products/{id}')
    )

## (with auth):

Authorization: Bearer <your_token> (Replace <your_token> with the actual token)

http://127.0.0.1:8000/api(

-   post('/logout')
-   post('/products')
-   put('/products/{id}')
-   delete('/products/{id}')
    )
