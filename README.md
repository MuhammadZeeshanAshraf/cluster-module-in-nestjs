## NestJS Cluster Module and Vertical Scaling
This GitHub repository provides an implementation of the NestJS Cluster Module, which enables horizontal scaling of your NestJS application. Horizontal scaling allows you to distribute your application's load across multiple instances running on different machines, improving its performance and availability.

In addition to the cluster module, this repository also includes an implementation of vertical scaling in NestJS. Vertical scaling refers to the process of increasing the resources allocated to a single instance of an application, such as CPU or RAM. This is particularly useful when dealing with a large volume of concurrent requests and can help improve the performance of your application.

Getting Started
To get started, simply clone the repository to your local machine:

```
git clone https://github.com/MuhammadZeeshanAshraf/cluster-module-in-nestjs.git
cd cluster-module-in-nestjs
npm i
npm run start:dev
```
Ok let’s run the server and test the performance with loadtest:

```
npm i loadtest
loadtest -c 10 -n 100 http://localhost:3000
```

Before Clustering 
![Before Clustering](https://github.com/MuhammadZeeshanAshraf/cluster-module-in-nestjs/blob/main/resources/Before%20Clustering.jpg)

After Clustering 
![Before Clustering](https://github.com/MuhammadZeeshanAshraf/cluster-module-in-nestjs/blob/main/resources/After%20Clustering.jpg)
