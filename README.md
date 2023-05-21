<h1 align="center">ReactGetStarted</h1>



***Tutorial de React***

- [x] Create React Learn
- [ ]  Account >> `https://codepen.io/` 

**Button:**

```
export default function Square() {
  return <button className="square">X</button>;
}

```
- [x] Retun X


***Add more X:***

```
export default function Square() {
  return (
    <>
    <button className="square">X</button>
    <button className="square">X</button>
    </>
  );
}

```
- [x] Add more X

***3x3 matrix***
``` 
export default function Square() {
  return (
    <>
    <div>
    <button className="square">1</button>
    <button className="square">2</button>
    <button className="square">3</button>
    </div>

    <div>
    <button className="square">1</button>
    <button className="square">2</button>
    <button className="square">3</button>
    </div>

    <div>
    <button className="square">1</button>
    <button className="square">2</button>
    <button className="square">3</button>
    </div>
    </>
  );
}

```
- [x] Matrix 3x3

***Update Sintax Code***

```


export default function Board() {
  return (
    <>
    <div align="center">
    <div>
    <button className="board-row">1</button>
    <button className="board-row">2</button>
    <button className="board-row">3</button>
    </div>

    <div>
    <button className="board-row">1</button>
    <button className="board-row">2</button>
    <button className="board-row">3</button>
    </div>

    <div>
    <button className="board-row">1</button>
    <button className="board-row">2</button>
    <button className="board-row">3</button>
    </div>
    </div>
    </>
  );
}
```


to:

```
function Square(){
  return <button className="square">X</button>;
}

export default function Board() {
  return (
    <>
    <div align="center">
    <div>
      <Square/>
      <Square/>
      <Square/>
    </div>

    <div> 
      <Square/>
      <Square/>
      <Square/>
    </div>

    <div>
      <Square/>
      <Square/>
      <Square/>
    </div>
    </div>
    </>
  );
}

```

- [x] Update Sintaxe
