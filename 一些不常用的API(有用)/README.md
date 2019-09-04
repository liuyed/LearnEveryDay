
- ```document.querySelector()```

> 注意：无论如何只返回一个元素，如果有多个素，那也只返回第一个✅

```
docuemnt.querySelector('.item');

document.querySelector('#item');

document.querySelector('li');
```

- ```document.querySelectorAll()```

> 返回的值是类数组 可以用 ```Array.from(xxx)``` 转成数组

```
document.querySelectorAll('li');
```

- ```closest```

> 向上查询 查询父元素

```
document.querySelector('li').closest('ul');
```
- ```dataset```

```
<p data-name="二狗子" data-age="22"></p>
document.querySelector('p').dataset
// {name:'二狗子',age:22}
```
