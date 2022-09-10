# Alvina Fedorova

## Junior Frontend Developer

### Contacts:
* Location: Khabarovsk, Russia
* Discord: AlvaF
* Email: [Es_@mail.ru](Es_@mail.ru)
* Telegram: [Alvina_f](tg://resolve?domain=<Alvina_f>) 
***
### Hard Skills:
* HTML
* CSS (SASS, LESS, BEM methodology, Bootstrap)
* JavaScript (Fundamentals,Functional Programming, Asynchronous JavaScript, ES6+)
* Vue JS (Basic )
* Git/GitHub
* Webpack

### Soft Skills:
* Sociability
* Teamwork skills
* Punctuality
* Flexibility in communication
***
### Cources:
* Frontend Developer ([GeekBrains](https://gb.ru/))
* JavaScript/Frontend Developer ([RS School](https://rs.school/))
***

Code Example:
``` JavaScript
addProduct(item){
            this.getJson(`${API}/addToBasket.json`)
                .then(data => {
                    if(data.result === 1){
                       let find = this.cartItems.find(el => el.id_product === item.id_product);
                       if(find){
                           find.quantity++;
                       } else {
                           const prod = Object.assign({quantity: 1}, item);
                           this.cartItems.push(prod)
                       }
                    }
                })
        }
```
***
### Languages:
* English - B1
* French - A1
* Russian - Native