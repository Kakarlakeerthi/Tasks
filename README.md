const products = [ { id: 1, name: "Laptop", price: 999.99, category: "Electronics" }, { id: 2, name: "Headphones", price: 49.99, category: "Electronics" }, { id: 3, name: "Smartphone", price: 699.99, category: "Electronics" }, { id: 4, name: "Keyboard", price: 39.99, category: "Electronics" }, { id: 5, name: "Mouse", price: 19.99, category: "Electronics" }, { id: 6, name: "Shirt", price: 29.99, category: "Clothing" }, { id: 7, name: "Jeans", price: 49.99, category: "Clothing" }, { id: 8, name: "Sneakers", price: 79.99, category: "Footwear" }, { id: 9, name: "Sandals", price: 39.99, category: "Footwear" }, { id: 10, name: "Backpack", price: 59.99, category: "Accessories" } ];

let new_arr = []
for(let each_product of products){
    new_arr.push(each_product.name)
}

console.log(new_arr)
