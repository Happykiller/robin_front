# robin_front
Front for service notes/lists

# Features

* Like todo list
* add elt to list by general or on elt, eatch elt is a node
```
[
  {
    _type: node
    label: string
    qantity?: number
    done: boolean
    childs: [
      ...nodes
    ]
  }
]
```
* tab display list, or tab display list conpunted (compiled)
* collaborative (subscription)
* AI for add ex "recette pizza" => 
```
{
  _type: node
  label: "pizza"
  done: false
  childs: [
    {
      _type: node
      qantity: 250
      label: "farine de blé (type T45) en g"
      done: false
    },
    {
      _type: node
      qantity: 1
      label: "sachet de levure de boulanger"
      done: false
    },
    {
      _type: node
      qantity: 3
      label: "c. à s. d'huile d'olive"
      done: false
    },
    {
      _type: node
      qantity: 300
      label: "coulis de tomate ou sauce tomate en ml"
      done: false
    },
    {
      _type: node
      qantity: 125
      label: "mozzarella en g"
      done: false
    }
  ]
}
```