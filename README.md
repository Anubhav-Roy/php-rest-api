# php-rest-api
This project contains PhP scripts which can perform basic CRUD actions on the database via REST.

----Description----

PhP scripts are being used to interact with the DB when accessed through URLs. The routes are as follows :-

    - creation :- /api/product/create.php { Pass in the data through JSON POST}
    
    - deletion :- /api/product/delete.php { Pass the object's ID , which has to be deleted , through JSON POST}
    
    - update :- /api/product/update.php  { Pass the object's ID along with the new data, which has to be updated , through JSON POST}
    
    - read :- /api/product/read.php { Returns all the objects present in the database as a JSON array }
    
    - read a single object :- /api/product/product_info.php?id=xx { Where xx is the object's ID whose data will be returned }
    

Models Used

    -Product :-
    
        - ID
        
        - name
        
        - description
        
        - price
        
{ Included the database as well , with the working tables. }
