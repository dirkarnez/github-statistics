```
var result = document.evaluate( '//*[@id="js-pjax-container"]/div[2]/div/div[2]/div[2]/div/div//div[2]/a', document, null, XPathResult.ANY_TYPE, null );
var node = null;
while(node = result.iterateNext()) {
    console.log(node.innerText); 
}
```

use API instead
