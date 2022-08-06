- 👋 Hi, I’m @poojavishwakarma001
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
poojavishwakarma001/poojavishwakarma001 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->



// way of capitalize first latter of a string without predefine method

var str='string is  way of wtiting Words';
var word= str.split(' ')
console.log(word)

for (let i=0;i<word.length;i++){

 word[i]=word[i].charAt(0).toUpperCase() + word[i].slice(1)
}

var newStr = word.join(' ')
console.log(newStr)
