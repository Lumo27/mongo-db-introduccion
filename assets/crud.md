## CREATE

instruccion que indica que podemos agregar nuevos registros o a las tablas/colecciones de nuestra BD
* __MYSQL__:
    ```sql
    -- insercion simple
    INSERT INTRO products 
    SET name = "Teclado",
    price = 8999.99
    -- insecion multiple
    INSERT INTO products (name,price, stock) VALUES 
    ('Monitor',240.000,30),
    ('Teclado',90.000,24),
    ('Auriculares',120.000,20),
    ```