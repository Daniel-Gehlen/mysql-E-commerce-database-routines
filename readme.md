**Report on Database Query Optimization and Utilization of Procedures**

---

### Introduction

This report aims to analyze and document the techniques employed in optimizing queries in an e-commerce database, as well as the use of procedures for efficient data manipulation. The goal is to ensure efficient system performance by improving access speed to information and simplifying data management.

![photo](/ecommercedb-routines.png)

### Methods

#### Query Optimization

To optimize queries, three frequent queries were identified and appropriate indexes were created to improve system performance. Indexes were chosen based on the most accessed and relevant data for each query, taking into account factors such as cardinality and selectivity.

Indexes were created using SQL language, specifically commands like `CREATE INDEX`, applied to relevant tables in the database. For each index, a set of columns that best represented the associated queries was defined to optimize search and reduce response time.

#### Utilization of Procedures

To simplify data manipulation, a procedure named `ManipulateCustomers` was created. This procedure allows insertion, update, and deletion operations of customers in the database. The procedure was developed using SQL language and allows flexible interaction with data, accepting parameters that determine the action to be performed and the data to be manipulated.

### Results

After implementing query optimization techniques and utilizing procedures, significant improvements in system performance were observed. Queries became executed more efficiently, providing faster responses to users. Additionally, the use of procedures simplified data manipulation, reducing the complexity of operations and ensuring data integrity in the database.

### Conclusion

Query optimization and the utilization of procedures are fundamental techniques to ensure efficient performance and effective data management in an e-commerce database. By choosing appropriate indexes and developing efficient procedures, it's possible to significantly improve system performance and provide a better user experience.

### Case Study

A practical case study can be conducted to evaluate the impact of the implemented techniques on system performance. This would involve comparing query response times before and after optimization, as well as assessing the ease of use and effectiveness of procedures in data manipulation. This practical analysis would help validate the effectiveness of the techniques used and identify possible areas of continuous improvement in the e-commerce database system.

---

I hope this report provides a comprehensive overview of the techniques used and their benefits in the context of query optimization and data manipulation in an e-commerce database. If you need anything else, I'm here to help!
