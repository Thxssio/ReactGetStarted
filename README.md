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
