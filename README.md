<snippet>
  <content><![CDATA[
# Angular Loading Interceptor
 Angular Loading Interceptor is library for loading in yout website until all http requests are done
## Installation
 Via bower `bower install angular-loading-interceptor`
 
 Via npm `npm install angular-loading-interceptor`
## Usage
First of all load this service in your project you can copy it from the file LoadingInterceptor.js or 
1. ```var app = angular.module("your project", ["loading-interceptor"])```

2. ```app.config(function ($httpProvider) {
      $httpProvider.interceptors.push("LoadingInterceptor")
    });```

3. ```<div class="loader" ng-if="loading">Loading ...</div>```
## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
]]></content>
  <tabTrigger>readme</tabTrigger>
</snippet>
