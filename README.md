- 👋 Hi, I’m @Kareem-Ganga1503
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Kareem-Ganga1503/Kareem-Ganga1503 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
public class AMG {
    String name;
    int num1;
    int num2;
    String family;
    int age;
    public QLM(String name, int num1, int num2, String family, int age) {
        this.name = name;
        this.num1 = num1;
        this.num2 = num2;
        this.family = family;
        this.age = age;
    }
    public void details() {
        System.out.println("my name is " + name);
        System.out.println("i am a " + num1 + " (second) children");
        System.out.println("out of " + num2 + " childrens");
        System.out.println("on " + family + " family");
    }
    public static void main(String[] args) {
        QLM f1 = new QLM("abdulkareem", 2, 4, "Ganga's", 22);
        f1.details();
        System.out.println("and am " + f1.age + " years old now");
    }
}
