# _React JS_ 🔯

- **`npx create-react-app .`**  _this will take **name of the folder**_

- If we add **_cdn_** link to **_add bootstrap_** or any other package, it will cause error in production 

- **`Ctrl + d`** : to select a particular word in the whole file

## _How to dump the infomation of props?_

<b>

```javascript
function Card(props) {
    console.log(props);
    return (
        <div className="card" style={{width: "18rem"}}>
            <img src={props.imgUrl} className="card-img-top" alt="..." />
            <div className="card-body">
              <h5 className="card-title">HC - {props.name}</h5>
              <p className="card-text">Some quick example text to build on the card              title and make up the bulk of the card's content.</p>
              <a href="#" className="btn btn-primary">Go somewhere</a>
            </div>
        </div>
    )
}
export default Card;
```
</b>

## _Destructured Way_
<b>

```javascript
function Card(imgUrl,name) {
    //console.log(props);
    return (
        <div className="card" style={{width: "18rem"}}>
            <img src={props.imgUrl} className="card-img-top" alt="..." />
            <div className="card-body">
              <h5 className="card-title">HC - {props.name}</h5>
              <p className="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" className="btn btn-primary">Go somewhere</a>
            </div>
        </div>
    )
}

export default Card;
```
</b>



