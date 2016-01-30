# HC-SR501


### Web GPIO

 + [SPEC](https://rawgit.com/browserobo/WebGPIO/master/index.html)
 + [polyfill](https://github.com/MozOpenHard/WebGPIO)


### use

### connect

|CHANNEL|PIN|PORT|HC-SR501|remarks|
|:--:|:--:|:--:|:--:|:---|
|CN1|1|-|GND| or any gnd port|
|CN1|8|197|OUTPUT| or any pulldown port|
|CN1|18|-|POWER|5V|

### code

##### index.html

```html
<!doctype html>
<html>
    <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1">
        <title>Test LED</title>
        <script src="./js/webGpio.js"></script>
        <script src="./js/app.js"></script>
    </head>
    <body>
        <h3 id="output"
            style="color:red; text-align: center; font-size: 256pt;">TEST</h3>
    </body>

</html>
```
##### js/app.js

```javascript

```
