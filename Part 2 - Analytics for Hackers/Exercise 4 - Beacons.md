Exercise 4 - Beacons
====================
<img src="https://api.keen.io/3.0/projects/52e4404a05cd66180c00000e/events/email_opened?api_key=184f7f08bc48a688b1a8a3eacd4c4a7b9ed6d11409345a57a6f0f3dde9dddab3c2d2ac1152bf0cea225ab47b65af5b4ab93e24375bd08e0ccd8e9ddf2a6bb71e29348e04c0d4027c78a3c5ac80243ce0f0522bdff2cc43491412573ca123318d2fe94745b2490a38ef6564846b9c3070&data=ew0KICAgICJjYW1wYWlnbiIgOiAiVGVzdGluZyBmcm9tIGFuYWx5dGljcyBjbGFzcyEiLA0KICAgICJzdWJqZWN0IiA6ICJIaSIsDQogICAgInRleHQiIDogIm15IGRhdGEgYW5hbHl0aWNzIHByb2plY3QiDQp9"></img>
Given image beacons a try! Add a Beacon to a README file in your Github repo. Now you can track how many people visit your repo!

Steps. 

1. Go to [Beacon Docs](https://keen.io/docs/data-collection/image-beacon/) for details on how to make a beacon URL.

2. To construct your beacon image URL, you'll need to create an event body like this:

```json
{
    "campaign" : "Testing from analytics class!",
    "subject" : "Hi",
    "text" : "espionage blah blah"
}
```

Don't forget to [base64 encode it](http://www.opinionatedgeek.com/dotnet/tools/base64encode/) before putting it into the redirect URL!

3. Write an email which contains a fake beacon image. You'll need to use an email editor that allows you to put HTML in the email. Like [this one](http://ctrlq.org/html-mail/). Note: click "Switch to HTML View" and then, after putting in your code, "Switch to Visual Editor". Then enter your email address and click send!

4. Send it and get someone to open the email. See if the tracking works!

5. What are some drawbacks to using beacons?
