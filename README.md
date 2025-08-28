# ◇───────◇ATIVIDADE-SQL-BEECROWD◇───────◇

## ✶⊶⊷⊶⊷❍⊶⊷⊶⊷✶ Nível 1 ✶⊶⊷⊶⊷❍⊶⊷⊶⊷✶

- 2603
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
    
- 2607
  <img width="1090" height="339" alt="Image" src="https://github.com/user-attachments/assets/af1368b6-0e8d-4dca-9ba7-5afd15725db7" />
    
    ```sql
    select 
    	city
    from 
    	providers
    order by city asc;
     
    ```
    
- 2608
  <img width="1106" height="331" alt="Image" src="https://github.com/user-attachments/assets/55cb7861-4a9f-4b7f-805a-4681e4d7a924" />
    
    ```sql
    select 
    	max(price),
      min(price)
    from
      products;
    ```
    
- 2615
  <img width="1101" height="333" alt="Image" src="https://github.com/user-attachments/assets/acc43f9b-8849-4404-941f-8ed1f9b31e8b" />
    
    ```sql
    select 
    	city
    from customers;
    ```
    
- 2617
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
    

---

## Nível 2

- ### 2604
    
    <img width="1087" height="33" alt="Image" src="https://github.com/user-attachments/assets/8a2ebc5b-6fd7-4e79-86e7-dd3133fdc283" />
    
    <img width="1090" height="469" alt="Image" src="https://github.com/user-attachments/assets/2c9e70f6-9849-4a78-ad71-359e4332b3ad" />
    
- ### 2613
    
    <img width="1080" height="36" alt="Image" src="https://github.com/user-attachments/assets/539c6027-9bb7-4ab7-adfb-297aa01e054e" />
    
    <img width="1102" height="577" alt="Image" src="https://github.com/user-attachments/assets/3895d175-a66b-4bcb-9a2b-cf09a7b3ce83" />
    

---

Nível 3

- 2610
    
    ![image.png](attachment:b5ee6f7f-60e1-4292-b1bb-1482fc5c351a:image.png)
    
    ![image.png](attachment:3b787ff3-664b-43ab-baca-46291fd9f98d:image.png)
    
- 2618
    
    ![image.png](attachment:56d6e110-6aa7-4e70-97cd-e01660379784:image.png)
    
    ![image.png](attachment:8416d4c0-4145-4434-9499-4a5cec79546e:image.png)
    

---

Nível 4

- 2602
    
    ![image.png](attachment:f35254c0-2aa6-4104-bc1b-c6681c078178:image.png)
    
    ![image.png](attachment:b7160674-3aa4-42df-a777-d93140a8058c:image.png)
    

---

Nível 5

- 2616
