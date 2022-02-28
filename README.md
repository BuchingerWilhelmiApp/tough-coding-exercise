# tough-coding-exercise

This exercise does not have to be completed perfectly, it is just supposed to show us the way you are working, and to show us the approach of how you would approach problems

# tasks

A Kubernetes deployment should be created, which stores patient data in a relational database, and offers a simple API which can retrieve patient blood pressure given the patient id. Another simple webpage should be offered in this Kubernetes Deployment which collects patient data in a form, and writes the results into the relational database to be retrieved by the simple API. 

Previous patient data should be included, which you are given as the .csv file in this root folder.

Another requirement is to save sensitive patient data in a safe way, because in case the database is exposed we do not want sensitive data to be shared!

Do not take longer than 1-2 hours for this exercise. It does not have to be perfect, but the result should be in a format that we could easily deploy to our cluster with helm or kubectl.
