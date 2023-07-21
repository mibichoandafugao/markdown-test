<!-- Headings -->
# my title
## my title h2
### my title h3
#### my title h4
##### my title h5
###### my title h6

<!-- Italic -->
This is an *italic* text

<!-- Strong -->
This is an **string** text

<!-- Strikethrough -->
Esto es un texto ~~tachado~~

<!-- Unordered List(UL) -->
* Apple
    * Apple 2
* Orange
    * Orange 2
* Dragon Fruit

<!-- Ordered List(OL) -->
1. Apple
2. Orange
3. Dragon Fruit

<!-- Urls -->
[faztweb.com](https://www.faztweb.com)

[faztweb.com](https://www.faztweb.com "Custom Title")

<!-- Quotes -->
> This is a Quote

<!-- Lines -->
---
___

<!-- Code -->
`console.log('hello world')`

```c#
namespace Entidades
{
    public class factura
    {
        public DateTime fecha { get; set; }
        [Key]
        public int id { get; set; } 
        public DateTime fecha_entrega {  get; set; }
        public double total { get; set; }  
        public string tipo_pago { get; set; }
        public persona cliente { get; set; }
        public List<producto> productos { get; set; }

    }
}
```

```python
print("hello world")
```

```html
<h1>Hello World</h1>
```

<!-- Tables -->
| Tables        | Are             | Cool    |
| ------------- | :-------------: | ------: |
| col 3 is      | right-aligned   | $1600   | 
| col 2 is      | centered        |   $12   |
| zebra stripes | are neat        |    $1   |

<!-- Images -->
![visual studio code logo](vscode.png "vscode logo")

<!-- Github Markdown -->
* [x] Task 1
* [ ] Task 2
* [ ] Task 3
* [ ] Task 4



