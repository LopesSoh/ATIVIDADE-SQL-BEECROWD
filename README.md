# ◇───────◇ATIVIDADE-SQL-BEECROWD◇───────◇
<img width="1738" height="367" alt="Image" src="https://github.com/user-attachments/assets/b614627b-e1f2-410f-b0d4-ad2b1b589613" />

## ✶⊶⊷⊶⊷❍⊶⊷⊶⊷✶ Nível 1 ✶⊶⊷⊶⊷❍⊶⊷⊶⊷✶

- ### ∴ ════ ∴ ❈ ∴ ════ ∴ 2603 ∴ ════ ∴ ❈ ∴ ════ ∴
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
    
- ### ∴ ════ ∴ ❈ ∴ ════ ∴ 2607 ∴ ════ ∴ ❈ ∴ ════ ∴
  <img width="1090" height="339" alt="Image" src="https://github.com/user-attachments/assets/af1368b6-0e8d-4dca-9ba7-5afd15725db7" />
    
    ```sql
    select 
    	city
    from 
    	providers
    order by city asc;
     
    ```
    
- ### ∴ ════ ∴ ❈ ∴ ════ ∴ 2608 ∴ ════ ∴ ❈ ∴ ════ ∴
  <img width="1106" height="331" alt="Image" src="https://github.com/user-attachments/assets/55cb7861-4a9f-4b7f-805a-4681e4d7a924" />
    
    ```sql
    select 
    	max(price),
      min(price)
    from
      products;
    ```
    
- ### ∴ ════ ∴ ❈ ∴ ════ ∴ 2615 ∴ ════ ∴ ❈ ∴ ════ ∴
  <img width="1101" height="333" alt="Image" src="https://github.com/user-attachments/assets/acc43f9b-8849-4404-941f-8ed1f9b31e8b" />
    
    ```sql
    select 
    	city
    from customers;
    ```
    
- ### ∴ ════ ∴ ❈ ∴ ════ ∴ 2617 ∴ ════ ∴ ❈ ∴ ════ ∴
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

- ### ∴ ════ ∴ ❈ ∴ ════ ∴ 2604 ∴ ════ ∴ ❈ ∴ ════ ∴
  <img width="1090" height="327" alt="Image" src="https://github.com/user-attachments/assets/858b4486-6e4f-4074-bfbf-a1e7f3df4807" />
    
    ```sql
    	  select
            id,name
        from 
            products
        where
            price <10 or price >100;
    ```
    
- ### ∴ ════ ∴ ❈ ∴ ════ ∴ 2613 ∴ ════ ∴ ❈ ∴ ════ ∴
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

- ### ∴ ════ ∴ ❈ ∴ ════ ∴ 2610 ∴ ════ ∴ ❈ ∴ ════ ∴
  <img width="1099" height="334" alt="Image" src="https://github.com/user-attachments/assets/1b33f72a-13a7-429d-b089-2a124ece7e04" />

```sql
select
	ROUND(AVG (price), 2) AS Preçomedio
from products;
```

- ### ∴ ════ ∴ ❈ ∴ ════ ∴ 2618 ∴ ════ ∴ ❈ ∴ ════ ∴
  <img width="826" height="250" alt="Image" src="https://github.com/user-attachments/assets/db864297-ec95-4f37-ac76-0cb9ab02f8aa" />

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

- ### ∴ ════ ∴ ❈ ∴ ════ ∴ 2602 ∴ ════ ∴ ❈ ∴ ════ ∴
- <img width="827" height="254" alt="Image" src="https://github.com/user-attachments/assets/7fb12e84-9167-4288-8387-3665bd5a77ac" />

```sql
select 
   name 
from 
   customers
where 
   state like '%RS%';
```

---

## ✶⊶⊷⊶⊷❍⊶⊷⊶⊷✶ Nível 5 ✶⊶⊷⊶⊷❍⊶⊷⊶⊷✶
<img width="878" height="266" alt="Image" src="https://github.com/user-attachments/assets/e39dbbed-ae76-4eb4-a130-b1361727722f" />

- ### ∴ ════ ∴ ❈ ∴ ════ ∴ 2616 ∴ ════ ∴ ❈ ∴ ════ ∴

```sql
		select
        customers.id, customers.name
    from
        customers
    LEFT JOIN locations
        on customers.id = locations.id_customers
    where
        locations.id_customers IS NULL;
        
```

