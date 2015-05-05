# Node.js examples

----


> This repo contains some demos of node.js express, mongodb and cool stuff like that.

## Summary
1. Install **node.js** as web server using javascript. 
2. Install **express** as *node.js* framework
3. Install **mongodb** as db engine
4. Mix all these things and create the demos

##Nodetest1

This demo is web project up and running which uses Node.JS, the Express framework, the Jade HTML pre-processor, and MongoDB for data. Demo can read to and write from the DB


###Terminal cheatsheet

```javascript
npm update -g express
npm update -g express-generator
express nodetest2
```

Add the following lines to package.json to add the latest version of MongoDB and Mongoskin to the project:

        "mongodb": "*",
        "mongoskin": "*"

```javascript	
cd nodetest2
npm install
mkdir data
npm start
```

I've followed this tutorial:
[nodetest1](http://cwbuecheler.com/web/tutorials/2013/node-express-mongo/)

##Nodetest2

In this tutorial, we're going to eliminate the need for page refreshing or visiting separate URIs entirely. It's all going to work out fine. But before we start building, let's get some REST:

    Use HTTP methods explicitly.
    Be stateless.
    Expose directory structure-like URIs.
    Transfer XML, JavaScript Object Notation (JSON), or both.

###Terminal cheatsheet

```javascript
npm update -g express
npm update -g express-generator
express nodetest2
```

Add the following lines to package.json to add the latest version of MongoDB and Mongoskin to the project:

        "mongodb": "*",
        "mongoskin": "*"

```javascript	
cd nodetest2
npm install
mkdir data
npm start
```
		
I've followed this tutorial:
[nodetest2](http://cwbuecheler.com/web/tutorials/2014/restful-web-app-node-express-mongodb/)