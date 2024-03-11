# ProductCategoryRelationshipOneTOMany


### Tech Stack Used
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?&style=for-the-badge&logo=java&logoColor=white) &nbsp;
![Spring](https://img.shields.io/badge/spring%20-%6DB33F.svg?&style=for-the-badge&logo=spring&logoColor=white) &nbsp;
![SpringBoot](https://img.shields.io/badge/spring_boot%20-%6DB33F.svg?&style=for-the-badge&logo=springboot&logoColor=white) &nbsp;
![Hibernate](https://img.shields.io/badge/hibernate_&_JPA_Repository%20-gray.svg?&style=for-the-badge&logo=hibernate&logoColor=white) &nbsp;


### Tools Used
![Intellij Idea](https://img.shields.io/badge/intellij_idea-000000.svg?style=for-the-badge&logo=intellijidea&logoColor=white) &nbsp;
![Postman](https://img.shields.io/badge/postman-FF6C37.svg?style=for-the-badge&logo=postman&logoColor=white) &nbsp;

---

#### To run application find file and run `ProductsApplication.java`  present at location `src/main/java/com/products` or run `Products-0.0.1-SNAPSHOT.jar` using command `java -jar Products-0.0.1-SNAPSHOT.jar`

#### CRUD operations on categories syntax

1. PostMapping <br>
      `
      http://localhost:8080/api/categories/
      `
      <br>
         {<br>
         &nbsp;&nbsp;&nbsp;&nbsp; "categoryId": 0,<br>
         &nbsp;&nbsp;&nbsp;&nbsp; "categoryName": "String",<br>
         &nbsp;&nbsp;&nbsp;&nbsp; "categoryDescription": "String",<br>
         &nbsp;&nbsp;&nbsp;&nbsp; "products": []<br>
         }<br><br>

2. PutMapping<br>
     `
     http://localhost:8080/api/categories/{id} 
     `
     <br>
        {<br>
        &nbsp;&nbsp;&nbsp;&nbsp; "id": 0,<br>
        &nbsp;&nbsp;&nbsp;&nbsp; "categoryId": 0,<br>
        &nbsp;&nbsp;&nbsp;&nbsp; "categoryName": "String",<br>
        &nbsp;&nbsp;&nbsp;&nbsp; "categoryDescription": "String",<br>
        &nbsp;&nbsp;&nbsp;&nbsp; "products": []<br>
        }<br><br>

3. GetMapping<br>
     `
     http://localhost:8080/api/categories/ 
     `
     <br><br>

4. GetMapping<br>
     `
     http://localhost:8080/api/categories/{id}
     `
     <br>
        {<br>
        &nbsp;&nbsp;&nbsp;&nbsp; "id": 0<br>
        }<br><br>

5. DeleteMapping<br>
     `
      http://localhost:8080/api/categories/{id}
     `
     <br>
        {<br>
        &nbsp;&nbsp;&nbsp;&nbsp; "id": 0<br>
        }<br>
     &nbsp;

#### CRUD operations on products syntax
1. PostMapping<br>
  `
   http://localhost:8080/api/products/
  `
   <br>
   {<br>
   &nbsp;&nbsp;&nbsp;&nbsp; "id": 0,<br>
   &nbsp;&nbsp;&nbsp;&nbsp; "name": "String",<br>
   &nbsp;&nbsp;&nbsp;&nbsp; "cost": 0.0,<br>
   &nbsp;&nbsp;&nbsp;&nbsp; "category": {<br>
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; "categoryId": 0,<br>
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; "categoryName": "String",<br>
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; "categoryDescription": "String",<br>
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; "products": []<br>
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}<br>
   }<br><br>

2. GetMapping<br>
    `
     http://localhost:8080/api/products/{id}
    `
    <br>
   {<br>
   &nbsp;&nbsp;&nbsp;&nbsp; "id": 0<br>
   }<br><br>

3. GetMapping<br>
   `
   http://localhost:8080/api/products/
   `
   <br><br>

4. DeleteMapping<br>
    `
   http://localhost:8080/api/products/{id}
    `
   <br>
   {<br>
   &nbsp;&nbsp;&nbsp;&nbsp; "id": 0<br>
   }<br><br>

5. PutMapping<br>
    `
   http://localhost:8080/api/products/{id}
    `
   <br>
   {<br>
   &nbsp;&nbsp;&nbsp;&nbsp; "id": 0,<br>
   &nbsp;&nbsp;&nbsp;&nbsp; "name": "String",<br>
   &nbsp;&nbsp;&nbsp;&nbsp; "cost": 0.0,<br>
   &nbsp;&nbsp;&nbsp;&nbsp; "category": {<br>
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; "categoryId": 0,<br>
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; "categoryName": "String",<br>
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; "categoryDescription": "String",<br>
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; "products": []<br>
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}<br>
   }<br><br>

---