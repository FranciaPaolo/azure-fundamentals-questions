# azure-fundamentals-questions
Azure fundamentals certification 2023 sample questions

The list of questions comes from:
https://github.com/Ditectrev/Microsoft-Azure-AZ-900-Microsoft-Azure-Fundamentals-Exam-Questions-Answers


## Try questions
If you want to try the questions:
* Download the source code
* Run it on a webserver. For example you can use the command line http-server from npm
```
npm install --global http-server
http-server
```
* Enjoy in the browser. For example using http-server open the browser at http://localhost:8080


## How does it works 
It's a simple html that JQuery and a the list of questions are from a Json file in the root of the website. 
The questions.json file it's in the following form:
```
[
  {
    "QuestionText": "If you plan to web application in the Azure platform as a service solution of Azure Web Apps, then the platform will have the ability to scale automatically?",
    "Responses": [
      {
        "ResponseText": " Yes.",
        "IsRight": true
      },
      {
        "ResponseText": " No.",
        "IsRight": false
      }
    ]
  },
  {
    "QuestionText": "You decide to create 2 Virtual machines. Each virtual machine is of the size D2s v3. Would these machines always generate the same monthly cost?",
    "Responses": [
      {
        "ResponseText": " Yes.",
        "IsRight": false
      },
      {
        "ResponseText": " No.",
        "IsRight": true
      }
    ]
  }
]
```
