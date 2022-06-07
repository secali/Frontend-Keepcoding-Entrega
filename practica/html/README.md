# html exercises

In this exercises you will have to complete the missing html or remark what should we include. For example:

What is wrong with this HTML?

```html
<customtag>lorem ipsum dolor</customtab>
```

Answer: It is using a key that does not exists.

## Exercise 1

Add what is missing in our html `<head>` tag.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
  </head>
</html>
```

Answer: Tags related with meta-information, 

## Exercise 2

This html is not semantic what could we do to improve it.

```html
<div class="main">
  <section>
    <div class="item-list">
      <li class="list-item">List item</li>
      <li class="list-item">List item</li>
      <li class="list-item">List item</li>
      <li class="list-item">List item</li>
    </div>
  </section>
  <section>
    <form>
      <label>description</label>
      <input type="text">
    </form>
  </section>
</div>
```

Answer: To use more sematics tags, <section>, <form>, <li>


## Exercise 3

If we want to include two CSS files like `reset.css`, `main.css`, and one javascript file `app.js`. Where should we include it in this html?

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="reset.css">
  <link rel="stylesheet" href="main.css">
</head>
<body>

  <script src="main.js"></script>
</body>
</html>
```

Answer: We  should incluide css on head and js file usually at the end of the body

## Exercise 4

We need to improve this html form markup. This form will call and endpoint `/register` with the right method. We also have to include the correct input type and mark all fields as required.

```html
<form method="POST" action="/register">
  <div>
    <label>name</label>
    <input>
  </div>
  <div>
    <label>surname</label>
    <input>
  </div>
  <div>
    <label>phone</label>
    <input>
  </div>
  <div>
    <label>email</label>
    <input>
  </div>
  <div>
    <label>password</label>
    <input>
  </div>
  <input value="register">
</form>
```

Answer: We need to add the http method, GET or POST,  and the endpoint on action section of the form