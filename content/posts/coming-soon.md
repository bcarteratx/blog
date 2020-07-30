---
title: Comparing Relational and Non-relational Databases
date: "2020-06-19T22:40:32.169Z"
template: "post"
draft: false
slug: "comparing-database-types"
category: "Post"
tags:
  - "Database"
  - "MongoDB"
  - "PostgreSQL"
description: "A brief comparison of database types, exploring their basic structures, use cases, and strengths"
---

By the end of this guide, you will understand the differences between relational and non-relational databases.

No prior knowledge of databases is required for this guide. However, it is helpful if you have used spreadsheets and also have an understanding of basic programming concepts including objects. After finishing this guide you will be able to:
* define relational and non-relational database types
* understand the use cases for each database type
* list the advantages of each database type
* understand the basic structure of each database type

## Overview

Relational databases are the oldest and most commonly used data stores. If you have used spreadsheets, in programs such as Excel, you will be familiar with the overall structure of relational databases; storing data in tables using rows and columns. Commonly used databases include MySQL and PostgreSQL.

Non-relational, also known as NoSQL databases are quickly becoming popular data stores. Much like modern programming, non-relational databases use objects to store data. Commonly used non-relational databases include MongoDB and Cassandra.

## Relational Databases

Now that you understand that relational databases are comprised of tables, let’s take a closer look at their components and terminology. Each table is also known as a relation. The data contained in the relation is organized in rows (also known as a Tuple or Record) and cColumns (also known as an Attribute or field). A row is a data set that represents a single entity. Columns  are labeled elements of a tuple (think “last name”, “phone number”, etc.).

An important distinction of relational databases is that the exact structure of data must be known at the time of implementation, the data structure is set at this time and cannot be changed. This may seem inflexible but for many cases this is not a concern and with proper planning should not be an issue.

The advantages of relational databases are a key to their success. Since table based data has been used by many for such a long time, it’s no wonder why relational databases are popular, many are already familiar with the basic structure and conceptualization which makes the adoption easier. Another advantage is the ability to easily connect (join) tables so that you can compare or review data from multiple tables.  

Finally, the greatest advantage is possibly  this style of databases is its Accuracy. Due to the immutable structure of the data, relational databases are incredibly accurate for transactional operations, which is why industries favor relational databases.

Since relational databases are so good at transactions, they are a natural fit for any organization that relies on data accuracy. For example, financial institutions such as banks use relational databases. Businesses also use them for inventories and other accounting needs.

## Non-relational databases

Non-relational databases store their data as  objects, where each object is a separate entity (like a row in a table). You can think of these objects like an object in real life, every object has attributes that define that object. These objects are composed of key value pairs. When connecting data entities in a non-relational database, primary keys need to be set to connect to another data set, this can be more difficult than in relational databases.

Contrary to relational databases, non-relational databases are very flexible allowing you to add and change data since every object contains its own key value pairs. This means that data can be added or changed without affecting other data contained in other objects. This flexibility is perfect for situations when the data structure is not completely known before initialization or where the data structure may change.

Being so flexible is a major advantage of non-relational databases. It also allows for great scalability. Non-relational databases also have the advantage over relational databases of being much faster to query.

Use cases for non-relational databases are becoming more and more common in the tech sphere. Since objects model real world entities so well, it’s no wonder they are used so highly in social media companies to store user data. non-relational databases are also used in ecommerce for shopping cart info as well as IOT (internet of things).

## Next steps

An interesting resource for tracking the popularity of databases can be found at https://db-engines.com/en/ranking, where it is interesting to see non-relational databases climbing the ranks. After exploring relational and non-relational databases, you should have a good idea of which is best suited for use in your next project. 

Look for future posts on how to set up a database using MongoDB and PostgreSQL.
