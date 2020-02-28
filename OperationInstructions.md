# Operation Instructions

## Create new repository

create a new repository from open source

![image-20200227085913626](assets/image-20200227085913626.png)

click the **import a repository ** 

![image-20200227090031245](assets/image-20200227090031245.png)



input repository's URL you need, and you can see [zookeeper](https://github.com/apache/zookeeper)as an example

![image-20200227090303877](assets/image-20200227090303877.png)



repository naming: **name of source project-read** (example: zookeeper-read)

waiting your import is done

![image-20200227090504716](assets/image-20200227090504716.png)





## Create branch

- branch naming: **source-hot-name of source branch** , example: source-hot-release-3.6.0





## Package path

- start package path with **`org.sourcehot`**

## Son project

- start son project's path with **source-hot**





##  Code style

- format your code style if you have code style file

  - example: there is code style xml in SpringBoot project 

    ![image-20200227100006800](assets/image-20200227100006800.png)

    you can set code style in IDEA as following

    ![image-20200227100033840](assets/image-20200227100033840.png)

- creator needs to create a style template if there is no existing code style file

  export from IDEA

  ![image-20200227100128708](assets/image-20200227100128708.png)

  - put exported file into **codestyle** folder

