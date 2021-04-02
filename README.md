# laravel-rect-install


  ## composer require laravel/ui
  ## php artisan ui react
  ## npm install
  ## npm run dev
  
# Add webpack.mix.js

```
mix.react('resources/js/app.js', 'public/js')
  .sass('resources/sass/app.scss', 'public/css');
  
  ```
# Add IN HTML
  ```
 <script src="{{ asset('js/app.js') }}" defer></script>
 ```
 # Add babel js in project to convert jxs to javascript 
 
 https://babeljs.io/docs/en/babel-plugin-proposal-class-properties
```
npm i @babel/plugin-proposal-class-properties

```
# create file .babilrc
```
{
    "plugins":["@babel/plugin-proposal-class-properties"]
}

```
