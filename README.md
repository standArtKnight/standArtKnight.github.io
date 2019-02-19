# standArtKnight.github.io

<h4>Заметки по обучению</h4>

---


<h5>Способы записи функций</h5>

``` javascript
// const <name> = (<argument>) => {
//   return <expressions>;
// };

const identity = (value) => {
  return value;
};

// функция-однострочник
// const <name> = (<argument>) => <expressions>;
const identity = value => value;

// Устаревший синтаксис, предпочтительным является () => {}. Кроме синтаксической разницы есть и семантическая.
const identity = function(value) {
  return value;
};

function identity(value) {
  return value;
}
```

