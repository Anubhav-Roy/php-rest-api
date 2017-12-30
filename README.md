# php-rest-api
This project contains PhP scripts which can perform basic CRUD actions on the database via REST.

# ----Description----

PhP scripts are being used to interact with the DB when accessed through URLs. The routes are as follows :-

    - creation :- /api/product/create.php { Pass in the data through JSON POST}
    
    - deletion :- /api/product/delete.php { Pass the object's ID , which has to be deleted , through JSON POST}
    
    - update :- /api/product/update.php  { Pass the object's ID along with the new data, which has to be updated , through JSON POST}
    
    - read :- /api/product/read.php { Returns all the objects present in the database as a JSON array }
    
    - read a single object :- /api/product/product_info.php?id=xx { Where xx is the object's ID whose data will be returned }
    

# Models 

    -Product :-
    
        - ID
        
        - name
        
        - description
        
        - price
        
{ Included the database as well , with the working tables. }


# Screenshots

![create](https://user-images.githubusercontent.com/13213436/34451053-631b7158-ed40-11e7-9e24-59bc7f0fbd74.png)
![delete](https://user-images.githubusercontent.com/13213436/34451054-63486212-ed40-11e7-9812-bdca031ff935.png)
![read](https://user-images.githubusercontent.com/13213436/34451055-63754052-ed40-11e7-9a2a-7c80f4bb80fd.png)
![read_single](https://user-images.githubusercontent.com/13213436/34451056-63a1aff2-ed40-11e7-899c-0babf9aee92e.png)
![update](https://user-images.githubusercontent.com/13213436/34451057-63d1a130-ed40-11e7-98a0-c5b1cceeb24f.png)
