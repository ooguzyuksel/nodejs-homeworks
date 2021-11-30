# nodejs-homeworks
nodejs-homeworks

## ÖDEV 1 - Dairenin Alanını Bulma

> Dairenin Alanı = π x r2
```
const argument = process.argv.slice(2);
const PI = 3.14;

function circleArea(r) {
  let area;
  area = PI * (r * 2);
  return area.toFixed(2) * 1;
}

let finalArea = circleArea(argument[0] * 1);

console.log(`Yarıçapı ${argument[0]} olan dairenin alanı: ${finalArea}`);
```

> Komut Satırında:

```
node {dosya-adi} {parametre}
```
