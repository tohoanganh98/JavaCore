# Class in Java
**DeFine**

```Một lớp là mô tả về các đối tượng sẽ được tạo ra. Mỗi class có tên class, trong nó có các thuộc tính như là dữ liệu của lớp và các ứng sử của lớp (các hàm) gọi là các phương thức.```

**Ví dụ một lớp về con người có thể có:**
- Các thuộc tính: tên, chiều cao, cân nặng, giới tính, tuổi ...
- Các ứng sử: đi, chạy, nhảy, nói, ngủ ...
	*Từ lớp con người như vậy tạo ra các đối tượng cụ thể khi chạy chương trình như: Đàn ông, Phụ nữ*
	
**Các class được định nghĩa dùng từ khóa class sẽ tìm hiểu sau, ví dụ:**

```
public class ClassName {
    //... Định nghĩa các thuộc tính
    //... Định nghĩa các phương thức
}
```
# Method in Java(Phương Thức)
**DeFine**

```Các phương thức định nghĩa ứng xử của lớp. Một phương thức là một tập hợp các khối lệnh (code) để thi hành một chức năng nào đó. Ví dụ như System.out.println() là một phương thức. Bạn có thể định nghĩa phương thức riêng của bạn, thi hành với một nhiệm vụ cụ thể nào đó.```

**Hãy xem ví dụ sau:**
```
class MyClass {

  static void sayHello() {
    System.out.println("Hello World!");
  }

  public static void main(String[ ] args) {
    sayHello();
  }
}
//Xuất ra: "Hello World!"
```
###### Trong ví dụ trên, đã định nghĩa một phương thức sayHello(), phương thức đó được hàm main() gọi để in ra lời chào mừng. Như vậy để gọi phương thức để thi hành code chỉ cần viết tên phương thức và truyền các tham số nếu cần thiết. Một phương thức có thể gọi bao nhiêu lần là tùy mục đích.

**Tham số của phương thức**
**DeFine**

```Bạn có thể tạo phương thức chấp nhận các tham số truyền vào. Tham số được mô tả trong dấu cặp ngoặc (), các tham số mô tả bởi kiểu dữ liệu và tên tham số, nhiều tham số thì cách nhau bởi dấu phẩy.```

**Ví dụ phương thức sau poem() có một tham số kiểu String có tên là atr:**

```
class MyClass {

    static void poem(String atr) {
        System.out.println("Java " + atr);
    }

    public static void main(String[ ] args) {
        poem("is Love");
        poem("is Life");
        poem("keeps you busy as bees in a hive");
    }

}

//Xuât ra:
//Java is Love
//Java is Life
//Java keeps you busy as bees in a hive
```
