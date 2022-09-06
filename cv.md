# CV#1. Markdown & Git
## _Chernysheva Svetlana_

##### Contacts:
- delusionkind@gmail.com
- twitter.com/delusiontea
- ✨Telegram: @Kindertei
##### Experience

- Senior Performance Engineer - Sberbank- (july 2021 -now)
- Load & Perfomance Qa - x5 - (december 2020 - july 2021)
- Performance Engineer - PerfLab (april 2019 - december 2020)

##### Skills

- Manage end-to-end performance testing lifecycle - including building scripts, scenarios, test execution and analyzing results.
- Creating mocks and stubs (Java+Spring)
- Expertise in backend and Batch performance testing
- Work with monitoring tools: Openshift, loadrunner, postgres, Grafana, zabbix, jenkins
- Performance scripting, dashboard integration and shifting performance testing into CICD pipeline
- English (B1)


##### About me


> The overriding design goal for Markdown's
> formatting syntax is to make it as readable
> as possible. The idea is that a
> Markdown-formatted document should be
> publishable as-is, as plain text, without
> looking like it's been marked up with tags
> or formatting instructions.


## Github repositories with code example:

| Project | link |
| ------ | ------ |
| Golang  - url-shorter service | [https://github.com/DelusionTea/praktikum-go][PlDb] |
| Golang - market bonus-system calculation | [https://github.com/DelusionTea/go-pet][PlGh] |
| Golang - leetcode - example | [https://github.com/DelusionTea/testtask][PlGd] |


## JavaScript - Code Example:

```js
function getLengthOfMissingArray(arrayOfArrays) {
  //console.log("array: "+arrayOfArrays)
  if (arrayOfArrays==null){
    return 0
  }
  result = 10000
  map = new Map()
  minArrayLengh =100000
  arrayOfArrays.forEach(elem=>{
    if((elem==null)||(elem.length==0)){
      result  = 0;
       return 0
    }
    console.log("lenth: "+elem.length)
   if ( map.get(elem.length)===undefined){
     map.set(elem.length, 1)
     if (elem.length<minArrayLengh){
         minArrayLengh=elem.length}
   }
  })
 
  for(i=0; i<arrayOfArrays.length;i++){
  if (   map.get(i+minArrayLengh) ===undefined){
    console.log("result: "+ (i+minArrayLengh))
    if(result!=0){
      result = i+minArrayLengh
    }
  }
  }
  if (result ==10000){
    result = 0
  }
  return result;
}
```


[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
