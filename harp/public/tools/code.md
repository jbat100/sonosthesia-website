```javascript
function appendText(node,txt) {
  node.appendChild(document.createTextNode(txt));
}

function appendElement(node,tag,id,htm) {
  var ne = document.createElement(tag);
  if(id) ne.id = id;
  if(htm) ne.innerHTML = htm;
  node.appendChild(ne);
}
```