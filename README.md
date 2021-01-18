# Install-everything
Here is place that I will show the way how to install packages, libraries, framework

## 1 Install laravel
#### 1.1 Required:
+ Install nodejs
+ Install composer
#### 1.2 Way to install
+ composer create-project laravel/laravel my-laravel
#### 1.3 Run app
+ php artisan serve

## 2.Install vuejs
#### 2.2.1 Way to install 
+ npm install -g @vue/cli
+ vue create my-vue
#### 2.2.2 Way to install with template "webpack"
+ npm install --global vue-cli
+ vue init webpack my-vue
#### 2.3 Run app
+ npm run serve
+ npm run dev

## 3 Install vuejs in laravel
#### 3.1 Required:
+ install laravel first
#### 3.2 Way to install
+ composer require laravel/ui
+ php artisan ui vue
#### 3.3 Run app:
+ php artisan serve
+ npm install && npm run dev

