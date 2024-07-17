- 👋 Hi, I’m @WL16172
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
WL16172/WL16172 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


1、String.valueOf(1.23)

2、 public String getString(String str){

 String getNumber;

 getNumber = str.replaceAll("[a-z|A-Z]", "");

 if(getNumber.indexOf(".") == -1){

  getNumber = getNumber+".00";

  }else {

  if(getNumber.indexOf(".")== getNumber.length()-1){

    getNumber= getNumber+"00";

   }else if (getNumber.indexOf(".")== getNumber.length()-2){

   getNumber = getNumber+"0";

   }else {

   getNumber = getNumber.substring(0, getNumber.indexOf(".")+3);

   }

  }

 return getNumber;

 } 
