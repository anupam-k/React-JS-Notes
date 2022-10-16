## _async await_


## _Card.js_
<b>

```javascript
function Card({details}) {
    //console.log(props);
    return (
        <div className="card" style={{width: "18rem"}}>
            <img src={details.picture?.large} className="card-img-top" alt="..." />
            <div className="card-body">
              <h5 className="card-title">{details.name?.first} - {details.phone}</h5>
              <p className="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" className="btn btn-primary">Go somewhere</a>
            </div>
        </div>
    )
}

export default Card;

// Change link and text of button
```
</b>

## _Optional Chaining_
- When you need to access like

<b>

```javascript
"picture": {
     "large": "https://randomuser.me/api/portraits/women/43.jpg",
     "medium": "https://randomuser.me/api/portraits/med/women/43.jpg",
     "thumbnail": "https://randomuser.me/api/portraits/thumb/women/43.jpg"
 },
 ```
 </b>
 
-  _large can be accessed like this_
 `details.picture?.large`

