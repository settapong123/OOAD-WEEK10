# OOAD-WEEK10
Sequence Diagram


README.md 
md เป็นภาษา Markdown นิยมใช้ใน wiki ของ github 

ตัวอย่างโค้ด
```
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3
 
```
```
Email
@startuml

user -> Computer : checkEmail()
Computer -> Server : sendEmail()
Computer -> Server : newEmail()
Server -> Computer :response()
Computer -> Server : downloadEmail()
Computer -> Server : deleteEmail()
Computer -> user: showEmail()

@enduml

```
<img src="http://www.plantuml.com/plantuml/img/SoWkIImgAStDuU8gBKujKj2rKt3EpoqeBG6ohHIICrAJirrp4pDpD3IvuE90DS6fHMLW5SMfUIbu5UIbbiFaeM8eLXIb5XVavnMdujAUab-UbvEVYD-EbDISr99KR4f0VW8wCYCVxWWk1w2BGVu50000">

```
@startuml

Browser-> URL_Routing : Post
URL_Routing -> Controller:new
URL_Routing -> Controller:Invoke_action
Controller -> Model : Invoke_Method
Controller -> Controller : Lookup_view
Controller -> Render
View -> Browser: HTML

@enduml

```

<img src="http://www.plantuml.com/plantuml/img/VOz12i8m44NtSufSm0ja8KKt2Wb8KRUXc453OqOca_Rw9b2mkd3v_tlm-LsMWQKy8y2EQSx8cwswzCRrL2IakzBgH5bWNLLZJqcOOaJM2US_z9Wc6j4DDmcKu0EQPibZh0EBOr4Uv7-SLTBA48tbvQPG9x-r7fD7XcibBIvNj3gShG7eAcqNtm00">

```
@startuml
actor Customer

Customer -> Cashier : Place_good()
Cashier -> Server_Computer :Login(Username and password)
Server_Computer -> Cashier :Return_Permiss(True)
Cashier -> Server_Computer :Input(IDGoods)
Server_Computer -> Cashier :Detail_Goods
Cashier -> Server_Computer :PrintSlip(IDGoods)
Server_Computer -> Server_Computer :Clear()
Server_Computer -> Customer :Recieve_slip()

@enduml
```
<img src="http://www.plantuml.com/plantuml/img/VP7B2i8m44Nt-OeiquK_u48AAKZ1HR6w3aCxr40UPIQflsyg54Ibkyjmvjvvr9o0KlPEm90YIPqvHOyanARauIGryCCMUPITWm7D5EEeAh6L2z4ZBKX6Hp_dj9ANEDcWxemKmAE4CCePc9-HnafyqvyHLqoPWkcGl6LMDygudzI68bJRdCjGlE_TO0Bhp9lSzUp8XjGxE-_w_hHfXq3g_mpRESk2WyK53Q_sbH0rXd5zm0i0">

```
@startuml
actor Officer

Officer -> order :getorderinfo()
order -> Customer :getcusinfo()
order -> Product :getProductinto()
order -> Officer :displayResult()

@enduml
```
<img scr="http://www.plantuml.com/plantuml/img/SoWkIImgAStDuKfCBialKl1FIyjCJYtYue8o57Jj5FABKe0Cg_JK4Z0hCoyjNqEJ2o8Ab7OkBIx9puMgI2ujHfSFACfFAKqk0Kj3sPbv9IXAO9PPfMGM5-GaLWQb5fVcb01LS3cavgM0N0S0">
ผลที่ได้
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3


## Code ภาษาซี

ตัวอย่างโค้ด
<pre>
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
</pre> 
ผลที่ได้
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
 
