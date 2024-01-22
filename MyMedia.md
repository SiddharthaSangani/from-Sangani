# Siddhartha_Sangani
Rich Dad Poor Dad" by Robert Kiyosaki is a timeless personal finance classic that provides valuable insights and a fresh perspective on wealth creation and financial independence. This book challenges conventional thinking about money and offers a wealth of knowledge that can transform your mindset and approach towards building wealth.

This is my image [***My image***](Myimage.jpeg)


---

### Table section 

The below table gives you the information about my favorite books and the reason why i like it and the author of it.

| Name | Reason | Author |
|:--- | :---: | ---:|
|Rich dad poor dad | nice information about wealth creation | Robert Kiyosaki |
| Wings of fire | Nice auto biography | Arun Tiwari |
| Learning how to fly | Teches how to overcome challenges | Abdul Kalam |
| Ignited Minds | Motivational book | Adbul Kalam |

---

### Favorite Quotes

> If you want to shine like a sun, first burn like a sun **Abdul kalam**
> 
>Pain is invetible. Suffering is optional. **Haruki Murakami**

---

### Code fencing
 
This simple Node.js code is used to get the data out of a Node.js HTTP get request with JavaScript, we can listen for the data event on the response and append it until the response has ended.

```

const callback = (response) => {
	let str = "";
	response.on("data", (chunk) => {
		str += chunk;
	});

	response.on("end", () => {
		console.log(str);
		// ...
	});
};
```
const request = http.request(options, callback).end(); 


Link to snippet source is <https://code.pieces.app/collections/node-js