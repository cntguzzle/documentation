#`GUZZLE FOR GITHUB`
##*`A Beginners Guide To Guzzle With Github`*
---

##Introduction:

###What Is An API?
> 
### API (*Application Programming Interface*)
#### A way for applications to connect and share data programmatically.
--

###**What Is CRUD?**
> ### CRUD (*Create,Read,Update,Delete*)
> #### A methodology for organizing an application. 
> Create Content | Read Data | Update User Content | Delete Data
--- | --- | --- | ---


###**What Is Guzzle?**
> #### A FrameWork For Working With API's And HTTP Client Requests
--

###The number of public API's is estimated to be at over 10,000

We live in a world where data is created in real time.

From Weather Data To Twitter Geo Location,
The web is filled with API's that can be connected into new types of applications.

By using Guzzle we can develop rapid prototypes connecting APIs into applications.

</br>
</br>

##Course Overview And Expectations
> ### To apply CRUD Methodology with Guzzle To GitHub
> --
> ### Connect multiple API's together for dynamic content
> --
> ### Have a working knowledge of how to implement a new API
--

#### The goal of this training material is to rapidly prototype and implement API's with Guzzle.

#### We will focus on applying a software engineering methodology that lets you focus on quickly developing working code.

##At the end of this guide you will be able to do the following:
> ### Share data with an API
> --
> ### Connect two API's together
> --
> ### Apply creative usages with the vast amount of APIs
--

###What Will We Cover?

### `1` Installing Guzzle
 
### `2` GitHub Authentication

### `3` CRUD With A GitHub Gist

### `4` Applying CRUD With A GitHub Repository

### `5` Intergrating Two API's To Create Dynamic Content Into GitHub 

</br>
</br>

# `1`  `Installing Guzzle`
###*`From Composer To Creating The First Client Connection`*


###**Create A Composer File With The Guzzle Requirement**

> #### Composer File As A Text File

```
{
    "require": {
        "guzzlehttp/guzzle": "5.3.0"
    }
}
```
> #### Composer From Terminal/Shell/Command Line
> 
```
composer require guzzlehttp/guzzle 5.3.0
```