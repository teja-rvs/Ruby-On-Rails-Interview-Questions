# Ruby On Rails Interview Questions

##### What is the difference between has_many: through and has_and_belongs_to_many? Also state which one is better.
<details>
    <summary>Answer</summary>

    https://guides.rubyonrails.org/association_basics.html#choosing-between-has-many-through-and-has-and-belongs-to-many
</details>
  

##### What are validations in rails? At what moment of an object's lifecycle validations are checked?

<details>
    <summary>Answer</summary>

    Validations are used to ensure that only valid data is saved into your database. For example, it may be important to your application to ensure that every user provides a valid email address and mailing address.

    Creating and saving a new record will send an SQL INSERT operation to the database. Updating an existing record will send an SQL UPDATE operation instead. Validations are typically run before these commands are sent to the database.

    The following methods trigger validations, and will save the object to the database only if the object is valid: 

    -   create

    -   create!

    -   save

    -   save!

    -   update

    -   update_attributes

    -   update_attributes!
    
</details>

