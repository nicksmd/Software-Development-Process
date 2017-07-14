##### 1. Unit testing Overview
* Test the **Interface** not the implementation
* Tính chất của Unit-testing:

    * automated
    * reusable
    * run at the push of a button
    * run quickly
    * easy to implement

* Câu hỏi nên đặt:

    * Tôi có thể dùng lại các unit test tôi viết tuần trước ko?
    * Đồng nghiệp có thể dùng lại các unit test tôi viết tuần trước ko?
    * Tôi có thể chạy tất cả các unit test = 1 cú click ko?
    * Tôi có thể viết 1 unit test trong vòng 1 vài phút ko?

Bất cứ câu trả lời NO nào cho các câu hỏi trên => bạn đang code điều gì đó khác Unit test.
Hầu hết các trường hợp là *Integration testing*.

* Khi nào là thời điểm viết Unit test?
    Cách truyền thống:

    ![](http://i.imgur.com/lLMA48i.png)

    Theo hướng Test-driven development (TDD): viết UT trước khi code được viết.

    ![](http://i.imgur.com/ESWMoqB.png)

* Đặt tên UT:

    * project: [ProjectUnderTest].Tests.
    * class: [ClassName]Tests
    * method: [MethodName]_[Condition]_[ExpectedBehavior]

* Viết UT như thế nào?

    3 phần:

    * Arrange
    * Act
    * Assert

##### 2. Best Practices:
* Tách biệt UT với Integration Test, ko cần tách thành 2 project, tách thành 2 folder là đủ.
* Đảm bảo UT là 1 phần của Source Control (GIT)


