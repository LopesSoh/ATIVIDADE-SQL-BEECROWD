# ◇───────◇ATIVIDADE-SQL-BEECROWD◇───────◇

## ✶⊶⊷⊶⊷❍⊶⊷⊶⊷✶ Nível 1 ✶⊶⊷⊶⊷❍⊶⊷⊶⊷✶

- ### 2603
  <img width="1103" height="336" alt="Image" src="https://github.com/user-attachments/assets/3d2bbb9d-cb6a-42f6-ae9c-939ac585ef04" />
    
    ```sql
    SELECT
    	name,
    	street
    FROM
    	 custumers
    WHERE
    	city LIKE '%Porto Alegre%';
    ```
    
- ### 2607
  <img width="1090" height="339" alt="Image" src="https://github.com/user-attachments/assets/af1368b6-0e8d-4dca-9ba7-5afd15725db7" />
    
    ```sql
    select 
    	city
    from 
    	providers
    order by city asc;
     
    ```
    
- ### 2608
  <img width="1106" height="331" alt="Image" src="https://github.com/user-attachments/assets/55cb7861-4a9f-4b7f-805a-4681e4d7a924" />
    
    ```sql
    select 
    	max(price),
      min(price)
    from
      products;
    ```
    
- ### 2615
  <img width="1101" height="333" alt="Image" src="https://github.com/user-attachments/assets/acc43f9b-8849-4404-941f-8ed1f9b31e8b" />
    
    ```sql
    select 
    	city
    from customers;
    ```
    
- ### 2617
  <img width="1093" height="322" alt="Image" src="https://github.com/user-attachments/assets/f556aa5c-2670-4ce5-a61d-8660aefbce69" />
    
    ```sql
    select 
    	products.name, 
    	providers.name
    from 
    	providers
    inner join products
        on products.id_providers = providers.id
    where providers.name = 'Ajax SA';
    ```
    
---
## ✶⊶⊷⊶⊷❍⊶⊷⊶⊷✶ Nível 2 ✶⊶⊷⊶⊷❍⊶⊷⊶⊷✶

- ### 2604
  <img width="1090" height="327" alt="Image" src="https://github.com/user-attachments/assets/858b4486-6e4f-4074-bfbf-a1e7f3df4807" />
    
    ```sql
    	  select
            id,name
        from 
            products
        where
            price <10 or price >100;
    ```
    
- ### 2613
- <img width="1102" height="319" alt="Image" src="https://github.com/user-attachments/assets/2a371465-963c-4795-8fbd-fff96ef7eb27" />
    
    ```sql
    select 
           movies.id, movies.name 
        from
            movies
        INNER join prices
            on movies.id_prices = prices.id
        where value < 2.00;
    ```    

---

## ✶⊶⊷⊶⊷❍⊶⊷⊶⊷✶ Nível 3 ✶⊶⊷⊶⊷❍⊶⊷⊶⊷✶

- ### 2610

```sql
select
	ROUND(AVG (price), 2) AS Preçomedio
from products;
```

- ### 2618

```sql
select
        products.name, providers.name, categories.name
    from
        products
    INNER JOIN providers
        on products.id_providers = providers.id
    INNER JOIN categories
        on products.id_categories = categories.id
    where 
        providers.name = 'Sansul SA'
        and categories.name = 'Imported';
```

---

## ✶⊶⊷⊶⊷❍⊶⊷⊶⊷✶ Nível 4 ✶⊶⊷⊶⊷❍⊶⊷⊶⊷✶
