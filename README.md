<h1 align="center">Добро пожаловать :</h1>

<h2 align="center"><i>"A single moment of weakness can lead to a lifetime of regrets" ~ Kokushibo</i></h2>

<p align='center'>



</p>

```java
public class Main {
    String name;
    String age;
    String country;
    String[] languages;
    String[] ops;
    public static String toString(Main asd){
        String space="    ";
        String languageText ="";
        for (String i : asd.languages) {
            languageText = languageText + i + "\n"+ space;
        }
        String OpsText = "";
        for (String i : asd.ops) {
            OpsText = OpsText + i + "\n"+ space;
        }
        return "Name " + asd.name + "\nAge " + asd.age + "\nLocation " + asd.country
                + "\nLanuages:\n"+ space + languageText + "\nOps:\n"+ space + OpsText;
    }
    public static void main(String[] args) {
        Main myObj = new Main();
        myObj.name = "Gavin";
        myObj.age = "this.year() - ((334.666666667 * 3) + √(3249) + √(1024) + 915)";
        myObj.country = "United Kingdom";
        String[] list = { "Javascript, Next.JS, React.JS, Nest.JS", "Java, Spring", "Python, Numpy","Swift, SwiftUI" ,"Groovy","C++, Node-gyp, Pybind11, Cmake","R","C, CS50","C#, MAUI, Console app",};
        myObj.languages = list;
        String[] ops = { "Vercel, Webapps","Render, Webapps, Services", "Railway.up, Webapps","Docker, Helm, K8s (GCP)","Jenkins, Brew, Docker","Ubuntu, 20.04, 18.10, Kali, OpenSUSE, RHAT, AntiX, Ubuntu Server 15.04,","DB, MongoDB, Mysql, Mysql Docker","Shell","GCP, K8s","Azure, AD"};
        myObj.ops = ops;
        System.out.println(toString(myObj));
    }
}
```



<!--
**yauae/yauae** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
