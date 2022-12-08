## Kotlin-TutorialProject-JetBrains

<b> This is a project that taken from https://ktor.io/docs/creating-http-apis.html </b>
```
  Note : I did not added the Orders part, 
  because I just wanted to see syntax of Kotlin and project structure when I work with it.  
```
<br>

<b> You can use this repository if you want to see all tutorial codes in one place.</b>

<br>

# Let me give you basic summary instructions about these repository

* When you clone this repo, you can open it via Intellij IDEA.</p>
* After that, you can start this program on your local machine easily by going <b>src/main/kotlin/com/example/Application.kt </b> and run the <b>main</b>
* As you can see that program started on 0.0.0.0:8080

# Sample Inputs

* Open <b>Postman</b> and send <b>POST http://0.0.0.0:8080/customer</b> request, here is the example body that I got from JetBrains.
```json
{
  "id": "100",
  "firstName": "Jane",
  "lastName": "Smith",
  "email": "jane.smith@company.com"
}
```
* Open <b>Postman</b> and send <b>GET http://0.0.0.0:8080/customer</b> request, and you will get customer that you just added.
<br>
<br>
<br>
<br>
Thank you, have a good time.
