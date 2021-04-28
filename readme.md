## mongo with docker
- run docker-compose up


## Download Mongo

https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/



## Download Client

https://studio3t.com/download/?utm_source=adwords&utm_medium=ppc&utm_term=mongo%20explorer&utm_campaign=GS+%7C+Long-Tail+%7C+Israel&hsa_net=adwords&hsa_ad=408187652634&hsa_src=g&hsa_ver=3&hsa_grp=58254899643&hsa_acc=1756351187&hsa_tgt=kwd-312473395350&hsa_mt=b&hsa_kw=mongo%20explorer&hsa_cam=1537319229&gclid=Cj0KCQjwppSEBhCGARIsANIs4p4H8lviTYkrvZvpRsp0kouzehLzedB92G5lnTlynQquYWwzJorcpj0aApd7EALw_wcB

https://robomongo.org/download


## Insall Mongo
1. run the MSI file
2. Run Mongodb 



## MongoDB docs:
https://docs.mongodb.com/manual/tutorial/query-documents/



## Subjects Learned
- find
- findOne
- findAndDelete
- Where : exact match, gt, gte,le,lte, and or

- example:

db.getCollection("cars").find({"$or": [{ "Cylinders": {"$gte": 2  } }, 
     { "Acceleration": {"$gte": 16  } } , { "$and": [  { "Displacement":318 },
         { "Horsepower":150 }  ] } ]  }); // select * from cars where Acceleration >= 8 



- update ( with $set )


## Homework

1. Update - try to update many documents (UpdateMany)
2. Update - try to update only 1 document (Update)
3. try to use sort method and bring result sorted by Horsepower find().sort() <=> order by
4. How to bring specific field ( the second parameter in find) <=> find({},{SECOND PARAMS})