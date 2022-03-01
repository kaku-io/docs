https://www.facebook.com/humpook2@live.com (https://fb.me/e/O1EkFlL8) watch/:id|os/1507772656048513/
https://github.com/kaku-io/Github.io
https://books.google.co.th/books?id=NuuCJnQ3LtAC&lpg=PP464&ots=Paragraph&http://purl.org/dc/terms/|
|foaf|http://xmlns.com/foaf/|
|xsd|http://www.w3.org/2001/XMLSchema#|

### Property label

***Element:*** <code>propertyLabel</code>

The property label is a human-facing label for the element that can be used in documentation and displays. Labels are optional but highly recommended so that displays are human-friendly. 

|propertyID|propertyLabel|
|----|----|
|dct:creator|Author
|dct:title|Book title
|dct:publisher|Publisher
|dct:date|Publication date

### Property cardinality

**Element**: <code>mandatory</code><br />
**Element**: <code>repeatable</code>

In many metadata designs some fields are required while others are not, and some fields are repeatable while others are not. This can be included in the simple profile using the columns `mandatory` and `repeatable`.  These  are defined as taking only Boolean values. Boolean values are a pair of values representing either *true* or *false*. There are two standard sets of values defined for Boolean elements:

* true/false
* 1/0

These values are commonly known and will be recognized by many programming languages and routines. Using the numbers 1 and 0 avoids requiring users to conform to the English language terms of "true" and "false". However, many persons not familiar with this use of 1 and 0 may not find these values natural. There is no reason not to use other binary values like "yes|no" or the equivalent in the language of the profile creators and users as long as the values chosen are documented for downstream users.

Either or both of the elements can be included in the profile, as needed. In the absence of these cardinality constraints, applications using this profile will need to assume default values of their own choosing. It is recommended to indicate these requirements in the profile to avoid misunderstandings about the nature of the metadata.

|propertyID|propertyLabel|mandatory|repeatable|
|----|----|----|----|
|dct:creator|Author|false|true|
|dct:date|Publication date|true|false
