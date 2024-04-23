# Tutorial 8

a. How many data your publisher program will send to the message broker in one
run?

Publisher program akan mengirim 5 data dalam bentuk UserCreatedEventMessage (dilihat dari call publish_event) yang saling berbeda kepada message broker setiap kali program di-run.

b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber
program, what does it mean?

Kedua program tersebut (publisher dan subscriber) memiliki url yang sama karena kedua program ini menggunakan protokol AMQP untuk berkomunikasi melalui message broker yang sama sehingga kedua program dapat saling berkomunikasi (mengirim dan memproses data).

![alt text](<Screenshot (523).png>)