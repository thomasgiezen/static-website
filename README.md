# Static-website
---
*stop worrying about dev envr, localhost, implementing sass or any other type of stuff!*

I made Static-website with the thought that it will make you happier with making websites and also speeds up your workflow by not having to think about if this thing works or nor or if your site actually launches.


## Getting Started
---

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

* Follow the steps and you will be there in no time!


### Prerequisites
---

#### You need to install these things for all of this to work
* Node
* NPM
* Bower


#### Node
Download node and install LTS (this is the most stable recent version they have, it should be compatible with my repo!)
```
[Node.js] (https://nodejs.org/en/)
```


#### NPM
NPM is used to install plugins and all kinds of stuff to make your workflow easier! (but mine is fine as well!)
###### NPM is pre-installed with node.js **hooray!**.
```
[NPM] (https://www.npmjs.com/)
```


###### Bower
Bower is used to make it easier to install jQuery, Mocha AnimeJS and all kinds of plugins!
* Bower is installed via the command line, so put this there and you should be fine!
```
npm install -g bower
```
**mac users may have to use ```sudo```**

###### Including bower components
To include bower components you have to include script tags into your html file.
* This is an example of how to include jQuery into your page
```
<script src="bower_components/jquery/dist/jquery.min.js"></script>
```

## Installing and running 
---

Here are the steps on installing and running your own dev server

1. First clone the repo to your own computer

```
git clone https://github.com/rubennijhuis/static-website
```

2. Then via the command line, go to the folder and run npm install. **(if you didn't do that yet)**
```
npm install
```

3. After that run bower install **(again only if you didn't do that yet)**
```
bower install
```

4. Now if everything went correctly run gulp!
```
gulp serve
```

#### **Right now you should have a live-reload server going! Well done! Now let's do some coding!**


## Gulp commands
---
* Gulp serve (sets up live-server for development use)
* Gulp build (build, minifies and forms your files for web deployment!)


## Authors
---
* **Ruben Nijhuis** - *Initial work* - [RubenNijhuis](https://github.com/RubenNijhuis)

See also the list of [contributors](https://github.com/RubenNijhuis/extra/contributors) who participated in this project.


## License
---
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


## Acknowledgments
---
* Me
* Myself
* and I
